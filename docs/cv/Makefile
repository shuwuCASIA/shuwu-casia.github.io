default: cv-full.pdf cv-full.tex

cv-full.pdf: cv-full.tex conference.tex
	pdflatex cv-full.tex

pub:
	cd ../../website-data; python generate_cv_pubs.py
	cp ../../website-data/*.tex . 
