methodes_num4.pdf: methodes_num4.tex
	pdflatex $<

view: methodes_num4.pdf
	open methodes_num4.pdf

indices: methodes_num4.pdf
	pdflatex methodes_num4.tex 

indicesview: indices
	open methodes_num4.pdf

clean:
	rm -f methodes_num4.aux
	rm -f methodes_num4.fdb_latexmk
	rm -f methodes_num4.fls
	rm -f methodes_num4.log
