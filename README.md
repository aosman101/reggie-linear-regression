# reggie-linear-regression

An educational walk-through of simple linear regression. This project re-creates “Reggie’s Linear Regression” from scratch (slope/intercept model, absolute/squared error, gradient descent to fit `m` and `b`), then validates the result against `scikit-learn`’s implementation and visualises the outcome.

> If you’re new to README formatting on GitHub, this file uses standard Markdown, so it renders nicely in the repo UI.

## 🚀 Highlights

- From-scratch Ordinary Least Squares (OLS): `y = m*x + b`.
- Error functions and gradient descent training loop.
- Side-by-side comparison with `sklearn.linear_model.LinearRegression`.
- Clean, commented notebook for step-by-step learning.
- Lightweight, no external data required (toy or generated data).

> Reference: `scikit-learn`’s `LinearRegression` minimises residual sum of squares for OLS. See the official docs for API details.  

## 📁 Repository structure

├─ Reggie_Linear_Regression.ipynb # main notebook (from-scratch + sklearn comparison).

├─ data/ # (optional) sample CSV(s) if you add them later on.

├─ imgs/ # (optional) saved plots.

└─ README.md
