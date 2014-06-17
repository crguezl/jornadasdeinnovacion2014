all:
	latex lpp_jie1314.tex
	latex lpp_jie1314.tex
	dvips -Ppdf -G0 -o lpp_jie1314.ps lpp_jie1314.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true lpp_jie1314.ps lpp_jie1314.pdf

clean:
	rm -f *.log *.dvi *.aux *.blg *.ps *.nav *.out *.snm *.toc

eps:
	convert  img/versioncontrol1.png img/versioncontrol1.eps

