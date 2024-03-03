# Useful softwares and websites.

# Writing, publishing

### [ArXiv LaTeX Cleaner](https://github.com/google-research/arxiv-latex-cleaner), clean papers before submission to arXiv.

### [Ar5iv](https://ar5iv.labs.arxiv.org/), turn papers into webpages in HTML.

### [CRediT](https://credit.niso.org/), a standardized list of roles for authors contributions.

### [Markdown](https://www.markdownguide.org/), langage to format many documents, can be used with LaTeX to generate maths pdf files.

### [Pandoc](https://pandoc.org/), <3 file converter, can be used with markdown to create pdfs or presentation slides.

### [Sherpa](https://v2.sherpa.ac.uk/romeo/), online resource that aggregates and analyses publisher open access policies.

### [VS Code Keyboard shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf), cheatsheet with VS Code Keyboard Shortcuts for Linux

### [webofknowledge](https://images.webofknowledge.com/images/help/WOS/A_abrvjt.html), list of scientific journals abreviations.

### [Zotero](https://www.zotero.org/), open source bibliography management tool.

# LaTeX

### [LaTeX Font Catalogue](https://tug.org/FontCatalogue/)

### [bibcure](https://github.com/bibcure/bibcure), set of tools to generate and tidy bib files. Generates bib files from list of DOIs.

### [BibTeX Tidy](https://flamingtempura.github.io/bibtex-tidy/index.html), tool to tidy bibtex files.

### [GNU aspell](http://aspell.net/), spell checker.  
  ```
  aspecll -c -t file.tex -d en
  -c: to check the file
  -t: LaTeX mode
  -d: name of the main dictionary to use (default en)
  ```

### [LaTeXdiff](https://www.overleaf.com/learn/latex/Articles/Using_Latexdiff_For_Marking_Changes_To_Tex_Documents), generates a pdf highlighting the differences between two git versions of a LaTeX file.
  ```bash
    #!/bin/bash
    latexdiff-vc -r <tag or git version> --force main.tex
    latexmk -shell-escape -pdf -pv -output-directory=build-diff main-diff<tag or git version>.tex
  ```

### [LaTeX is dead ?](https://www.quora.com/Is-LaTeX-dead-If-yes-what-are-some-modern-alternatives)

### [Online tables generator](https://www.tablesgenerator.com/)
### [Online tikz diagram editor](https://tikzcd.yichuanshen.de/)

# Presentations

### [Marp](https://marp.app/#get-started), tool for presentations creation using markdown.

### [Revealjs](https://revealjs.com/), tool for presentations creation in html.

# Coding

### [FEniCSx Tutorial](https://jorgensd.github.io/dolfinx-tutorial)

### Git
- [Git visual explanation](http://marklodato.github.io/visual-git-guide/index-fr.html)
- [Learn Git Branching](https://learngitbranching.js.org/)
- [Gitignore generator](https://www.toptal.com/developers/gitignore) 

### Python

- [Pep8](https://www.python.org/dev/peps/pep-0008/), standard python code formating.  
  `autopep8 -i *.py`

- [PyMesh](https://pymesh.readthedocs.io/en/latest/index.html), tools for geometry processing and meshing, wraps Shewchuk's triangle library.

### Others
- [GNU Screen](https://www.gnu.org/software/screen/manual/screen.html), allows to keep an ssh
- [Screen Cheatsheet](https://maojr.github.io/screencheatsheet/)

### [NERDTree](https://github.com/preservim/nerdtree), file system explorer in Vim.
- `s` to open file in split panel  
- `Crtl + w + Left` `Crtl + w + Right` to navigate panels

# Miscellaneous

### [Anna's archive](https://annas-archive.org/), Mirrors Sci-hub, LibGen, Z-lib etc.
### [Data visualisation catalogue](https://datavizcatalogue.com/index.html)
### [FriendsDontLetFriends](https://github.com/cxli233/FriendsDontLetFriends#1-friends-dont-let-friends-make-bar-plots-for-means-separation), examples of bad data visualizations.

### [Jekyll](https://jekyllrb.com/), software to create static webpages from Markdown files ([here](https://www.taniarascia.com/make-a-static-website-with-jekyll/) for a nice tutorial).

### [LibRedirect](https://libredirect.github.io/), web extension redirecting many websites to alternative privacy friendly frontends.

### [Mathjobs](https://www.mathjobs.org/jobs)

### [Mermaid](https://github.com/mermaid-js/mermaid), a tool to create diagrams in Markdown.

### [RAWGraphs](https://www.rawgraphs.io/), online data visualization tool.

### [10 minutes mail](https://10minutemail.net/), generate a temporary email address.

<!--- ### Ghostscript scripts
- See `~/Documents/code/pdf_management` for compression/merging bash scripts.
--->

### [Pomodoro](https://pomofocus.io/)

### [Task Warrior](https://taskwarrior.org/), todo list management software in terminal.
- [Task Warrior Cheatsheet](https://taskwarrior.org/download/task-2.3.0.ref.pdf)

### [Coolors](https://coolors.co/cabac8-ff101f-b2ddf7-81d6e3-4cb5ae), generate color palettes.

# Relax

### [Nandgame](https://nandgame.com/), build a computer from scratch.

### [N step Steve part 1](https://epicpikaguy.itch.io/n-step-steve-part-1)

### [Rogule](https://rogule.com/), a dungeon a day keeps the Balrog away.

### [The wiki game](https://www.thewikigame.com/), a game on Wikipedia.