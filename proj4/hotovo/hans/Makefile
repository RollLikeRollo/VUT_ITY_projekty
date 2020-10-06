PROJ=main

all:
	latex $(PROJ).tex
	bibtex $(PROJ)
	latex $(PROJ).tex
	latex $(PROJ).tex
	dvips -o $(PROJ).ps $(PROJ).dvi 
	ps2pdf -sPAPERSIZE=a4 $(PROJ).ps
clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).out $(PROJ).pdf $(PROJ).ps
