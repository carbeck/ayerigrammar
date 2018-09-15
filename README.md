A Grammar of Ayeri
==================

This is a renewed effort, started in July 2016, to revise and to expand on earlier attempts of documenting Ayeri's grammar. A PDF of the [most recent version of the working draft](https://rawgit.com/carbeck/ayerigrammar/master/grammar.pdf) is compiled regularly (see the [file's history](https://github.com/carbeck/ayerigrammar/commits/master/grammar.pdf)). Ayeri is a fictional language (a "conlang") which I have been developing since December 2003. Work on this project basically serves as a creative outlet to my ongoing interest in linguistics.

I had been leaving the old grammar document ([PDF, January 2011](https://rawgit.com/carbeck/ayerigrammar/master/misc/ayeri_grammar_2011.pdf)) in a very sorry and unfinished state for over 5 years before finally returning to working on documentation, prompted by a [class on constructed languages](http://www.sfs.uni-tuebingen.de/~abuch/16ss/conlang.html) at the University of Tübingen in the summer semester of 2016 which used Ayeri as one of its objects of study. The work presented here is mostly a complete rewrite of the old grammar sketch from scratch, not merely an extension.

I hope that by using LaTeX and GitHub, the whole process of editing will be more easy to handle and more transparent than when I was trying to work with one big LibreOffice document before. If you feel inclined to do so, you can [report issues on GitHub](https://github.com/carbeck/ayerigrammar/issues).

Download
========

[Download the most recent draft in PDF format](https://rawgit.com/carbeck/ayerigrammar/master/grammar.pdf)

Currently working on
====================

**WARNING**: This is work in progress! Currently working on:

* Proofreading the whole thing again (with additional support from [Greg Shuflin](https://github.com/neunenak) and [Joey Windsor](https://sites.google.com/view/joseph-windsor/))
* NPs and APs probably need to be reanalyzed slightly, [read why and how on the blog](https://ayeri.de/archives/7104)

The document has been proofread at least three times, by myself. It should already provide useful information, however, I may still make changes if I notice something to be wrong or information to be missing or inconsistent. Note that I am not a native English speaker; corrections are thus welcome, both regarding language and content. The latter especially regarding my analysis of Ayeri's syntax.

I will tag a release (basically "first edition") only when everything is as complete as I can get it for the moment. Complete means that the finished manuscript contains information on the phonology, morphology and syntax of the language which provides a consistent description and analysis of the most frequently occurring structures and constructions of the language. The finished manuscript is also supposed to be on par with professional literature in both language and style with regards to good readability and accuracy of description.

Compiling
=========

Compile `grammar.tex` with `xelatex`, `biber`, `makeindex` and `makeglossaries`, or use `arara grammar` to do all the required steps automatically. 
TeXLive 2018 should bring all package dependencies, with the notable exception of the `avm` package, which you may have to download from [Christopher Manning's website](http://nlp.stanford.edu/manning/tex/) and unzip somewhere in LaTeX's `PATH` (e.g. `~/texmf/tex/latex`). Fonts used:

* Body text: [Junicode](http://junicode.sourceforge.net/)
* Captions, Headings: [Fira Sans](https://carrois.com/typefaces/FiraSans/)
* Examples: [Tagati Book G](https://github.com/carbeck/tagatibookg)
* Other:
  * [DejaVu Sans Mono](http://dejavu-fonts.org/)
  * [Free Serif](https://www.gnu.org/software/freefont/)
  * [Tuladha Jejeg](https://sites.google.com/site/jawaunicode/main-page)

Licensing
=========

Carsten Becker, 2016–18. This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
