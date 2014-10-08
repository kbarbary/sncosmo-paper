sncosmo-paper
=============

Latex source for sncosmo paper(s):

* `paper1`: General introduction to SNCosmo itself.
* `paper2`: Light curve parameter posterior sampling (with sncosmo).

Currently being prepared for submission to _Astronomy & Computing_, using
the Elsevier document class.

How to Build
------------

In subdirectory, type `make`.

To compile the paper, you need the usual latex suite: `latex`,
`bibtex`, `dvips`, `ps2pdf`. Also, Elsevier's document class,
`elsarticle.cls` and its associated bibliography style file. On Ubuntu,
this comes with the `texlive-publishers` package.

The style file `aas_macros.sty` is included here to define journal
abbreviations used in the bibtex file (for entries provided by ADS).
