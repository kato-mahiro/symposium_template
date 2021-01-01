## Environment  
ubuntu

## SetUp  
```
$sudo apt update
$sudo apt upgrade
$sudo apt install texlive
$sudo apt install texlive-lang-cjk
$sudo apt install xdvik-ja
$sudo apt install gv
$sudo apt install texlive-fonts-recommended texlive-fonts-extra
$sudo apt install texlive-publishers
$sudo apt install epstool
```  

## Compile
```
$ uplatex template.tex
$ dvipdfmx template.dvi
```
