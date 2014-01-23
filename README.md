#SVG Crowbar

A fork of [NYTimes SVG-Crowbar](http://nytimes.github.com/svg-crowbar/), this is a standalone client script instead of a Chrome-specific bookmarklet. Instead of bookmarking a script, it is loaded with the document and can be used to give the user the option to download a graphic. For more information, see the [original version](http://nytimes.github.com/svg-crowbar/). Requires [d3.js](http://d3js.org).

Check out [the example](http://jczaplew.github.io/svg-crowbar). Only works in Chrome and Firefox.

## Usage
````crowbar.getSvg("#targetSvg")```` or ````crowbar.getSvg(".targetSvg")````