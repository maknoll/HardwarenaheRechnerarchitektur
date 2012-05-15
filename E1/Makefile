NAME = $(shell basename `pwd`)
$(NAME).pdf: $(NAME).tex
	pdflatex $<
	open $@
