### Overview

My sty file contains basic commands for generating theorems, table of contents, simple math shortcuts, etc. I usually use sublime+skim as a simple setup, building my pdfs using:

```
latexmk -pdf -pvc -interaction=nonstopmode -synctex=1 example.tex
```

See example.tex and example.pdf as a living document of all functionality supported by my sty file.

### References
Heavily inspired by Jeff Erikson's LaTeX sty files for scribing (https://jeffe.cs.illinois.edu/pubs/latex.html) and Tyler Zhu and Evan Chen's LaTeX notes. 
