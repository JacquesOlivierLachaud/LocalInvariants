all:
	pdflatex paper.tex

release:
	pdflatex paper.tex
	bibtex paper
	pdflatex paper.tex
	pdflatex paper.tex

clean:
	rm -f *.aux *.log *.toc *.log *.bbl *.idx *.out *.blg
	rm -f paper.pdf

fullclean: clean
	rm -f *~

