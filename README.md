# webview-tile-template
Template of webview tile for fast development start

WebView tile is a simple single page "website" that consists of bunch of HTML, CSS and JavaScript. Absolute mininum files for tile are:
- index.html (entry point)
- manifest.json (tile description file)
- icon.svg (icon of your tile to show on dashboard)

This template also includes default folder and file structure, plus additional nexpaq related files to make your developement process easier and faster. Clone or fork this repository and start your development. Everyone is also welcome to contribute and improve this template, just do a pull request.

File structure:
- css - folder to store your styles
  - normilize.css - makes styles same in all browsers
  - styles.css - root file for your custom styles with few helpful initial styles
- fonts - folder to store your non-standard fonts or icon fonts
- img - folder to store your images, content releated sub-folders adviced
- js - folder to keep you JavaScript
  - NexpaqHeader.js - script that can create standard header for tile which will automatically adapt it's appeareance to match platform
  - scripts.js - root file for your custom scripts
- vendor - folder to store third party libraries, styles, etc...
- icon.svg - tile to be displayed at dashboard
- index.html - main html file of your tile
- manifest.json - description of your tile, you can read more about manifests here (TODO: add link to manifest generator)  