# Baseline Classifier Benchmark

**TL;DR:** Compare Logistic Regression vs Random Forest on a small dataset (Iris). Includes accuracy, ROC-AUC, and confusion matrix.

## What’s inside
- Load the Iris dataset from scikit-learn
- Train two classifiers: Logistic Regression and Random Forest
- Evaluate using Accuracy, ROC-AUC, and Confusion Matrix
- PM-style commentary on tradeoffs

## How to run
Open the notebook in Google Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ibrahimasifali94/baseline_classifiers_mini/blob/main/GH_baseline_classifiers.ipynb)

## Results
- Logistic Regression accuracy: ~95%
- Random Forest accuracy: ~97%
- Random Forest performs slightly better, but Logistic Regression is simpler and faster to train.
- Both models separate classes well, but Random Forest handles nonlinear boundaries better.

## Screenshot
![Confusion Matrix](assets/confusion_matrix.png)

## Next ideas
- Try more classifiers (SVM, KNN, Gradient Boosting)
- Add cross-validation instead of a single train/test split
- Plot feature importance from Random Forest
