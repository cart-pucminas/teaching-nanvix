LATEX = latexmk
LATEX_FLAGS = -shell-escape -e "\$$pdflatex=q/pdflatex -synctex=1 -interaction=nonstopmode/" -pdf

all: main.tex
	$(LATEX) $(LATEX_FLAGS) main.tex

clean:
	rm -f             \
		*.aux         \
		*.bbl         \
		*.bcf         \
		*.blg         \
		*.fls         \
		*.log         \
		*.out         \
		*.xml         \
		*.toc         \
		*.fdb_latexmk \
		*.pdf         \
		*.gz          \
		*.glo         \
		*.ist         \
		*.acn
