A Grammar of Ayeri
==================

This is a renewed effort, started in July 2016, to revise and to expand on what is currently on [my Ayeri website](https://benung.nfshost.com) as _A Grammar of Ayeri_ ([PDF](https://dl.dropboxusercontent.com/u/8026017/Ayeri%20grammar/grammar.pdf)). This earlier attempt has been left in a very sorry and unfinished state for over 5 years now. I hope that by transferring things to LaTeX, the whole process of editing will become more easy to handle than when I was trying to work with one big document in LibreOffice before. If you feel inclined to do so, you can report issues as such on the [repository page](https://github.com/carbeck/ayerigrammar).

Table of Contents
=================

**WARNING**: This is work heavily in progress! The table of contents encompasses the following topics so far:

1. Phonology `chapters/phonology.tex`
   1. Phoneme Inventory
   2. Phonotactics
   3. Notes on Prosody
2. Writing System `chapters/writing.tex`
3. Morphological Typology `chapters/morphtyp.tex`
4. Grammatical Categories `chapters/gramcat.tex`
   1. Nouns
   2. Pronouns
   3. Adjectives
   4. Adpositions
   5. Verbs

Currently working on:

* Grammatical Categories
  6. Adverbs
  7. Numerals
  8. Conjunctions

The sections not currently worked on have been proofread once by myself. Note that I am not a native English speaker; corrections are thus welcome. The proofread parts should already provide useful information, however, I will still make changes every now and then if I notice something to be wrong or information to be missing. If you're brave, you can also [take a look at the most recently compiled PDF](https://rawgit.com/carbeck/ayerigrammar/master/grammar.pdf). I will tag a release (basically "first edition") only when everything is as complete as I can get it for the moment. Notably, the section on syntax—discussing the various constituent types (NP, VP, PP, ...) and how to put them together to form valid sentences—is missing so far, since my approach is to go from the smallest to the largest units.

Compiling
=========

Compile with `xelatex`, `biber`, `makeindex` and `makeglossaries`, or use `arara`. A standard TeXLive 2015 installation should bring all package dependencies. Fonts used:

* Body text: [Junicode](http://junicode.sourceforge.net/)
* Captions, Headings: [Fira Sans](https://carrois.com/typefaces/FiraSans/)
* Examples: [Tagati Book G](https://github.com/carbeck/tagatibookg)
* Other:
  * [DejaVu Sans Mono](http://dejavu-fonts.org/)
  * [Free Serif](https://www.gnu.org/software/freefont/)
  * [Tuladha Jejeg](https://sites.google.com/site/jawaunicode/main-page)

Licensing
=========

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

Carsten Becker, 2016. This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
