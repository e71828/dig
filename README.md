# dig

the `py` code was written in the `Colab`, then uploaded here,.

## Use nputhesis
1. nbconvert to latex;
2. export the red.bib(bibtex or biblatex) to current directory;
3. in root `.tex`, add `\usepackage[biber, numbers]{nputhesis}` before `\begin{document}`;
4. add `\printbibliography` before `\end{document}`;
5. if needed, add `\nocite{*}`;
6. if needed, use `\intobmk\section*{}` and `\intobmk\subsection*{}`
