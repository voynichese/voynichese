## About the project ##

The Voynichese project provides an open-source [Query Viewer](http://www.voynichese.com) and [DataSets](DataSets.md) to aid researchers in the study of the Voynich Manuscript.

If you'd like to learn more about the manuscript itself, see the following resources:
<br>
<a href='http://en.wikipedia.org/wiki/Voynich_manuscript'>http://en.wikipedia.org/wiki/Voynich_manuscript</a>
<br>
<a href='http://www.voynich.nu/'>http://www.voynich.nu/</a>

If you're performing analysis of the manuscript and would like to use the project's enhanced transcription, see <a href='DataSets.md'>this page</a>.<br>
<br>
<h2>Getting Started</h2>

To get started with the query tool, point your browser to <a href='http://www.voynichese.com'>http://www.voynichese.com</a>. When loaded, the application renders a grid containing 225 of the VM's folios, upon which query results are rendered.<br>
<br>
Note that the 225 folios exclude folios f85v/f86r, also known as the <i>Nine Rosettes</i> page. If you'd like to study that particular folio, see the following resources:<br>
<br>
<a href='http://brbl-zoom.library.yale.edu/viewer/1006231'>http://brbl-zoom.library.yale.edu/viewer/1006231</a>
<br>
<a href='https://www.jasondavies.com/voynich/#Ros2/0.501/0.501/1.00'>https://www.jasondavies.com/voynich/#Ros2/0.501/0.501/1.00</a>

<h2>Browsing Folios</h2>

The 225 available folios are interactive - clicking on a specific folio cell produces an enlarged version. Within the enlarged folios each individual word is also selectable. Upon selecting a given word, a query is automatically performed to highlight all of its occurrences.<br>
<br>
Note that only exact matches are highlighted. For example, selecting the word <i>daiin</i> matches all occurrences of <i>daiin</i> exactly, excluding other words containing <i>daiin</i>, such as <i>cheodaiin</i>. To perform an inexact version of the query, ensure that the <i>Exact</i> option (with the <img src='http://wiki.voynichese.googlecode.com/git/bullseye.png' /> icon) is unselected.<br>
<br>
<h2>Application Bars</h2>

The application's graphical user interface relies upon a collection of horizontal bars for acquiring user input, displaying information or specifying configuration settings.<br>
<br>
At the bottom is the main character bar.<br>
<br>
<h3>Character Bar</h3>
<p align='center'><img src='http://wiki.voynichese.googlecode.com/git/character_bar.png' /></p>

Use the character bar to assemble a query. Clicking on each character button appends or inserts the corresponding character at the active cursor position within the query input box.<br>
<br>
Note that the asterisk is a special character that matches one or more characters - for more information see <a href='QueryBasics.md'>QueryBasics</a>.<br>
<br>
The character bar contains two additional buttons, for displaying configuration options and active queries.<br>
<br>
<h3>Input Bar</h3>
<p align='center'><img src='http://wiki.voynichese.googlecode.com/git/input_bar.png' width='500px' /></p>

Use the input bar to enter and configure a query. When then the <i>Exact</i> <img src='http://wiki.voynichese.googlecode.com/git/bullseye.png' /> option is selected, partial matches are ignored. For more information see <a href='QueryBasics.md'>QueryBasics</a>

Click the pencil button, or press enter, to render and persist the active query with a distinct color.<br>
<br>
The input bar also displays a brief description of the query results, including the total number of word matches and a sample of the containing folios - click a folio name to locate the corresponding folio cell.<br>
<br>
<h3>Color Bar</h3>
<p align='center'><img src='http://wiki.voynichese.googlecode.com/git/color_bar.png' /></p>

The color bar allows you to select one of the 32 supported query colors. Select a value to preview the query results using the corresponding color and click the accept button to persist the query.<br>
<br>
<h3>Query Bar</h3>
<p align='center'><img src='http://wiki.voynichese.googlecode.com/git/query_bar.png' /></p>

The query bar lists the set of persistent queries. Persistent queries remain even as selection changes and are assigned custom colors.<br>
<br>
<h3>Chart Bar</h3>
<p align='center'><img src='http://wiki.voynichese.googlecode.com/git/chart_bar.png' /></p>

The chart bar is accessible by clicking the chart button in the input bar.<br>
<br>
The chart bar's top row displays a bar chart reflecting the distribution of the query matches throughout the 225 folios. Hover the mouse cursor over a specific column to display the number of matches within the corresponding folio - click the column to locate the folio cell.<br>
<br>
The chart bar's bottom row lists a set of quantities detailing the query results. Use the percentage button to toggle between absolute and percentage values. For more information see the <a href='QueryResults.md'>QueryResults</a> page.<br>
<br>
<h3>Share Bar</h3>
<p align='center'><img src='http://wiki.voynichese.googlecode.com/git/share_bar.png' /></p>

The share bar is accessible by clicking the share button in the input bar. The share bar enables you to publish a query to popular social sites and obtain minified URLs for your queries.<br>
<br>
<h3>Options Bar</h3>
<p align='center'><img src='http://wiki.voynichese.googlecode.com/git/options_bar.png' /></p>

The options bar lists the following configuration settings.<br>
<br>
<h4>A Folios & B Folios</h4>
Indicates whether A or B folios should be displayed. To learn more about the A and B folio classification, see <a href='http://voynich.nu/writing.html#hands'>Currier's hands</a>.<br>
<br>
<h4>Unique Words</h4>
Specifies whether an overlay should be rendered that highlights words that occur exactly once in the manuscript.<br>
<br>
<h4>Word Density</h4>
Specifies whether an overlay should be rendered  that highlights words using a color scale that reflects each word's occurrence in the manuscript - the darker the color the more common the word is.<br>
<br>
<h4>High Contrast</h4>
Indicates whether folio images should be rendered with high contrast. High contrast helps increase the visibility of certain folio features.<br><i>Note: currently only supported in Chrome and Safari web browsers.</i>

<h4>Invert Colors</h4>
Indicates whether folio images should be rendered with inverted colors, resulting in a darker background color that some users may find more comfortable.<br><i>Note: currently only supported in Chrome and Safari web browsers.</i>

<h4>Color Cells</h4>
Specifies whether folio cells should render in color, instead of black & white. Folio cells render in monochrome by default in order to accentuate query results.<br>
<br>
<h4>Color Folios</h4>
Specifies whether enlarged folios should render in color, instead of black & white.<br><i>Note: currently only supported in Chrome and Safari web browsers.</i>
