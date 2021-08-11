# Change NAME accordingly
NAME = 07_不正な取引に関与した業者への取引停止の処分方針

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