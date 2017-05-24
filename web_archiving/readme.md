Comparison of web archiving software
====================================

There exist many software systems for crawling and archiving web sites.  It is not always easy to tell which features different software systems possess or how different software systems differ from each other.  The goal of this research project is to fill this gap, by providing a comprehensive comparison of software systems for archiving web sites.

[![dependencies](https://img.shields.io/badge/dependencies-none-brightgreen.svg?style=flat-square)](http://shields.io)
[![chat](https://img.shields.io/badge/chat-Slack-yellow.svg?style=flat-square)](https://archivers-slack.herokuapp.com)

📚 Data
--------

The current form of this comparison is a [Google spreadsheet](https://docs.google.com/spreadsheets/d/1FqxwaZnIhhQ7jDCC-W64NMRf5rDeh2Shx3u01MsBmTQ/edit#gid=0), for simplicity of presentation and (hopefully) to make it easier for other people to get involved:

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

* _**Library API**:_ does it provide an explicit libary interface? (I.e., does it provide an API so that you can use it in your own program?)

* _**Network API**:_ whether the software offers a way to control its operation at run-time, either via a separate client program or via a well-defined RPC mechanism.

* _**Extensibility framework**:_ whether the base software can be extended via plug-ins or some other relatively easy way.

* _**Parallel crawling**:_ can the software _itself_ harvest website data from multiple sites in parallel?  (Note that this does not refer to trivial parallelism that one can achieve by running multiple copies of the software; this refers to whether the software itself is designed for doing parallel crawling.)

* _**Scheduled crawling**:_ does the software provide a way to schedule crawls, for example, based on the time of day?

* _**URL filtering**:_ does the software offer a way to filter the URLs to be crawled/scraped/harvested using rules, regular expressions, or other filter scheme?

* _**Crawl storage format(s)**:_ storage format(s) in which web archiving results are stored. 

* _**Capture raw response**:_ does the software capture and archive the raw HTTP server responses along with the web page content?

* _**Extract links from JavaScript**:_ Can the software read the text of JavaScript (even if it can't execute the JavaScript) and extract links/URLs from the text?

* _**Run JavaScript**:_ Can the software run JavaScript (e.g., using a headless browser, PhantomJS, or some other technology)?

* _**Extract links from Flash**:_ Can the software analyze Adobe Flash content to extract links/URLs?

* _**Run Flash**:_ Can the software run Adobe Flash content?

* _**Targeted scraping**:_ Can the user specify how subregions of web pages should be processed? (E.g., using some kind of rule-based scraping or pattern languages like XPath.)

* _**Manual form interaction**:_ Can the user define ways of interacting with web forms? This typically means describing web page scraping procedures. Usually these are defined using a scripting language of some kind, but some software systems offer using a visual GUI to define scraping procedures.

* _**Auto form extraction**:_ Can the software automatically infer how to interact with web forms, and interrogate the data resource behind the web form?

* _**Browse**:_ does the software offer a way to browse the archives it creates?

* _**Playback**:_ does the software offer a way to view/playback the contents of archives it creates?

* _**Full-text search**:_ does the software offer a way to search the contents of the archives it creates?

* _**Notable users**:_ list of notable users or organizations that use the software.

* _**Notes and comments**:_ miscellaneous comments and notes.

* _**Evaluation date**:_ last date when the content of this entry was reviewed and/or updated.


👋 Get involved
----------------

Please **help us improve this resource**!  We welcome additions and corrections.  You can do this in a number of ways:

* Edit the spreadsheet directly &ndash; the spreadsheet is publicly editable.

* Leave a comment on the spreadsheet.  You can use Google docs' built-in facility for putting comments into spreadsheet cells, and tell us something that way.

* Log an issue in this repo.

* Contact us directly: you can [join the archivers.space Slack](https://github.com/edgi-govdata-archiving/archivers.space) or email [mhucka](https://github.com/mhucka) or [b5](https://github.com/b5).

Please make sure to follow the general [EDGI code of conduct](https://github.com/edgi-govdata-archiving/overview/blob/master/CONDUCT.md) for involvement in this work.
