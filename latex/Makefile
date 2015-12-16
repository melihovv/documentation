#!/bin/bash

MAIN_FILE=main

biblio:
	pdflatex $(MAIN_FILE).tex
	bibtex $(MAIN_FILE).aux
	pdflatex $(MAIN_FILE).tex
	pdflatex $(MAIN_FILE).tex

clear:
	rm *.pdf *.aux *.log *.gz *.out *.toc *.dvi *.bbl *.blg
