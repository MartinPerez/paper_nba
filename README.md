In order to compile:

	pdflatex modeling-nba.tex
	bibtex modeling-nba.tex
	pdflatex modeling-nba.tex
	pdflatex modeling-nba.tex

Or, if you have `latexmf`:

	latexmf -pdf modeling-nba.tex


Note:
Use meld on tex sources or latexdiff for diffs
https://gitlab.com/git-latexdiff/git-latexdiff.git
