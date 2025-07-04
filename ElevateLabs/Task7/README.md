# AIML_-Intern_-Task7
# SVM - Breast Cancer Classification

This notebook demonstrates the use of Support Vector Machines (SVM) for binary classification on the breast cancer dataset.

---

## Objective

- Train and evaluate SVM models using linear and RBF kernels
- Understand the effect of C and gamma hyperparameters
- Visualize decision boundaries in 2D
- Use cross-validation to evaluate performance

---

## Dataset Used

- **Dataset**: `sklearn.datasets.load_breast_cancer()`
- **Target**: 0 → Malignant, 1 → Benign
- **Features**: 30 numerical features related to tumor measurements

---

## Tasks Performed

- Loaded and standardized the dataset
- Split data into training and testing sets
- Trained SVM with:
  - Linear kernel
  - RBF (non-linear) kernel
- Evaluated using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - Cross-validation
- Visualized 2D decision boundary using first 2 features

---

## Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn` (SVC, confusion matrix, cross_val_score)

---

## Results
 Linear SVM-- Accuracy (Test) = ~0.97 
           -- CV Accuracy    = ~0.96
           
 RBF SVM   --  Accuracy (Test)= ~0.99 
           --  CV Accuracy    = ~0.98 
           
---

## Includes
  - Jupyter Notebook (.ipynb)
  - README.md
  - Visualizations of decision boundaries and confusion matrix

