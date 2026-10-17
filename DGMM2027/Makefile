all:
	pdflatex paper.tex

release:
	pdflatex paper.tex
	bibtex paper
	pdflatex paper.tex
	pdflatex paper.tex

clean:
	rm *.aux *.log *.toc *.log *.bbl *.idx
	rm paper.pdf

fullclean: clean
	rm *~

