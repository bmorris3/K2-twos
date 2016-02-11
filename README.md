# K2-twos

Check out `findtargets.ipynb` to see how the candidate target list `on_chip.csv` is made.

Peek inside `findtwos.ipyb` to find how that long list of targets on silicon is narrowed down to those with "ideal" comparison stars, which are then listed in `candidates_with_neighbors.txt`.

Then filter down to `k2-twos.csv` by removing contaminated pairs, upload that file to [MAST](http://archive.stsci.edu/k2/epic/search.php?form=fuf) for EPIC matches.
