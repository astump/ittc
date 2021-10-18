MiniClass.pdf:	MiniClass.tex Makefile biblio.bib
	texfot pdflatex MiniClass.tex
	bibtex   MiniClass
	texfot pdflatex MiniClass.tex
	texfot pdflatex MiniClass.tex


clean:
	rm -f *.aux *.bbl *.blg *.log *.out *.toc
