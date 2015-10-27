FILE=Thesis



all:
	latexmk -pdf ${FILE}.tex 

clean:
	rm -rf *.aux *.log *.toc *.out *.bbl *.fls *.blg *.fdb_latexmk *.glo *.lof *.lot *.nlo *.ist

veryclean: clean
	rm -rf ${FILE}.pdf

