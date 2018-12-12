all: solution.pdf dfa.pdf
solution.pdf: solution.tex 
	pdflatex solution.tex
	pdflatex solution.tex
	pdflatex solution.tex

dfa.pdf: dfa.gv
	dot -Tpdf dfa.gv > dfa.pdf
