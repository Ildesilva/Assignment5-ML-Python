# Assignment5-ML-Python
**Author**: Ilmini De Silva    
**Date**: 07.23.2025 
**Environment**: See `environment.yml`  
**Description**:  


This project uses the classic **Iris dataset** to train, evaluate, and compare six different classification algorithms using **Scikit-Learn** and other Python scientific libraries. The goal is to select the best-performing model based on validation performance.

---

## 📁 Project Structure

- `iris.csv` – The dataset used (CSV version of the Iris dataset)
- `ML_py.ipynb` – Jupyter notebook with code and analysis
- `README.md` – Project overview and instructions (this file)

---

## 📊 Objective

To build a machine learning pipeline in Python that:
- Loads and explores the Iris dataset
- Trains multiple classification models
- Evaluates model performance
- Selects the best model based on validation results
- Uses the final model (SVM) for prediction and validation

---

## 🧪 Algorithms Evaluated

Using **Scikit-Learn**, the following classification algorithms were trained and tested:

- **Logistic Regression (LR)**
- **Linear Discriminant Analysis (LDA)**
- **K-Nearest Neighbors (KNN)**
- **Classification and Regression Trees (CART)**
- **Naive Bayes (NB)**
- **Support Vector Machine (SVM)** ✅ *(Selected: best validation performance)*

Each model was evaluated using **cross-validation accuracy**, and **SVM** showed the best overall performance.

---

## 📦 Requirements

This project uses Python and the following packages

-numpy
-pandas
-matplotlib
-scikitlearn
-scipy

This project follows the **"Machine Learning in Python: Step-by-Step"** tutorial by Jason Brownlee from *Machine Learning Mastery*. It demonstrates how to build a machine learning workflow to classify flower species using the Iris dataset.
🔗 Tutorial: [Machine Learning in Python Step-by-Step](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)
