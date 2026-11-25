# Week 8 starter

Practice repository for **Week 8: Double/Debiased Machine Learning (DML)**.
Full instructions: <https://yoonismo.github.io/causal-computing/week8.html>

## What is in here

| File | Purpose |
|---|---|
| `week8.ipynb` | The code from the Week 8 page, in the same order |
| `requirements.txt` | The packages the automatic check installs |
| `.github/workflows/ci.yml` | The automatic check: runs the notebook on GitHub's computer after every push |

## Before you start

Week 8 uses `scikit-learn` (Lasso, Ridge, random forest), `joblib` (running model fits on several cores) and `doubleml`. Activate the course environment and install the packages (this works from any folder, and the ones you already have are skipped):

```bash
source ~/ECON481/.venv/bin/activate      # macOS
~\ECON481\.venv\Scripts\activate          # Windows (PowerShell)
uv pip install pandas causaldata statsmodels matplotlib scikit-learn joblib doubleml
```

Run only the `activate` line for your system.

The NHEFS data come with the `causaldata` package. Some cells fit hundreds of models, and the simulation in Section 4.2 can take a few minutes.

## Steps

1. Click **Use this template** → **Create a new repository**, then clone your copy to your computer, as in Week 1 Lab 3.
2. Run `week8.ipynb` in order along with the Week 8 page.
3. Clear all outputs, then `git add`, `git commit` and `git push`. The **Actions** tab should turn green.
