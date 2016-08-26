#! /usr/bin/make -f

# makefile for Bachelorarbeit

all: clean build

build:
	pdflatex -8bit bachelorarbeit.tex
	biber bachelorarbeit
	pdflatex -8bit bachelorarbeit.tex
	pdflatex -8bit bachelorarbeit.tex
	
clean:
	rm -f bachelorarbeit.aux
	rm -f bachelorarbeit.bcf
	rm -f bachelorarbeit.blg
	rm -f bachelorarbeit.bbl
	rm -f bachelorarbeit.pdf
