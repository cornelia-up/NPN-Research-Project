# NPN-Research-Project

# Credit Scoring Model Using MOPSO-CS and Logistic Regression

This repository implements a **credit scoring model** using **Multi-Objective Particle Swarm Optimization with Crowding Search (MOPSO-CS)** and evaluates its performance through various metrics such as accuracy, F1 score, and confusion matrix visualization. The project leverages Python and libraries like `scikit-learn`, `seaborn`, and `matplotlib` for data preprocessing, model optimization, and performance visualization.

## Features
- Implements a custom Multi-Objective Particle Swarm Optimization (MOPSO-CS) algorithm.
- Preprocessing of credit scoring data with feature scaling and cleaning.
- Evaluation metrics:
  - **Accuracy**
  - **F1 Score**
  - **Confusion Matrix** (with heatmap and color bar)
- Data visualization for confusion matrix.
- Optimization results with custom fitness functions for misclassifications.

## Prerequisites
The following Python libraries are required to run the project:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `tqdm`

You can install all dependencies using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn tqdm
