A Grammar of Ayeri
==================

This is a renewed effort, started in July 2016, to revise and to expand on what can be found on the internet as _A Grammar of Ayeri_ ([PDF](https://rawgit.com/carbeck/ayerigrammar/master/misc/ayeri_grammar_2011.pdf)). This earlier documentation attempt had been left in a very sorry and unfinished state for over 5 years before returning to it. I hope that by transferring things to LaTeX, the whole process of editing will be more easy to handle and more transparent than when I was trying to work with one big document in LibreOffice before. If you feel inclined to do so, you can report issues as such on the [repository page](https://github.com/carbeck/ayerigrammar).

Ayeri is a fictional language project I have been working on since December 2003. Work on this project basically serves as a creative outlet to my ongoing interest in linguistics.

Currently working on
====================

**WARNING**: This is work heavily in progress! Things may still be a little rough around the edges, especially the parts currently worked on:

* Phrase structures (source: `chapters/syntax.tex`)
    1. Noun- and determiner phrases

Table of Contents
=================

The table of contents encompasses the following topics so far:

1. Phonology (source: `chapters/phonology.tex`)
   1. Phoneme Inventory
   2. Phonotactics
   3. Notes on Prosody
2. Writing System (source: `chapters/writing.tex`)
3. Morphological Typology (source: `chapters/morphtyp.tex`)
4. Grammatical Categories (source: `chapters/gramcat.tex`)
   1. Nouns
   2. Pronouns
   3. Adjectives
   4. Adpositions
   5. Verbs
   6. Adverbs
   7. Numerals
   8. Conjunctions

The sections not currently worked on have been proofread once by myself. The proofread parts should already provide useful information, however, I may still make changes occasionally if I notice something to be wrong or information to be missing. Note that I am not a native English speaker; corrections are thus welcome. If you're brave, you can [take a look at the most recently compiled PDF](https://rawgit.com/carbeck/ayerigrammar/master/grammar.pdf).

I will tag a release (basically "first edition") only when everything is as complete as I can get it for the moment. Notably, the section on syntax—discussing the various constituent types (NP, VP, PP, ...) and how to put them together to form valid sentences—is incomplete so far, since my approach is to go from the smallest to the largest units.

Compiling
=========

Compile `grammar.tex` with `xelatex`, `biber`, `makeindex` and `makeglossaries`, or use `arara grammar` to do all the required steps automatically. A standard TeXLive 2015 installation should bring all package dependencies, with the notable exception of the `avm` package, which you may have to download from [Christopher Manning's website](http://nlp.stanford.edu/manning/tex/) and unzip somewhere in TeX's `PATH` (e.g. `~/texmf/tex/latex`). Fonts used:

* Body text: [Junicode](http://junicode.sourceforge.net/)
* Captions, Headings: [Fira Sans](https://carrois.com/typefaces/FiraSans/)
* Examples: [Tagati Book G](https://github.com/carbeck/tagatibookg)
* Other:
  * [DejaVu Sans Mono](http://dejavu-fonts.org/)
  * [Free Serif](https://www.gnu.org/software/freefont/)
  * [Tuladha Jejeg](https://sites.google.com/site/jawaunicode/main-page)

Licensing
=========

Carsten Becker, 2016–17. This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
