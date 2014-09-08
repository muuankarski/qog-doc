---
title: Example of a simple convertible documentation with Markdown & Pandoc
author: Author Name
date: September 8, 2014
...


# Introduction

Content of this doc is copy-pasted from from [Pandoc Markdown](http://rmarkdown.rstudio.com/authoring_pandoc_markdown.html)-documentation by Rstudio, which is basicly a reproduction of most of the pandoc markdown documentation on the Pandoc website, and is © 2006-2013 John MacFarlane (jgm at berkeley dot edu), released under the GPL, version 2 or greater.

Pandoc understands an extended and slightly revised version of John Gruber’s original markdown syntax. This document explains the syntax, noting differences from standard markdown.

# Lists

* fruits
    + apples
        - macintosh
        - red delicious
    + pears
    + peaches
* vegetables
    + broccoli
    + chard

# Images

![Caption is placed here](http://www.qog.pol.gu.se/digitalAssets/1349/1349208_qogeng_webheader.png)

![Picture of the day in Wikimedia Commons [See](http://commons.wikimedia.org/wiki/Main_Page)](Independence_of_Brazil_1888.jpg)


# Tables

## Simple tables

Four kinds of tables may be used. The first three kinds presuppose the use of a fixed-width font, such as Courier. The fourth kind can be used with proportionally spaced fonts, as it does not require lining up columns.
Simple tables

  Right     Left     Center     Default
-------     ------ ----------   -------
     12     12        12            12
    123     123       123          123
      1     1          1             1

Table:  Demonstration of simple table syntax.


## Multiline tables


-------------------------------------------------------------
 Centered   Default           Right Left
  Header    Aligned         Aligned Aligned
----------- ------- --------------- -------------------------
   First    row                12.0 Example of a row that
                                    spans multiple lines.

  Second    row                 5.0 Here's another one. Note
                                    the blank line between
                                    rows.
-------------------------------------------------------------

Table: Here's the caption. It, too, may span
multiple lines.


# Footnotes

Here is a footnote reference,[^1] and another.[^longnote]

[^1]: Here is the footnote.

[^longnote]: Here's one with multiple blocks.

    Subsequent paragraphs are indented to show that they
belong to the previous footnote.

        { some.code }

    The whole paragraph can be indented, or just the first
    line.  In this way, multi-paragraph footnotes work like
    multi-paragraph list items.

This paragraph won't be part of the note, because it
isn't indented.


