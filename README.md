# Logistic Regression Implementation

## Overview
This project implements logistic regression using gradient descent from scratch. It includes feature scaling, decision boundary visualization, cost function analysis, and evaluation metrics.

## Requirements
Ensure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Files
- `logistic_regression.py`: Main script implementing logistic regression.
- `logisticX.csv`: Input feature dataset.
- `logisticY.csv`: Target labels dataset.

## Implementation Details
1. **Data Preprocessing:**
   - Loads the dataset from CSV files.
   - Applies feature scaling using StandardScaler.

2. **Logistic Regression:**
   - Uses the sigmoid function for classification.
   - Implements gradient descent for optimization.
   - Computes cost function value after convergence.

3. **Visualization:**
   - Plots decision boundary for the dataset.
   - Generates cost function vs iterations graph.
   - Compares learning rates (0.1 and 5) for gradient descent.

4. **Performance Evaluation:**
   - Computes confusion matrix.
   - Calculates accuracy, precision, recall, and F1-score.

## Usage
Run the script in Jupyter Notebook or as a standalone Python file:

```python
python logistic_regression.py
```

```




