# lrmi-examples
This repository contains examples of LRMI learning resoursce descriptions.

##Contents:
###LRexample01.jsonld 
Example of description with many alignments to Common Core State Standards, in JSON LD, from Learning Registry provided by Jason Hoekstra.
* LRexample01a_md.html - same resource described in LRexample01.jsonld, but simplified and expressed in html with microdata.
* LRexample01a.json-ld - same description asLRexample01a_md.html but expressed in JSON-LD

###type+audience+level.html 
Example plain HTML description including educational resource types, an educational target audience, and an alignment to an educational level. Designed to illustrate that the target audience and educational level alignment do not necessarily relate to the same user.
* type+audience+level_md.html - same as type+audience+level.htm but with microdata in the HTML
* type+audience+level_rdfa.html - same as type+audience+level.htm but with RDFa in the HTML
* type+audience+level_jsonld.json - same resource as described in type+audience+level.htm but described in JSON-LD

Note: all variants of type+audience+level.html validate with:
* https://developers.google.com/structured-data/testing-tool/
* https://webmaster.yandex.com/microtest.xml
* http://linter.structured-data.org/
