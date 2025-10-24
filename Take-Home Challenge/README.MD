
Relax Inc. Challenge Submission
==============================

This project package contains everything needed to reproduce the analysis for the Relax Inc. take‑home challenge.

### Contents

- **`relax inc.ipynb`** – A fully executed Jupyter notebook that loads the user and engagement data, labels adopted users, performs exploratory analysis, engineers features, trains models, and displays results.  All charts are embedded in the notebook.
- **`graphs/`** – A folder with the images referenced in the notebook (adoption rates by creation source and invite status, session recency distribution, and random‑forest feature importances).

### How to run

1. Make sure you have Python with `pandas`, `numpy`, `matplotlib` and `scikit‑learn` installed.
2. Open `relax inc.ipynb` using Jupyter Notebook or JupyterLab.
3. Run all cells from top to bottom to reproduce the results and figures.  The notebook expects the original CSV files under `relax_challenge/relax_challenge`.

No additional configuration is required; the notebook will generate the same outputs as shown in the provided version.
