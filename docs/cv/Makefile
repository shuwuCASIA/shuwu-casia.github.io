default: cv-full.pdf

cv-full.pdf: cv-full.tex conference.tex
	pdflatex cv-full.tex

conference.tex:
	cd ../../website; python generate_cv_pubs.py
	cp ../../website/*.tex . 
