# Titanic Survival Prediction
A machine learning project to predict Titanic passenger survival, featuring statistical analysis and custom feature engineering. Key features include `relatives` and `family_size`, a chi-squared test (p < 0.0001 for `sex` vs. `survived`), and a correlation heatmap. Models (Naive Bayes, Neural Network, Logistic Regression, XGBoost) achieve up to 81.34% accuracy with XGBoost. See `titanic_survival_prediction.ipynb` for details.

## Dataset
The dataset (`titanic3.csv`) is sourced from [hbiostat.org](https://hbiostat.org/data/repo/titanic3.csv).

## Setup
- Clone the repo.
- Install dependencies: `conda env create -f environment.yml` (this creates an environment named `titanic_survival_prediction`).
- Open `titanic_survival_prediction.code-workspace` in VS Code.

## Skills Demonstrated
- Data wrangling (`pandas`, feature engineering).
- Statistical analysis (`scipy` chi-squared test).
- Visualisation (`seaborn`, `matplotlib`).
- Machine learning (`sklearn`, `xgboost`, `keras`).
  
## Acknowledgements
This project builds upon the [Data Science in VS Code tutorial](https://code.visualstudio.com/docs/datascience/data-science-tutorial), extending it with additional features (`family_size`), statistical tests (chi-squared), and models (Logistic Regression, XGBoost).

## License
This project is licensed under the MIT License: see the [LICENSE](LICENSE) file for details.