# Multi-Class Benchmark Classification Pipeline

## Overview
This project implements and compares two supervised machine learning classification algorithms using the Iris dataset provided for the Datheon ML & DS task.

## Objectives
- Explore the Iris dataset.
- Split the data into training and testing sets using an 80:20 ratio.
- Standardize numerical features.
- Train Logistic Regression and Decision Tree classifiers.
- Compare accuracy, macro precision, macro recall, and macro F1-score.
- Visualize confusion matrices and decision boundaries.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook

## Project Files
- `iris.csv` — Original dataset.
- `iris_classification_pipeline.ipynb` — Complete implementation and visualizations.
- `iris_dataset.csv` — Saved dataset copy.
- `model_comparison.csv` — Model evaluation results.

## How to Run
1. Install Python 3.
2. Install the required packages:
   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter ipykernel`
3. Open `iris_classification_pipeline.ipynb` in VS Code or Jupyter Notebook.
4. Run all cells from top to bottom.

## Evaluation
The notebook evaluates both classifiers using a held-out test set and compares their accuracy, macro precision, macro recall, and macro F1-score.

## Learning Outcomes
This project demonstrates data exploration, feature scaling, model training, multi-class evaluation, confusion matrix interpretation, and decision boundary visualization.