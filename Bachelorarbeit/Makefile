#! /usr/bin/make -f

# makefile for Bachelorarbeit

all: clean build

build:
	rm -f bachelorarbeit.aux
	rm -f bachelorarbeit.bcf
	rm -f bachelorarbeit.blg
	rm -f bachelorarbeit.bbl
	pdflatex bachelorarbeit.tex
	biber bachelorarbeit
	pdflatex bachelorarbeit.tex
	pdflatex bachelorarbeit.tex
	
clean:
	rm -f bachelorarbeit.aux
	rm -f bachelorarbeit.bcf
	rm -f bachelorarbeit.blg
	rm -f bachelorarbeit.bbl
	rm -f bachelorarbeit.pdf
