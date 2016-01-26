# Key Concepts #

The Voynichese project (VP) defines a simple syntax for querying words in the Voynich Manuscript. While this syntax is only used internally, by the VP's query processor, it's important to be aware of how it operates in order to effectively query the manuscript.

Note that, unlike most query languages, Voynichese queries are evaluated at the word level. As such, word delimiters like whitespace and punctuation are not allowed.

Voynichese queries may use the following characters:

`a,c,d,e,f,g,h,i,k,l,m,n,o,p,q,r,s,t,v,x,y,z,*,^,$`

The characters a-z each match the corresponding EVA character.

The wildcard character "`*`" matches one or more EVA characters. Note that the wildcard may also be represented as a dash "-", for example when used in an URL.

The "`^`" character matches the start of a word.

The "`$`" character matches the end of a word.

For example, the query `^daiin$` will exactly match the EVA word _daiin_, whereas the query `daiin` (excluding the `^` and `$` symbols) will match any EVA word containing _daiin_, such as _chodaiindy_.

See the [QueryResults](QueryResults.md) overview for information about quantities resulting from Voynichese queries.

# Exact Queries #

When interacting with the Voynichese query user interface, queries are implicitly wrapped between "`^`" and "`$`" whenever the _Exact_ option is selected.

The following screenshot shows a query for `daiin` with the _Exact_ option selected - highlighted in red - which internally evaluates to `^daiin$`.

![http://wiki.voynichese.googlecode.com/git/exact.png](http://wiki.voynichese.googlecode.com/git/exact.png)


# Wildcard Queries #

Queries containing the wildcard character "`*`" match a variable number of words. For example the query `^da*n$` will match _dain_, _daiin_ and _daiiin_ in addition to _daiiiolkaiin_. In these cases the wildcard character matches _i_, _ii_, _iii_ and _iiiolkaii_ respectively.

Voynichese queries may contain any number of wildcards. For example, the query `^q*e*y$` will match _qokeedy_, _qopeedy_, _qoeey_ and so on.

Note that multiple consecutive wildcard characters are collapsed into a single one - for example the query `^q***y$` is equivalent to `^q*y$`.


# Prefix & Suffix Queries #

A combination of the wildcard character "`*`" with the _Exact_ option may be used to query words by suffix or prefix.

For example, the query `^*edy$` matches all words ending with _edy_. Note that without the _Exact_ option, this query becomes `*edy` which will also match words like _chedyty_. It is therefore important to use the _Exact_ option when performing a prefix or suffix query.

An example of a prefix query is `^qo*$`, which matches words like _qokeedy_ and _qokol_.


# Character Queries #

It's possible to query the manuscript to analyze the occurrence of a given character, using non-exact queries.

For example, the simple query `o` will match any word containing the character _o_ one or more times. Note that the exact version of this query, `^o$`, will only match the word _o_. As such, character queries should not use the _Exact_ option.