hcar-28-all:
	find hcar-28-*.tex ! -name hcar-28-template.tex -exec latexmk -xelatex {} +

hcar-28-octohat:
	latexmk -xelatex hcar-28-octohat.pdf

clean:
	latexmk -c -silent hcar-28-*.tex
