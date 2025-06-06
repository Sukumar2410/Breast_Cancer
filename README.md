# Breast_Cancer
This project demonstrates how to use **Support Vector Machines (SVM)** for both **linear** and **non-linear classification** on a real-world dataset (Breast Cancer Wisconsin). It includes model training, visualization of decision boundaries using PCA, and accuracy comparison between kernels.

## 📁 Dataset

- **Name**: Breast Cancer Wisconsin Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Attributes**: 30 numeric features, 1 binary target (Malignant/Benign)
 
## 🎯 Objective

1. Load and preprocess a dataset for binary classification.
2. Train and evaluate:
   - **Linear SVM**
   - **RBF (Radial Basis Function) SVM**
3. Visualize the **decision boundaries** using PCA (2D).
4. Tune and compare **accuracy** of both models.
5. Discuss insights and findings.

## 🔧 Tools & Libraries

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn (SVMs, PCA, accuracy_score, train_test_split)

## 📊 Results

| Model        | Accuracy (%) |
|--------------|--------------|
| Linear SVM   | **99.12%**   |
| RBF SVM      | 96.49%       |

## 📌 Key Insights

- The dataset is **linearly separable**, making Linear SVM the better choice in terms of both performance and interpretability.
- The RBF SVM's flexibility creates a curved decision boundary but does not outperform the simpler linear model in this case.
- PCA was used for 2D visualization, but full-feature training was retained for classification.

## 📈 Visualizations

### 🔹 Linear SVM Decision Boundary
![Linear SVM Decision Boundary](linear_svm.png)

### 🔹 RBF SVM Decision Boundary
![RBF SVM Decision Boundary](rbf_svm.png)

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/svm-breast-cancer.git
   cd svm-breast-cancer
