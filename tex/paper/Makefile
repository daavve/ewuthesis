#
# Hacky make file to assist building thesis project
#
###################################################################################

all:
	pdflatex CaliSet\:\ The\ Calligraphy\ Dataset.tex
	bibtex CaliSet\:\ The\ Calligraphy\ Dataset.aux 
	pdflatex CaliSet\:\ The\ Calligraphy\ Dataset.tex

clean:
	rm -f *.aux \
		*.bbl \
		*.blg \
		*.ist \
		*.lof \
		*.log \
		*.lot \
		*.out \
		*.toc \
		*.xdy
