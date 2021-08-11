# Change NAME accordingly
NAME = 08_研究補助者取扱規程

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