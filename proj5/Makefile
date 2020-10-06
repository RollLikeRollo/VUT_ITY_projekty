PROJ=proj5

all:
	latex $(PROJ).tex
	dvips -o $(PROJ).ps $(PROJ).dvi 
	ps2pdf -sPAPERSIZE=a4 $(PROJ).ps
clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).out $(PROJ).pdf $(PROJ).ps $(PROJ).nam $(PROJ).nav $(PROJ).toc $(PROJ).snm
