solution.pdf: solution.tex dfa.pdf
	pdflatex solution.tex
	pdflatex solution.tex
	pdflatex solution.tex

dfa.pdf: dfa.gv
	dot -Tpdf dfa.gv > dfa.pdf
