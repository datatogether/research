Comparison of web archiving software
====================================

There exist many software systems for crawling and archiving web sites.  It is not always easy to tell which features different software systems possess or how different software systems differ from each other.  The goal of this research project is to fill this gap, by providing a comprehensive comparison of software systems for archiving web sites.

The current form of this comparison is a [Google spreadsheet](https://docs.google.com/spreadsheets/d/1FqxwaZnIhhQ7jDCC-W64NMRf5rDeh2Shx3u01MsBmTQ/edit#gid=0):

<div align="center">
<a href="https://docs.google.com/spreadsheets/d/1FqxwaZnIhhQ7jDCC-W64NMRf5rDeh2Shx3u01MsBmTQ/edit#gid=0"><img src=".graphics/spreadsheet-image-v2.png"></a>
<br>
</div>

The meanings of the columns are the following:

* _**Name**:_ the most common name for the software.

* _**Open source?**:_ the open source license for the software, if it is open source; if it is not open source, then this column will have a cross in it; and if it is some kind of mix (such as a for-pay service that uses an open-source tool at its core), then it will have the symbol &frac12;.

* _**Source repo**:_ link to source code repository (if the software is open source.

* _**Operating system(s)**:_ operating systems on which the software can run.

* _**Primary dev. language**:_ the primary language in which the software is written.

* _**CLI**:_ whether the software offers a command-line interface.

* _**GUI**:_ whether the software offers a graphical user interface.

* _**WUI**:_ whether the software offers a web-based user interface.

* _**Remote control API**:_ whether the software offers a way to control its operation at run-time

* _**Extensibility framework**:_ whether the base software can be extended via plug-ins or some other relatively easy way

* _**Parallel crawling**:_ can the software _itself_ harvest website data from multiple sites in parallel?  (Note that this does not refer to trivial parallelism that one can achieve by running multiple copies of the software; this refers to whether the software itself is designed for doing parallel crawling.)

* _**Scheduled crawling**:_ does the software provide a way to schedule crawls, for example, based on the time of day?

* _**URL filtering**:_ does the software offer a way to filter the URLs to be crawled/scraped/harvested using rules, regular expressions, or other filter scheme?

* _**Crawl storage format(s)**:_ storage format(s) in which web archiving results are stored. 

* _**Capture raw response?**:_ does the software capture and archive the raw HTTP server responses along with the web page content?

* _**Handle JavaScript?**:_ can the software process JavaScript that may be present in web pages?  (This can range from ignoring JavaScript, to being limited to reading only the text of the JavaScript code, to running a JavaScript interpreter and acting on the results.)

* _**Handle web forms?**:_ can the software analyze web forms and submit queries to get results from the forms?

* _**Handle Flash?**:_ can the software analyze Adobe Flash content? (Note: this means to do more than merely store the `.swf` file.)

* _**Handle databases?**:_ can the software harvest the content of databases? (Note: although this sometimes requires handling web forms, for some websites database access is via POST or GET URLs; this is why this is a separate column.)

* _**Browse?**:_ does the software offer a way to browse the archives it creates?

* _**Playback?**:_ does the software offer a way to view/playback the contents of archives it creates?

* _**Full-text search**:_ does the software offer a way to search the contents of the archives it creates?

* _**Notable users**:_ list of notable users or organizations that use the software.

* _**Notes and comments**:_ miscellaneous comments and notes.

* _**Evaluation date**:_ last date when the content of this entry was reviewed and/or updated.

