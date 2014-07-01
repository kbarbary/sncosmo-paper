sncosmo-paper
=============

Latex source for sncosmo paper

Currently being prepared for submission to _Astronomy & Computing_.

Build
-----

Type `make`.

To compile the paper, you need the usual latex suite: `latex`,
`bibtex`, `dvips`, `ps2pdf`. Also, Elsevier's document class,
`elsarticle.cls` and its associated bibliography style file. On Ubuntu,
this comes with the `texlive-publishers` package.

The style file `aas_macros.sty` is included here to define journal
abbreviations used in the bibtex file (for entries provided by ADS).
