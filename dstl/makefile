allversions:
	make headers
	make noheading

headers:
	pdflatex proposal.tex
	bibtex proposal.aux
	pdflatex proposal.tex
	pdflatex proposal.tex

noheading:
	pdflatex proposal_no_subs.tex
	bibtex proposal_no_subs.aux
	pdflatex proposal_no_subs.tex
	pdflatex proposal_no_subs.tex
