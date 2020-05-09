# `gr-math`
## Overview
`gr-math` is a XeLaTeX package. It is based on the `grmath` `babel` package by Apostolos Syropoulos. It can be used without `babel`. `gr-math`'s purpose is to redefine mathematics operators in Greek. Also, offers some macros for operators that are common in Greek school mathematics.

The macros of the package are:
* `\sin, \cos, \tan, \arcsin, \arccos, \arctan, \cot, \sec, \csc, \arccot, \arcsec, \arccsc` and `\gcd`. `gr-math` redefines these in Greek.
* `\lcm`. Least common multiple operator.
* `\limdisplay`. `\lim` operator in display mode.
* `\parallel`. `gr-math` redefines the operator `\parallel`. The parallel lines appear sloping.
* `\rightangle`. A symbol for the right angle.

## Installation
### Linux
Clone repository `gr-math` under `~/texmf/tex/xelatex/`.

## Usage
As usual, load the package in the preable of the document

\usepackage{gr-math}

For an overview see [`overview-gr-math.pdf`](overview-gr-math.pdf).

## License
[MIT License](LICENSE)
