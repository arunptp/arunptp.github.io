---
title: Thermal Power Plants in India - An Interactive Visualization
author: Arun Thomas
image: /img/PowerPlant.jpg
---
 <font color="blue"> \# Geo-Tagging | # Visualization | # Tableau </font>
---
> ## An  interactive demo is explored at <a href="https://arun-thomas.xyz/rul/">https://arun-thomas.xyz/vizthermalin/</a>

---

<div text="align">
This project was an attempt to study Data visualization using Tableau. Serendeptiously, I came across a visualization of thermal power in the whole world developed by Carbon Brief (https://www.carbonbrief.org/mapped-worlds-coal-power-plants). Carbon Brief sourced their data from www.globalenergymonitor.com and it had a plethora of information regarding thermal power plants. The data of the Indian power plants had some very interesting attributes like parent company, installed capacity, cancelled projects, retired projects, start year etc. However, my plan of plotting the thermal plants hit a road block when I found that geo-location (latitude and longitude) was not available.


> FInding the locations of 662 power stations (Geo-Tagging) was challenging.


</div>
<div text="align">
Further perusal and experimentation with geo-tagging literature available on the internet yielded the following method of finding latitude and logitudes of 662 numbers of power stations.
</div>


## Geo Tagging Using Google Geo Code API


```python
import pandas as pd
sheet = 'Sheet1'
# Name of excel file sourced from www.globalenergymonitor.org
file_name = 'CPI.xlsx' 

# Conversion to Dataframe
dfs = pd.read_excel(file_name, sheet_name=sheet)
# Remove Duplicates and convert to list.
plantlist = dfs[dfs.columns[1]].drop_duplicates(keep='first', inplace=False).values.tolist()
```


```python
# Number of Power Stations
len(plantlist)
```




    662




```python
# Sanity Check - First 11 plants
testList = namelist[0:10]
```


```python
testList
```




    ['Zawar Mines power station',
     'Yermarus power station',
     'Yadadri power station',
     'West Khasi power station',
     'West Godavari Super Thermal Power Station',
     'Welspun Mega Industrial & Energy Park',
     'Welspun Maxsteel power station',
     'Welspun Ghazipur project',
     'Welspun Energy Parbahal Thermal Power Plant',
     'Welspun Energy Mirzapur power station']




```python
# Importing the requests library 
import requests 
  
# Api-endpoint 
URL = "https://maps.googleapis.com/maps/api/geocode/json"

# Output json location with station name.
jso = pd.DataFrame(columns = ['location','json'])

# key = # Get key from Google Cloud 
for location in plantlist:
  
  # Defining a params dict for the parameters to be sent to the API 
  PARAMS = {'address':location,'key':key} 
  
  # Sending get request and saving the response as response object 
  r = requests.get(url = URL, params = PARAMS) 
  
  # Extracting data in json format 
  data = r.json() 
  
  # Appending Location to json output
  jso = jso.append(pd.Series([location,data], index=jso.columns), ignore_index=True)
```


```python
# Output station name with location in Json.
jso
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>location</th>
      <th>json</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Zawar Mines power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Yermarus power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Yadadri power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>3</th>
      <td>West Khasi power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>4</th>
      <td>West Godavari Super Thermal Power Station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Welspun Mega Industrial &amp; Energy Park</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Welspun Maxsteel power station</td>
      <td>{'results': [], 'status': 'ZERO_RESULTS'}</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Welspun Ghazipur project</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Welspun Energy Parbahal Thermal Power Plant</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Welspun Energy Mirzapur power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Welspun Energy Anuppur Thermal Power Plant</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Welspun Amla power station</td>
      <td>{'results': [], 'status': 'ZERO_RESULTS'}</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Wardha Works power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Wardha Warora Power Plant</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Waral power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Wanakbori Thermal Power Station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>16</th>
      <td>VS Lignite Plant</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Vizag Thermal Power Plant</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Vizag Steel Plant power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>19</th>
      <td>Vizag Simhadri power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Vizag Kaizen power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>21</th>
      <td>Visakhapatnam Sarda power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Visa Power Jharkhand project</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Vindhyachal power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Vilayat Caustic power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>25</th>
      <td>Vikas Power thermal plant</td>
      <td>{'results': [], 'status': 'ZERO_RESULTS'}</td>
    </tr>
    <tr>
      <th>26</th>
      <td>Vijaynagar (KPCL) power station</td>
      <td>{'results': [], 'status': 'ZERO_RESULTS'}</td>
    </tr>
    <tr>
      <th>27</th>
      <td>Vijayawada Thermal Power Station (IGCC)</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>28</th>
      <td>Vidarbha Thermal Power</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>29</th>
      <td>Vemavaram power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>632</th>
      <td>Athiyakurichi power station</td>
      <td>{'results': [], 'status': 'ZERO_RESULTS'}</td>
    </tr>
    <tr>
      <th>633</th>
      <td>Athena Chhattisgarh power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>634</th>
      <td>ASTARC power station</td>
      <td>{'results': [], 'status': 'ZERO_RESULTS'}</td>
    </tr>
    <tr>
      <th>635</th>
      <td>Asansol power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>636</th>
      <td>Asansol Crescent power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>637</th>
      <td>ARS Metals Gummidipoondi captive power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>638</th>
      <td>Arasmeta Cement Plant power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>639</th>
      <td>Anuppur Thermal Power Project</td>
      <td>{'results': [], 'status': 'ZERO_RESULTS'}</td>
    </tr>
    <tr>
      <th>640</th>
      <td>Anuppur power station (Newzone)</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>641</th>
      <td>Anpara-E power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>642</th>
      <td>Anpara-D power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>643</th>
      <td>Anpara-C power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>644</th>
      <td>Anpara power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>645</th>
      <td>Ankulapatur power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>646</th>
      <td>Angul Steel power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>647</th>
      <td>Angul Smelter power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>648</th>
      <td>Angul power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>649</th>
      <td>Amreli power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>650</th>
      <td>Amravati Thermal Power Project</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>651</th>
      <td>Amoda power station</td>
      <td>{'results': [], 'status': 'ZERO_RESULTS'}</td>
    </tr>
    <tr>
      <th>652</th>
      <td>Ambujanagar Cement Plant power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>653</th>
      <td>Amauli Fatehpur power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>654</th>
      <td>Akrimota Power Project</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>655</th>
      <td>Ajmer power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>656</th>
      <td>Adra Purulia power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>657</th>
      <td>Adityapur Works power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>658</th>
      <td>Aditya Aluminium power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>659</th>
      <td>Adilibad power station (Shalivahana Power Corp.)</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
    <tr>
      <th>660</th>
      <td>Adani Korba West power station</td>
      <td>{'results': [], 'status': 'ZERO_RESULTS'}</td>
    </tr>
    <tr>
      <th>661</th>
      <td>Adani Godda power station</td>
      <td>{'results': [{'address_components': [{'long_na...</td>
    </tr>
  </tbody>
</table>
<p>662 rows × 2 columns</p>
</div>



### Extracting output json to yield location, latitude and longitude.


```python
f = pd.DataFrame(columns = ['location', 'latitude', 'longitude'])
```


```python
j = jso['json']
i = 0
for location in plantlist:
   # Extracting latitude, longitude and formatted address of the first matching location 
  if len(j[i]['results']) != 0  :
    latitude = j[i]['results'][0]['geometry']['location']['lat'] 
    longitude = j[i]['results'][0]['geometry']['location']['lng']
  else:
    latitude = ''
    longitude = ''

  f = f.append(pd.Series([location,latitude,longitude], index=f.columns), ignore_index=True)
  i = i + 1
```


```python
# Final dataframe f with location, latitude and longitude
f
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>location</th>
      <th>latitude</th>
      <th>longitude</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Zawar Mines power station</td>
      <td>24.3516</td>
      <td>73.7476</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Yermarus power station</td>
      <td>16.2952</td>
      <td>77.3563</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Yadadri power station</td>
      <td>16.7018</td>
      <td>79.6207</td>
    </tr>
    <tr>
      <th>3</th>
      <td>West Khasi power station</td>
      <td>25.8383</td>
      <td>91.7438</td>
    </tr>
    <tr>
      <th>4</th>
      <td>West Godavari Super Thermal Power Station</td>
      <td>16.8616</td>
      <td>81.3652</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Welspun Mega Industrial &amp; Energy Park</td>
      <td>34.1546</td>
      <td>-84.7879</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Welspun Maxsteel power station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>Welspun Ghazipur project</td>
      <td>25.5878</td>
      <td>83.5783</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Welspun Energy Parbahal Thermal Power Plant</td>
      <td>23.4494</td>
      <td>86.325</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Welspun Energy Mirzapur power station</td>
      <td>25.1366</td>
      <td>82.5717</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Welspun Energy Anuppur Thermal Power Plant</td>
      <td>23.1137</td>
      <td>81.6976</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Welspun Amla power station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>12</th>
      <td>Wardha Works power station</td>
      <td>20.7458</td>
      <td>78.5985</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Wardha Warora Power Plant</td>
      <td>20.2716</td>
      <td>78.9815</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Waral power station</td>
      <td>53.311</td>
      <td>-2.94093</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Wanakbori Thermal Power Station</td>
      <td>22.8766</td>
      <td>73.3588</td>
    </tr>
    <tr>
      <th>16</th>
      <td>VS Lignite Plant</td>
      <td>27.8489</td>
      <td>72.8545</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Vizag Thermal Power Plant</td>
      <td>17.5961</td>
      <td>83.0875</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Vizag Steel Plant power station</td>
      <td>17.6467</td>
      <td>83.166</td>
    </tr>
    <tr>
      <th>19</th>
      <td>Vizag Simhadri power station</td>
      <td>17.5961</td>
      <td>83.0875</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Vizag Kaizen power station</td>
      <td>17.5961</td>
      <td>83.0875</td>
    </tr>
    <tr>
      <th>21</th>
      <td>Visakhapatnam Sarda power station</td>
      <td>17.5961</td>
      <td>83.0875</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Visa Power Jharkhand project</td>
      <td>23.6102</td>
      <td>85.2799</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Vindhyachal power station</td>
      <td>24.096</td>
      <td>82.6716</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Vilayat Caustic power station</td>
      <td>21.7647</td>
      <td>72.8811</td>
    </tr>
    <tr>
      <th>25</th>
      <td>Vikas Power thermal plant</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>26</th>
      <td>Vijaynagar (KPCL) power station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>27</th>
      <td>Vijayawada Thermal Power Station (IGCC)</td>
      <td>16.6002</td>
      <td>80.5369</td>
    </tr>
    <tr>
      <th>28</th>
      <td>Vidarbha Thermal Power</td>
      <td>20.8223</td>
      <td>78.4879</td>
    </tr>
    <tr>
      <th>29</th>
      <td>Vemavaram power station</td>
      <td>16.0975</td>
      <td>80.0392</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>632</th>
      <td>Athiyakurichi power station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>633</th>
      <td>Athena Chhattisgarh power station</td>
      <td>21.9061</td>
      <td>83.129</td>
    </tr>
    <tr>
      <th>634</th>
      <td>ASTARC power station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>635</th>
      <td>Asansol power station</td>
      <td>23.7164</td>
      <td>87.0695</td>
    </tr>
    <tr>
      <th>636</th>
      <td>Asansol Crescent power station</td>
      <td>23.7164</td>
      <td>87.0695</td>
    </tr>
    <tr>
      <th>637</th>
      <td>ARS Metals Gummidipoondi captive power station</td>
      <td>13.4236</td>
      <td>80.0668</td>
    </tr>
    <tr>
      <th>638</th>
      <td>Arasmeta Cement Plant power station</td>
      <td>21.9491</td>
      <td>82.3316</td>
    </tr>
    <tr>
      <th>639</th>
      <td>Anuppur Thermal Power Project</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>640</th>
      <td>Anuppur power station (Newzone)</td>
      <td>23.0729</td>
      <td>81.7787</td>
    </tr>
    <tr>
      <th>641</th>
      <td>Anpara-E power station</td>
      <td>24.2049</td>
      <td>82.7832</td>
    </tr>
    <tr>
      <th>642</th>
      <td>Anpara-D power station</td>
      <td>24.1958</td>
      <td>82.8056</td>
    </tr>
    <tr>
      <th>643</th>
      <td>Anpara-C power station</td>
      <td>24.2052</td>
      <td>82.7965</td>
    </tr>
    <tr>
      <th>644</th>
      <td>Anpara power station</td>
      <td>24.2052</td>
      <td>82.7965</td>
    </tr>
    <tr>
      <th>645</th>
      <td>Ankulapatur power station</td>
      <td>20.4628</td>
      <td>76.9384</td>
    </tr>
    <tr>
      <th>646</th>
      <td>Angul Steel power station</td>
      <td>20.855</td>
      <td>85.1907</td>
    </tr>
    <tr>
      <th>647</th>
      <td>Angul Smelter power station</td>
      <td>20.855</td>
      <td>85.1907</td>
    </tr>
    <tr>
      <th>648</th>
      <td>Angul power station</td>
      <td>20.855</td>
      <td>85.1907</td>
    </tr>
    <tr>
      <th>649</th>
      <td>Amreli power station</td>
      <td>21.6062</td>
      <td>71.2228</td>
    </tr>
    <tr>
      <th>650</th>
      <td>Amravati Thermal Power Project</td>
      <td>21.0728</td>
      <td>77.9025</td>
    </tr>
    <tr>
      <th>651</th>
      <td>Amoda power station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>652</th>
      <td>Ambujanagar Cement Plant power station</td>
      <td>20.8334</td>
      <td>70.6877</td>
    </tr>
    <tr>
      <th>653</th>
      <td>Amauli Fatehpur power station</td>
      <td>26.0958</td>
      <td>80.3504</td>
    </tr>
    <tr>
      <th>654</th>
      <td>Akrimota Power Project</td>
      <td>23.7698</td>
      <td>68.6454</td>
    </tr>
    <tr>
      <th>655</th>
      <td>Ajmer power station</td>
      <td>26.4074</td>
      <td>74.6267</td>
    </tr>
    <tr>
      <th>656</th>
      <td>Adra Purulia power station</td>
      <td>23.4959</td>
      <td>86.6892</td>
    </tr>
    <tr>
      <th>657</th>
      <td>Adityapur Works power station</td>
      <td>22.7879</td>
      <td>86.1482</td>
    </tr>
    <tr>
      <th>658</th>
      <td>Aditya Aluminium power station</td>
      <td>21.7323</td>
      <td>84.0466</td>
    </tr>
    <tr>
      <th>659</th>
      <td>Adilibad power station (Shalivahana Power Corp.)</td>
      <td>19.6641</td>
      <td>78.532</td>
    </tr>
    <tr>
      <th>660</th>
      <td>Adani Korba West power station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>661</th>
      <td>Adani Godda power station</td>
      <td>24.8186</td>
      <td>87.2068</td>
    </tr>
  </tbody>
</table>
<p>662 rows × 3 columns</p>
</div>




```python
# Converting to .csv for further exploration and vizualization in Tableau.
f.to_csv('raw.csv')
```

## Visualization using Tableau

<div align="justify">
Tableau is great because data can be analyzed very quickly with it. Also, visualizations are generated as dashboards and worksheets. Tableau allows one to create dashboards that provide actionable insights.
</div>

<div align="justify">
The filtering is done company wise, with the size of bubble on the map indicating installed capacity. NTPC, India's largest power major is shown in blue. 

A date filter is also provided which shows the evolution across time.
</div>

## References


1.  http://engineering.hackerearth.com/2014/08/21/python-requests-module/
2. https://globalenergymonitor.org/coal/global-coal-plant-tracker/
3. https://developers.google.com/maps/documentation/geocoding/intro
4. https://www.carbonbrief.org/mapped-worlds-coal-power-plants
