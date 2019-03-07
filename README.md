# basisTex
졸업논문과 논문투고

# 논문 컴파일
``` bash
pdflatex document.tex
bibtex document.aux
pdflatex document.tex
pdflatex document.tex
```

# 순서도 컴파일
``` bash
cd flowchart/
pdflatex flowchart.tex
pdftops -eps flowchart.pdf
```

# Compile ToReferees
``` bash
cd ToReferees
pdflatex ToReferees.tex
```
