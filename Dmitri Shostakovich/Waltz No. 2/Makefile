all :
	rm *.mx1 2> /dev/null || true
	rm *.mx2 2> /dev/null || true
	rm *.log 2> /dev/null || true
	rm *.fls 2> /dev/null || true
	rm *.dvi 2> /dev/null || true
	latexmk main.tex
	musixflx main.mx1
	latexmk -pdf main.tex

clean :
	rm *.mx1 2> /dev/null || true
	rm *.mx2 2> /dev/null || true
	rm *.log 2> /dev/null || true
	rm *.fls 2> /dev/null || true

