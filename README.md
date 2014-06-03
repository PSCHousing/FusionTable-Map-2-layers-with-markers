FusionTable-Map-2-layers-with-markers
=====================================
See live demo at: http://PSCHousing.github.io/FusionTable-Map-2-layers-with-markers

Credit to @veronicaxarmendariz

Use this template if you wish to create a Search-and-Filter map that turns on/off at least 2 layers (points and polygons), draws data from Google Fusion Tables, AND uses up to 10 point markers (5 large, 5 small). The default point map displays a textual legend (A, B, C), with option to switch to numeric (0-100) values. Based on template customized by Derek Eder http://derekeder.com/searchable_map_template/

Basic steps:

1) Use Google Fusion Tables to create your point and polygon map layers, and change the feature styles (set ranges, colors, etc.) and info windows.

2) Make your own copy of this template: either Fork to your own GitHub account, or Clone in Desktop, or Download a ZIP compressed version to your desktop.

3) Modify two files, following instructions in the code comments, to match your Google Fusion Table data:

- index.html
- maps_lib.js (located inside the js folder)

3) Host everything on the web (such as a GitHub repository gh-pages branch)

Learn more in an open-access Data Visualization book-in-progress by Jack Dougherty at Trinity College CT
http://epress.trincoll.edu/dataviz

TO DO: 
* change legend to closely resemble small markers
* add reminder that the Google Fusion Table structure (e.g. Program Type variables) must match EXACTLY the js code
* change image labels to match exact wording in Google Fusion Table feature style options (large_red, small_yellow, etc.)
* add polygon legend on index.html, similar to http://chicagobuildings.org/

