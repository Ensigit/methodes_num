methodes_num3.pdf: methodes_num3.tex
	pdflatex $<

view: methodes_num3.pdf
	open methodes_num3.pdf

indices: methodes_num3.pdf
	pdflatex methodes_num3.tex 

indicesview: indices
	open methodes_num3.pdf

clean:
	rm -f methodes_num3.aux
	rm -f methodes_num3.fdb_latexmk
	rm -f methodes_num3.fls
	rm -f methodes_num3.log
