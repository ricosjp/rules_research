# Change NAME accordingly
NAME = 01_公的研究費等の不正防止に関する基本方針

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