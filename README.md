A Grammar of Ayeri
==================

This is a renewed effort, started in July 2016, to revise and to expand on earlier attempts of documenting Ayeri's grammar. A PDF of the [most recent version of the working draft](https://rawgit.com/carbeck/ayerigrammar/master/grammar.pdf) is compiled regularly (see the [file's history](https://github.com/carbeck/ayerigrammar/commits/master/grammar.pdf)). Ayeri is a fictional language (a "conlang") which I have been developing since December 2003. Work on this project basically serves as a creative outlet to my ongoing interest in linguistics.

I had been leaving the old grammar document ([PDF, January 2011](https://rawgit.com/carbeck/ayerigrammar/master/misc/ayeri_grammar_2011.pdf)) in a very sorry and unfinished state for over 5 years before finally returning to working on documentation, prompted by a [class on constructed languages](http://www.sfs.uni-tuebingen.de/~abuch/16ss/conlang.html) at the University of Tübingen in the summer semester of 2016 which used Ayeri as one of its objects of study. The work presented here is mostly a complete rewrite of the old grammar sketch from scratch, not merely an extension.

I hope that by using LaTeX and GitHub, the whole process of editing will be more easy to handle and more transparent than when I was trying to work with one big LibreOffice document before. If you feel inclined to do so, you can [report issues on GitHub](https://github.com/carbeck/ayerigrammar/issues).

Currently working on
====================

The book has been proofread fully at least three times by myself, and the first 2 chapters have also been read over for style and consistency by 2 other English speakers (thanks, guys!). Either way, I am not a native English speaker and especially small mistakes like missing or swapped letters are easy to overlook. Corrections are thus definitely still welcome, both regarding language and content. The latter especially regarding my analyses of Ayeri's syntax. There are also still some topics that the grammar admittedly does not cover yet, see the 'desiderata' keyword in the index and the pages referenced there. These are still open for future consideration (check out the [Blog](https://ayeri.de/blog)).

Download
========

* [Download the most recent **stable version** (v1.0) in PDF format](https://github.com/carbeck/ayerigrammar/releases/download/v1.0/ayeri-grammar-20181001.pdf)
* [Download the most recent **working draft** in PDF format](https://rawgit.com/carbeck/ayerigrammar/master/grammar.pdf)

<!--
Print on Demand
===============

* You can also [buy a full-fledged on-demand **print edition** of the book from Lulu.com]() or your favorite bookseller. This corresponds to v1.0 as hosted on GitHub.
-->

Compiling
=========

Compile `grammar.tex` with `xelatex`, `biber`, `makeindex` and `makeglossaries`, or use `arara grammar` to do all the required steps automatically. 
TeXLive 2018 should bring all package dependencies, with the notable exception of the `avm` package, which you may have to download from [Christopher Manning's website](http://nlp.stanford.edu/manning/tex/) and unzip somewhere in LaTeX's `PATH` (e.g. `~/texmf/tex/latex`). Fonts used:

* Body text: [Junicode](http://junicode.sourceforge.net/)
* Captions, Headings: [Fira Sans](https://carrois.com/typefaces/FiraSans/)
* Ayeri text: [Tagati Book G](https://github.com/carbeck/tagatibookg)
* Other:
  * [DejaVu Sans Mono](http://dejavu-fonts.org/)
  * [Free Serif](https://www.gnu.org/software/freefont/)
  * [Tuladha Jejeg](https://sites.google.com/site/jawaunicode/main-page)

Licensing
=========

Carsten Becker, 2016–18. This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
