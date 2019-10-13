All: moveassets clean

assets:
	./latexdockercmd.sh pdflatex motivation_tiles.tex
	./latexdockercmd.sh pdflatex support_tiles.tex
	./latexdockercmd.sh pdflatex playerboards.tex
	./latexdockercmd.sh pdflatex trial_tiles.tex

moveassets: assets
	mv motivation_tiles.pdf ../
	mv support_tiles.pdf ../
	mv playerboards.pdf ../
	mv trial_tiles.pdf ../

clean:
	rm *.log *.aux
