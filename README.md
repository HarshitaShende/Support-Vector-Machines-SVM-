# Task-7-Support-Vector-Machines-SVM-
Support Vector Machines (SVM)


## 🎯 Objective
Implement and evaluate Support Vector Machines (SVM) for both linear and non-linear classification using the Breast Cancer Wisconsin dataset.

---

## 🛠️ Tools & Libraries
- Python
- Scikit-learn
- NumPy
- Matplotlib
- Seaborn
- PCA (for visualization)

---

## 📂 Dataset
Used built-in `load_breast_cancer()` dataset from `sklearn.datasets`.

- 569 samples
- 30 numeric features
- Binary classification: `0 = Malignant`, `1 = Benign`

---

## 📌 Task Steps

### 1. Data Preprocessing
- Loaded dataset and separated features/target
- Applied `StandardScaler` for normalization

### 2. Model Training
- Trained two models using:
  - **SVC(kernel='linear')**
  - **SVC(kernel='rbf')**

### 3. Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report
- 5-Fold Cross-Validation

### 4. Visualization
- Reduced feature space to 2D using **PCA**
- Plotted decision boundaries for both models

---

## 📊 Results

| Model       | Accuracy | CV Score |
|-------------|----------|----------|
| Linear SVM  | ~96%     | -        |
| RBF SVM     | ~98%     | ~97%     |

---

## 🔍 Inferences

- **Linear SVM** performs well but is outperformed by **RBF kernel** on non-linear patterns.
- **RBF kernel** captures complex boundaries effectively.
- **PCA** helped us visualize high-dimensional decision boundaries.




