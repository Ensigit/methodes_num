methodes_num6.pdf: methodes_num6.tex
	pdflatex $<

view: methodes_num6.pdf
	open methodes_num6.pdf

indices: methodes_num6.pdf
	pdflatex methodes_num6.tex 

indicesview: indices
	open methodes_num6.pdf

clean:
	rm -f methodes_num6.aux
	rm -f methodes_num6.fdb_latexmk
	rm -f methodes_num6.fls
	rm -f methodes_num6.log
