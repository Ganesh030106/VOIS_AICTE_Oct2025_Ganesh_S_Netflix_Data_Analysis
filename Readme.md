#Netflix Data Analysis

This repository contains an exploratory data analysis notebook for a Netflix dataset used in the VOIS AICTE Oct 2025 workshop by Ganesh S.

**Contents**
- `Netflix_Analysis 2.ipynb`: Main Jupyter Notebook with data loading, cleaning, analysis, visualizations, and (optional) modeling experiments.

**Getting Started**

1. Install Python 3.8+ (3.10 or 3.11 recommended).
2. Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

3. Install recommended packages (adjust as needed):

```powershell
pip install --upgrade pip
pip install jupyterlab notebook pandas numpy matplotlib seaborn scikit-learn plotly
```

4. Start Jupyter and open the notebook:

```powershell
jupyter notebook "Netflix_Analysis 2.ipynb"
```

**Notebook Notes**
- The notebook expects the dataset files to be in the same folder as the notebook, or the code cell that loads data should be updated with the correct path.
- If large datasets are used, consider increasing Jupyter memory or sampling before running all cells.

**Quick Tips**
- To export a static HTML of the notebook:

```powershell
jupyter nbconvert --to html "Netflix_Analysis 2.ipynb"
```

- To run the notebook headlessly (requires `nbconvert` and `papermill`):

```powershell
pip install papermill
papermill "Netflix_Analysis 2.ipynb" output.ipynb
```

**Dependencies**
- Core: `pandas`, `numpy`
- Visualization: `matplotlib`, `seaborn`, optional `plotly`
- Modeling (optional): `scikit-learn`


**License**
- No license file is included. If you want this repository to be open-source, add a `LICENSE` file (e.g., MIT, Apache-2.0) and update this section.

---

