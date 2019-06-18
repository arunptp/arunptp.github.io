---
title: CONDITION MONITORING & PREDICTIVE MAINTENANCE
author: Arun Thomas
image: /img/powerlines.jpg

---


<html>
<head><meta charset="utf-8" />
<title>BearingAnalytics</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>

<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.2.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.2.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.2.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.2.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.2.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
@media (max-width: 991px) {
  #ipython_notebook {
    margin-left: 10px;
  }
}
[dir="rtl"] #ipython_notebook {
  float: right !important;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#login_widget {
  float: right;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  text-align: center;
  vertical-align: middle;
  display: inline;
  opacity: 0;
  z-index: 2;
  width: 12ex;
  margin-right: -12ex;
}
.alternate_upload .btn-upload {
  height: 22px;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
[dir="rtl"] #tabs li {
  float: right;
}
ul#tabs {
  margin-bottom: 4px;
}
[dir="rtl"] ul#tabs {
  margin-right: 0px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons {
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-right {
  padding-top: 1px;
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-left {
  float: right !important;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: baseline;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
#tree-selector {
  padding-right: 0px;
}
[dir="rtl"] #tree-selector a {
  float: right;
}
#button-select-all {
  min-width: 50px;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
[dir="rtl"] #new-menu {
  text-align: right;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
[dir="rtl"] #running .col-sm-8 {
  float: right !important;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI colors. */
.ansibold {
  font-weight: bold;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  border-left-width: 1px;
  padding-left: 5px;
  background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%);
}
div.cell.jupyter-soft-selected {
  border-left-color: #90CAF9;
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected {
  border-color: #ababab;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 5px, transparent 5px, transparent 100%);
}
@media print {
  div.cell.selected {
    border-color: transparent;
  }
}
div.cell.selected.jupyter-soft-selected {
  border-left-width: 0;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 7px, #E3F2FD 7px, #E3F2FD 100%);
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #66BB6A -40px, #66BB6A 5px, transparent 5px, transparent 100%);
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  padding: 0.4em;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */
  /* .CodeMirror-lines */
  padding: 0;
  border: 0;
  border-radius: 0;
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul {
  list-style: disc;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ul ul {
  list-style: square;
  margin: 0em 2em;
}
.rendered_html ul ul ul {
  list-style: circle;
  margin: 0em 2em;
}
.rendered_html ol {
  list-style: decimal;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
  margin: 0em 2em;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  background-color: #fff;
  color: #000;
  font-size: 100%;
  padding: 0px;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: 1px solid black;
  border-collapse: collapse;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  border: 1px solid black;
  border-collapse: collapse;
  margin: 1em 2em;
}
.rendered_html td,
.rendered_html th {
  text-align: left;
  vertical-align: middle;
  padding: 4px;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget {
  float: right !important;
  float: right;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  margin-top: 6px;
}
span.save_widget span.filename {
  height: 1em;
  line-height: 1em;
  padding: 3px;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  display: none;
}
.command-shortcut:before {
  content: "(command)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="CONDITION-MONITORING-&amp;-PREDICTIVE-MAINTENANCE">CONDITION MONITORING &amp; PREDICTIVE MAINTENANCE<a class="anchor-link" href="#CONDITION-MONITORING-&amp;-PREDICTIVE-MAINTENANCE">&#182;</a></h1><p><em><b> --- By Arun A Thomas </em></p>
<blockquote><p><em><b>"The Mantra : Less time spent on figuring out the problem, more time spent on fixing and preventing it "</em></p>
</blockquote>
<p><font color="blue">This notebook is intended to illustrate conditioning monitoring of industrial machinery by walking  through a real life dataset of bearing vibration data.</font></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Introduction">Introduction<a class="anchor-link" href="#Introduction">&#182;</a></h1><p>Generally, conditioning monitoring of a machine is done by looking at a sensor mesurement (Eg. Temperature, Vibration ) and imposing bounds to it, i.e. under normal operating conditions, the measurement values are bounded by a maximum and minimum value (similar to control charts). Any deviation is the defined bounds sends an alarm. This is often generally defined as <em><b>anamoly detection.</em>&lt;/b&gt;</p>
<p>However, this method often sends false alarms (false positives) or misses an alarm (false negative). Furthermore, a single signal is observed/analysed in isolation. For example, an alarm may sound if the temperature exceeeds a certain level. A system defined above often cannot look at mutiple parameters and come to a conclusion about the state of a machine. Or technical parlance, one cannot take advantage of the multi-dimensionality of the data.</p>
<p>This is where machine learning and other AI based techniques step in.</p>
<p>This notes walks one through anamoly detection of a single dimension data (vibration). This is easier to visualise. The same principles hold true for mutildimensional data as well.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Machine-Learning-Anamoly-Detection-Engine">Machine Learning Anamoly Detection Engine<a class="anchor-link" href="#Machine-Learning-Anamoly-Detection-Engine">&#182;</a></h1><p>A Machine Learning Anomaly Detection (MLAD) Engine uses sensor data like tempearture, flow, vibration and other variables (multi-dimensional) to create a multi-dimensional pattern ., i.e. the state of a machine is "learned" under healthy operating conditions.  By learning the healthy state, the engine guages if an alert should be triggered or not under any deviation.</p>
<p>The second step is to forecast the probability of future breakdown or in other words, asses the RUL (Residual Useful Life) of a machine. This provides valuable information regarding urgent repairs or regarding planned maintenance activity.</p>
<p>Finally, can integrate them into dashboards  or  into alarm systems that will be monitored by maintenance teams.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Softwares-/-Packages-Used">Softwares / Packages Used<a class="anchor-link" href="#Softwares-/-Packages-Used">&#182;</a></h1><p>All sofware packages used are open-sourced packages. The language used is Python and asscoiated packages like pandas, matplotlib.</p>
<p>For anamoly detection, a open source package developed by Facebook team called Prophet is used.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="The-Dataset">The Dataset<a class="anchor-link" href="#The-Dataset">&#182;</a></h1><p>The dataset is sourced from the NASA repo <a href="https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/">https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/</a>.</p>
<hr>
<p><em>Dataset Citation : J. Lee, H. Qiu, G. Yu, J. Lin, and Rexnord Technical Services (2007). IMS, University of Cincinnati. "Bearing Data Set", NASA Ames Prognostics Data Repository (<a href="http://ti.arc.nasa.gov/project/prognostic-data-repository">http://ti.arc.nasa.gov/project/prognostic-data-repository</a>), NASA Ames Research Center, Moffett Field, CA</em></p>
<hr>
<h2 id="Breif-Description-of-Test-Rig-for-Data-Collection">Breif Description of Test Rig for Data Collection<a class="anchor-link" href="#Breif-Description-of-Test-Rig-for-Data-Collection">&#182;</a></h2><p>This is a <em><b>"Run to Failure "</em>&lt;/b&gt; dataset.</p>
<p>Four bearings were installed on a shaft. The rotation speed was kept constant at 2000 RPM by an AC motor coupled to the shaft via rub belts.  A radial load of 6000 lbs is applied onto the shaft and bearing by a spring mechanism. All bearings are force lubricated.</p>
<p>Rexnord ZA-2115 double row bearings were installed on the shaft as shown in Figure 1. PCB 353B33 High Sensitivity Quartz ICP accelerometers were installed on the bearing housing (two accelerometers for each bearing [x- and y-axes] for data set 1, one accelerometer for each bearing for data sets 2 and 3). Sensor placement is also shown in figure. All failures occurred after exceeding designed life time of the bearing which is more than 100 million revolutions.</p>
<p><img src="https://drive.google.com/uc?id=18StOAh4ugVJuhV__RpxeCq2lZNhePC9m" alt="Image not Available"></p>
<ul>
<li>Recording Duration:  February 12, 2004 10:32:39 to February 19, 2004 06:22:39</li>
<li>No. of Files: 984 </li>
<li>No. of Channels:  4 </li>
<li>Channel Arrangement:  Bearing 1 – Ch 1; Bearing2 – Ch 2; Bearing3 – Ch3; Bearing 4 – Ch 4.</li>
<li>File Recording Interval:  Every 10 minutes</li>
<li>File Format:  ASCII Description</li>
</ul>
<hr>
<p>At the end of the test-to-failure experiment, Outer race failure occurred in bearing 1.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Loading-of-Data-from-G.Cloud">Loading of Data from G.Cloud<a class="anchor-link" href="#Loading-of-Data-from-G.Cloud">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Confirming the Working Directory</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">os</span>
<span class="n">os</span><span class="o">.</span><span class="n">chdir</span><span class="p">(</span><span class="s1">&#39;/content&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot; Current Working Directory&quot;</span><span class="p">)</span>
<span class="o">%</span> <span class="n">pwd</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre> Current Working Directory
</pre>
</div>
</div>

<div class="output_area">

<div class="prompt output_prompt">Out[0]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&#39;/content&#39;</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Importing Python Packages</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Common imports</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="k">import</span> <span class="n">preprocessing</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">color_codes</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="o">%</span><span class="k">matplotlib</span> inline
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Connecting to G.Cloud Account where data has been stored. Needs Google ID and Password for Verfication.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Install the PyDrive wrapper &amp; import libraries.</span>
<span class="c1"># This only needs to be done once per notebook.</span>
<span class="o">!</span>pip install -U -q PyDrive
<span class="kn">from</span> <span class="nn">pydrive.auth</span> <span class="k">import</span> <span class="n">GoogleAuth</span>
<span class="kn">from</span> <span class="nn">pydrive.drive</span> <span class="k">import</span> <span class="n">GoogleDrive</span>
<span class="kn">from</span> <span class="nn">google.colab</span> <span class="k">import</span> <span class="n">auth</span>
<span class="kn">from</span> <span class="nn">oauth2client.client</span> <span class="k">import</span> <span class="n">GoogleCredentials</span>

<span class="c1"># Authenticate and create the PyDrive client.</span>
<span class="c1"># This only needs to be done once per notebook.</span>
<span class="n">auth</span><span class="o">.</span><span class="n">authenticate_user</span><span class="p">()</span>
<span class="n">gauth</span> <span class="o">=</span> <span class="n">GoogleAuth</span><span class="p">()</span>
<span class="n">gauth</span><span class="o">.</span><span class="n">credentials</span> <span class="o">=</span> <span class="n">GoogleCredentials</span><span class="o">.</span><span class="n">get_application_default</span><span class="p">()</span>
<span class="n">drive</span> <span class="o">=</span> <span class="n">GoogleDrive</span><span class="p">(</span><span class="n">gauth</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>     |████████████████████████████████| 993kB 2.8MB/s 
  Building wheel for PyDrive (setup.py) ... done
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Download a file based on its file ID</span>
<span class="n">file_id</span> <span class="o">=</span> <span class="s1">&#39;1bljNTBDZr701KXs8wfPB6KAyi8dtM8QG&#39;</span>
<span class="n">download</span> <span class="o">=</span> <span class="n">drive</span><span class="o">.</span><span class="n">CreateFile</span><span class="p">({</span><span class="s1">&#39;id&#39;</span><span class="p">:</span> <span class="n">file_id</span><span class="p">})</span>
<span class="n">download</span><span class="o">.</span><span class="n">GetContentFile</span><span class="p">(</span><span class="s1">&#39;data.zip&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Downloaded Data File&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Downloaded Data File
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Unzipping the data file</span>
<span class="o">!</span>unzip data.zip
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The data is downloaded into the remote instance as data in the /content folder and is used for analytics.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># renaming file from 2nd_test to data</span>
<span class="n">os</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="s1">&#39;2nd_test&#39;</span><span class="p">,</span><span class="s1">&#39;data&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Understanding-the-Data">Understanding the Data<a class="anchor-link" href="#Understanding-the-Data">&#182;</a></h1><p>Measurement files are available as seperate files (Total 984)</p>
<p>Start of Directory Data<br>
data/2004.02.12.10.32.39   (12th Feb, 2004) <br>
data/2004.02.12.10.42.39</p>
<p>End Directory Data<br>
data/2004.02.19.06.12.39   (19th Feb, 2004) <br>
data/2004.02.19.06.22.39</p>
<p>Each file contains 10mins of accelerometer data.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Data-Wrangling">Data Wrangling<a class="anchor-link" href="#Data-Wrangling">&#182;</a></h2><p>Each of the 10min file is averaged and stored to a pandas dataframe</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">data_dir</span> <span class="o">=</span> <span class="s1">&#39;data&#39;</span>
<span class="n">merged_data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span>

<span class="c1"># Looping over all files from 12th Feb to 19th Feb</span>
<span class="k">for</span> <span class="n">filename</span> <span class="ow">in</span> <span class="n">os</span><span class="o">.</span><span class="n">listdir</span><span class="p">(</span><span class="n">data_dir</span><span class="p">):</span>
    <span class="n">dataset</span><span class="o">=</span><span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="n">os</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">data_dir</span><span class="p">,</span> <span class="n">filename</span><span class="p">),</span> <span class="n">sep</span><span class="o">=</span><span class="s1">&#39;</span><span class="se">\t</span><span class="s1">&#39;</span><span class="p">)</span>
    <span class="n">dataset_mean_abs</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">array</span><span class="p">(</span><span class="n">dataset</span><span class="o">.</span><span class="n">abs</span><span class="p">()</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>
    <span class="n">dataset_mean_abs</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">dataset_mean_abs</span><span class="o">.</span><span class="n">reshape</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span><span class="mi">4</span><span class="p">))</span>
    <span class="n">dataset_mean_abs</span><span class="o">.</span><span class="n">index</span> <span class="o">=</span> <span class="p">[</span><span class="n">filename</span><span class="p">]</span>
    <span class="n">merged_data</span> <span class="o">=</span> <span class="n">merged_data</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">dataset_mean_abs</span><span class="p">)</span>
    
<span class="c1"># Renaming columns</span>
<span class="n">merged_data</span><span class="o">.</span><span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Bearing 1&#39;</span><span class="p">,</span><span class="s1">&#39;Bearing 2&#39;</span><span class="p">,</span><span class="s1">&#39;Bearing 3&#39;</span><span class="p">,</span><span class="s1">&#39;Bearing 4&#39;</span><span class="p">]</span>
<span class="c1"># Identifying index as datetime format</span>
<span class="n">merged_data</span><span class="o">.</span><span class="n">index</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">to_datetime</span><span class="p">(</span><span class="n">merged_data</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="nb">format</span><span class="o">=</span><span class="s1">&#39;%Y.%m.</span><span class="si">%d</span><span class="s1">.%H.%M.%S&#39;</span><span class="p">)</span>
<span class="n">merged_data</span> <span class="o">=</span> <span class="n">merged_data</span><span class="o">.</span><span class="n">sort_index</span><span class="p">()</span>
<span class="n">merged_data</span><span class="o">.</span><span class="n">to_csv</span><span class="p">(</span><span class="s1">&#39;merged_dataset_BearingTest_2.csv&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Check - Begining of Data</span>
<span class="n">merged_data</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[0]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
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
      <th>Bearing 1</th>
      <th>Bearing 2</th>
      <th>Bearing 3</th>
      <th>Bearing 4</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2004-02-12 10:32:39</th>
      <td>0.058333</td>
      <td>0.071832</td>
      <td>0.083242</td>
      <td>0.043067</td>
    </tr>
    <tr>
      <th>2004-02-12 10:42:39</th>
      <td>0.058995</td>
      <td>0.074006</td>
      <td>0.084435</td>
      <td>0.044541</td>
    </tr>
    <tr>
      <th>2004-02-12 10:52:39</th>
      <td>0.060236</td>
      <td>0.074227</td>
      <td>0.083926</td>
      <td>0.044443</td>
    </tr>
    <tr>
      <th>2004-02-12 11:02:39</th>
      <td>0.061455</td>
      <td>0.073844</td>
      <td>0.084457</td>
      <td>0.045081</td>
    </tr>
    <tr>
      <th>2004-02-12 11:12:39</th>
      <td>0.061361</td>
      <td>0.075609</td>
      <td>0.082837</td>
      <td>0.045118</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Check - End of Data</span>
<span class="n">merged_data</span><span class="o">.</span><span class="n">tail</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[0]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
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
      <th>Bearing 1</th>
      <th>Bearing 2</th>
      <th>Bearing 3</th>
      <th>Bearing 4</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2004-02-19 05:42:39</th>
      <td>0.453335</td>
      <td>0.161016</td>
      <td>0.137440</td>
      <td>0.119047</td>
    </tr>
    <tr>
      <th>2004-02-19 05:52:39</th>
      <td>0.337583</td>
      <td>0.132400</td>
      <td>0.144992</td>
      <td>0.092125</td>
    </tr>
    <tr>
      <th>2004-02-19 06:02:39</th>
      <td>0.351111</td>
      <td>0.152266</td>
      <td>0.151299</td>
      <td>0.100817</td>
    </tr>
    <tr>
      <th>2004-02-19 06:12:39</th>
      <td>0.001857</td>
      <td>0.003732</td>
      <td>0.003656</td>
      <td>0.001786</td>
    </tr>
    <tr>
      <th>2004-02-19 06:22:39</th>
      <td>0.001168</td>
      <td>0.000767</td>
      <td>0.000716</td>
      <td>0.001699</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Check Total Points</span>
<span class="nb">print</span><span class="p">(</span><span class="n">f</span><span class="s1">&#39;Total Data Points {merged_data.shape[0] + 1}&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Total Data Points 984
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Visualising-Vibration-Data">Visualising Vibration Data<a class="anchor-link" href="#Visualising-Vibration-Data">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Visualising Data</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">merged_data</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">12</span><span class="p">,</span><span class="mi">6</span><span class="p">),</span> <span class="n">title</span><span class="o">=</span><span class="s2">&quot;Vibration Data&quot;</span> <span class="p">,</span> <span class="n">legend</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">xlabel</span><span class="o">=</span><span class="s2">&quot;Year-Month-Date&quot;</span><span class="p">,</span> <span class="n">ylabel</span><span class="o">=</span><span class="s2">&quot;Vibration/Acceleration(g)&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">axvline</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s1">&#39;2004-02-19 06:12:39&#39;</span><span class="p">,</span> <span class="n">linewidth</span><span class="o">=</span><span class="mi">4</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;b&#39;</span><span class="p">,</span> <span class="n">label</span> <span class="o">=</span><span class="s2">&quot;Breakdown of Bearing 1&quot;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="s1">&#39;2004-02-19 06:12:39&#39;</span><span class="p">,</span><span class="mf">0.3</span><span class="p">,</span><span class="s1">&#39;Breakdown of Bearing 1&#39;</span><span class="p">,</span><span class="n">rotation</span><span class="o">=</span><span class="mi">90</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">14</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;b&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[0]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(2004-02-19 06:12:39, 0.3, &#39;Breakdown of Bearing 1&#39;)</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The above figure shows the accelereometer data for all four bearings. Bearing 1 fails at end of measurement, @ 2004-02-19 06:22:39.</p>
<p>Observing the time plot, it is pretty obvious that the vibration increases after 2004-02-16. However, how does a machine access that there has been an increase in bearing vibration?</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Zooming-in-Data-for-Bearing-1">Zooming in Data for Bearing 1<a class="anchor-link" href="#Zooming-in-Data-for-Bearing-1">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">fig</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">()</span>

<span class="c1"># Divide the figure into a 1x2 grid, and give me the first section</span>
<span class="n">ax1</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">add_subplot</span><span class="p">(</span><span class="mi">121</span><span class="p">)</span>
<span class="c1"># Divide the figure into a 1x2 grid, and give me the second section</span>
<span class="n">ax2</span> <span class="o">=</span> <span class="n">fig</span><span class="o">.</span><span class="n">add_subplot</span><span class="p">(</span><span class="mi">122</span><span class="p">)</span>

<span class="n">healthy</span> <span class="o">=</span> <span class="n">merged_data</span><span class="p">[</span><span class="s1">&#39;2004-02-12 11:02:39&#39;</span><span class="p">:</span><span class="s1">&#39;2004-02-12 23:52:39&#39;</span><span class="p">]</span>
<span class="n">healthy</span><span class="p">[</span><span class="s1">&#39;Bearing 1&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">12</span><span class="p">,</span><span class="mi">6</span><span class="p">),</span> <span class="n">title</span><span class="o">=</span><span class="s2">&quot;Healthy State&quot;</span> <span class="p">,</span> <span class="n">legend</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span> <span class="n">ax</span><span class="o">=</span><span class="n">ax1</span><span class="p">)</span>
<span class="n">ax1</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">xlabel</span><span class="o">=</span><span class="s2">&quot;Month-Date Time&quot;</span><span class="p">,</span> <span class="n">ylabel</span><span class="o">=</span><span class="s2">&quot;Vibration/Acceleration(g)&quot;</span><span class="p">)</span>

<span class="n">faulty</span> <span class="o">=</span> <span class="n">merged_data</span><span class="p">[</span><span class="s1">&#39;2004-02-18 11:02:39&#39;</span><span class="p">:</span><span class="s1">&#39;2004-02-18 23:52:39&#39;</span><span class="p">]</span>
<span class="n">ax2</span> <span class="o">=</span> <span class="n">faulty</span><span class="p">[</span><span class="s1">&#39;Bearing 1&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">12</span><span class="p">,</span><span class="mi">6</span><span class="p">),</span> <span class="n">title</span><span class="o">=</span><span class="s2">&quot;Faulty State&quot;</span> <span class="p">,</span> <span class="n">legend</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span> <span class="n">ax</span><span class="o">=</span> <span class="n">ax2</span><span class="p">)</span>
<span class="n">ax2</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">xlabel</span><span class="o">=</span><span class="s2">&quot;Month-Date Time&quot;</span><span class="p">,</span> <span class="n">ylabel</span><span class="o">=</span><span class="s2">&quot;Vibration/Acceleration(g)&quot;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[0]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>[Text(0, 0.5, &#39;Vibration/Acceleration(g)&#39;), Text(0.5, 0, &#39;Month-Date Time&#39;)]</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
jHHQ/wf0Bq0JIF8IFgAAAABJRU5ErkJggg==
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The above graphs shows the vibration data fro bearing 1 at the for the same time peiod , '11:02:39' to "23:52:39' on 12th (Healthy) and on the 18th(Faulty/Poor Heath Score).</p>
<p>The vibration is definetly higher. Furthermore, the frequency component are also different.  It is easy to identify for one variable (one dimension). However, when the number of variables (dimensions) increase, i.e. when we consider more variable likes temperature, humidity etc., the complexity increases.</p>
<p>The beauty of ML lies in the fact that the same methods hold true for mutli dimensional data as well. Multiple sensor variables (dimensions) can be considered to get a more accurate measure of the "Health Score" of a machine.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Anamoly-Detection-using-Prophet-Package-(Black-Box-Modelling)">Anamoly Detection using Prophet Package (Black Box Modelling)<a class="anchor-link" href="#Anamoly-Detection-using-Prophet-Package-(Black-Box-Modelling)">&#182;</a></h1><p>Anomaly detection problem for time series can be formulated as finding outlier data points relative to some standard or usual signal. Our focus shall be from a machine persopective, such as unexpected spikes, level shift pointing to deteriorating health of a machine.</p>
<p>Prophet is open source software released by Facebook’s Core Data Science team.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">fbprophet</span> <span class="k">import</span> <span class="n">Prophet</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Creating-Training-Data-Set">Creating Training Data Set<a class="anchor-link" href="#Creating-Training-Data-Set">&#182;</a></h2><p>The training of the anamoly detection model is using data from the healthy phase of the bearing. The input to Prophet is always a dataframe with two columns: ds and y. The ds (datestamp) column should be of a format expected by Pandas, ideally YYYY-MM-DD for a date or YYYY-MM-DD HH:MM:SS for a timestamp. The y column must be numeric, and represents the measurement we wish to forecast.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">healthy_bearing1</span> <span class="o">=</span> <span class="n">merged_data</span><span class="p">[</span><span class="s1">&#39;2004-02-12 10:32:39&#39;</span><span class="p">:</span><span class="s1">&#39;2004-02-15 23:42:39&#39;</span><span class="p">][</span><span class="s1">&#39;Bearing 1&#39;</span><span class="p">]</span>

<span class="c1"># Creating training dataframe</span>
<span class="n">prophet_healthy_train</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span>
<span class="n">prophet_healthy_train</span><span class="p">[</span><span class="s1">&#39;ds&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">healthy_bearing1</span><span class="o">.</span><span class="n">index</span>
<span class="n">prophet_healthy_train</span><span class="p">[</span><span class="s1">&#39;y&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">healthy_bearing1</span><span class="o">.</span><span class="n">values</span>

<span class="n">prophet_healthy_train</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[0]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
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
      <th>ds</th>
      <th>y</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2004-02-12 10:32:39</td>
      <td>0.058333</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2004-02-12 10:42:39</td>
      <td>0.058995</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2004-02-12 10:52:39</td>
      <td>0.060236</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2004-02-12 11:02:39</td>
      <td>0.061455</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2004-02-12 11:12:39</td>
      <td>0.061361</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Creating-the-Model">Creating the Model<a class="anchor-link" href="#Creating-the-Model">&#182;</a></h2><p>Calling the In-Bulit Prophet Module for training a model</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">m</span> <span class="o">=</span> <span class="n">Prophet</span><span class="p">(</span><span class="n">interval_width</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>
<span class="c1"># Using the training data from &quot;healthy part&quot;</span>
<span class="n">m</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">prophet_healthy_train</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stderr output_text">
<pre>INFO:fbprophet:Disabling yearly seasonality. Run prophet with yearly_seasonality=True to override this.
INFO:fbprophet:Disabling weekly seasonality. Run prophet with weekly_seasonality=True to override this.
</pre>
</div>
</div>

<div class="output_area">

<div class="prompt output_prompt">Out[0]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;fbprophet.forecaster.Prophet at 0x7f84a9ec7da0&gt;</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Evaluation-on-Training-Data">Evaluation on Training Data<a class="anchor-link" href="#Evaluation-on-Training-Data">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">forecast</span> <span class="o">=</span> <span class="n">m</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">prophet_healthy_train</span><span class="p">)</span>
<span class="n">forecast</span><span class="p">[</span><span class="s1">&#39;fact&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">prophet_healthy_train</span><span class="p">[</span><span class="s1">&#39;y&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">drop</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Displaying Prophet plot&#39;</span><span class="p">)</span>
<span class="n">fig1</span> <span class="o">=</span> <span class="n">m</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">forecast</span><span class="p">)</span>
<span class="n">fig1</span> <span class="o">=</span> <span class="n">healthy_bearing1</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">12</span><span class="p">,</span><span class="mi">6</span><span class="p">),</span> <span class="n">title</span><span class="o">=</span><span class="s2">&quot;Fit of Training Data&quot;</span><span class="p">)</span>
<span class="n">fig1</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">xlabel</span><span class="o">=</span><span class="s2">&quot;Month (MM)-Date(DD) Time&quot;</span><span class="p">,</span> <span class="n">ylabel</span><span class="o">=</span><span class="s2">&quot;Vibration/Acceleration(g)&quot;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Displaying Prophet plot
</pre>
</div>
</div>

<div class="output_area">

<div class="prompt output_prompt">Out[0]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>[Text(45.125, 0.5, &#39;Vibration/Acceleration(g)&#39;),
 Text(0.5, 30.5, &#39;Month (MM)-Date(DD) Time&#39;)]</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA0cAAAGjCAYAAADn8G4+AAAABHNCSVQICAgIfAhkiAAAAAlwSFlz
AAALEgAACxIB0t1+/AAAADl0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uIDMuMC4zLCBo
dHRwOi8vbWF0cGxvdGxpYi5vcmcvnQurowAAIABJREFUeJzsvWuMZFd1/v3sfU5VdffcZzwDHkxi
THiBfySSEbYJIXb4x8YGPBMbB2MJcxOBQHBAIoEPIMVcJRQlEVECDrmIi0MuwiIKghiMgLyJiBw7
Nn5jY2PH2GM89vRl+lL3c9m398Pe+9Q5Vaeqq7urp7vH6/fFnu5T1afq3PZa61nPYsYYA4IgCIIg
CIIgiGc5fKt3gCAIgiAIgiAIYjtAwRFBEARBEARBEAQoOCIIgiAIgiAIggBAwRFBEARBEARBEAQA
Co4IgiAIgiAIgiAAUHBEEARBEARBEAQBgIIjgiAIYgxOnz6NY8eOQSk1kfd74okncO211+LYsWO4
7bbbJvKeo7j66qtx7733TnxbgiAI4tyC0ZwjgiAIwvMbv/EbWFxcRBAE2c++853v4DnPeU5hu7e+
9a34zd/8Tdxwww3r+jsf/ehHsXv3bnz0ox8d+N0111yD06dPAwDiOEYYhgjDEADwnve8B+9973vX
9Te3mttvvx233HILpqamAAAHDhzAK17xCrznPe/BhRdeONZ7fOhDH8LP//zP4/3vf/8m7ilBEMSz
l3Crd4AgCILYXnzhC1/Ar/7qr27q3zh9+jSuueaa0t/967/+a/b/4wRhUsoseNruXHzxxfi7v/s7
KKXwzDPP4G//9m/xW7/1W/ja176GF77whVu9ewRBEM96SFZHEARBrMrTTz+NF7/4xZBS4rOf/Szu
vfdefPKTn8SxY8fwyU9+svQ13//+93HNNdfg4osvxlvf+lY8/vjjAIC3ve1tuPvuu7PXnzx5ck37
cvvtt+Omm27Cpz/9aVx66aX4y7/8Szz55JN461vfiksvvRSveMUr8OEPfxitVit7zeWXX467774b
APDZz34Wv//7v48PfehDOHbsGI4fP46HHnpoXds++OCDmTzwgx/8ID7wgQ/gL/7iL1b9DEEQ4Od+
7ufwyU9+Er/8y7+Mz33ucwAArTU+8IEP4FWvetXA9/b3f//3+Pa3v42/+qu/wrFjx3DzzTcDAG69
9VZcccUVOHbsGK655hp8//vfX9P3SRAEQfSg4IggCIJYEx/84Adx8cUX45ZbbsH999+PW265ZWCb
kydP4g/+4A/w0Y9+FHfddRcuv/xyvPe970WaprjtttsKr3/BC16w5n24//77cdFFF+Guu+7Cu9/9
bhhj8L73vQ8//OEPcccdd+DUqVO49dZbh77+e9/7Hq699lrce++9uOyyy/DpT396zdumaYqbb74Z
N9xwA+655x5cddVV6wpMrrrqqkKP06tf/Wrceeed+M///E+86EUvwoc//GEAwE033YTXve51eM97
3oP7778fn//85wEAF154If7xH/8R9913H9773vfiQx/6EBYXF9e8HwRBEAQFRwRBEEQfN998My6+
+GJcfPHFeN/73reu97jjjjvw67/+63jVq16FSqWC3/7t30Ycx7j//vsnso/nn38+3vzmNyMIAkxN
TeEFL3gBXvnKV6JareLQoUN4xzvegXvuuWfo6y+55BJcdtllCIIA1157LR555JE1b3vfffeBc463
vOUtqFQqeN3rXodf/MVfXPNnOXLkCBqNBgCAc47rr78eu3fvRq1Ww+/93u/hoYceQrfbHfr617/+
9Thy5Ag45zhx4gSe97zn4cc//vGa94MgCIKgniOCIAiij89//vMb7jlaWFjA0aNHs39zznH++edj
fn5+o7sHwAZHec6cOYNPf/rT+NGPfoROpwNjDA4cODD09YcPH87+f3p6emTwMWzbhYUFPPe5zy1s
2//vcZifn8e+ffsAAEop/Omf/inuvPNOrKysgHObw1xZWcHMzEzp6//5n/8ZX/7ylzMTi263i5WV
lTXvB0EQBEGVI4IgCGITOHLkSLZYBwBjDGZnZwdc79YLY6zw7z/5kz9BtVrFN7/5TfzoRz/CZz7z
mYn8nVEcOXJkINibm5tb8/t873vfw8UXXwwA+Jd/+Rf8x3/8B77yla/gvvvuw3e/+10A9vsDBj/3
qVOn8PGPfxwf//jHcffdd+Pee+/FRRddBDKiJQiCWB8UHBEEQRBr5rzzzsOpU6eG/v51r3sd/v3f
/x133XUXhBD44he/iGq1imPHjm3K/nQ6HUxPT2PPnj2YnZ3FF7/4xU35O3le/vKXQ0qJf/iHf4CU
EnfeeWfBrGEUSqkssLnvvvsy+WKn00G1WsX+/fsRRRH+7M/+rPC6/u+90+mAMYaDBw/CGIOvfe1r
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
hLVr17b4ilcv3/zmN/HUU09hamoKGzZsQE9PDzo6OrBx40Y89thjeP3113HwwQejs7MTUkoyklrM
rbfeiieffBLT0xSM1HAAABghSURBVNM46KCDMDU1hRtvvBG///u/j97eXvz0pz9FsVjE5OQkjjvu
OHR0dLT6klcttGe1DzSv2ouVNLcorY5YEI8++ijOPvtsPPTQQ/jNb36Dc889F2+88Qay2Sw8zwMA
fPCDH8SOHTvwzDPPtPhqVy9SSkxOTuJv//Zv8ctf/hKHHnoobrjhBnzlK1/B4Ycfjg984AO4//77
cc455+Dhhx/GJz/5SezatavVl71qefzxx3HWWWeFhupHP/pR7Ny5E67rhvPqfe97H3bv3o1f/OIX
AKj2qFVIKbF//35ccMEF+PnPf45UKoWLLroI9957L97xjndg+/btuPHGG3HmmWfiiSeewGc/+1k8
+eSTmJycbPWlr0poz2oPaF61HytxblmtvgCi/ZicnMRdd92Fc889F6effjoA4IUXXsBXvvIVXHrp
pbAs9VidcMIJeOihh/Doo4+CMYZHH30Un/jEJ1p56asOxhjK5TKGh4dx8803o6OjAz09PXjwwQfx
rW99C+eeey5KpRJeeOEFHHHEEQCA9evXo1wut/jKVx/T09N46KGHcO655+J973sfAKUi+NWvfhXX
X389hBAAgDe/+c048sgj8fzzz+N73/sedu7cifPOOw+dnZ2tvPxVB2MMMzMzkFLin/7pnyCEQDqd
xo9+9CN0dnbisssuw/j4OF566SUcffTRAIAtW7bA932K9i0xtGe1DzSv2ouVOrcockTMCyklcrkc
/uzP/gwnnXRSWBC+YcMGbN68OXydkRs+++yzceutt+Jv/uZvwpQtYmnZu3cvent78dprrwEA3v3u
d+Ooo47C008/jWeffRaO4+CII45AqVTCNddcg7179+LII49s8VWvPjKZDLZt24aTTjopnD9btmzB
hg0bwteY+XbSSSfh7rvvxuc+9zlwzskwahEvvvgibNvG9PQ0AGD79u1Yu3Ytfvazn+G1115DPp/H
0UcfDSklrr76apTLZWzevJkOcEsI7VntB82r9mAlzy0yjoiGMA+9WXy2bt0Kx3HCn+/atQuO44Sv
55zj2WefxRVXXIGTTz4Z999/Pz71qU8t/YUTOOigg7B37178z//8D4IgAGMMb33rW8E5x9jYGADl
6fnLv/xL7N+/HzfffDPy+XyLr3p1YvKxzTx7/PHHQ8OHMQbGGF555RVcfvnleOc734kHHniA5tUS
Uq0O+Ja3vAW/+tWv8PTTTwNQ696JJ56Il156KUwn+e///m+ce+65GB0dxfXXX98W+fYrAdqz2hea
V+3Bip5bkiDq8PTTT8uf/OQncnJyctbX7dmzR55yyinS87zw31JKuXv3bvnSSy8t+nUSUj7++OPy
9ttvl7t27Yr93Pd9KaWU//Zv/yY//OEPy1deeUUGQSCllPKDH/ygvPPOO6WUUk5NTcnh4eGlvehV
Sr2xqmZiYkKecsopcmRkREop5W9/+9vw56+99tqiXyehePLJJ+U111wjpZTh3JFShuvdzTffLN//
/vfHfn/66afLBx98UEop5b59++Srr766lJe8aqk3VtXQntV6fv7zn8svfOELcmxsLPZzmlfLk3rj
Vc1KmVukVkfU8MYbb+CKK67AXXfdhV27duFnP/sZenp6sHbt2sSc3ueffx4TExN4xzvegYsvvhjf
//73ceqpp6Kzs5PSfRaZPXv24JprrsHdd98Nx3Hw7W9/G/l8Pgxpm7E66qij8NBDD+HFF19ELpfD
0NAQHnjgAZx44olYv349bNtGNptt5VdZ8cw1Vkmv/+1vf4t3vvOduOKKK/C9730PJ554IvL5PKky
LRFSSlxzzTX4j//4DxxzzDHYuHFjGH01/3v729+O22+/HXv37sX69euRSqWwY8cOnH766ejt7UU6
nabxWgJmG6tqaM9qHXv27MF1112He+65ByeeeCKOPfbY2O9pXi0v5hqvalbK3CJBBiLG1NQUvvjF
L6Kvrw/XX3899uzZg3/913/Fzp078ba3vS1xo3n66adx++2346mnnsJpp52GCy64oAVXvjr50pe+
hN7eXtxxxx0AgM9+9rOxcDagmogKIfDpT38aDz74IG644Qa88cYbeM973oN3vvOdrbjsVUkjYxXl
mWeewV133YWdO3five99L82rJcY4gt7+9rejt7cXl112GXbs2AHOVTY6Ywye58GyLFx99dX4zne+
g8suuwyvv/46Tj75ZBx++OEt/garh7nGqhras1rHeeedB9u2ceeddyb+njEW7lk0r1rPXONVzUqZ
W0xKarFOKKSU8DwPzz33HA499NDw4PbpT38ahx9+OM4///zEyNEll1yC6elpXHHFFejt7W3Fpa86
yuUybNtGoVAIm7Xeeeed+PKXv4zzzz8fRxxxBN7+9reHm0yUF154AV1dXeju7m7Fpa86FjpWX/rS
l7B7925cfPHFNK+WkCAIwkP1zMwMPvKRj+D222/H6aefjg984AP4yEc+Eo5pNb/61a8wNDRE47VE
LHSsaM9aekqlEhzHwU9+8hN85jOfwY4dO3D//ffjsccew5FHHoktW7bgyCOPjI2pgebV0rPQ8Vop
c4sEGVY5TzzxBP7u7/4OgPLY2LaNww8/HI7joFQqAVCRh/7+/vA1BqM28rnPfQ433nhjW0+EdiA6
VmazN4ftH/3oR7jrrrtw0UUXgTGGT33qU3jxxRchhKgpIt+0aRMZRovMgYyVUfa58MILcd1119G8
WgKi42U2es/zEAQBNm3aBAD44he/iOuvvx5nnXVWWChezVFHHUXjtcgcyFiZuUV71tIQHSvHcRAE
QZjK/aY3vQn33Xcftm7dip/+9KdhpkpStI/m1dJwIOO10s6DlFa3SpFS4qtf/Spuu+02vPrqqzjk
kENw5plnIgiCUJfesiwEQYDdu3eHeabGmwAg9HLPlhpEHDizjZVZmN7znvfgPe95T/g3jz76KO6+
+2789V//NcmbLiHNGCszXjSvFp964+X7PizLwv79++H7Pl5++WXceeedSKfTKBaLOO6441p96auO
ZoyVmYM0txaXemPleR4cx8Hf//3f47vf/S4+9rGPAQB+7/d+D1dffTWeeuopnHLKKS2++tVHM8Zr
pZ0HKXK0SmGMYd26dfja176GW265Bddddx183495bTjn+NWvfoV169Zh8+bNuPXWW3HppZdi3759
Lbzy1UcjY1WNbds44YQTlvAqCYDGqt2oN15mox8fH8dvf/tbfPCDH4Rt2/jud7+LZ599tm26vK8k
aKzah3pj5TgOfN/H4OBgeNAGgK6uLhSLReqv1yJovGohtbpViKkb2rx5M7LZLDZt2oTvf//72LVr
F0444QR4nhce5h544AH84Ac/wA9+8AOMjY3h05/+NNasWdPib7B6aHSsTEj7gQcewFVXXYXu7m5s
376dej8sITRW7cVc4wVUUksuvvhinHbaaejo6MCaNWuwdetW5HK5Fn+D1QONVfsw11hV16h8//vf
x1VXXYXNmzfj5JNPhmVZlO2whNB41WHJRMOJllKv54P5+bPPPiu3bNlSo0P/+c9/Xv7BH/yBfOyx
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
aMDPz69XahERuVGoORIRMRk/Pz/8/f3ZuXPneU8gGzRoEP369ePIkSPce++9ABw9erTLVZreZrVa
Xe4t6qy7us81adIkVq1a5XJPT2cHDx7Ez88PLy8v7HY7TqezR/UVFRUZzcymTZvYvn07WVlZ+Pv7
09TUhMPhMO6n6njiXIehQ4fi7+/Ptm3bLnjs7ubeWWVlJQ0NDYSGhnY55uTJk5SWlhr3OoHrnK+l
oUOHkpSUpAc7iMgtQZfViYiY0PLly8nOzqZ///4ur7u5uTF+/HjS0tJobm6mvr6erKysHv/H1tfX
l9ra2suuKyIigqqqKlpaWi6p7nPNnDmTrKwsHA7HBfeXlZUxZsyYHtXU2tpKbW0tS5cuZd++fSQn
JwNnGxB3d3cGDRrEqVOn+OCDD1zeN3jwYJfHowcHBzNgwAAyMzP5559/aG1t5cCBA1RWVvZo7s3N
zRQXFzN37lwmTZqE1Wo9b8zp06f5+eefSU5OxsfHh8mTJ1/WnHtTfHw8mZmZxsMqmpqaKCwsvOZ1
iIhcC2qORERMaNiwYTz00EMX3Pf222/j6enJuHHjmDFjBjExMTzzzDM9Ou6sWbPYunUrDoeDZcuW
XXJdvr6+hIWFsX379kuuu7Pbb7+dUaNGnbd606GgoID4+Phuj1FRUYHNZiM0NJRZs2bR3NxMTk6O
0ZTExcVhsVh49NFHmTBhAiEhIS7vnzJlCjU1Ndjtdl5++WXc3NzIyMigurqaqKgowsPDeeutt4wH
JHQ196SkJGw2G2PHjiUjI4PZs2fz3nvvuYzpeCpeWFgYCxYsYMSIEaxfv96liezJnK+G6Oho5syZ
w9y5c3n44YeJiYlh165d17wOEZFroU/71foKcxERuSXV1NSwYMECcnJyumxursSOHTvIy8sjPT29
1499pa7W3G/kOYuI3EzUHImIiIiIiKDL6kRERERERAA1RyIiIiIiIoCaIxEREREREUDNkYiIiIiI
CKDmSEREREREBFBzJCIiIiIiAqg5EhERERERAdQciYiIiIiIAPBfPwthE6RxQVIAAAAASUVORK5C
YII=
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The black points are the true data points of the vibration sensor. The blue line represents the fitted line (trend line) with the light blue portion showing the acceptable variance.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Evaluation-on-Test-Data-(Unseen,-Fault-Data)">Evaluation on Test Data (Unseen, Fault Data)<a class="anchor-link" href="#Evaluation-on-Test-Data-(Unseen,-Fault-Data)">&#182;</a></h2><p>Finally, the moment of truth!</p>
<p>Can the model developed above detect faulty machine condition. To evaluate this, the fault portion of the data is fed into the model.</p>
<p>Note that this data has not been seen by the model during training stage.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">prophet_faultydata</span> <span class="o">=</span> <span class="n">merged_data</span><span class="p">[</span><span class="s1">&#39;2004-02-15 23:22:39&#39;</span><span class="p">:</span><span class="s1">&#39;2004-02-16 23:52:39&#39;</span><span class="p">][</span><span class="s1">&#39;Bearing 1&#39;</span><span class="p">]</span>
<span class="n">prophet_faultydata</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>

<span class="n">prophet_faulty_test</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span>

<span class="n">prophet_faulty_test</span><span class="p">[</span><span class="s1">&#39;ds&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">prophet_faultydata</span><span class="o">.</span><span class="n">index</span>
<span class="c1">#pd.to_datetime(prophet_healthy.index, format=&#39;%Y.%m.%d.%H.%M.%S&#39;)</span>
<span class="n">prophet_faulty_test</span><span class="p">[</span><span class="s1">&#39;y&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">prophet_faultydata</span><span class="o">.</span><span class="n">values</span>

<span class="n">forecast</span> <span class="o">=</span> <span class="n">m</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">prophet_faulty_test</span><span class="p">)</span>
<span class="n">forecast</span><span class="p">[</span><span class="s1">&#39;fact&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">prophet_faulty_test</span><span class="p">[</span><span class="s1">&#39;y&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">drop</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Displaying Prophet plot&#39;</span><span class="p">)</span>
<span class="n">fig1</span> <span class="o">=</span> <span class="n">m</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">forecast</span><span class="p">)</span>
<span class="n">fig1</span> <span class="o">=</span> <span class="n">prophet_faultydata</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">12</span><span class="p">,</span><span class="mi">6</span><span class="p">),</span><span class="n">title</span><span class="o">=</span><span class="s2">&quot;Fit of Test/Unseen/Fault Data&quot;</span><span class="p">)</span>
<span class="n">fig1</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">xlabel</span><span class="o">=</span><span class="s2">&quot;Month (MM)-Date(DD) Time&quot;</span><span class="p">,</span> <span class="n">ylabel</span><span class="o">=</span><span class="s2">&quot;Vibration/Acceleration(g)&quot;</span><span class="p">)</span>
<span class="n">fig1</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="mf">731626.875</span><span class="p">,</span><span class="mf">0.057</span><span class="p">,</span><span class="s1">&#39;Expected/Predicted&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">14</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;r&#39;</span><span class="p">)</span>
<span class="n">fig1</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="mf">731626.875</span><span class="p">,</span><span class="mf">0.075</span><span class="p">,</span><span class="s1">&#39;Actual/Faulty Data&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">14</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;r&#39;</span><span class="p">)</span>
<span class="n">fig1</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="mf">731624.875</span><span class="p">,</span><span class="mf">0.057</span><span class="p">,</span><span class="s1">&#39;Actual/Healthy&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">14</span><span class="p">,</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;r&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Displaying Prophet plot
</pre>
</div>
</div>

<div class="output_area">

<div class="prompt output_prompt">Out[0]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(731624.875, 0.057, &#39;Actual/Healthy&#39;)</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The black points are the true data points of the vibration sensor. The blue line represents the expected values from 2004-02-15, 23:42:39  with the light blue portion showing the acceptable variance.</p>
<p>Clearly, the values are higher than the predicted values and an alarm can be sounded.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[0]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Healper functions to annotate the graph.</span>
<span class="nb">print</span><span class="p">(</span><span class="n">fig1</span><span class="o">.</span><span class="n">get_xticks</span><span class="p">())</span>
<span class="nb">print</span><span class="p">(</span><span class="n">fig1</span><span class="o">.</span><span class="n">get_yticks</span><span class="p">())</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>[731623.875 731624.375 731624.875 731625.375 731625.875 731626.375
 731626.875 731627.375 731627.875]
[0.055 0.06  0.065 0.07  0.075 0.08  0.085]
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Conclusion">Conclusion<a class="anchor-link" href="#Conclusion">&#182;</a></h1><p>By analysing past trends of healthy, the model learns the expected trend with acceptable variance (hyperparameter).The trained model predicts the trends for the future and if any deviation is observed, an alarm can be raised.</p>
<p>The same principle hold true for analysing multiple signal (multi-dimensional) at a time and creating a single metric like, the "health score" of a machine.</p>
<p>Using such predictive maintenace strategies, one can find the earliest stages of damage and reduce operating costs. Rather than shutting down equipment for scheduled preventive maintenance routines, maintenance can be planned to match convenient schedules and improve reliability. Predictive maintenance uses sensors, machine learning, and advanced algorithms to detect faults and predict failure. Connecting to the Industrial Internet of Things (IIoT) enables access to historical baseline data while building the statistical and trend analyses that point to why and where problems occur and what actions are needed.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="References">References<a class="anchor-link" href="#References">&#182;</a></h1><ol>
<li><a href="https://www.plantengineering.com/articles/roller-bearings-and-predictive-analytics/">https://www.plantengineering.com/articles/roller-bearings-and-predictive-analytics/</a></li>
<li><a href="https://towardsdatascience.com/how-to-use-machine-learning-for-anomaly-detection-and-condition-monitoring-6742f82900d7">https://towardsdatascience.com/how-to-use-machine-learning-for-anomaly-detection-and-condition-monitoring-6742f82900d7</a></li>
<li><a href="https://iot.ieee.org/images/files/pdf/phm2017/06-19-2017-Rick-Durham_IEEE-PHM_Presentation20170610.pdf">https://iot.ieee.org/images/files/pdf/phm2017/06-19-2017-Rick-Durham_IEEE-PHM_Presentation20170610.pdf</a></li>
<li><a href="https://facebook.github.io/prophet/docs/quick_start.html">https://facebook.github.io/prophet/docs/quick_start.html</a></li>
</ol>

</div>
</div>
</div>
    </div>
  </div>
</body>

 


</html>
