# 🚨 Credit Card Fraud Detection & Anomaly Analysis

## 📌 Overview

Fraudulent transactions may be rare, but their impact is huge. Even a small number of fraud cases can lead to significant financial loss and damage customer trust.

In this project, I focused on identifying such transactions using **anomaly detection techniques** along with data visualization. The goal was not just to detect fraud, but to understand how fraudulent behavior differs from normal transaction patterns.

---

## 🎯 Objectives

* Explore transaction data to uncover fraud patterns
* Compare how fraudulent and normal transactions behave
* Apply anomaly detection algorithms to identify suspicious activity
* Build a system that can flag potential fraud cases

---

## 📊 Exploratory Data Analysis (EDA)

I started by analyzing the data to understand underlying patterns and differences.

Some key analyses include:

* Comparing **transaction time vs amount**
* Visualizing fraud vs normal transaction behavior
* Identifying unusual trends, clusters, and outliers

---

## 🤖 Models Used

To detect anomalies, I used multiple machine learning approaches:

### 🔹 Isolation Forest

This model works by isolating data points. Since fraudulent transactions are rare and different, they tend to get isolated quickly.

* Effective for large and imbalanced datasets
* Fast and efficient
* Does not require labeled data

---

### 🔹 Local Outlier Factor (LOF)

LOF focuses on how dense a data point’s neighborhood is.

* Detects anomalies based on **local density differences**
* Flags points that behave differently compared to nearby data

---

### 🔹 One-Class SVM

This model learns what “normal” data looks like and identifies anything outside that boundary as an anomaly.

* Good for learning patterns of normal behavior
* Useful when fraud cases are limited

---

## ⚙️ Tech Stack

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 📈 Key Insights

* Fraudulent transactions show **distinct patterns** compared to normal ones
* Time-based analysis can reveal unusual activity periods
* Using multiple models provides more reliable detection than relying on just one
