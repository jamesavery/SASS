.PHONY: main.pdf
SN-main.pdf: main.tex
	pdflatex main
	bibtex main
	pdflatex main
	pdflatex main

fast: main.tex
	pdflatex main

clean:
	rm -f *.aux *.log *.toc *.spl *.out *.bbl *.blg *~ \#*\#
