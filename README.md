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
### Dependencies for Ubuntu (20.04):

```
sudo apt-get install -y fonts-font-awesome latexmk texlive-xetex evince
```

### Optional Dependencies for Real-Time Latex Compilation :

* latexmk : `mkpdf` 
* Evince (PDF Viewer) : `evince`
Can be compiled using : 
```shell
$ latexmk -pdf -pdf=xelatex -pvc cv.tex
```
##

