# This Project is a Homework Assignment for CS 4372.501
## Titanic Survival Prediction and Model Comparison

This project explores the famous **Titanic dataset** to predict passenger survival using multiple machine learning classification models.  
It compares model performance based on accuracy, precision, recall, F1-score, and ROC-AUC metrics.  

The models built and evaluated in this project are:
1. **Decision Tree Classifier:** A tree-based model that recursively splits the dataset based on feature conditions.
2. **Random Forest Classifier:** An ensemble model that combines multiple decision trees to improve accuracy and reduce overfitting.
3. **AdaBoost Classifier:** An ensemble technique that sequentially combines weak learners, focusing on misclassified samples.
4. **XGBoost Classifier:** A gradient boosting method that efficiently optimizes model performance through parallel tree construction.

---

## Prerequisites

To run this project, you need a Python environment with the following libraries, and any that it installs as dependents.  
You can install them using `pip`:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost jupyter
```

---

## How to Run the Code

1. **Open the Jupyter Notebook:**

Start a Jupyter Notebook server in your terminal from the project directory:

```bash
jupyter notebook
```

This will open a browser window with the Jupyter interface.
Select `MainCode.ipynb` to open the notebook.
If it does not auto-launch, control-right click the link in the terminal to open it manually.

---

2. **Run the Cells:**

Execute the notebook cells **in order**, from top to bottom.

* **Data Preprocessing:**
  Handles missing values, encodes categorical features, and scales numerical attributes for model readiness.

* **Model Building:**

  * Trains and tunes four classifiers using `GridSearchCV`.
  * Extracts best estimators and computes key performance metrics for each model.
  * Visualizes feature importances.

* **Model Evaluation:**
  Generates and compares:

  * Confusion Matrices
  * ROC Curves
  * Precision-Recall Curves
  * Metrics Comparison Table
  * Classification Reports
  * Cross-Validation Scores

---


## Contributers

* **@mariptime** - Akshay Nagarajan
* **@vaipos** - Vaishnavi Pasumarthi

CS 4372.501 - Assignment 2
Anurag Nagar - Fall 2025