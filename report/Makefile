all:
	pdflatex tesis
	bibtex tesis
	pdflatex tesis

clean: 
	rm -f *.aux *.bbl *.log *.blg *.dvi *.toc *.out *.glo *.ist *.lof *.lot *.acn *.tex~ *.swp

cleanall: clean
	rm -f tesis.pdf
