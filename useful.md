# Useful
Useful pieces of code and websites.
## ArXiv
- [ArXiv latex cleaner](https://github.com/google-research/arxiv-latex-cleaner)

## Authoring
- [Contribution Roles Taxonomy](https://credit.niso.org/)

## FEniCS
- [Tutorial](https://jorgensd.github.io/dolfinx-tutorial)

## Jobs
- [Mathjobs](https://www.mathjobs.org/jobs)

## LaTeX
- [Doc latexdiff on overleaf](https://www.overleaf.com/learn/latex/Articles/Using_Latexdiff_For_Marking_Changes_To_Tex_Documents)
- Ex. latexdiff script:
  ```bash
    #!/bin/bash
    latexdiff-vc -r <tag or git version> --force main.tex
    latexmk -shell-escape -pdf -pv -output-directory=build-diff main-diff<tag or git version>.tex
  ```
- Spell checker:  
  `aspell -c -t file.tex -d en`   
  `-c` command to check the file  
  `-t` LaTeX mode  
  `-d` name of the main dictionary to use (optional)

## Python formating
- [Documentation](https://www.python.org/dev/peps/pep-0008/)
- `autopep8 -i *.py`





