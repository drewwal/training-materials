# training-materials

Companion materials for the Intro to Data Science training session.

## Contents

- **new-starter-training.ipynb** — A guided notebook that walks through building a binary
  classification model on tabular data, from initial exploration through to a
  Kaggle submission. Designed to be uploaded to Kaggle and run against the
  [Predicting Loan Payback](https://www.kaggle.com/competitions/playground-series-s5e11)
  competition (Playground Series S5E11).

## What the notebook covers

- Data loading and exploratory analysis
- Visualisation of feature distributions and correlations
- Building a rules-based baseline model
- Categorical encoding and feature scaling
- Train/test splitting and evaluation metric selection
- Training Logistic Regression and LightGBM models
- Hyperparameter tuning with cross-validation
- Generating a competition submission file

## Usage

1. Go to the [competition page](https://www.kaggle.com/competitions/playground-series-s5e11) and join the competition
2. Create a new Kaggle Notebook attached to the competition
3. Upload `my-first-model.ipynb` and run through the cells, filling in the `# TODO` sections as you go

## Requirements

If running locally rather than on Kaggle, you'll need:
```
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm
```
