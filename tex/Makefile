.PHONY: all light clean

all: 
	pdflatex --shell-escape fosalrs.tex
	#bibtex   fosalrs.aux
	pdflatex --shell-escape fosalrs.tex
	pdflatex --shell-escape fosalrs.tex
	pdflatex --shell-escape fosalrs.tex

clean:
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg
	rm -f *.log
	rm -f *.out
	rm -f *.toc
	rm -f *.lot
	rm -f *.lof
	rm -f *.gnuplot
	rm -f *.table

