NAME = main

all: ${NAME}.tex ${NAME}.bib
	latex ${NAME}
	bibtex ${NAME}
	latex ${NAME}
	latex ${NAME}
	dvips ${NAME}.dvi -Ppdf -tletter -o

        # PDFX option makes it embed all fonts (incl. times)
	ps2pdf -dPDFX ${NAME}.ps

	rm -f ${NAME}.aux ${NAME}.blg ${NAME}.log ${NAME}.spl
	rm -f ${NAME}.dvi ${NAME}.ps

clean:
	rm ${NAME}.pdf ${NAME}.bbl
