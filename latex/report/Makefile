CC=pdflatex
SOURCES=report.latex
OBJECTS=$(SOURCES:.latex=.pdf)

all: $(OBJECTS) 

%.pdf: %.latex
	$(CC) $?

clean:
	rm -f *.log *.aux

real-clean:
	rm -f *.pdf *.log *.aux
