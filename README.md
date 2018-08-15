# bbcodes_to_html_2
bbcodes to html with pure erlang
for using with https://github.com/221V/SCEditor-2.1.2-fork and google prettify

(updated version of https://github.com/221V/bbcodes_to_html_1 )


use
```
BB_Post3 = bb2html:bb_parser(BB_Post), % here (in BB_Post var) we have list string with bbcodes-text 
unicode:characters_to_binary(BB_Post3 ,utf8) % here we have binary
```
