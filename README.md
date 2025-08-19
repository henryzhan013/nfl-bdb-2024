# NFL Big Data Bowl 2024 — Tackle Efficiency

Solo Tackle Impact Rating (SITR) exploration across positions. Curated DB/DL/LB datasets, reproducible visuals, and a quarantined third-party animation notebook. Minimal dependencies, no raw competition data in git.

## Highlights
- Curated CSVs: `results/db_df.csv`, `results/dl_df.csv`, `results/lb_df.csv`
- Reproducible figures via `src/make_figures.py`
- Notebook for analysis: `notebooks/01_analysis.ipynb`
- Third-party animation notebook isolated under `notebooks/third_party/` with attribution

## Quick start
Conda:
```bash
conda env create -f environment.yml
conda activate nfl-bdb-2024
python src/make_figures.py


