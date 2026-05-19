# Diamond Price Prediction

## Project Summary

This project is a clean, student-friendly implementation of a **diamond price prediction**. The main goal is to estimate diamond price from cut, carat, color, clarity, and dimensions. The notebook keeps the workflow simple: load the dataset, understand the columns, clean the data, train a baseline model, and check how well the model performs.

No external repository links or profile links are included in this description. Everything needed to understand and run the project is kept inside this folder.

## Problem Statement

A raw dataset is useful only when it is converted into a clear decision-making workflow. In this project, the data is processed step by step so that important patterns can be found and a machine learning model can be trained. The expected output is based on `price`.

## Files Included

| File | Purpose | Quick Note |
|---|---|---|
| `diamonds.csv` | Main data source for this folder | 2000 sampled rows x 10 columns |
| Notebook file | Complete Python workflow | Includes loading, cleaning, training, and evaluation |
| PDF report | Human-readable project summary | Matches the updated project structure |

## Important Columns

| Column | Role |
|---|---|
| `carat` | Input feature used in the modelling workflow |
| `cut` | Input feature used in the modelling workflow |
| `color` | Input feature used in the modelling workflow |
| `clarity` | Input feature used in the modelling workflow |
| `depth` | Input feature used in the modelling workflow |
| `table` | Input feature used in the modelling workflow |
| `price` | Target / output column used in the modelling workflow |
| `x` | Input feature used in the modelling workflow |
| `y` | Input feature used in the modelling workflow |
| `z` | Input feature used in the modelling workflow |

## Workflow Followed

1. **Load the data** from the local dataset file present in the same project folder.
2. **Inspect the structure** using shape, column names, missing values, and basic statistics.
3. **Clean the dataset** by removing empty columns, handling missing values, and keeping only useful features.
4. **Prepare the model input** by separating features and the target column.
5. **Train a baseline model** using a simple scikit-learn pipeline with preprocessing.
6. **Evaluate the result** using practical metrics such as accuracy, classification report, MAE, RMSE, or R2 score depending on the target type.
7. **Write observations** in a short and direct way so the project can be explained easily.

## How to Run

1. Open the notebook in Jupyter Notebook, JupyterLab, Google Colab, or VS Code.
2. Keep the dataset files in the same folder as the notebook.
3. Run the cells from top to bottom.
4. Read the printed metrics and notes at the end before making conclusions.

## Final Note

This version keeps the logic understandable and avoids unnecessary complexity. The aim is not to make the notebook look overloaded, but to make it readable, explainable, and useful for a student-level data science portfolio.
