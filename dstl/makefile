allversions:
	make headers
	make noheading
	make submittable

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

submittable:
	pdflatex submittable.tex
	bibtex submittable.aux
	pdflatex submittable.tex
	pdflatex submittable.tex
