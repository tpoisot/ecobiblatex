[Ecology Letters](http://bit.ly/IdEIY5) Citation and Bibliography Biblatex README
=============

Style originally coded by Timothée Poisot (GitHub - tpoisot)

To use:
- Ensure the ele.cbx and the ele.bbx files are in the folder of your .tex file.

- Include in the preamble of your .tex file

\usepackage[citestyle=ele,
bibstyle=ele,
backend=biber,
bibencoding=utf8]{biblatex}

Include where you want to place your bibliography:

\begin{refcontext}[sorting=nyt]
\printbibliography
\end{refcontext}


Notes:
- As of 2018-06-07 Have not checked the case when same authors and same year - ELE requirements is James et al. 1986a, b

Changes made
-------------

2018-06-07 by Christopher J. Greyson-Gaito (GitHub - cgreysongaito)

ele.bbx:
- Article titles in sentence case. 
- Use of shortjournal for journal abbreviations.
- Ensured journal number is not included in reference.
- Removed space between initials.

ele.cbx
- Sorts citations in chronological order
- Prevents either initials of first author being included or second author being included when two articles with same first author