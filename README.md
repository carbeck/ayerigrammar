A Grammar of Ayeri
==================

This is a renewed effort, started in July 2016, to revise and to expand on what can be found on the internet as _A Grammar of Ayeri_ ([PDF, January 2011](https://rawgit.com/carbeck/ayerigrammar/master/misc/ayeri_grammar_2011.pdf)). You can also take a look at the [most recently compiled PDF of the current working draft](https://rawgit.com/carbeck/ayerigrammar/master/grammar.pdf) (see the [file's history](https://github.com/carbeck/ayerigrammar/commits/master/grammar.pdf)). Ayeri is a fictional language (a "conlang") which I have been developing since December 2003. Work on this project basically serves as a creative outlet to my ongoing interest in linguistics.

I had been leaving the earlier grammar document in a very sorry and unfinished state for over 5 years before finally returning to it, prompted by a [class on constructed languages](http://www.sfs.uni-tuebingen.de/~abuch/16ss/conlang.html) at the University of Tübingen in the summer semester of 2016 which used Ayeri as one of its objects of study. The work presented here is mostly a complete rewrite of the old grammar sketch from scratch, not merely an extension.

I hope that by using LaTeX and GitHub, the whole process of editing will be more easy to handle and more transparent than when I was trying to work with one big LibreOffice document before. If you feel inclined to do so, you can [report issues on GitHub](https://github.com/carbeck/ayerigrammar/issues).

Currently working on
====================

**WARNING**: This is work heavily in progress! The following part(s) are currently being proofread for a second time, since there are still some typos, inattentive gibberish, and odd-looking page breaks in need of fixing here and there:

* Phrase structures (`chapters/syntax.tex`)
  * Adjective and adverb phrases

Proofreading also resulted in the realization that a number of additional content-related changes need to be made besides changes in phrasing and spelling corrections:
  * AP subchapter: Possessive pronouns are not adjectives but determiners.
  * PP subchapter: *ku-* serves as a preposition with case-unmarked nouns: 'as a X'/'like X (is)'.
  * CP subchapter: *ku-*/*-ku* serves as a conjunction with case-marked nouns: 'like X (does)'.
  * IP subchapter: modifiers of I⁰ should be in a separate IP so that S can remain a complement. An analysis of S as Spec makes no sense at all.

These changes will be made as I am reviewing the respective sections for spelling etc.

The [sections not currently worked on](https://github.com/carbeck/ayerigrammar#table-of-contents) have been proofread at least once, by myself. They should already provide useful information, however, I may still make changes if I notice something to be wrong or information to be missing or inconsistent. Note that I am not a native English speaker; corrections are thus welcome.

I will tag a release (basically "first edition") only when everything is as complete as I can get it for the moment. Complete means that the finished manuscript contains information on the phonology, morphology and syntax of the language which provides a consistent description and analysis of the most frequently occurring structures and constructions of the language. The finished manuscript is also supposed to be on par with professional literature in both language and style with regards to good readability.

Roadmap
=======

* proofread and correct *whole* thing again
* maybe extend name list with etymologies
* make index
* look into print-on-demand options

Table of Contents
=================

The table of contents encompasses the following topics so far; the LaTeX source files for each chapter are given in brackets.

1. Phonology (`chapters/phonology.tex`)
   1. Phoneme inventory
   2. Phonotactics
   3. Notes on prosody
2. Writing system (`chapters/writing.tex`)
3. Morphological typology (`chapters/morphtyp.tex`)
4. Grammatical categories (`chapters/gramcat.tex`)
   1. Nouns
   2. Pronouns
   3. Adjectives
   4. Adpositions
   5. Verbs
   6. Adverbs
   7. Numerals
   8. Conjunctions
5. Phrase structures (`chapters/syntax.tex`)
   1. Noun and determiner phrases
   2. Adjective and adverb phrases
   3. Adpositional phrases
   4. Inflectional and verb phrases
   5. Complementizer phrases

Compiling
=========

Compile `grammar.tex` with `xelatex`, `biber`, `makeindex` and `makeglossaries`, or use `arara grammar` to do all the required steps automatically. A standard TeXLive 2015 installation should bring all package dependencies, with the notable exception of the `avm` package, which you may have to download from [Christopher Manning's website](http://nlp.stanford.edu/manning/tex/) and unzip somewhere in LaTeX's `PATH` (e.g. `~/texmf/tex/latex`). Fonts used:

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
