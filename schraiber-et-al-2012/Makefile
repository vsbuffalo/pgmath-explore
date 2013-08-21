all: schraiber-et-al-2012.Rtex schraiber-et-al-2012-bib.bib
	Rscript -e "library(knitr); knit('schraiber-et-al-2012.Rtex')"
	pdflatex schraiber-et-al-2012.tex
	bibtex schraiber-et-al-2012
	pdflatex schraiber-et-al-2012.tex
	pdflatex schraiber-et-al-2012.tex

clean:
	rm -f schraiber-et-al-2012.{bbl,out,log,aux,blg}
