Number One 
* `:%s/^\(.*\)$/"\1"/c`

`s/regex/replace/ is vim command for search n replace.
% makes it apply throughout the file
^ and $ denotes start and end of the line respectively.
(.*) captures everything in between. ( and ) needs to be escaped in vim regexes.
\1 puts the captured content between two quotes.`
