LATEX = latex -halt-on-error -output-format=pdf

RM = rm -f

%.pdf: %.tex
	$(LATEX) $*.tex
	$(RM) $*.log $*.div $*.aux
	evince $*.pdf &
