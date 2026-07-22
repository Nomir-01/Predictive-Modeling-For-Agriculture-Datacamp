# Predictive Modeling for Agriculture

A classification project exploring which soil measurement is most useful for recommending a crop. The notebook evaluates candidate features independently with logistic regression and compares their predictive performance.

## Workflow

1. Inspect and prepare the soil-measurement dataset.
2. Separate features from the crop target.
3. Create training and test partitions.
4. Fit a logistic regression model for each soil feature.
5. Compare model performance and identify the strongest predictor.

## Tools

- Python
- pandas
- scikit-learn
- Jupyter Notebook

## Repository contents

- `notebook.ipynb` — exploratory analysis, modeling, and feature comparison
- `soil_measures.csv` — soil measurements and crop labels
- `farmer_in_a_field.jpg` — project cover image
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter lab notebook.ipynb
```

## Project context

This is a personal learning project completed as guided DataCamp coursework. It demonstrates multiclass classification, train/test evaluation, and systematic comparison of individual predictors.
