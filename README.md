# LOWE_RECONSTRUCTION_TECHNOTE
This is a repository to save and sync the latex files of the LOWE RECONSTRUCTION TECHNOTE

## Figures and tables
Figures and generated tables are produced in
[lowe_reco_paper_plots](https://github.com/DUNE/lowe_reco_paper_plots) (plotipus, frozen inputs) with its
`technote` lists (`input/plots/technote_scripts.txt`, `input/tables/technote_scripts.txt`), and copied here with

```
python run_paper.py --technote ../LOWE_RECONSTRUCTION_TECHNOTE   # in lowe_reco_paper_plots: regenerate, compare (reports/technote_status.md), copy
```

which writes `Images/Reco/`, `Images/LowE/` (paper figures) and the generated `Tables/`. `Images/` is gitignored;
only the tables the text `\input`s are committed. `Tables/Flash_{Finding,Matching}_Parameters.tex` and the
geometry and schematic images are hand-made; the few figures the lists do not reproduce are listed in the
lowe_reco_paper_plots README.
