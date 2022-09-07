# Anno LaTeX posters and template
Posters in A0 format.
Based on <https://github.com/IMISE/imise-poster>.
Use template.tex as a starting point.
tagung.tex is the poster for the 3rd SaxFDM Tagung in Leipzig on 2022-09-03.

## Online Editor
If you are a LaTeX beginner or just prefer working in a web editor, you can copy and edit this template on [Overleaf](https://www.overleaf.com/read/bxbbygxjhpdx).

## Compile
Compile the LaTeX file to PDF:

    pdflatex myposter.tex
    bibtex myposter
    pdflatex myposter.tex

If you don't have any literature references, `pdflatex myposter.tex` is enough.
If you have `latexmk` installed, you can do it in one command using `latexmk -pdf myposter.tex` or under Linux just execute the `compile` script.

