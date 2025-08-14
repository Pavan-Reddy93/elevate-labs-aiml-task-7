
# Support Vector Machines (SVM) – Breast Cancer Classification

##  Overview

This project demonstrates how to use **Support Vector Machines (SVM)** for binary classification on the **Breast Cancer dataset**.
We train both **Linear** and **RBF kernel** models, visualize the decision boundary after **PCA dimensionality reduction**, tune hyperparameters, evaluate using **cross-validation**, and save the trained model for future predictions.

##  Dataset

* Dataset file: `breast-cancer.csv`
* Target variable: **diagnosis** (`M` = Malignant, `B` = Benign)
* Features: Various cell nucleus measurements.



##  Steps Performed

1. **Load Dataset** – Read the CSV file using `pandas`.
2. **Data Preprocessing**

   * Encode the target column (`diagnosis`) using `LabelEncoder`.
   * Standardize features with `StandardScaler`.
3. **Train SVM Models**

   * Linear kernel SVM
   * RBF kernel SVM
4. **Hyperparameter Tuning** – Tune `C` and `gamma` for better accuracy.
5. **Visualization**

   * Reduce features to **2D using PCA**.
   * Plot decision boundaries for both kernels.
6. **Cross-Validation** – Evaluate baseline model using 5-fold CV.
7. **Save Model** – Store the trained model as `svm_model.pkl` for later predictions.



##  Results

* **Cross-Validation Accuracy**: \~XX% (varies depending on parameters)
* **Best Parameters (RBF)**: Example – `C=10`, `gamma=0.001`
* Decision boundaries show clear separation after PCA transformation.


##  Author

Pavan Reddy Kasara
B.Tech – Artificial Intelligence & Machine Learning
Presidency University, Bengaluru
