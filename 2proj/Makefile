PROJ=proj1
PACK=xkmeto00

all:
	latex $(PROJ).tex
	latex $(PROJ).tex
	dvips -t a4 $(PROJ).dvi
	ps2pdf -sPAPERSIZE=a4 $(PROJ).ps

zip:
	zip $(PACK)-fit.zip *.tex Makefile

clean:
	rem -f $(PROJ).{aux, log, pdf, dvi, ps} $(PACK)-fit.zip