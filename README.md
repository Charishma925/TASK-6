# K-Nearest Neighbors (KNN) Classification – Wine Dataset

## Objective

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Wine dataset** from Scikit-learn. The goal is to understand how KNN works and evaluate its performance for a multi-class classification task.

---

## Tools & Libraries

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## Dataset: Wine (UCI / Scikit-learn)

- **Samples:** 178
- **Classes:** 3 (different types of wines)
- **Features:** 13 numerical features such as alcohol, magnesium, flavanoids, etc.

---

## Steps Performed

### 1. Load and Prepare Dataset
- Loaded the Wine dataset using `sklearn.datasets.load_wine()`
- Split into training and testing sets
- Applied feature scaling using `StandardScaler`

### 2. Train KNN Model
- Used `KNeighborsClassifier` from Scikit-learn
- Trained models for various values of **K** (e.g., 1, 3, 5, 7)

### 3. Evaluate the Model
- Evaluated accuracy for each K
- Generated and displayed **confusion matrices** using `ConfusionMatrixDisplay`

### 4. Visualize Accuracy
- Plotted **Accuracy vs K** to find optimal value

### 5. Visualize Decision Boundaries
- Reduced dimensionality to 2D using **PCA**
- Plotted decision boundaries using `contourf` and scatter plots

---

## Results

- Accuracy was highest at K = 3 and K = 5
- Confusion matrix showed good class separation
- PCA decision boundary plot illustrated KNN’s classification regions
