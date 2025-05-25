# Useful software and websites.

# Literature review

### [Inciteful](https://inciteful.xyz/), generate academic papers graph.

### [mathscinetify](https://gitlab.com/rbulle/mathscinetify), cleans up a .bib file by fetching info from [Mathscinet](https://mathscinet.ams.org/mathscinet/publications-search).

### [Scholar-inbox](https://www.scholar-inbox.com/), personal paper recommender.

# Writing, publishing

### [ArXiv LaTeX Cleaner](https://github.com/google-research/arxiv-latex-cleaner), clean papers before submission to arXiv.

### [Ar5iv](https://ar5iv.labs.arxiv.org/), turn papers into webpages in HTML.

### [Coblis](https://www.color-blindness.com/coblis-color-blindness-simulator/), a colorblindness simulator to help choose colors in figures.

### [CRediT](https://credit.niso.org/), a standardized list of roles for authors contributions.

### [diagrams.net](https://app.diagrams.net/), online site to create diagrams.

### [Markdown](https://www.markdownguide.org/), langage to format many documents, can be used with LaTeX to generate maths pdf files.

### [NN-SVG](https://github.com/alexlenail/NN-SVG), open-source neural networks architectures illustrations generator.

### [Pandoc](https://pandoc.org/), <3 file converter, can be used with markdown to create pdfs or presentation slides.

- [Pandoc-crossref](https://github.com/lierdakil/pandoc-crossref?tab=readme-ov-file), allows to use crossref for equations, figures etc in pandoc-markdown files.

### [Sherpa](https://v2.sherpa.ac.uk/romeo/), online resource that aggregates and analyses publisher open access policies.

### [Ten simple rules for better figures](https://journals.plos.org/ploscompbiol/article?id=10.1371%2Fjournal.pcbi.1003833)

### [VS Code Keyboard shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf), cheatsheet with VS Code Keyboard Shortcuts for Linux

### [webofknowledge](https://images.webofknowledge.com/images/help/WOS/A_abrvjt.html), list of scientific journals abreviations.

### [Zotero](https://www.zotero.org/), open source bibliography management tool.

### [awesome-zotero](https://github.com/MohamedElashri/awesome-zotero?tab=readme-ov-file), curated list of zotero plugins.

# Organization

### [Obsidian](https://obsidian.md/), note taking software with sync between devices (can be used with Git).

### [Pomodoro](https://pomofocus.io/), timer to help focus on your tasks.

### [Task Warrior](https://taskwarrior.org/), todo list management software in terminal.
- [Task Warrior Cheatsheet](https://taskwarrior.org/download/task-2.3.0.ref.pdf)

# LaTeX

### [bibcure](https://github.com/bibcure/bibcure), set of tools to generate and tidy bib files. Generates bib files from list of DOIs.

### [BibTeX Tidy](https://flamingtempura.github.io/bibtex-tidy/index.html), tool to tidy bibtex files.

### [LaTeX Font Catalogue](https://tug.org/FontCatalogue/)

### [GNU aspell](http://aspell.net/), spell checker.  
  ```
  aspell -c -t file.tex -d en
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

### [Overleaf-sync](https://github.com/svennniiii/overleaf-sync), sync Overleaf free version ([here](https://github.com/JulesColas97/overleaf-sync-plm/tree/master) for the PLM version) with git.

# Presentations

### [Marp](https://marp.app/#get-started), tool for presentations creation using markdown.

### [Quarto](https://quarto.org/), <3 tool for presentations creation using markdown.

### [Awesome quarto](https://github.com/mcanouil/awesome-quarto?tab=readme-ov-file), curated list of Quarto docs, talks, tools, examples & articles the internet has to offer.

### [Revealjs](https://revealjs.com/), tool for presentations creation in html.

# Coding

### [Algoim](https://algoim.github.io/), Algorithms for implicitly defined geometry, level set methods, and Voronoi implicit interface methods.

### Bash
- [Advanced shell scripting techniques](https://omid.dev/2024/06/19/advanced-shell-scripting-techniques-automating-complex-tasks-with-bash/)
- [Shellcheck](https://www.shellcheck.net/), find bugs in shell scripts.

### [Docker](https://www.docker.com/), container manager to help with code deployment on any platform. Very useful for reproducibility.

### FEniCSx

- [FEniCSx](https://fenicsproject.org/), FEniCSx an opensource finite element software in C++ with a Python interface.
- [FEniCSx Tutorial](https://jorgensd.github.io/dolfinx-tutorial), the FEniCSx tutorial by J. S. Dokken.
- [multiphenicsx](https://multiphenics.github.io/), a python library to solve multiphysics problems with finite elements, based on FEniCSx.

### [FreeFEM++](https://freefem.org/), an opensource finite element software in C++.

### Git
- [Git visual explanation](http://marklodato.github.io/visual-git-guide/index-fr.html)
- [Learn Git Branching](https://learngitbranching.js.org/)
- [Gitignore generator](https://www.toptal.com/developers/gitignore)

### [Ninja](https://ninja-build.org/), a build system with a focus on speed.

### [Podman](https://podman.io/), container manager that does not require root privileges.

### Python

- [Pep8](https://www.python.org/dev/peps/pep-0008/), standard python code formating.  
  `autopep8 -i *.py`
- [Polars](https://docs.pola.rs/), dataframes library.
- [PyMesh](https://pymesh.readthedocs.io/en/latest/index.html), tools for geometry processing and meshing, wraps Shewchuk's triangle library.
- [Ruff](https://docs.astral.sh/ruff/), python linter and code formatter.
- [SnakeViz](https://jiffyclub.github.io/snakeviz/), graphical viewer in browser to visualize the output of Python's [cProfile](https://docs.python.org/3/library/profile.html#module-cProfile).
- [SimRender](https://github.com/RobinEnjalbert/SimRender), a library for 3D interactive rendering of numerical simulations.
- [uv](https://github.com/astral-sh/uv), python package and project manager.
- [Vedo](https://vedo.embl.es/), visualization library in python.

### [GNU Screen](https://www.gnu.org/software/screen/), opensource window manager can be used to open and keep several terminals connected by ssh and recover them when the connection shuts.
- [Screen Cheatsheet](https://maojr.github.io/screencheatsheet/)

### Other

- [Pika backup](https://www.linuxtricks.fr/wiki/pika-backup-la-sauvegarde-graphique-avec-la-puissance-de-borg)
- [GNU Screen](https://www.gnu.org/software/screen/manual/screen.html), allows to keep an ssh connexion active.
- [NERDTree](https://github.com/preservim/nerdtree), file system explorer in Vim.
  - `s` to open file in split panel  
  - `Crtl + w + Left` `Crtl + w + Right` to navigate panels


# Miscellaneous

### [Anna's archive](https://annas-archive.org/), Mirrors Sci-hub, LibGen, Z-lib etc.

### [CHATONS](https://www.chatons.org/node/1), <3 French collective structure offering free, ethical and decentralized online services.

### [Data visualisation catalogue](https://datavizcatalogue.com/index.html)

### [Diataxis](https://diataxis.fr/), a systematic approach to technical documentation authoring.

### [FriendsDontLetFriends](https://github.com/cxli233/FriendsDontLetFriends#1-friends-dont-let-friends-make-bar-plots-for-means-separation), examples of bad data visualizations.

### [GrapheneOS](https://grapheneos.org/), opensource and privacy oriented mobile OS.

### [Jekyll](https://jekyllrb.com/), software to create static webpages from Markdown files ([here](https://www.taniarascia.com/make-a-static-website-with-jekyll/) for a nice tutorial).

### [LibRedirect](https://libredirect.github.io/), web extension redirecting many websites to alternative privacy friendly frontends.

### [Mathjobs](https://www.mathjobs.org/jobs)

### [Mermaid](https://github.com/mermaid-js/mermaid), a tool to create diagrams in Markdown.

### [RAWGraphs](https://www.rawgraphs.io/), online data visualization tool.

### [10 minutes mail](https://10minutemail.net/), generate a temporary email address.

<!--- ### Ghostscript scripts
- See `~/Documents/code/pdf_management` for compression/merging bash scripts.
--->

### [Coolors](https://coolors.co/cabac8-ff101f-b2ddf7-81d6e3-4cb5ae), generate color palettes.

### [i want hue](http://medialab.github.io/iwanthue/), generate and refine palettes of optimally distinct colors.

# Relax

### [Accuracity](https://accura.city/), geography game where you locate cities.

### [Bézier game](https://bezier.method.ac/)

### [Existential Comics](https://existentialcomics.com/)

### [First person tetris](https://firstpersontetris.com/)

### [Is my blue your blue?](https://ismy.blue/)

### [Nandgame](https://nandgame.com/), build a computer from scratch.

### [N step Steve part 1](https://epicpikaguy.itch.io/n-step-steve-part-1)

### [Pokédle](https://pokedle.com/), guess pokemons.

### [Rogule](https://rogule.com/), a dungeon a day keeps the Balrog away.

### [The wiki game](https://www.thewikigame.com/), a game on Wikipedia.

### [Travle](https://travle.earth/), geography game where you travel from one country to another.

### [Whentaken](https://whentaken.com/), guess where and when the picture has been taken.