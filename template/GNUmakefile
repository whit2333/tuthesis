TARGET := thesis_template.pdf

default: pdf

pdf: 
	pdflatex  thesis_template.tex
	bibtex    thesis_template.aux
	makeindex thesis_template
	pdflatex  thesis_template.tex
	pdflatex  thesis_template.tex


dvi:
	latex  thesis_template.tex

.PHONY: all clean

clean: 
	rm thesis_template.pdf
	rm *.aux
	rm *.log


