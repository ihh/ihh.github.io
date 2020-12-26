+++
description = ""
external_link = ""
image = ""
participants = []
project_id = "jbrowse"
short_description = "Why shouldn't bioinformatics be as easy, intuitive, and collaborative as the rest of the web?"
title = "Web Genomics"

+++

Our work developing web-based visualizations of genomic data is based on observation of how the consumer web has transformed user interface design.
Genome sciences are fundamental to the 21st century, so why shouldn't genome scientsts enjoy web tools that are as sophisticated as those used
for web-based word processors, spreadsheets, and maps?

This is not just a frivolous issue: the consensus doctrine of web app design that has emerged in the early 21st century
includes many lessons about issues such as navigational continuity and dynamic data representation.
Genomes are a foreign type of data that present an inherently alien landscape;
navigating them is at least as tricky as navigating a word processor document or a spreadsheet.

At the end of the 20th century, bioinformatics hackers were also web pioneers,
with our [Perl scripts](https://en.wikipedia.org/wiki/CGI.pm) powering the likes of Amazon.
Sadly, things have gone downhill (relatively speaking), and bioinformatics tools these days are generally not nearly as usable as consumer-facing websites.

With the aim of changing that, we take front-end engineering as seriously, in genomics, as it is in Silicon Valley.
[JBrowse](http://jbrowse.org/), our JavaScript genome browser, uses modern infrastructure (e.g. npm, React, TypeScript) and a modular plugin-based approach.
It's highly popular for small genome projects, logging over 110k [Monthly Active Users](https://en.wikipedia.org/wiki/Active_users);
Colin Diesh maintains a list of [awesome sites that use it](https://github.com/cmdcolin/awesome-jbrowse).
JBrowse is also the basis for [Apollo](http://genomearchitect.org/), our collaborative genome annotation tool.

We are actively extending JBrowse for applications in cancer (particularly the visualization of [structural variation](https://en.wikipedia.org/wiki/Structural_variation))
and comparative genomics.
