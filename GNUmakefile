all: thesis.pdf

IMAGES=$(wildcard images/*.{png,pdf})

thesis.pdf: thesis.tex ${IMAGES}
	pdflatex $<
	#bibtex $<
	pdflatex $<
	pdflatex $<
