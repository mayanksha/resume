# Two Page CV

### Dependencies for ARCH Linux : 
```
* xelatex
* texlive-most  
* texlive-fontsextra 
* texlive-langextra
```

Can be compiled using :
```shell
$ xelatex cv.tex
```
### Optional Dependencies for Real-Time Latex Compilation :

* latexmk : `mkpdf` 
* Evince (PDF Viewer) : `evince`
Can be compiled using : 
```shell
$ latexmk -pdf -pdf=xelatex -pvc cv.tex
```
##

