# An Empirical Study on Parameter Rules

## Project summary
Developers widely use software libraries to reduce programming efforts. When calling library APIs, developers should understand
rules of API usage and correctly use APIs. As violating such rules can introduce bugs, researchers have proposed various approaches
that mine and check API usage rules. Although the research topic is intensively studied, some fundamental problems are still open.
For example, existing approaches typically use predefined templates to mine rules, but it is unclear how effectively those templates can
reveal API parameter rules. Some researchers built approaches to mine parameter rules from traces or documents, but it is unclear how
the two research lines complement each other. 

In this project, we analyzed 93,643 methods of 9 popular API libraries. The results are reported in our submitted paper. 

## Dataset
[asm](/rep/asm.rar) [commons-io](/rep/commons-io.rar) [itext](/rep/itext.rar) [jfreechart](/rep/jfreechart.rar) [jmonkey](/rep/jmonkey.rar) [lucene](/rep/lucene.rar) [pdfbox](/rep/pdfbox.rar) [poi](/rep/poi.rar) [shiro](/rep/shiro.rar)

## Found parameter rules
[asm](/rules/asm.txt) [commons-io](/rules/commons-io.txt) [itext](/rules/itext.txt) [jfreechart](/rules/jfreechart.txt) [jmonkey](/rules/jmonkey.txt) [lucene](/rules/lucene.txt) [pdfbox](/rules/pdfbox.txt) [poi](/rules/poi.txt) [shiro](/rules/shiro.txt)

+c denotes that a parameter has a code rule.
+d denotes that a parameter has a document rule.
