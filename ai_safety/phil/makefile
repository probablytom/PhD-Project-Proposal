proposal:
	pdflatex proposal.tex
	bibtex proposal.aux
	pdflatex proposal.tex
	pdflatex proposal.tex

upload:
	make proposal
	git add .
	git commit
	git push
