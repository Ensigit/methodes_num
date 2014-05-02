methodes_num1.pdf: methodes_num1.tex
	pdflatex $<

view: methodes_num1.pdf
	open methodes_num1.pdf

indices: methodes_num1.pdf
	pdflatex methodes_num1.tex 

indicesview: indices
	open methodes_num1.pdf

clean:
	rm -f methodes_num1.aux
	rm -f methodes_num1.fdb_latexmk
	rm -f methodes_num1.fls
	rm -f methodes_num1.log
