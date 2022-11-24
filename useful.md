# Useful
Useful pieces of code and websites.
## ArXiv
- ArXiv LaTeX cleaner ([Doc](https://github.com/google-research/arxiv-latex-cleaner)): cleans papers before submission on arXiv.  
- Ar5iv ([Doc](https://ar5iv.labs.arxiv.org/)): turns papers to webpages in HTML.

## Authoring
- Contribution roles taxonomy ([Doc](https://credit.niso.org/)): a standardized list of roles for authors contributions.

## FEniCS
- [Tutorial](https://jorgensd.github.io/dolfinx-tutorial)

## Jobs
- [Mathjobs](https://www.mathjobs.org/jobs)

## LaTeX
- LaTeXdiff ([Doc](https://www.overleaf.com/learn/latex/Articles/Using_Latexdiff_For_Marking_Changes_To_Tex_Documents)): generates a pdf highlighting the differences between two git versions of a LaTeX file.
  ```bash
    #!/bin/bash
    latexdiff-vc -r <tag or git version> --force main.tex
    latexmk -shell-escape -pdf -pv -output-directory=build-diff main-diff<tag or git version>.tex
  ```
- GNU aspell ([Doc](http://aspell.net/)): spell checker.  
  `aspell -c -t file.tex -d en`  
  `-c` command to check the file  
  `-t` LaTeX mode  
  `-d` name of the main dictionary to use (optional)

## Python formating
- Pep8 ([Doc](https://www.python.org/dev/peps/pep-0008/)): standard python code formating.  
  `autopep8 -i *.py`

## GNU Screen ([Doc](https://www.gnu.org/software/screen/manual/screen.html)): allows to keep an ssh session open even if the connexion is lost.
  `screen -S <nom session>`  
  `screen -ls` liste les sessions.  
  `Ctrl-a d` pour quitter une session attachée.  




