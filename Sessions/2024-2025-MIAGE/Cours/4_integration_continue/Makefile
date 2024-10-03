SOURCE=$(wildcard *.tex)

TARGETS=$(patsubst %.tex, %.pdf, $(SOURCE))

all: $(TARGETS)


%.pdf: %.tex
	pdflatex $<
	pdflatex $<
	pdflatex $<

clean:
	rm -rf *.aux *.log *.out *~ *.pdf *.nav *.snm *.toc *.vrb *.bcf *.xml
