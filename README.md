## Environment  
ubuntu

## SetUp  
```
$ sudo apt update
$ sudo apt upgrade
$ sudo apt install texlive-lang-japanese
$ sudo apt install texlive-lang-cjk
$ sudo apt install texlive-fonts-recommended
$ sudo apt install texlive-fonts-extra
$ sudo apt install xdvik-ja
$ sudo apt install dvipsk-ja
$ sudo apt install gv
```  

## Compile
```
$ uplatex template.tex
$ dvipdfmx template.dvi
```
