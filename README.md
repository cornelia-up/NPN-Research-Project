# Optimization and Credit Scoring Models Using MOPSO-CS, Logistic Regression, and LBSA

This repository contains implementations of two advanced optimization algorithms, **Multi-Objective Particle Swarm Optimization with Crowding Search (MOPSO-CS)** and **Logistic Regression**, as well as a second approach using **Leader-Based Swarm Algorithm (LBSA)** for credit scoring applications. The projects aim to demonstrate effective optimization techniques for feature selection, credit scoring, and performance evaluation through metrics and visualizations.

---

## Repository Overview

### Files
1. **`MOPSO-CS & LR.ipynb`**
   - Implements a **MOPSO-CS algorithm** to optimize a logistic regression model for credit scoring.
   - Includes data preprocessing, training, and evaluation metrics like accuracy, F1 score, and confusion matrix visualization.

2. **`LBSA code 1.ipynb`**
   - Implements the **Leader-Based Swarm Algorithm (LBSA)** for a similar credit scoring application.
   - Focuses on swarm intelligence and optimization techniques for solving complex classification problems.

---

## Features
- **Multi-Objective Optimization**:
  - Uses MOPSO-CS and LBSA to optimize feature weights and classifier performance.
- **Credit Scoring Application**:
  - Evaluates creditability based on a dataset of customer credit information.
- **Performance Metrics**:
  - Includes accuracy, F1 score, confusion matrix, sensitivity, and specificity.
- **Data Visualization**:
  - Generates confusion matrix heatmaps with color bars for better interpretability.

---

## Prerequisites

### Required Libraries
Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `tqdm`

Install these libraries using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn tqdm
