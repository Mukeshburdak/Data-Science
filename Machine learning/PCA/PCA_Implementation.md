# 🧠 Breast Cancer Classification using PCA & Logistic Regression

📌 Project Overview
-
* This project explores dimensionality reduction using Principal Component Analysis (PCA) and evaluates its impact on breast cancer classification.
The goal is to visualize high-dimensional data, reduce complexity, and compare model performance using 2 vs 3 PCA components.

📂 Dataset
-
* Breast Cancer Wisconsin Dataset

* Source: sklearn.datasets

* Classes:

> 0 → Benign

> 1 → Malignant

🔍 Workflow
-
* Data preprocessing and standardization

* Dimensionality reduction using PCA

* 2D and 3D PCA visualization

* Model training using Logistic Regression

* Performance evaluation using:

> Accuracy

> Precision

> Recall

> F1-score

> Confusion Matrix

> Comparison of PCA with 2 vs 3 components

📊 PCA Visualization
-
* 2D PCA for basic class separation

* 3D PCA for deeper structure understanding

* Interactive 3D scatter plots used for exploratory analysis

🤖 Model Used
-
* Logistic Regression

* Chosen for its interpretability and strong baseline performance in medical datasets

📈 Evaluation Metrics
-
* Confusion Matrix

* Precision, Recall, F1-score

🔬 Results Summary
-
* PCA Components	Performance Insight
* 2 Components	Good visualization, slightly lower recall
* 3 Components	Better class separation and higher ROC–AUC

* Observation:
> PCA with 3 components captures more variance, leading to improved classification performance, especially in detecting malignant cases.

🛠 Technologies Used
-
> Python

> NumPy

> Pandas

> Matplotlib

> Scikit-learn

🚀 Key Learnings
-
* Importance of feature scaling before PCA

* Trade-off between dimensionality and performance

* Visual analysis as a decision-making tool

📌 Future Work
-
* Compare PCA vs no PCA

* Try non-linear dimensionality reduction (t-SNE, UMAP)

* Test advanced models (SVM, Random Forest)

* Hyperparameter tuning

---
