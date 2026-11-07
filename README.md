# LOWE_RECONSTRUCTION_TECHNOTE
This is a repository to save and sync the latex files of the LOWE RECONSTRUCTION TECHNOTE

## Figures and tables
Figures and generated tables are produced in
[LOWE_RECONSTRUCTION_PUBLICATION](https://github.com/DUNE/LOWE_RECONSTRUCTION_PUBLICATION) with the `reco` lists and copied here through the
`reco` route of its `config/output_paths.json`:

```
python run_plot_scripts.py  -s reco   # input/plots/reco_scripts.txt  -> Images/Reco/
python run_table_scripts.py -s reco   # input/tables/reco_scripts.txt -> Tables/
```

`Images/` is gitignored. Generated tables land in `Tables/` untracked; only the tables the text `\input`s are committed.
