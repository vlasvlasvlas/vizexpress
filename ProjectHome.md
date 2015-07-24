## What is the problem we are trying to solve? ##
Tables and Graphs are effective visualizations for presenting data. However, generating them in wiki pages requires time, effort, and complicated syntax. This becomes more problematic if you have large sets of data, or if you want more customized visualizations. Hence, we decided to make vizExpress.


## What is vizExpress? ##
vizExpress is a Mediawiki extensions that allows users to create highly customized tables and graphs quickly and easily. vizExpress features a simple, excel-like wizard that can be accessed through a button in the editing toolbar. When you start the vizExpress wizard, you can:

Indent lists 2 spaces:
  * Provide data by typing it, copying and pasting it from another source, or by browsing to an existing Excel or CSV file.
  * Choose one of eight graph types.
  * Choose one of seven pre-defined color schemes, or simply make your own scheme.
  * Apply further options such as titles, graph size, legend position, etc..
  * Preview the graph before inserting it.

Once you have the graph in your wiki page, you can:
  * Allow users to download the graph data as a csv file.
  * Edit the graph easily by restarting the wizard again.

You can visit [this page](http://www.cs.toronto.edu:40154/mediawiki/index.php/VizExpress) to see examples of graphs created by vizExpress.
## Installation ##
  1. Download [vizExpress.rar](http://code.google.com/p/vizexpress/downloads/list) and extract it to your /your MediaWiki installation directory/extensions.
  1. Add the following to LocalSettings.php: require\_once("$IP/extensions/vizExpress/vizExpress.php");



More about vizExpress can be found [here](http://www.mediawiki.org/wiki/Extension:VizExpress)