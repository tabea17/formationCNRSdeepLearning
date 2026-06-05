all: 1 2 3

clean:
	rm -rf day1.ipynb day2.ipynb day3.ipynb  
	rm -rf day1_solution.ipynb day2_solution.ipynb day3_solution.ipynb
	rm -rf .ipynb_checkpoints .DS_Store
1 2 3:
	jupyter nbconvert day$@_corrige.ipynb --clear-output --TagRemovePreprocessor.enabled=True --TagRemovePreprocessor.remove_cell_tags "solution" --to notebook --output day$@.ipynb
	jupyter nbconvert day$@_corrige.ipynb --clear-output --TagRemovePreprocessor.enabled=True --TagRemovePreprocessor.remove_cell_tags "edit" --to notebook --output day$@_solution.ipynb

