# 📧 Spam Mail Detection using Machine Learning

A Machine Learning project that classifies emails/messages as **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** techniques.

This project uses:
- **TF-IDF Vectorization**
- **Logistic Regression**
- **Naive Bayes**
- Model comparison using Accuracy, Confusion Matrix, and ROC Curve

---

## 🚀 Features

✅ Load and preprocess email dataset  
✅ Convert text into numerical features using TF-IDF  
✅ Train multiple ML models  
✅ Compare model performance  
✅ Predict custom messages manually  
✅ Visualize results with graphs  

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

Dataset file used:

`mail_data.csv`

Contains two columns:
- **Category** → spam / ham
- **Message** → email or SMS text

---

## 📌 Workflow

1. Import Libraries  
2. Load Dataset  
3. Handle Missing Values  
4. Encode Labels  
   - Spam = 0  
   - Ham = 1  
5. Split Data into Train/Test  
6. Apply TF-IDF Vectorizer  
7. Train Models:
   - Logistic Regression
   - Multinomial Naive Bayes
8. Evaluate Models
9. Predict New Messages
10. Plot Accuracy & ROC Curve

---

## 🤖 Models Used

### 1️⃣ Logistic Regression
A linear classification model used for binary classification.

### 2️⃣ Multinomial Naive Bayes
A probabilistic model commonly used for text classification.

---

## 📊 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve
- Training vs Testing Accuracy Comparison

---

## 📈 Sample Prediction

### Input:
```text
Congratulations! You have won a free gift card. Click now!
```
### Output:
```text
Spam Mail
```
