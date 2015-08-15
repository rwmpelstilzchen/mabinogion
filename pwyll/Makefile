all:
	latexmk -xelatex -file-line-error main

pvc:
	latexmk -silent -pvc -file-line-error main

clean:
	-rm *.aux *.bbl *.blg *.log *.toc *.url *.cut *.run.xml *.bst *.bcf *.fls *.fdb_latexmk *.out *.dvi *.idx *.ilg *.ind

distclean: clean
	-rm *.pdf
