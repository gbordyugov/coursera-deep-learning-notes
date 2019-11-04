DOCUMENT_NAME = logistic-regression-gradient-descent

$(DOCUMENT_NAME).pdf: $(DOCUMENT_NAME).tex
	pdflatex $?
	pdflatex $?

clean:
	rm -rf *.aux *.log *.bbl *.blg *.out *.toc $(DOCUMENT_NAME).pdf
