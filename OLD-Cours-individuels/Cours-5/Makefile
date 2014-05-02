methodes_num5.pdf: methodes_num5.tex
	pdflatex $<

view: methodes_num5.pdf
	open methodes_num5.pdf

indices: methodes_num5.pdf
	pdflatex methodes_num5.tex 

indicesview: indices
	open methodes_num5.pdf

clean:
	rm -f methodes_num5.aux
	rm -f methodes_num5.fdb_latexmk
	rm -f methodes_num5.fls
	rm -f methodes_num5.log
