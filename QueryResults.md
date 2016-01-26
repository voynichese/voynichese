# Overview #

Voynichese queries are evaluated at the word level - see [QueryBasics](QueryBasics.md) - and yield a set of values describing the occurrence of matching words within the manuscript and individual folios.

The following are the quantities resulting from Voynichese queries.

<p align='center'>
<img src='http://wiki.voynichese.googlecode.com/git/voynichese-result-info.png' />
</p>
<p align='center'>
<i>The resulting quantities for the query matching all occurrences of EVA "daiin".</i>
</p>

### Total ###

The total number of words in the manuscript that match the query.

_If a matching word occurs X times in the manuscript then all X occurrences are included in the total value._

When the percentages option is selected, the value is computed relative to the total number of words in the manuscript - currently estimated at 37,886.

### A Folios ###

The total number of words in the set of A folios that match the query.

_If a matching word occurs X times among A folios then all X occurrences are included in the value._

When the percentages option is selected, the value is computed relative to the total number of words in A folios - currently estimated at 11,405.

Note that some folios are not classified as either A or B, therefore the sum of the totals for A and B folios is not equivalent to the manuscript total. To learn more about A and B folios see [Currier's hands](http://voynich.nu/writing.html#hands).

### B Folios ###

The total number of words in the set of B folios that match the query.

_If a matching word occurs X times among B folios then all X occurrences are included in the value._

When the percentages option is selected, the value is computed relative to the total number of words in B folios - currently estimated at 23,202.

Note that some folios are not classified as either A or B, therefore the sum of the totals for A and B folios is not equivalent to the manuscript total. To learn more about A and B folios see [Currier's hands](http://voynich.nu/writing.html#hands).

### Folio Start ###

The total number of words, among the set of folio-initial words, that match the query.

Note that the first word in folios containing circular diagrams is often subject to interpretation and should thus be taken as an estimate according to the transcription author's best judgement.

_If a matching word occurs X times at the start of multiple folios then all X occurrences are included in the value._

When the percentages option is selected, the value is computed relative to the total number of transcribed folios - currently 225.

### Folio End ###

The total number of words, among the set of folio-final words, that match the query.

Note that the last word in folios containing circular diagrams is often subject to interpretation and should thus be taken as an estimate according to the transcription author's best judgement.

_If a matching word occurs X times at the end of multiple folios then all X occurrences are included in the value._

When the percentages option is selected, the value is computed relative to the total number of transcribed folios - currently 225.

### Paragraph Start ###

The total number of words, among the set of paragraph-initial words, that match the query.

Note that paragraph boundaries may be subject to interpretation and should thus be taken as an estimate according to the transcription author's best judgement. Additionally, labels and other isolated words are processed as single-word paragraphs.

_If a matching word occurs X times at the start of multiple paragraphs then all X occurrences are included in the value._

When the percentages option is selected, the value is computed relative to the total number of paragraphs, estimated at 1,775.

### Paragraph End ###

The total number of words, among the set of paragraph-final words, that match the query.

Note that paragraph boundaries may be subject to interpretation and should thus be taken as an estimate according to the transcription author's best judgement. Additionally, labels and other isolated words are processed as single-word paragraphs.

_If a matching word occurs X times at the end of multiple paragraphs then all X occurrences are included in the value._

When the percentages option is selected, the value is computed relative to the total number of paragraphs, estimated at 1,775.

### Line Start ###

The total number of words, among the set of line-initial words, that match the query.

Note that lines intersected by illustrations are treated as a single line. Additionally, labels and other isolated words are processed as single-word lines.

_If a matching word occurs X times at the start of multiple lines then all X occurrences are included in the value._

When the percentages option is selected, the value is computed relative to the total number of lines, estimated at 5,171.

### Line End ###

The total number of words, among the set of line-final words, that match the query.

Note that lines intersected by illustrations are treated as a single line. Additionally, labels and other isolated words are processed as single-word lines.

_If a matching word occurs X times at the end of multiple lines then all X occurrences are included in the value._

When the percentages option is selected, the value is computed relative to the total number of lines, estimated at 5,171.

### Distinct ###

The total number of distinct words in the manuscript that match the query.

_Note that, unlike other values, even if a matching word occurs multiple times in the manuscript, it is only counted once._

When the percentages option is selected, the value is computed relative to the total number of distinct words in the manuscript, estimated at 8,078. The set of distinct words corresponds to the Voynichese vocabulary.

### Unique ###

The total number of words in the manuscript that match the query and occur exactly once.

When the percentages option is selected, the value is computed relative to the total number of unique words in the manuscript, estimated at 5,571.

### Variants ###

The total number of words in the manuscript that differ from the query word by at most one operation - where an operation is either a character insertion, deletion or replacement.

Note that this quantity is only applicable to exact queries that do not contain wildcards - see [QueryBasics](QueryBasics.md) for more information on exact queries and wildcards.