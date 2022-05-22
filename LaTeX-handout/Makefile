tex = pdflatex
out = LaTeX_handout.pdf

$(out): main.tex
	$(tex) $<
	mv main.pdf $@

clean:
	-rm main.aux main.log main.toc
	-rm $(out)