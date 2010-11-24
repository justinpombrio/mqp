PAPER = graph-homomorphisms

paper:
	latex -halt-on-error -output-format=pdf $(PAPER).tex
	rm -f *.aux *.log *.dvi
	evince $(PAPER).pdf &