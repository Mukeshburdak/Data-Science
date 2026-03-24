# 🌳 Decision Tree Classifier from Scratch & Analysis

## 📌 Overview
This project implements a **Decision Tree Classifier from scratch in Python** using **Information Gain (Entropy)**.  
It also includes:
- 📊 Entropy vs Gini Impurity visualization
- 💼 Salary prediction using Decision Tree (sklearn)
- 🌲 Tree visualization using Graphviz

---

# 🧠 1. Decision Tree (From Scratch)

## 🔹 Intuition
A Decision Tree splits the dataset recursively by selecting the feature that gives the **maximum Information Gain**, reducing uncertainty at each step.

---

## 🔹 Approach
- Compute **Entropy** of the dataset
- Try all possible splits
- Choose split with **maximum Information Gain**
- Recursively build left & right subtrees
- Stop when:
  - Pure node OR
  - Max depth reached

---

## 🔹 Complexity
- Time Complexity: **O(n * m * log n)**
- Space Complexity: **O(n)**

---

## 🔹 Code

```python
# Decision Tree from Scratch (Entropy + Information Gain)
# [Code file uploded with dataset]
