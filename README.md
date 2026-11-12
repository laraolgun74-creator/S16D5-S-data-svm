# Support Vector Machines (SVM)

## Overview

This project explores Support Vector Machines (SVM) and different kernel functions to develop an intuitive understanding of how SVM classifiers work and how kernel selection affects classification performance.

The exercises use synthetic datasets to visualize decision boundaries, compare classification models, and evaluate their generalization performance.

## Topics Covered

- **XOR Classification:** Exploring a non-linearly separable dataset.
- **Linear SVM:** Building a linear SVM classifier and comparing it with Logistic Regression.
- **Kernel SVM:** Experimenting with Polynomial, RBF, and Sigmoid kernels.
- **Hyperparameter Tuning:** Using `RandomizedSearchCV` to find suitable SVM parameters.
- **Model Generalization:** Evaluating model performance on unseen test data.
- **KNN vs. SVM:** Comparing the classification performance of K-Nearest Neighbors and SVM.

## Models and Techniques

- Support Vector Machines (SVM)
- Linear and nonlinear kernel functions
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Cross-validation
- Hyperparameter optimization
- Decision boundary visualization

## Evaluation

The models are evaluated using cross-validation and test-set performance. Decision boundary visualizations are also used to understand how different kernels separate data points.

In the final comparison, KNN achieved **96% test accuracy**, while SVM achieved **94% test accuracy** on the evaluated test set.

## Repository Structure

```text
S16D5-S-data-svm/
├── SVM.ipynb
└── tests/
    ├── generalization.pickle
    ├── linear_svm.pickle
    ├── poly_svm.pickle
    ├── rbf_svm.pickle
    └── sigmoid_svm.pickle
```

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/laraolgun74-creator/S16D5-S-data-svm.git
   ```

2. Navigate to the project directory:

   ```bash
   cd S16D5-S-data-svm
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib scikit-learn jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `SVM.ipynb` and follow the exercises.

## Purpose

The main goal of this project is to build a practical understanding of SVM classification, explore the impact of different kernel functions, and compare SVM with another widely used classification algorithm.

---

*This project was completed as part of my Data Science and Machine Learning training.*
