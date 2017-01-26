MAIN_FILE = document

BUILD = latexmk -pdf -pdflatex='pdflatex -interaction=nonstopmode -halt-on-error --shell-escape'
CLEAN = latexmk -C

REMOVE = rm -f

all:
	$(BUILD) $(MAIN_FILE).tex

clean:
	$(CLEAN)
	$(REMOVE) *.aux **/*.aux
	$(REMOVE) *.bbl **/*.bbl
	$(REMOVE) *.log **/*.log
	$(REMOVE) *.tdo **/*.tdo
	$(REMOVE) *.run.xml
