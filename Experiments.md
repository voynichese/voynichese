The Voynichese query viewer supports custom query overlays. Use the links below to view these custom queries.

<a href="#information-bits">Information Bits</a><br>
<a href="#diverse-words">Diverse Words</a><br>
<a href="#wrapped-words">Wrapped Words</a><br>
<a href="#palindromes">Palindromes</a><br>
<a href="#word-grids">Word Grids</a><br>
<a href="#word-graphs">Word Graphs</a><br>
<a href="#label-words">Label Words</a><br>
<a href="#initial--final-words">Initial &amp; Final Words</a><br>
<a href="#split-words">Split Words</a><br>
<a href="#recurring-word-sequences">Recurring Word Sequences</a><br>
<a href="#word-lengths">Word Lengths</a><br>
<a href="#superfluous-characters">Superfluous Characters</a><br>
<a href="#variants">Variants</a><br>
<a href="#folio--paragraphs-contents">Folio &amp; Paragraph Contents</a><br>
<a href="#character-substitutions">Character Substitutions</a><br>

## Information Bits ##
The following is a heat map of the amount of information bits per word, with the darker colors assigned to the words with the most information:<br>
<a href='http://www.voynichese.com/#/lay:word-bits'>http://www.voynichese.com/#/lay:word-bits</a><br>

The number of bits per word is given by the log (base-2) of the word's associated probability. The probability of a word in the text has been computed as the product of the conditional probabilities of its characters. E.g.:

<i>p(daiin) = p(d) * p(a|d) * p(i|da) * p(i|dai) * p(n|daii) * p(&lt;space&gt;|daiin)</i>

## Diverse Words ##
The following queries highlight all words (with minimum size of five, six and seven characters) which do not contain repeated characters.

http://www.voynichese.com/#/lay:word-five-diverse<br>
<a href='http://www.voynichese.com/#/lay:word-six-diverse'>http://www.voynichese.com/#/lay:word-six-diverse</a><br>
<a href='http://www.voynichese.com/#/lay:word-seven-diverse'>http://www.voynichese.com/#/lay:word-seven-diverse</a><br>

<h2>Wrapped Words</h2>
The following query highlights in red all words that occur across a line boundary with unwrapped occurrences highlighted in blue.<br>
<br>
<a href='http://www.voynichese.com/#/lay:word-wraps'>http://www.voynichese.com/#/lay:word-wraps</a>

<h2>Palindromes</h2>
The following query highlights words that read the same backward or forward.<br>
<br>
<a href='http://www.voynichese.com/#/lay:word-palindromes'>http://www.voynichese.com/#/lay:word-palindromes</a>

<h2>Word Grids</h2>
All words that differ from EVA <i>chedy</i> by one character insertion, removal or replacement, sorted:<br>
<a href='http://www.voynichese.com/sample/chedy-variants.jpg'>View Image</a> (2.7Mb size)<br>
<br>
All words beginning with EVA 'p' or 'f', sorted without distinguishing 'p' from 'f':<br>
<a href='http://www.voynichese.com/sample/pf-words.jpg'>View Image</a> (1.8Mb size)<br>
<br>
All words beginning with EVA 't' or 'k', sorted without distinguishing 't' from 'k':<br>
<a href='http://www.voynichese.com/sample/tk-words.jpg'>View Image</a> (7.2Mb size)<br>
<br>
All words containing 'cXh', where X is 'p', 'f', 'k' or 't', sorted without distinguishing 'p' from 'f' or 'k' from 't':<br>
<a href='http://www.voynichese.com/sample/cxh-words.jpg'>View Image</a> (8.6Mb size)<br>
<br>
All words containing 'iiin':<br>
<a href='http://www.voynichese.com/sample/iiin-words.jpg'>View Image</a> (237Kb size)<br>
<br>
All words containing 'in' (excluding 'iiin' and 'iin'):<br>
<a href='http://www.voynichese.com/sample/in-words.jpg'>View Image</a> (5.4Mb size)<br>
<br>
All words containing 'an':<br>
<a href='http://www.voynichese.com/sample/an-words.jpg'>View Image</a> (260Kb size)<br>
<br>
<h2>Word Graphs</h2>
In the following graphs, nodes represent a word in the Voynich vocabulary.<br>
<br>
The color assigned to each node indicates the frequency of the respective word in the text, with white nodes having the lowest occurrence count.<br>
<br>
Two nodes are connected if their respective words differ by at most one insertion, deletion or replacement.<br>
<br>
Voynich words:<br>
<a href='http://www.voynichese.com/sample/vm-word-graph.png'>View Image</a> (3.11Mb)<br>
<br>
Voynich words - No Edges:<br>
<a href='http://www.voynichese.com/sample/vm-word-graph-noedges.png'>View Image</a> (2.35Mb)<br>
<br>
Voynich words with 6 or more characters:<br>
<a href='http://www.voynichese.com/sample/vm-word-graph-sixers.png'>View Image</a> (4.25Mb)<br>
<br>
Voynich words with 6 or more characters - No Edges:<br>
<a href='http://www.voynichese.com/sample/vm-word-graph-sixers-noedges.png'>View Image</a> (2.42Mb)<br>
<br>
For contrast, consider the same graphs for Dante's Divine Comedy (in Italian).<br>
<br>
Dante's words:<br>
<a href='http://www.voynichese.com/sample/dante-word-graph.png'>View Image</a> (5.51Mb)<br>
<br>
Dante's words - No Edges:<br>
<a href='http://www.voynichese.com/sample/dante-word-graph-noedges.png'>View Image</a> (3.09Mb)<br>
<br>
Dante's words with 6 or more characters:<br>
<a href='http://www.voynichese.com/sample/dante-word-graph-sixers.png'>View Image</a> (3.64Mb)<br>
<br>
<h2>Label Words</h2>
The following query highlights all labels, where a label is a word that occurs by itself in the text, according to the EVA transcription.<br>
<br>
The actual labels are highlighted in green, with all other occurrences highlighted in blue. For example, the label <i>okchoy</i>, at the center of folio f57v, is highlighted in green, whereas the occurrence of <i>okchoy</i> in the second paragraph of f1r is highlighted in blue.<br>
<br>
All labels: <a href='http://www.voynichese.com/#/lay:label-words'>http://www.voynichese.com/#/lay:label-words</a><br>

Folio f1r (2 labels): <a href='http://www.voynichese.com/#/lay:f1r-labels/f1r'>http://www.voynichese.com/#/lay:f1r-labels/f1r</a><br>
Folio f8r (1 label): <a href='http://www.voynichese.com/#/lay:f8r-labels/f8r'>http://www.voynichese.com/#/lay:f8r-labels/f8r</a><br>
Folio f8v (1 label): <a href='http://www.voynichese.com/#/lay:f8v-labels/f8v'>http://www.voynichese.com/#/lay:f8v-labels/f8v</a><br>
Folio f24r (1 label): <a href='http://www.voynichese.com/#/lay:f24r-labels/f24r'>http://www.voynichese.com/#/lay:f24r-labels/f24r</a><br>
Folio f27r (1 label): <a href='http://www.voynichese.com/#/lay:f27r-labels/f27r'>http://www.voynichese.com/#/lay:f27r-labels/f27r</a><br>
Folio f37v (1 label): <a href='http://www.voynichese.com/#/lay:f37v-labels/f37v'>http://www.voynichese.com/#/lay:f37v-labels/f37v</a><br>
Folio f41v (1 label): <a href='http://www.voynichese.com/#/lay:f41v-labels/f41v'>http://www.voynichese.com/#/lay:f41v-labels/f41v</a><br>
Folio f49v (20 labels): <a href='http://www.voynichese.com/#/lay:f49v-labels/f49v'>http://www.voynichese.com/#/lay:f49v-labels/f49v</a><br>
Folio f57v (8 labels): <a href='http://www.voynichese.com/#/lay:f57v-labels/f57v'>http://www.voynichese.com/#/lay:f57v-labels/f57v</a><br>
Folio f66r (47 labels): <a href='http://www.voynichese.com/#/lay:f66r-labels/f66r'>http://www.voynichese.com/#/lay:f66r-labels/f66r</a><br>
Folio f67r1 (7 labels): <a href='http://www.voynichese.com/#/lay:f67r1-labels/f67r1'>http://www.voynichese.com/#/lay:f67r1-labels/f67r1</a><br>
Folio f67r2 (27 labels): <a href='http://www.voynichese.com/#/lay:f67r2-labels/f67r2'>http://www.voynichese.com/#/lay:f67r2-labels/f67r2</a><br>
Folio f67v1 (9 labels): <a href='http://www.voynichese.com/#/lay:f67v1-labels/f67v1'>http://www.voynichese.com/#/lay:f67v1-labels/f67v1</a><br>
Folio f67v2 (2 labels): <a href='http://www.voynichese.com/#/lay:f67v2-labels/f67v2'>http://www.voynichese.com/#/lay:f67v2-labels/f67v2</a><br>
Folio f68r1 (32 labels): <a href='http://www.voynichese.com/#/lay:f68r1-labels/f68r1'>http://www.voynichese.com/#/lay:f68r1-labels/f68r1</a><br>
Folio f68r2 (23 labels): <a href='http://www.voynichese.com/#/lay:f68r2-labels/f68r2'>http://www.voynichese.com/#/lay:f68r2-labels/f68r2</a><br>
Folio f68r3 (8 labels): <a href='http://www.voynichese.com/#/lay:f68r3-labels/f68r3'>http://www.voynichese.com/#/lay:f68r3-labels/f68r3</a><br>
Folio f68v1 (1 label): <a href='http://www.voynichese.com/#/lay:f68v1-labels/f68v1'>http://www.voynichese.com/#/lay:f68v1-labels/f68v1</a><br>
Folio f68v3 (2 labels): <a href='http://www.voynichese.com/#/lay:f68v3-labels/f68v3'>http://www.voynichese.com/#/lay:f68v3-labels/f68v3</a><br>
Folio f69r (8 labels): <a href='http://www.voynichese.com/#/lay:f69r-labels/f69r'>http://www.voynichese.com/#/lay:f69r-labels/f69r</a><br>
Folio f69v (22 labels): <a href='http://www.voynichese.com/#/lay:f69v-labels/f69v'>http://www.voynichese.com/#/lay:f69v-labels/f69v</a><br>
Folio f70r1 (7 labels): <a href='http://www.voynichese.com/#/lay:f70r1-labels/f70r1'>http://www.voynichese.com/#/lay:f70r1-labels/f70r1</a><br>
Folio f70v1 (8 labels): <a href='http://www.voynichese.com/#/lay:f70v1-labels/f70v1'>http://www.voynichese.com/#/lay:f70v1-labels/f70v1</a><br>
Folio f70v2 (21 labels): <a href='http://www.voynichese.com/#/lay:f70v2-labels/f70v2'>http://www.voynichese.com/#/lay:f70v2-labels/f70v2</a><br>
Folio f71r (11 labels): <a href='http://www.voynichese.com/#/lay:f71r-labels/f71r'>http://www.voynichese.com/#/lay:f71r-labels/f71r</a><br>
Folio f71v (9 labels): <a href='http://www.voynichese.com/#/lay:f71v-labels/f71v'>http://www.voynichese.com/#/lay:f71v-labels/f71v</a><br>
Folio f72r1 (7 labels): <a href='http://www.voynichese.com/#/lay:f72r1-labels/f72r1'>http://www.voynichese.com/#/lay:f72r1-labels/f72r1</a><br>
Folio f72r2 (26 labels): <a href='http://www.voynichese.com/#/lay:f72r2-labels/f72r2'>http://www.voynichese.com/#/lay:f72r2-labels/f72r2</a><br>
Folio f72r3 (17 labels): <a href='http://www.voynichese.com/#/lay:f72r3-labels/f72r3'>http://www.voynichese.com/#/lay:f72r3-labels/f72r3</a><br>
Folio f72v1 (29 labels): <a href='http://www.voynichese.com/#/lay:f72v1-labels/f72v1'>http://www.voynichese.com/#/lay:f72v1-labels/f72v1</a><br>
Folio f72v2 (27 labels): <a href='http://www.voynichese.com/#/lay:f72v2-labels/f72v2'>http://www.voynichese.com/#/lay:f72v2-labels/f72v2</a><br>
Folio f72v3 (24 labels): <a href='http://www.voynichese.com/#/lay:f72v3-labels/f72v3'>http://www.voynichese.com/#/lay:f72v3-labels/f72v3</a><br>
Folio f73r (28 labels): <a href='http://www.voynichese.com/#/lay:f73r-labels/f73r'>http://www.voynichese.com/#/lay:f73r-labels/f73r</a><br>
Folio f73v (29 labels): <a href='http://www.voynichese.com/#/lay:f73v-labels/f73v'>http://www.voynichese.com/#/lay:f73v-labels/f73v</a><br>
Folio f75r (4 labels): <a href='http://www.voynichese.com/#/lay:f75r-labels/f75r'>http://www.voynichese.com/#/lay:f75r-labels/f75r</a><br>
Folio f75v (28 labels): <a href='http://www.voynichese.com/#/lay:f75v-labels/f75v'>http://www.voynichese.com/#/lay:f75v-labels/f75v</a><br>
Folio f76r (9 labels): <a href='http://www.voynichese.com/#/lay:f76r-labels/f76r'>http://www.voynichese.com/#/lay:f76r-labels/f76r</a><br>
Folio f77r (10 labels): <a href='http://www.voynichese.com/#/lay:f77r-labels/f77r'>http://www.voynichese.com/#/lay:f77r-labels/f77r</a><br>
Folio f77v (6 labels): <a href='http://www.voynichese.com/#/lay:f77v-labels/f77v'>http://www.voynichese.com/#/lay:f77v-labels/f77v</a><br>
Folio f78r (5 labels): <a href='http://www.voynichese.com/#/lay:f78r-labels/f78r'>http://www.voynichese.com/#/lay:f78r-labels/f78r</a><br>
Folio f80r (10 labels): <a href='http://www.voynichese.com/#/lay:f80r-labels/f80r'>http://www.voynichese.com/#/lay:f80r-labels/f80r</a><br>
Folio f82r (11 labels): <a href='http://www.voynichese.com/#/lay:f82r-labels/f82r'>http://www.voynichese.com/#/lay:f82r-labels/f82r</a><br>
Folio f82v (13 labels): <a href='http://www.voynichese.com/#/lay:f82v-labels/f82v'>http://www.voynichese.com/#/lay:f82v-labels/f82v</a><br>
Folio f83r (4 labels): <a href='http://www.voynichese.com/#/lay:f83r-labels/f83r'>http://www.voynichese.com/#/lay:f83r-labels/f83r</a><br>
Folio f83v (4 labels): <a href='http://www.voynichese.com/#/lay:f83v-labels/f83v'>http://www.voynichese.com/#/lay:f83v-labels/f83v</a><br>
Folio f84r (11 labels): <a href='http://www.voynichese.com/#/lay:f84r-labels/f84r'>http://www.voynichese.com/#/lay:f84r-labels/f84r</a><br>
Folio f84v (10 labels): <a href='http://www.voynichese.com/#/lay:f84v-labels/f84v'>http://www.voynichese.com/#/lay:f84v-labels/f84v</a><br>
Folio f85r2 (1 label): <a href='http://www.voynichese.com/#/lay:f85r2-labels/f85r2'>http://www.voynichese.com/#/lay:f85r2-labels/f85r2</a><br>
Folio f88r (14 labels): <a href='http://www.voynichese.com/#/lay:f88r-labels/f88r'>http://www.voynichese.com/#/lay:f88r-labels/f88r</a><br>
Folio f88v (12 labels): <a href='http://www.voynichese.com/#/lay:f88v-labels/f88v'>http://www.voynichese.com/#/lay:f88v-labels/f88v</a><br>
Folio f89r1 (11 labels): <a href='http://www.voynichese.com/#/lay:f89r1-labels/f89r1'>http://www.voynichese.com/#/lay:f89r1-labels/f89r1</a><br>
Folio f89r2 (16 labels): <a href='http://www.voynichese.com/#/lay:f89r2-labels/f89r2'>http://www.voynichese.com/#/lay:f89r2-labels/f89r2</a><br>
Folio f89v1 (5 labels): <a href='http://www.voynichese.com/#/lay:f89v1-labels/f89v1'>http://www.voynichese.com/#/lay:f89v1-labels/f89v1</a><br>
Folio f89v2 (15 labels): <a href='http://www.voynichese.com/#/lay:f89v2-labels/f89v2'>http://www.voynichese.com/#/lay:f89v2-labels/f89v2</a><br>
Folio f99r (33 labels): <a href='http://www.voynichese.com/#/lay:f99r-labels/f99r'>http://www.voynichese.com/#/lay:f99r-labels/f99r</a><br>
Folio f99v (22 labels): <a href='http://www.voynichese.com/#/lay:f99v-labels/f99v'>http://www.voynichese.com/#/lay:f99v-labels/f99v</a><br>
Folio f100r (16 labels): <a href='http://www.voynichese.com/#/lay:f100r-labels/f100r'>http://www.voynichese.com/#/lay:f100r-labels/f100r</a><br>
Folio f100v (11 labels): <a href='http://www.voynichese.com/#/lay:f100v-labels/f100v'>http://www.voynichese.com/#/lay:f100v-labels/f100v</a><br>
Folio f101v2 (17 labels): <a href='http://www.voynichese.com/#/lay:f101v2-labels/f101v2'>http://www.voynichese.com/#/lay:f101v2-labels/f101v2</a><br>
Folio f102r1 (4 labels): <a href='http://www.voynichese.com/#/lay:f102r1-labels/f102r1'>http://www.voynichese.com/#/lay:f102r1-labels/f102r1</a><br>
Folio f102r2 (5 labels): <a href='http://www.voynichese.com/#/lay:f102r2-labels/f102r2'>http://www.voynichese.com/#/lay:f102r2-labels/f102r2</a><br>
Folio f102v1 (8 labels): <a href='http://www.voynichese.com/#/lay:f102v1-labels/f102v1'>http://www.voynichese.com/#/lay:f102v1-labels/f102v1</a><br>
Folio f102v2 (21 labels): <a href='http://www.voynichese.com/#/lay:f102v2-labels/f102v2'>http://www.voynichese.com/#/lay:f102v2-labels/f102v2</a><br>
Folio f114r (1 label): <a href='http://www.voynichese.com/#/lay:f114r-labels/f114r'>http://www.voynichese.com/#/lay:f114r-labels/f114r</a><br>

<h2>Initial & Final Words</h2>
The following queries highlight the sets of words that occur at the start or end of folios, paragraphs and lines.<br>
<a href='http://www.voynichese.com/#/lay:folio-start-words'>http://www.voynichese.com/#/lay:folio-start-words</a><br>
<a href='http://www.voynichese.com/#/lay:folio-end-words'>http://www.voynichese.com/#/lay:folio-end-words</a><br>
<a href='http://www.voynichese.com/#/lay:paragraph-start-words'>http://www.voynichese.com/#/lay:paragraph-start-words</a><br>
<a href='http://www.voynichese.com/#/lay:paragraph-end-words'>http://www.voynichese.com/#/lay:paragraph-end-words</a><br>
<a href='http://www.voynichese.com/#/lay:line-start-words'>http://www.voynichese.com/#/lay:line-start-words</a><br>
<a href='http://www.voynichese.com/#/lay:line-end-words'>http://www.voynichese.com/#/lay:line-end-words</a><br>

<h2>Split Words</h2>
The following query highlights all word pairs that also occur as a single word in the manuscript. The first word of each such pair is highlighted in green, the second in blue.<br>
<br>
<a href='http://www.voynichese.com/#/lay:split-words'>http://www.voynichese.com/#/lay:split-words</a>

<h2>Recurring Word Sequences</h2>
The following queries highlight word sequences that occur more than once in the manuscript - ignoring line and paragraph boundaries.<br>
<br>
In the plots, each individual word is highlighted if it forms a recurring sequence with its left or right adjacent words - green indicates that the word is the first of the recurring sequence. Separate plots are provided for recurring sequences of two, three or four consecutive words.<br>
<br>
<a href='http://www.voynichese.com/#/lay:word-pairs'>http://www.voynichese.com/#/lay:word-pairs</a><br>
<a href='http://www.voynichese.com/#/lay:word-triplets'>http://www.voynichese.com/#/lay:word-triplets</a><br>
<a href='http://www.voynichese.com/#/lay:word-quads'>http://www.voynichese.com/#/lay:word-quads</a><br>

<h2>Word Lengths</h2>
The following queries highlight words by size.<br>
<br>
<a href='http://www.voynichese.com/#/lay:words-length-1'>http://www.voynichese.com/#/lay:words-length-1</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-2'>http://www.voynichese.com/#/lay:words-length-2</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-3'>http://www.voynichese.com/#/lay:words-length-3</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-4'>http://www.voynichese.com/#/lay:words-length-4</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-5'>http://www.voynichese.com/#/lay:words-length-5</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-6'>http://www.voynichese.com/#/lay:words-length-6</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-7'>http://www.voynichese.com/#/lay:words-length-7</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-8'>http://www.voynichese.com/#/lay:words-length-8</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-9'>http://www.voynichese.com/#/lay:words-length-9</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-10'>http://www.voynichese.com/#/lay:words-length-10</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-11'>http://www.voynichese.com/#/lay:words-length-11</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-12'>http://www.voynichese.com/#/lay:words-length-12</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-13'>http://www.voynichese.com/#/lay:words-length-13</a><br>
<a href='http://www.voynichese.com/#/lay:words-length-14'>http://www.voynichese.com/#/lay:words-length-14</a><br>

<h2>Superfluous Characters</h2>
The following queries - one per character - highlight in blue all words that contain the character but for which a variant of the word also exists without the character. Words that contain the character but do not have any such variants are highlighted in white.<br>
<br>
As an example, the query for superfluous "P", highlights <i>opcholor</i> in white (<i>ocholor</i> does not occur in the manuscript) and <i>polchedy</i> in blue (<i>olchedy</i> does occurs 38 times).<br>
<br>
<a href='http://www.voynichese.com/#/lay:a-superfluous'>http://www.voynichese.com/#/lay:a-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:c-superfluous'>http://www.voynichese.com/#/lay:c-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:d-superfluous'>http://www.voynichese.com/#/lay:d-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:e-superfluous'>http://www.voynichese.com/#/lay:e-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:f-superfluous'>http://www.voynichese.com/#/lay:f-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:g-superfluous'>http://www.voynichese.com/#/lay:g-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:h-superfluous'>http://www.voynichese.com/#/lay:h-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:i-superfluous'>http://www.voynichese.com/#/lay:i-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:k-superfluous'>http://www.voynichese.com/#/lay:k-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:l-superfluous'>http://www.voynichese.com/#/lay:l-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:m-superfluous'>http://www.voynichese.com/#/lay:m-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:n-superfluous'>http://www.voynichese.com/#/lay:n-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:o-superfluous'>http://www.voynichese.com/#/lay:o-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:p-superfluous'>http://www.voynichese.com/#/lay:p-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:q-superfluous'>http://www.voynichese.com/#/lay:q-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:r-superfluous'>http://www.voynichese.com/#/lay:r-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:s-superfluous'>http://www.voynichese.com/#/lay:s-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:t-superfluous'>http://www.voynichese.com/#/lay:t-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:v-superfluous'>http://www.voynichese.com/#/lay:v-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:x-superfluous'>http://www.voynichese.com/#/lay:x-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:y-superfluous'>http://www.voynichese.com/#/lay:y-superfluous</a><br>
<a href='http://www.voynichese.com/#/lay:z-superfluous'>http://www.voynichese.com/#/lay:z-superfluous</a><br>

<h2>Variants</h2>
The following query highlights all words that have one or more variants - where a variant is a similar word that differs by at most one character insertion, deletion or replacement.<br>
<br>
<a href='http://www.voynichese.com/#/lay:all-variants'>http://www.voynichese.com/#/lay:all-variants</a>

Note that the majority of Voynichese words have at least one variant.<br>
<br>
<h2>Folio & Paragraphs Contents</h2>

The following queries highlight all the words that occur in each specific folio or paragraph - with common words highlighted in white and uncommon words (less than 20 occurrences in the manuscript) in blue.<br>
<br>
The images below condense all such queries in a single animation.<br>
<br>
<img src='http://www.voynichese.com/2/image/folio-density.gif' />
<img src='http://www.voynichese.com/2/image/paragraph-density.gif' />

Folio <a href='http://www.voynichese.com/#/lay:f1r-density'>f1r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f1r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f1r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f1r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f1r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f1r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f1r-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f1v-density'>f1v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f1v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f1v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f2r-density'>f2r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f2r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f2r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f2v-density'>f2v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f2v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f2v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f3r-density'>f3r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f3r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f3r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f3r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f3r-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f3v-density'>f3v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f3v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f3v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f4r-density'>f4r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f4r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f4r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f4v-density'>f4v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f4v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f4v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f5r-density'>f5r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f5r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f5r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f5v-density'>f5v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f5v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f6r-density'>f6r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f6r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f6v-density'>f6v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f6v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f6v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f7r-density'>f7r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f7r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f7r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f7v-density'>f7v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f7v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f7v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f8r-density'>f8r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f8r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f8r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f8r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f8r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f8r-p5-density'>5</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f8v-density'>f8v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f8v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f8v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f9r-density'>f9r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f9r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f9r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f9r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f9v-density'>f9v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f9v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f9v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f10r-density'>f10r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f10r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f10r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f10v-density'>f10v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f10v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f10v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f11r-density'>f11r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f11r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f11r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f11v-density'>f11v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f11v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f13r-density'>f13r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f13r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f13r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f13v-density'>f13v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f13v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f13v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f14r-density'>f14r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f14r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f14r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f14v-density'>f14v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f14v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f15r-density'>f15r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f15r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f15v-density'>f15v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f15v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f16r-density'>f16r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f16r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f16r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f16r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f16r-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f16v-density'>f16v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f16v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f16v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f17r-density'>f17r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f17r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f17r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f17r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f17v-density'>f17v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f17v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f18r-density'>f18r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f18r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f18r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f18r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f18v-density'>f18v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f18v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f19r-density'>f19r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f19r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f19v-density'>f19v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f19v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f19v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f19v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f20r-density'>f20r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f20r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f20r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f20r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f20v-density'>f20v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f20v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f20v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f21r-density'>f21r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f21r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f21r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f21r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f21v-density'>f21v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f21v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f22r-density'>f22r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f22r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f22r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f22r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f22r-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f22v-density'>f22v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f22v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f22v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f22v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f23r-density'>f23r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f23r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f23r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f23r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f23v-density'>f23v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f23v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f23v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f24r-density'>f24r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f24r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f24v-density'>f24v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f24v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f24v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f24v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f25r-density'>f25r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f25r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f25r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f25v-density'>f25v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f25v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f26r-density'>f26r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f26r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f26r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f26v-density'>f26v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f26v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f26v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f26v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f26v-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f27r-density'>f27r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f27r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f27r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f27v-density'>f27v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f27v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f28r-density'>f28r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f28r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f28v-density'>f28v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f28v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f28v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f28v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f28v-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f29r-density'>f29r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f29r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f29r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f29v-density'>f29v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f29v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f29v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f29v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f30r-density'>f30r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f30r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f30r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f30v-density'>f30v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f30v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f31r-density'>f31r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f31r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f31r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f31r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f31r-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f31v-density'>f31v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f31v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f31v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f32r-density'>f32r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f32r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f32r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f32v-density'>f32v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f32v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f32v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f33r-density'>f33r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f33r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f33v-density'>f33v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f33v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f33v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f34r-density'>f34r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f34r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f34r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f34v-density'>f34v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f34v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f34v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f35r-density'>f35r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f35r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f35r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f35v-density'>f35v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f35v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f36r-density'>f36r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f36r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f36r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f36v-density'>f36v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f36v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f36v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f37r-density'>f37r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f37r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f37r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f37r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f37v-density'>f37v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f37v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f37v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f37v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f38r-density'>f38r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f38r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f38v-density'>f38v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f38v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f39r-density'>f39r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f39r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f39r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f39r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f39r-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f39v-density'>f39v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f39v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f39v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f40r-density'>f40r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f40r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f40r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f40v-density'>f40v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f40v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f40v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f40v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f41r-density'>f41r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f41r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f41r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f41v-density'>f41v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f41v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f42r-density'>f42r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f42r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f42r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f42r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f42r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f42r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f42r-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f42v-density'>f42v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f42v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f42v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f42v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f43r-density'>f43r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f43r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f43r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f43r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f43v-density'>f43v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f43v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f43v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f43v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f44r-density'>f44r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f44r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f44r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f44r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f44v-density'>f44v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f44v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f44v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f44v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f45r-density'>f45r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f45r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f45r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f45r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f45v-density'>f45v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f45v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f45v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f45v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f46r-density'>f46r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f46r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f46r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f46r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f46r-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f46v-density'>f46v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f46v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f47r-density'>f47r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f47r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f47r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f47v-density'>f47v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f47v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f47v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f48r-density'>f48r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f48r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f48v-density'>f48v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f48v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f48v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f49r-density'>f49r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f49r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f49r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f49r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f49v-density'>f49v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f49v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f49v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f49v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f50r-density'>f50r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f50r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f50v-density'>f50v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f50v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f51r-density'>f51r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f51r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f51v-density'>f51v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f51v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f52r-density'>f52r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f52r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f52v-density'>f52v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f52v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f52v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f53r-density'>f53r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f53r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f53v-density'>f53v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f53v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f54r-density'>f54r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f54r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f54r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f54v-density'>f54v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f54v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f55r-density'>f55r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f55r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f55r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f55v-density'>f55v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f55v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f55v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f56r-density'>f56r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f56r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f56r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f56v-density'>f56v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f56v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f56v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f57r-density'>f57r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f57r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f57r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f57v-density'>f57v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f57v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f57v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f57v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f58r-density'>f58r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f58r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f58r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f58r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f58v-density'>f58v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f58v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f58v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f58v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f58v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f58v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f58v-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f65r-density'>f65r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f65r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f65v-density'>f65v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f65v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f65v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f66r-density'>f66r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f66r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f66r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f66r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f66r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f66r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f66r-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f66v-density'>f66v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f66v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f66v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f66v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f67r1-density'>f67r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f67r1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f67r1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f67r1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f67r1-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f67r1-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f67r1-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f67r1-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f67r1-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f67r1-p9-density'>9</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f67r2-density'>f67r2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f67r2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f67r2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f67r2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f67r2-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f67r2-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f67r2-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f67r2-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f67r2-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f67r2-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f67r2-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f67r2-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f67r2-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f67r2-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f67r2-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f67r2-p15-density'>15</a> <a href='http://www.voynichese.com/#/lay:f67r2-p16-density'>16</a> <a href='http://www.voynichese.com/#/lay:f67r2-p17-density'>17</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f67v1-density'>f67v1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f67v1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f67v1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f67v1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f67v1-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f67v1-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f67v1-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f67v1-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f67v1-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f67v1-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f67v1-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f67v1-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f67v1-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f67v1-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f67v1-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f67v1-p15-density'>15</a> <a href='http://www.voynichese.com/#/lay:f67v1-p16-density'>16</a> <a href='http://www.voynichese.com/#/lay:f67v1-p17-density'>17</a> <a href='http://www.voynichese.com/#/lay:f67v1-p18-density'>18</a> <a href='http://www.voynichese.com/#/lay:f67v1-p19-density'>19</a> <a href='http://www.voynichese.com/#/lay:f67v1-p20-density'>20</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f67v2-density'>f67v2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f67v2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f67v2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f67v2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f67v2-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f67v2-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f67v2-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f67v2-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f67v2-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f67v2-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f67v2-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f67v2-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f67v2-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f67v2-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f67v2-p14-density'>14</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f68r1-density'>f68r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f68r1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f68r1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f68r1-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f68r2-density'>f68r2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f68r2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f68r2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f68r2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f68r2-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f68r3-density'>f68r3</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f68r3-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f68r3-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f68r3-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f68r3-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f68r3-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f68r3-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f68r3-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f68r3-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f68r3-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f68r3-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f68r3-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f68r3-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f68r3-p13-density'>13</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f68v1-density'>f68v1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f68v1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f68v1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f68v1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f68v1-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f68v1-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f68v1-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f68v1-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f68v2-density'>f68v2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f68v2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f68v2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f68v2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f68v2-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f68v2-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f68v2-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f68v2-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f68v2-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f68v2-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f68v2-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f68v2-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f68v2-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f68v2-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f68v2-p14-density'>14</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f68v3-density'>f68v3</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f68v3-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f68v3-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f68v3-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f68v3-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f68v3-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f68v3-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f68v3-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f68v3-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f68v3-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f68v3-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f68v3-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f68v3-p12-density'>12</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f69r-density'>f69r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f69r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f69r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f69r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f69r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f69r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f69r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f69r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f69r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f69r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f69r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f69r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f69r-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f69r-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f69r-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f69r-p15-density'>15</a> <a href='http://www.voynichese.com/#/lay:f69r-p16-density'>16</a> <a href='http://www.voynichese.com/#/lay:f69r-p17-density'>17</a> <a href='http://www.voynichese.com/#/lay:f69r-p18-density'>18</a> <a href='http://www.voynichese.com/#/lay:f69r-p19-density'>19</a> <a href='http://www.voynichese.com/#/lay:f69r-p20-density'>20</a> <a href='http://www.voynichese.com/#/lay:f69r-p21-density'>21</a> <a href='http://www.voynichese.com/#/lay:f69r-p22-density'>22</a> <a href='http://www.voynichese.com/#/lay:f69r-p23-density'>23</a> <a href='http://www.voynichese.com/#/lay:f69r-p24-density'>24</a> <a href='http://www.voynichese.com/#/lay:f69r-p25-density'>25</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f69v-density'>f69v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f69v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f69v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f69v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f69v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f69v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f69v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f69v-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f70r1-density'>f70r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f70r1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f70r1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f70r1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f70r1-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f70r1-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f70r1-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f70r1-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f70r1-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f70r1-p9-density'>9</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f70r2-density'>f70r2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f70r2-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f70v1-density'>f70v1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f70v1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f70v1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f70v1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f70v1-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f70v1-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f70v1-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f70v1-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f70v2-density'>f70v2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f70v2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f70v2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f70v2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f70v2-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f70v2-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f70v2-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f70v2-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f70v2-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f70v2-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f70v2-p10-density'>10</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f71r-density'>f71r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f71r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f71r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f71r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f71r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f71r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f71r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f71r-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f71v-density'>f71v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f71v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f71v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f71v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f71v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f71v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f71v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f71v-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f72r1-density'>f72r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f72r1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f72r1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f72r1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f72r1-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f72r1-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f72r1-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f72r1-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f72r1-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f72r1-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f72r1-p10-density'>10</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f72r2-density'>f72r2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f72r2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f72r2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f72r2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f72r2-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f72r2-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f72r2-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f72r3-density'>f72r3</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f72r3-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f72r3-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f72r3-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f72r3-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f72r3-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f72r3-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f72r3-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f72r3-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f72r3-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f72r3-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f72r3-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f72r3-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f72r3-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f72r3-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f72r3-p15-density'>15</a> <a href='http://www.voynichese.com/#/lay:f72r3-p16-density'>16</a> <a href='http://www.voynichese.com/#/lay:f72r3-p17-density'>17</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f72v1-density'>f72v1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f72v1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f72v1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f72v1-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f72v2-density'>f72v2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f72v2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f72v2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f72v2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f72v2-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f72v2-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f72v2-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f72v3-density'>f72v3</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f72v3-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f72v3-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f72v3-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f72v3-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f72v3-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f72v3-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f72v3-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f72v3-p8-density'>8</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f73r-density'>f73r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f73r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f73r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f73r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f73v-density'>f73v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f73v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f73v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f73v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f73v-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f75r-density'>f75r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f75r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f75r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f75r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f75r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f75r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f75r-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f75v-density'>f75v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f75v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f75v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f75v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f75v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f75v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f75v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f75v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f75v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f75v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f75v-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f75v-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f75v-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f75v-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f75v-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f75v-p15-density'>15</a> <a href='http://www.voynichese.com/#/lay:f75v-p16-density'>16</a> <a href='http://www.voynichese.com/#/lay:f75v-p17-density'>17</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f76r-density'>f76r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f76r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f76r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f76r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f76r-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f76v-density'>f76v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f76v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f76v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f76v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f76v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f76v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f76v-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f77r-density'>f77r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f77r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f77r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f77r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f77v-density'>f77v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f77v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f77v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f77v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f77v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f77v-p5-density'>5</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f78r-density'>f78r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f78r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f78r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f78r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f78v-density'>f78v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f78v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f78v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f79r-density'>f79r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f79r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f79r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f79r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f79r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f79r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f79r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f79r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f79r-p8-density'>8</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f79v-density'>f79v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f79v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f79v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f79v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f79v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f79v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f79v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f79v-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f80r-density'>f80r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f80r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f80r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f80r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f80r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f80r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f80r-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f80v-density'>f80v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f80v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f80v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f80v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f80v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f80v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f80v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f80v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f80v-p8-density'>8</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f81r-density'>f81r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f81r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f81r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f81r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f81v-density'>f81v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f81v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f81v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f81v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f82r-density'>f82r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f82r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f82r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f82r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f82r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f82r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f82r-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f82v-density'>f82v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f82v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f82v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f82v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f82v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f82v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f82v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f82v-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f83r-density'>f83r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f83r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f83r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f83r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f83r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f83r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f83r-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f83v-density'>f83v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f83v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f83v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f83v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f84r-density'>f84r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f84r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f84r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f84r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f84r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f84r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f84r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f84r-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f84v-density'>f84v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f84v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f84v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f84v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f84v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f84v-p5-density'>5</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f85r1-density'>f85r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f85r1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f85r1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f85r1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f85r1-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f85r1-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f85r1-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f85r1-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f85r1-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f85r1-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f85r1-p10-density'>10</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f85r2-density'>f85r2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f85r2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f85r2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f85r2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f85r2-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f85r2-p5-density'>5</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f86v3-density'>f86v3</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f86v3-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f86v3-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f86v3-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f86v3-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f86v3-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f86v3-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f86v3-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f86v4-density'>f86v4</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f86v4-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f86v4-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f86v4-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f86v4-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f86v5-density'>f86v5</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f86v5-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f86v5-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f86v5-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f86v5-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f86v5-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f86v5-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f86v6-density'>f86v6</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f86v6-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f86v6-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f86v6-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f86v6-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f87r-density'>f87r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f87r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f87r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f87v-density'>f87v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f87v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f87v-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f88r-density'>f88r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f88r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f88r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f88r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f88r-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f88v-density'>f88v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f88v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f88v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f88v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f88v-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f89r1-density'>f89r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f89r1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f89r1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f89r1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f89r1-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f89r1-p5-density'>5</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f89r2-density'>f89r2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f89r2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f89r2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f89r2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f89r2-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f89r2-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f89r2-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f89r2-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f89r2-p8-density'>8</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f89v1-density'>f89v1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f89v1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f89v1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f89v1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f89v1-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f89v1-p5-density'>5</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f89v2-density'>f89v2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f89v2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f89v2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f89v2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f89v2-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f90r1-density'>f90r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f90r1-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f90r2-density'>f90r2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f90r2-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f90v1-density'>f90v1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f90v1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f90v1-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f90v2-density'>f90v2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f90v2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f90v2-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f93r-density'>f93r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f93r-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f93v-density'>f93v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f93v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f94r-density'>f94r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f94r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f94r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f94v-density'>f94v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f94v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f94v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f94v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f95r1-density'>f95r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f95r1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f95r1-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f95r2-density'>f95r2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f95r2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f95r2-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f95v1-density'>f95v1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f95v1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f95v1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f95v1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f95v1-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f95v2-density'>f95v2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f95v2-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f96r-density'>f96r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f96r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f96r-p2-density'>2</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f96v-density'>f96v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f96v-p1-density'>1</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f99r-density'>f99r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f99r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f99r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f99r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f99r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f99r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f99r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f99r-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f99v-density'>f99v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f99v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f99v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f99v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f99v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f99v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f99v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f99v-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f100r-density'>f100r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f100r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f100r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f100r-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f100v-density'>f100v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f100v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f100v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f100v-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f101r1-density'>f101r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f101r1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f101r1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f101r1-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f101v2-density'>f101v2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f101v2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f101v2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f101v2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f101v2-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f101v2-p5-density'>5</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f102r1-density'>f102r1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f102r1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f102r1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f102r1-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f102r2-density'>f102r2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f102r2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f102r2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f102r2-p3-density'>3</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f102v1-density'>f102v1</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f102v1-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f102v1-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f102v1-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f102v1-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f102v2-density'>f102v2</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f102v2-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f102v2-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f102v2-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f102v2-p4-density'>4</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f103r-density'>f103r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f103r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f103r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f103r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f103r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f103r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f103r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f103r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f103r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f103r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f103r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f103r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f103r-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f103r-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f103r-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f103r-p15-density'>15</a> <a href='http://www.voynichese.com/#/lay:f103r-p16-density'>16</a> <a href='http://www.voynichese.com/#/lay:f103r-p17-density'>17</a> <a href='http://www.voynichese.com/#/lay:f103r-p18-density'>18</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f103v-density'>f103v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f103v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f103v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f103v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f103v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f103v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f103v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f103v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f103v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f103v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f103v-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f103v-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f103v-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f103v-p13-density'>13</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f104r-density'>f104r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f104r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f104r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f104r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f104r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f104r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f104r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f104r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f104r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f104r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f104r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f104r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f104r-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f104r-p13-density'>13</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f104v-density'>f104v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f104v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f104v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f104v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f104v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f104v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f104v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f104v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f104v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f104v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f104v-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f104v-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f104v-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f104v-p13-density'>13</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f105r-density'>f105r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f105r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f105r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f105r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f105r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f105r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f105r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f105r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f105r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f105r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f105r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f105r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f105r-p12-density'>12</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f105v-density'>f105v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f105v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f105v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f105v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f105v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f105v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f105v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f105v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f105v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f105v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f105v-p10-density'>10</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f106r-density'>f106r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f106r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f106r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f106r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f106r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f106r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f106r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f106r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f106r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f106r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f106r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f106r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f106r-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f106r-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f106r-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f106r-p15-density'>15</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f106v-density'>f106v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f106v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f106v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f106v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f106v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f106v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f106v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f106v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f106v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f106v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f106v-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f106v-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f106v-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f106v-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f106v-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f106v-p15-density'>15</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f107r-density'>f107r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f107r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f107r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f107r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f107r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f107r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f107r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f107r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f107r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f107r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f107r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f107r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f107r-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f107r-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f107r-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f107r-p15-density'>15</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f107v-density'>f107v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f107v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f107v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f107v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f107v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f107v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f107v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f107v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f107v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f107v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f107v-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f107v-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f107v-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f107v-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f107v-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f107v-p15-density'>15</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f108r-density'>f108r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f108r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f108r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f108r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f108r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f108r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f108r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f108r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f108r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f108r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f108r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f108r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f108r-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f108r-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f108r-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f108r-p15-density'>15</a> <a href='http://www.voynichese.com/#/lay:f108r-p16-density'>16</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f108v-density'>f108v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f108v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f108v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f108v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f108v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f108v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f108v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f108v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f108v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f108v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f108v-p10-density'>10</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f111r-density'>f111r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f111r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f111r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f111r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f111r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f111r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f111r-p6-density'>6</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f111v-density'>f111v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f111v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f111v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f111v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f111v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f111v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f111v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f111v-p7-density'>7</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f112r-density'>f112r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f112r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f112r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f112r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f112r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f112r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f112r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f112r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f112r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f112r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f112r-p10-density'>10</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f112v-density'>f112v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f112v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f112v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f112v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f112v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f112v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f112v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f112v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f112v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f112v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f112v-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f112v-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f112v-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f112v-p13-density'>13</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f113r-density'>f113r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f113r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f113r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f113r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f113r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f113r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f113r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f113r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f113r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f113r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f113r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f113r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f113r-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f113r-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f113r-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f113r-p15-density'>15</a> <a href='http://www.voynichese.com/#/lay:f113r-p16-density'>16</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f113v-density'>f113v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f113v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f113v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f113v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f113v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f113v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f113v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f113v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f113v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f113v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f113v-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f113v-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f113v-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f113v-p13-density'>13</a> <a href='http://www.voynichese.com/#/lay:f113v-p14-density'>14</a> <a href='http://www.voynichese.com/#/lay:f113v-p15-density'>15</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f114r-density'>f114r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f114r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f114r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f114r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f114r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f114r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f114r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f114r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f114r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f114r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f114r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f114r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f114r-p12-density'>12</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f114v-density'>f114v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f114v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f114v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f114v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f114v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f114v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f114v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f114v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f114v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f114v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f114v-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f114v-p11-density'>11</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f115r-density'>f115r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f115r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f115r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f115r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f115r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f115r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f115r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f115r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f115r-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f115r-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f115r-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f115r-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f115r-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f115r-p13-density'>13</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f115v-density'>f115v</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f115v-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f115v-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f115v-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f115v-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f115v-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f115v-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f115v-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f115v-p8-density'>8</a> <a href='http://www.voynichese.com/#/lay:f115v-p9-density'>9</a> <a href='http://www.voynichese.com/#/lay:f115v-p10-density'>10</a> <a href='http://www.voynichese.com/#/lay:f115v-p11-density'>11</a> <a href='http://www.voynichese.com/#/lay:f115v-p12-density'>12</a> <a href='http://www.voynichese.com/#/lay:f115v-p13-density'>13</a><br>
Folio <a href='http://www.voynichese.com/#/lay:f116r-density'>f116r</a> Paragraphs:  <a href='http://www.voynichese.com/#/lay:f116r-p1-density'>1</a> <a href='http://www.voynichese.com/#/lay:f116r-p2-density'>2</a> <a href='http://www.voynichese.com/#/lay:f116r-p3-density'>3</a> <a href='http://www.voynichese.com/#/lay:f116r-p4-density'>4</a> <a href='http://www.voynichese.com/#/lay:f116r-p5-density'>5</a> <a href='http://www.voynichese.com/#/lay:f116r-p6-density'>6</a> <a href='http://www.voynichese.com/#/lay:f116r-p7-density'>7</a> <a href='http://www.voynichese.com/#/lay:f116r-p8-density'>8</a>

<h2>Character Substitutions</h2>

The following queries, one for each pair of characters X and Y, highlight all words containing X in green if replacing X with Y yields a valid word and red if it does not.<br>
<br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-c'>http://www.voynichese.com/#/lay:character-a-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-d'>http://www.voynichese.com/#/lay:character-a-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-e'>http://www.voynichese.com/#/lay:character-a-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-f'>http://www.voynichese.com/#/lay:character-a-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-g'>http://www.voynichese.com/#/lay:character-a-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-h'>http://www.voynichese.com/#/lay:character-a-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-i'>http://www.voynichese.com/#/lay:character-a-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-k'>http://www.voynichese.com/#/lay:character-a-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-l'>http://www.voynichese.com/#/lay:character-a-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-m'>http://www.voynichese.com/#/lay:character-a-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-n'>http://www.voynichese.com/#/lay:character-a-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-o'>http://www.voynichese.com/#/lay:character-a-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-p'>http://www.voynichese.com/#/lay:character-a-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-q'>http://www.voynichese.com/#/lay:character-a-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-r'>http://www.voynichese.com/#/lay:character-a-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-s'>http://www.voynichese.com/#/lay:character-a-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-t'>http://www.voynichese.com/#/lay:character-a-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-v'>http://www.voynichese.com/#/lay:character-a-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-x'>http://www.voynichese.com/#/lay:character-a-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-y'>http://www.voynichese.com/#/lay:character-a-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-a-vs-z'>http://www.voynichese.com/#/lay:character-a-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-a'>http://www.voynichese.com/#/lay:character-c-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-d'>http://www.voynichese.com/#/lay:character-c-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-e'>http://www.voynichese.com/#/lay:character-c-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-f'>http://www.voynichese.com/#/lay:character-c-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-g'>http://www.voynichese.com/#/lay:character-c-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-h'>http://www.voynichese.com/#/lay:character-c-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-i'>http://www.voynichese.com/#/lay:character-c-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-k'>http://www.voynichese.com/#/lay:character-c-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-l'>http://www.voynichese.com/#/lay:character-c-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-m'>http://www.voynichese.com/#/lay:character-c-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-n'>http://www.voynichese.com/#/lay:character-c-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-o'>http://www.voynichese.com/#/lay:character-c-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-p'>http://www.voynichese.com/#/lay:character-c-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-q'>http://www.voynichese.com/#/lay:character-c-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-r'>http://www.voynichese.com/#/lay:character-c-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-s'>http://www.voynichese.com/#/lay:character-c-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-t'>http://www.voynichese.com/#/lay:character-c-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-v'>http://www.voynichese.com/#/lay:character-c-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-x'>http://www.voynichese.com/#/lay:character-c-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-y'>http://www.voynichese.com/#/lay:character-c-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-c-vs-z'>http://www.voynichese.com/#/lay:character-c-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-a'>http://www.voynichese.com/#/lay:character-d-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-c'>http://www.voynichese.com/#/lay:character-d-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-e'>http://www.voynichese.com/#/lay:character-d-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-f'>http://www.voynichese.com/#/lay:character-d-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-g'>http://www.voynichese.com/#/lay:character-d-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-h'>http://www.voynichese.com/#/lay:character-d-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-i'>http://www.voynichese.com/#/lay:character-d-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-k'>http://www.voynichese.com/#/lay:character-d-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-l'>http://www.voynichese.com/#/lay:character-d-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-m'>http://www.voynichese.com/#/lay:character-d-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-n'>http://www.voynichese.com/#/lay:character-d-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-o'>http://www.voynichese.com/#/lay:character-d-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-p'>http://www.voynichese.com/#/lay:character-d-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-q'>http://www.voynichese.com/#/lay:character-d-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-r'>http://www.voynichese.com/#/lay:character-d-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-s'>http://www.voynichese.com/#/lay:character-d-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-t'>http://www.voynichese.com/#/lay:character-d-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-v'>http://www.voynichese.com/#/lay:character-d-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-x'>http://www.voynichese.com/#/lay:character-d-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-y'>http://www.voynichese.com/#/lay:character-d-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-d-vs-z'>http://www.voynichese.com/#/lay:character-d-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-a'>http://www.voynichese.com/#/lay:character-e-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-c'>http://www.voynichese.com/#/lay:character-e-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-d'>http://www.voynichese.com/#/lay:character-e-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-f'>http://www.voynichese.com/#/lay:character-e-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-g'>http://www.voynichese.com/#/lay:character-e-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-h'>http://www.voynichese.com/#/lay:character-e-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-i'>http://www.voynichese.com/#/lay:character-e-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-k'>http://www.voynichese.com/#/lay:character-e-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-l'>http://www.voynichese.com/#/lay:character-e-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-m'>http://www.voynichese.com/#/lay:character-e-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-n'>http://www.voynichese.com/#/lay:character-e-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-o'>http://www.voynichese.com/#/lay:character-e-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-p'>http://www.voynichese.com/#/lay:character-e-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-q'>http://www.voynichese.com/#/lay:character-e-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-r'>http://www.voynichese.com/#/lay:character-e-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-s'>http://www.voynichese.com/#/lay:character-e-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-t'>http://www.voynichese.com/#/lay:character-e-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-v'>http://www.voynichese.com/#/lay:character-e-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-x'>http://www.voynichese.com/#/lay:character-e-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-y'>http://www.voynichese.com/#/lay:character-e-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-e-vs-z'>http://www.voynichese.com/#/lay:character-e-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-a'>http://www.voynichese.com/#/lay:character-f-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-c'>http://www.voynichese.com/#/lay:character-f-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-d'>http://www.voynichese.com/#/lay:character-f-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-e'>http://www.voynichese.com/#/lay:character-f-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-g'>http://www.voynichese.com/#/lay:character-f-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-h'>http://www.voynichese.com/#/lay:character-f-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-i'>http://www.voynichese.com/#/lay:character-f-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-k'>http://www.voynichese.com/#/lay:character-f-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-l'>http://www.voynichese.com/#/lay:character-f-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-m'>http://www.voynichese.com/#/lay:character-f-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-n'>http://www.voynichese.com/#/lay:character-f-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-o'>http://www.voynichese.com/#/lay:character-f-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-p'>http://www.voynichese.com/#/lay:character-f-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-q'>http://www.voynichese.com/#/lay:character-f-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-r'>http://www.voynichese.com/#/lay:character-f-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-s'>http://www.voynichese.com/#/lay:character-f-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-t'>http://www.voynichese.com/#/lay:character-f-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-v'>http://www.voynichese.com/#/lay:character-f-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-x'>http://www.voynichese.com/#/lay:character-f-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-y'>http://www.voynichese.com/#/lay:character-f-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-f-vs-z'>http://www.voynichese.com/#/lay:character-f-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-a'>http://www.voynichese.com/#/lay:character-g-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-c'>http://www.voynichese.com/#/lay:character-g-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-d'>http://www.voynichese.com/#/lay:character-g-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-e'>http://www.voynichese.com/#/lay:character-g-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-f'>http://www.voynichese.com/#/lay:character-g-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-h'>http://www.voynichese.com/#/lay:character-g-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-i'>http://www.voynichese.com/#/lay:character-g-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-k'>http://www.voynichese.com/#/lay:character-g-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-l'>http://www.voynichese.com/#/lay:character-g-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-m'>http://www.voynichese.com/#/lay:character-g-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-n'>http://www.voynichese.com/#/lay:character-g-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-o'>http://www.voynichese.com/#/lay:character-g-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-p'>http://www.voynichese.com/#/lay:character-g-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-q'>http://www.voynichese.com/#/lay:character-g-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-r'>http://www.voynichese.com/#/lay:character-g-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-s'>http://www.voynichese.com/#/lay:character-g-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-t'>http://www.voynichese.com/#/lay:character-g-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-v'>http://www.voynichese.com/#/lay:character-g-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-x'>http://www.voynichese.com/#/lay:character-g-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-y'>http://www.voynichese.com/#/lay:character-g-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-g-vs-z'>http://www.voynichese.com/#/lay:character-g-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-a'>http://www.voynichese.com/#/lay:character-h-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-c'>http://www.voynichese.com/#/lay:character-h-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-d'>http://www.voynichese.com/#/lay:character-h-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-e'>http://www.voynichese.com/#/lay:character-h-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-f'>http://www.voynichese.com/#/lay:character-h-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-g'>http://www.voynichese.com/#/lay:character-h-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-i'>http://www.voynichese.com/#/lay:character-h-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-k'>http://www.voynichese.com/#/lay:character-h-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-l'>http://www.voynichese.com/#/lay:character-h-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-m'>http://www.voynichese.com/#/lay:character-h-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-n'>http://www.voynichese.com/#/lay:character-h-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-o'>http://www.voynichese.com/#/lay:character-h-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-p'>http://www.voynichese.com/#/lay:character-h-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-q'>http://www.voynichese.com/#/lay:character-h-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-r'>http://www.voynichese.com/#/lay:character-h-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-s'>http://www.voynichese.com/#/lay:character-h-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-t'>http://www.voynichese.com/#/lay:character-h-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-v'>http://www.voynichese.com/#/lay:character-h-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-x'>http://www.voynichese.com/#/lay:character-h-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-y'>http://www.voynichese.com/#/lay:character-h-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-h-vs-z'>http://www.voynichese.com/#/lay:character-h-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-a'>http://www.voynichese.com/#/lay:character-i-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-c'>http://www.voynichese.com/#/lay:character-i-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-d'>http://www.voynichese.com/#/lay:character-i-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-e'>http://www.voynichese.com/#/lay:character-i-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-f'>http://www.voynichese.com/#/lay:character-i-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-g'>http://www.voynichese.com/#/lay:character-i-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-h'>http://www.voynichese.com/#/lay:character-i-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-k'>http://www.voynichese.com/#/lay:character-i-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-l'>http://www.voynichese.com/#/lay:character-i-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-m'>http://www.voynichese.com/#/lay:character-i-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-n'>http://www.voynichese.com/#/lay:character-i-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-o'>http://www.voynichese.com/#/lay:character-i-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-p'>http://www.voynichese.com/#/lay:character-i-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-q'>http://www.voynichese.com/#/lay:character-i-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-r'>http://www.voynichese.com/#/lay:character-i-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-s'>http://www.voynichese.com/#/lay:character-i-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-t'>http://www.voynichese.com/#/lay:character-i-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-v'>http://www.voynichese.com/#/lay:character-i-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-x'>http://www.voynichese.com/#/lay:character-i-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-y'>http://www.voynichese.com/#/lay:character-i-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-i-vs-z'>http://www.voynichese.com/#/lay:character-i-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-a'>http://www.voynichese.com/#/lay:character-k-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-c'>http://www.voynichese.com/#/lay:character-k-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-d'>http://www.voynichese.com/#/lay:character-k-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-e'>http://www.voynichese.com/#/lay:character-k-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-f'>http://www.voynichese.com/#/lay:character-k-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-g'>http://www.voynichese.com/#/lay:character-k-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-h'>http://www.voynichese.com/#/lay:character-k-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-i'>http://www.voynichese.com/#/lay:character-k-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-l'>http://www.voynichese.com/#/lay:character-k-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-m'>http://www.voynichese.com/#/lay:character-k-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-n'>http://www.voynichese.com/#/lay:character-k-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-o'>http://www.voynichese.com/#/lay:character-k-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-p'>http://www.voynichese.com/#/lay:character-k-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-q'>http://www.voynichese.com/#/lay:character-k-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-r'>http://www.voynichese.com/#/lay:character-k-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-s'>http://www.voynichese.com/#/lay:character-k-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-t'>http://www.voynichese.com/#/lay:character-k-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-v'>http://www.voynichese.com/#/lay:character-k-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-x'>http://www.voynichese.com/#/lay:character-k-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-y'>http://www.voynichese.com/#/lay:character-k-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-k-vs-z'>http://www.voynichese.com/#/lay:character-k-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-a'>http://www.voynichese.com/#/lay:character-l-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-c'>http://www.voynichese.com/#/lay:character-l-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-d'>http://www.voynichese.com/#/lay:character-l-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-e'>http://www.voynichese.com/#/lay:character-l-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-f'>http://www.voynichese.com/#/lay:character-l-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-g'>http://www.voynichese.com/#/lay:character-l-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-h'>http://www.voynichese.com/#/lay:character-l-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-i'>http://www.voynichese.com/#/lay:character-l-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-k'>http://www.voynichese.com/#/lay:character-l-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-m'>http://www.voynichese.com/#/lay:character-l-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-n'>http://www.voynichese.com/#/lay:character-l-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-o'>http://www.voynichese.com/#/lay:character-l-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-p'>http://www.voynichese.com/#/lay:character-l-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-q'>http://www.voynichese.com/#/lay:character-l-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-r'>http://www.voynichese.com/#/lay:character-l-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-s'>http://www.voynichese.com/#/lay:character-l-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-t'>http://www.voynichese.com/#/lay:character-l-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-v'>http://www.voynichese.com/#/lay:character-l-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-x'>http://www.voynichese.com/#/lay:character-l-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-y'>http://www.voynichese.com/#/lay:character-l-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-l-vs-z'>http://www.voynichese.com/#/lay:character-l-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-a'>http://www.voynichese.com/#/lay:character-m-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-c'>http://www.voynichese.com/#/lay:character-m-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-d'>http://www.voynichese.com/#/lay:character-m-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-e'>http://www.voynichese.com/#/lay:character-m-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-f'>http://www.voynichese.com/#/lay:character-m-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-g'>http://www.voynichese.com/#/lay:character-m-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-h'>http://www.voynichese.com/#/lay:character-m-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-i'>http://www.voynichese.com/#/lay:character-m-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-k'>http://www.voynichese.com/#/lay:character-m-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-l'>http://www.voynichese.com/#/lay:character-m-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-n'>http://www.voynichese.com/#/lay:character-m-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-o'>http://www.voynichese.com/#/lay:character-m-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-p'>http://www.voynichese.com/#/lay:character-m-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-q'>http://www.voynichese.com/#/lay:character-m-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-r'>http://www.voynichese.com/#/lay:character-m-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-s'>http://www.voynichese.com/#/lay:character-m-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-t'>http://www.voynichese.com/#/lay:character-m-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-v'>http://www.voynichese.com/#/lay:character-m-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-x'>http://www.voynichese.com/#/lay:character-m-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-y'>http://www.voynichese.com/#/lay:character-m-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-m-vs-z'>http://www.voynichese.com/#/lay:character-m-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-a'>http://www.voynichese.com/#/lay:character-n-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-c'>http://www.voynichese.com/#/lay:character-n-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-d'>http://www.voynichese.com/#/lay:character-n-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-e'>http://www.voynichese.com/#/lay:character-n-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-f'>http://www.voynichese.com/#/lay:character-n-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-g'>http://www.voynichese.com/#/lay:character-n-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-h'>http://www.voynichese.com/#/lay:character-n-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-i'>http://www.voynichese.com/#/lay:character-n-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-k'>http://www.voynichese.com/#/lay:character-n-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-l'>http://www.voynichese.com/#/lay:character-n-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-m'>http://www.voynichese.com/#/lay:character-n-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-o'>http://www.voynichese.com/#/lay:character-n-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-p'>http://www.voynichese.com/#/lay:character-n-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-q'>http://www.voynichese.com/#/lay:character-n-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-r'>http://www.voynichese.com/#/lay:character-n-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-s'>http://www.voynichese.com/#/lay:character-n-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-t'>http://www.voynichese.com/#/lay:character-n-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-v'>http://www.voynichese.com/#/lay:character-n-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-x'>http://www.voynichese.com/#/lay:character-n-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-y'>http://www.voynichese.com/#/lay:character-n-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-n-vs-z'>http://www.voynichese.com/#/lay:character-n-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-a'>http://www.voynichese.com/#/lay:character-o-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-c'>http://www.voynichese.com/#/lay:character-o-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-d'>http://www.voynichese.com/#/lay:character-o-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-e'>http://www.voynichese.com/#/lay:character-o-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-f'>http://www.voynichese.com/#/lay:character-o-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-g'>http://www.voynichese.com/#/lay:character-o-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-h'>http://www.voynichese.com/#/lay:character-o-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-i'>http://www.voynichese.com/#/lay:character-o-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-k'>http://www.voynichese.com/#/lay:character-o-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-l'>http://www.voynichese.com/#/lay:character-o-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-m'>http://www.voynichese.com/#/lay:character-o-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-n'>http://www.voynichese.com/#/lay:character-o-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-p'>http://www.voynichese.com/#/lay:character-o-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-q'>http://www.voynichese.com/#/lay:character-o-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-r'>http://www.voynichese.com/#/lay:character-o-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-s'>http://www.voynichese.com/#/lay:character-o-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-t'>http://www.voynichese.com/#/lay:character-o-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-v'>http://www.voynichese.com/#/lay:character-o-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-x'>http://www.voynichese.com/#/lay:character-o-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-y'>http://www.voynichese.com/#/lay:character-o-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-o-vs-z'>http://www.voynichese.com/#/lay:character-o-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-a'>http://www.voynichese.com/#/lay:character-p-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-c'>http://www.voynichese.com/#/lay:character-p-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-d'>http://www.voynichese.com/#/lay:character-p-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-e'>http://www.voynichese.com/#/lay:character-p-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-f'>http://www.voynichese.com/#/lay:character-p-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-g'>http://www.voynichese.com/#/lay:character-p-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-h'>http://www.voynichese.com/#/lay:character-p-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-i'>http://www.voynichese.com/#/lay:character-p-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-k'>http://www.voynichese.com/#/lay:character-p-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-l'>http://www.voynichese.com/#/lay:character-p-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-m'>http://www.voynichese.com/#/lay:character-p-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-n'>http://www.voynichese.com/#/lay:character-p-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-o'>http://www.voynichese.com/#/lay:character-p-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-q'>http://www.voynichese.com/#/lay:character-p-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-r'>http://www.voynichese.com/#/lay:character-p-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-s'>http://www.voynichese.com/#/lay:character-p-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-t'>http://www.voynichese.com/#/lay:character-p-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-v'>http://www.voynichese.com/#/lay:character-p-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-x'>http://www.voynichese.com/#/lay:character-p-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-y'>http://www.voynichese.com/#/lay:character-p-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-p-vs-z'>http://www.voynichese.com/#/lay:character-p-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-a'>http://www.voynichese.com/#/lay:character-q-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-c'>http://www.voynichese.com/#/lay:character-q-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-d'>http://www.voynichese.com/#/lay:character-q-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-e'>http://www.voynichese.com/#/lay:character-q-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-f'>http://www.voynichese.com/#/lay:character-q-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-g'>http://www.voynichese.com/#/lay:character-q-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-h'>http://www.voynichese.com/#/lay:character-q-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-i'>http://www.voynichese.com/#/lay:character-q-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-k'>http://www.voynichese.com/#/lay:character-q-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-l'>http://www.voynichese.com/#/lay:character-q-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-m'>http://www.voynichese.com/#/lay:character-q-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-n'>http://www.voynichese.com/#/lay:character-q-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-o'>http://www.voynichese.com/#/lay:character-q-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-p'>http://www.voynichese.com/#/lay:character-q-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-r'>http://www.voynichese.com/#/lay:character-q-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-s'>http://www.voynichese.com/#/lay:character-q-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-t'>http://www.voynichese.com/#/lay:character-q-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-v'>http://www.voynichese.com/#/lay:character-q-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-x'>http://www.voynichese.com/#/lay:character-q-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-y'>http://www.voynichese.com/#/lay:character-q-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-q-vs-z'>http://www.voynichese.com/#/lay:character-q-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-a'>http://www.voynichese.com/#/lay:character-r-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-c'>http://www.voynichese.com/#/lay:character-r-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-d'>http://www.voynichese.com/#/lay:character-r-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-e'>http://www.voynichese.com/#/lay:character-r-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-f'>http://www.voynichese.com/#/lay:character-r-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-g'>http://www.voynichese.com/#/lay:character-r-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-h'>http://www.voynichese.com/#/lay:character-r-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-i'>http://www.voynichese.com/#/lay:character-r-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-k'>http://www.voynichese.com/#/lay:character-r-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-l'>http://www.voynichese.com/#/lay:character-r-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-m'>http://www.voynichese.com/#/lay:character-r-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-n'>http://www.voynichese.com/#/lay:character-r-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-o'>http://www.voynichese.com/#/lay:character-r-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-p'>http://www.voynichese.com/#/lay:character-r-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-q'>http://www.voynichese.com/#/lay:character-r-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-s'>http://www.voynichese.com/#/lay:character-r-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-t'>http://www.voynichese.com/#/lay:character-r-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-v'>http://www.voynichese.com/#/lay:character-r-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-x'>http://www.voynichese.com/#/lay:character-r-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-y'>http://www.voynichese.com/#/lay:character-r-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-r-vs-z'>http://www.voynichese.com/#/lay:character-r-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-a'>http://www.voynichese.com/#/lay:character-s-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-c'>http://www.voynichese.com/#/lay:character-s-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-d'>http://www.voynichese.com/#/lay:character-s-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-e'>http://www.voynichese.com/#/lay:character-s-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-f'>http://www.voynichese.com/#/lay:character-s-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-g'>http://www.voynichese.com/#/lay:character-s-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-h'>http://www.voynichese.com/#/lay:character-s-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-i'>http://www.voynichese.com/#/lay:character-s-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-k'>http://www.voynichese.com/#/lay:character-s-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-l'>http://www.voynichese.com/#/lay:character-s-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-m'>http://www.voynichese.com/#/lay:character-s-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-n'>http://www.voynichese.com/#/lay:character-s-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-o'>http://www.voynichese.com/#/lay:character-s-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-p'>http://www.voynichese.com/#/lay:character-s-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-q'>http://www.voynichese.com/#/lay:character-s-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-r'>http://www.voynichese.com/#/lay:character-s-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-t'>http://www.voynichese.com/#/lay:character-s-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-v'>http://www.voynichese.com/#/lay:character-s-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-x'>http://www.voynichese.com/#/lay:character-s-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-y'>http://www.voynichese.com/#/lay:character-s-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-s-vs-z'>http://www.voynichese.com/#/lay:character-s-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-a'>http://www.voynichese.com/#/lay:character-t-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-c'>http://www.voynichese.com/#/lay:character-t-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-d'>http://www.voynichese.com/#/lay:character-t-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-e'>http://www.voynichese.com/#/lay:character-t-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-f'>http://www.voynichese.com/#/lay:character-t-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-g'>http://www.voynichese.com/#/lay:character-t-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-h'>http://www.voynichese.com/#/lay:character-t-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-i'>http://www.voynichese.com/#/lay:character-t-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-k'>http://www.voynichese.com/#/lay:character-t-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-l'>http://www.voynichese.com/#/lay:character-t-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-m'>http://www.voynichese.com/#/lay:character-t-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-n'>http://www.voynichese.com/#/lay:character-t-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-o'>http://www.voynichese.com/#/lay:character-t-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-p'>http://www.voynichese.com/#/lay:character-t-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-q'>http://www.voynichese.com/#/lay:character-t-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-r'>http://www.voynichese.com/#/lay:character-t-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-s'>http://www.voynichese.com/#/lay:character-t-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-v'>http://www.voynichese.com/#/lay:character-t-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-x'>http://www.voynichese.com/#/lay:character-t-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-y'>http://www.voynichese.com/#/lay:character-t-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-t-vs-z'>http://www.voynichese.com/#/lay:character-t-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-a'>http://www.voynichese.com/#/lay:character-v-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-c'>http://www.voynichese.com/#/lay:character-v-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-d'>http://www.voynichese.com/#/lay:character-v-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-e'>http://www.voynichese.com/#/lay:character-v-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-f'>http://www.voynichese.com/#/lay:character-v-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-g'>http://www.voynichese.com/#/lay:character-v-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-h'>http://www.voynichese.com/#/lay:character-v-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-i'>http://www.voynichese.com/#/lay:character-v-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-k'>http://www.voynichese.com/#/lay:character-v-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-l'>http://www.voynichese.com/#/lay:character-v-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-m'>http://www.voynichese.com/#/lay:character-v-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-n'>http://www.voynichese.com/#/lay:character-v-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-o'>http://www.voynichese.com/#/lay:character-v-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-p'>http://www.voynichese.com/#/lay:character-v-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-q'>http://www.voynichese.com/#/lay:character-v-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-r'>http://www.voynichese.com/#/lay:character-v-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-s'>http://www.voynichese.com/#/lay:character-v-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-t'>http://www.voynichese.com/#/lay:character-v-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-x'>http://www.voynichese.com/#/lay:character-v-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-y'>http://www.voynichese.com/#/lay:character-v-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-v-vs-z'>http://www.voynichese.com/#/lay:character-v-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-a'>http://www.voynichese.com/#/lay:character-x-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-c'>http://www.voynichese.com/#/lay:character-x-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-d'>http://www.voynichese.com/#/lay:character-x-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-e'>http://www.voynichese.com/#/lay:character-x-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-f'>http://www.voynichese.com/#/lay:character-x-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-g'>http://www.voynichese.com/#/lay:character-x-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-h'>http://www.voynichese.com/#/lay:character-x-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-i'>http://www.voynichese.com/#/lay:character-x-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-k'>http://www.voynichese.com/#/lay:character-x-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-l'>http://www.voynichese.com/#/lay:character-x-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-m'>http://www.voynichese.com/#/lay:character-x-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-n'>http://www.voynichese.com/#/lay:character-x-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-o'>http://www.voynichese.com/#/lay:character-x-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-p'>http://www.voynichese.com/#/lay:character-x-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-q'>http://www.voynichese.com/#/lay:character-x-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-r'>http://www.voynichese.com/#/lay:character-x-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-s'>http://www.voynichese.com/#/lay:character-x-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-t'>http://www.voynichese.com/#/lay:character-x-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-v'>http://www.voynichese.com/#/lay:character-x-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-y'>http://www.voynichese.com/#/lay:character-x-vs-y</a><br>
<a href='http://www.voynichese.com/#/lay:character-x-vs-z'>http://www.voynichese.com/#/lay:character-x-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-a'>http://www.voynichese.com/#/lay:character-y-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-c'>http://www.voynichese.com/#/lay:character-y-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-d'>http://www.voynichese.com/#/lay:character-y-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-e'>http://www.voynichese.com/#/lay:character-y-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-f'>http://www.voynichese.com/#/lay:character-y-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-g'>http://www.voynichese.com/#/lay:character-y-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-h'>http://www.voynichese.com/#/lay:character-y-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-i'>http://www.voynichese.com/#/lay:character-y-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-k'>http://www.voynichese.com/#/lay:character-y-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-l'>http://www.voynichese.com/#/lay:character-y-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-m'>http://www.voynichese.com/#/lay:character-y-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-n'>http://www.voynichese.com/#/lay:character-y-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-o'>http://www.voynichese.com/#/lay:character-y-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-p'>http://www.voynichese.com/#/lay:character-y-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-q'>http://www.voynichese.com/#/lay:character-y-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-r'>http://www.voynichese.com/#/lay:character-y-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-s'>http://www.voynichese.com/#/lay:character-y-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-t'>http://www.voynichese.com/#/lay:character-y-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-v'>http://www.voynichese.com/#/lay:character-y-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-x'>http://www.voynichese.com/#/lay:character-y-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-y-vs-z'>http://www.voynichese.com/#/lay:character-y-vs-z</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-a'>http://www.voynichese.com/#/lay:character-z-vs-a</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-c'>http://www.voynichese.com/#/lay:character-z-vs-c</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-d'>http://www.voynichese.com/#/lay:character-z-vs-d</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-e'>http://www.voynichese.com/#/lay:character-z-vs-e</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-f'>http://www.voynichese.com/#/lay:character-z-vs-f</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-g'>http://www.voynichese.com/#/lay:character-z-vs-g</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-h'>http://www.voynichese.com/#/lay:character-z-vs-h</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-i'>http://www.voynichese.com/#/lay:character-z-vs-i</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-k'>http://www.voynichese.com/#/lay:character-z-vs-k</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-l'>http://www.voynichese.com/#/lay:character-z-vs-l</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-m'>http://www.voynichese.com/#/lay:character-z-vs-m</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-n'>http://www.voynichese.com/#/lay:character-z-vs-n</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-o'>http://www.voynichese.com/#/lay:character-z-vs-o</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-p'>http://www.voynichese.com/#/lay:character-z-vs-p</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-q'>http://www.voynichese.com/#/lay:character-z-vs-q</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-r'>http://www.voynichese.com/#/lay:character-z-vs-r</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-s'>http://www.voynichese.com/#/lay:character-z-vs-s</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-t'>http://www.voynichese.com/#/lay:character-z-vs-t</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-v'>http://www.voynichese.com/#/lay:character-z-vs-v</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-x'>http://www.voynichese.com/#/lay:character-z-vs-x</a><br>
<a href='http://www.voynichese.com/#/lay:character-z-vs-y'>http://www.voynichese.com/#/lay:character-z-vs-y</a><br>
