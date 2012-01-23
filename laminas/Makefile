# Makefile 
# Creado para ahorrar un poco el trabajo. 
# Walter Vargas <walter@covetel.com.ve>

SRC=./rest01

all: latex clean view

latex: $(SRC).tex
	pdflatex $(SRC).tex

clean: 
	rm -f *.aux *.log *.out *.ps *.toc *.nav *.snm *.dvi

view:
	evince $(SRC).pdf
