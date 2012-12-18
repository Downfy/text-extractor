Text Extractor
==============
Implement project Boilerplate Removal and Fulltext Extraction from HTML pages


Summary
=======
The boilerpipe library provides algorithms to detect and remove the surplus "clutter" (boilerplate, templates) around the main textual content of a web page.

The library already provides specific strategies for common tasks (for example: news article extraction) and may also be easily extended for individual problem settings.

Extracting content is very fast (milliseconds), just needs the input document (no global or site-level information required) and is usually quite accurate.

Boilerpipe is a Java library written by Christian Kohlschütter. It is released under the Apache License 2.0.

The algorithms used by the library are based on (and extending) some concepts of the paper "Boilerplate Detection using Shallow Text Features" by Christian Kohlschütter et al., presented at WSDM 2010 -- The Third ACM International Conference on Web Search and Data Mining New York City, NY USA. Click here to read the paper and the presentation slides. A video of the presentation is freely available on Videolectures.net (turn speaker balance to the left to improve audio quality).

Commercial support is available through Kohlschütter Search Intelligence.

News
====
(2011-06-06) boilerpipe 1.2.0
Bug fixes, some new label extensions, heuristics. Brings boilerpipe-core up-to-date with boilerpipe-web.

(2010-11-02) boilerpipe Web API
You can now test drive boilerpipe on the Web: http://boilerpipe-web.appspot.com/.

(2010-11-02) boilerpipe 1.1.0
Added an estimator for Extraction Quality, HTML-level Extraction capabilities, a new CanolaExtractor, a home for common extractors, TextBlock#clone and a new block-level labeling framework. Plus some bug fixes, especially affecting the extraction of HTML from wikipedia.org.

(2010-05-06) boilerpipe 1.0.4
Now supports TagSoup and other HTML balancers through a SAX ContentHandler. Boilerpipe now available in its own Maven repository.

(2010-01-30) boilerpipe 1.0.3
Two bug fixes (XML parsing issues). Issues #1 and #2. (Thanks to Tom Taylor, Kaspar Fischer and nedunk for reporting the problems)

(2009-12-10) boilerpipe 1.0.2
This release hot-fixes a NekoHTML bug which caused low-quality results in a rare situation. (Thanks to Kris Jirapinyo for reporting the problem)

(2009-12-04) boilerpipe 1.0.1
Added the dependency libs (xerces and nekohtml) and the javadocs to the binary tarball. (Thanks to Mike Matthews for reporting the problem)

(2009-12-03) boilerpipe 1.0.0
The code is now online. Have fun!

Getting Started
===============
To get started, see the documentation in the Wiki and the binary and source tarballs. Please also read the FAQ, it contains important information.

About the Author
================
Christian Kohlschütter has done his PhD research on boilerplate removal at L3S Research Center. His main research interests are in the area of Web Information Retrieval and Quantitative Linguistics.
