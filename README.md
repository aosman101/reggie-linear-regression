# reggie-linear-regression

An educational walk-through of simple linear regression. This project re-creates “Reggie’s Linear Regression” from scratch (slope/intercept model, absolute/squared error, gradient descent to fit `m` and `b`), then validates the result against `scikit-learn`’s implementation and visualises the outcome.

> If you’re new to README formatting on GitHub, this file uses standard Markdown, so it renders nicely in the repo UI.

## 🚀 Highlights

✅ From-scratch Ordinary Least Squares (OLS) model: y = m * x + b.
⚙️ Implementation of absolute and squared error functions.
🔁 Gradient descent training loop for learning slope/intercept.
🧠 Comparison with sklearn.linear_model.LinearRegression.
🧾 Clean, commented notebook for step-by-step learning.
💡 Lightweight — no external datasets required (uses generated data).
📊 New: Companion notebook Linear-Regression-Plots.ipynb showcasing diverse Matplotlib plots for documentation or reporting.

> Reference: `scikit-learn`’s `Linear Regression` minimises residual sum of squares for OLS. See the official docs for API details.  

## 📁 Repository structure

├─ Reggie_Linear_Regression.ipynb. # main notebook (from-scratch + sklearn comparison).

├─ Linear-Regression-Plots.ipynb # 5 reusable Matplotlib plots (line, scatter, bar, box, heatmap).

├─ data/ # (optional) sample CSVs if added later.

├─ imgs/ # (optional) saved output plots.

└─ README.md

