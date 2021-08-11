# Change NAME accordingly
NAME = 00_公的研究費等の運営・管理責任体制

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