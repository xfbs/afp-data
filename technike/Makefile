all: technik_e.pdf

%.pdf: %.tex
	latexmk -lualatex $<

clean:
	$(RM) *.aux *.log *.toc *.fdb_latexmk *.fls
