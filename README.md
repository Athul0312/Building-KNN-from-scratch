# Building-KNN-from-scratch
# KNN from Scratch (Iris Dataset)

Built a fully custom K-Nearest Neighbors classifier from scratch using only NumPy.  
Used it to classify flower species on the Iris dataset and visualized results.

---

## What I Did

- Implemented custom KNN class with:
  - Euclidean distance calculation
  - Manual sorting + voting logic
- Used `train_test_split` to split data
- Evaluated accuracy and compared predicted vs actual labels

---

## Results

- **Test Accuracy:** 98.3%
- **Precision per class:** [1.00, 1.00, 0.95]
- **Recall per class:** [1.00, 0.96, 1.00]
- Visualized predictions using:
  - Confusion matrix heatmap
  - 3D scatter plot of feature space
  - Seaborn pairplot by predicted class

---

## Takeaway

This project was built to understand KNN at a low level by avoiding sklearn's classifier entirely.  
The high accuracy confirms the algorithm logic, and the visualizations helped highlight prediction confidence and errors.
