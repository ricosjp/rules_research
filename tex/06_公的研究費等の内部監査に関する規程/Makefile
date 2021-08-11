# Change NAME accordingly
NAME = 06_公的研究費等の内部監査に関する規程

TEX = platex
DVI = dvipdfmx

all: pdf view

pdf: $(NAME).pdf

view:
	open $(NAME).pdf

clean:
	$(RM) $(NAME).pdf $(NAME).dvi $(NAME).aux $(NAME).log

$(NAME).pdf: $(NAME).tex include/body.tex
	$(TEX) $(NAME).tex
	$(TEX) $(NAME).tex
	$(TEX) $(NAME).tex