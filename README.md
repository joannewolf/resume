# resume
## Install Latex on Mac
http://www.tug.org/mactex/mactex-download.html

It will create
* `/Library/TeX/Distributions/.DefaultTeX/Contents/Programs/texbin`
* `/etc/paths.d/Tex` which contains single line `/Library/TeX/texbin` so the library will be included in environmental variable `$PATH`

## Built resume
`xelatex *.tex`
