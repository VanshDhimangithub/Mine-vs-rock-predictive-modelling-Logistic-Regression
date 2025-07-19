# 🪨🔍 Mine vs Rock Classification (with Logistic Regression)

Are you a sonar machine struggling to tell if it's a rock or a mine? Same. That's why I built this model — to classify sonar signals as either **Mine (💣)** or **Rock (🪨)** using the power of *Logistic Regression* (yes, the classic linear boi).

## 📌 Project Overview

This project trains a Logistic Regression model on the [Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+sonar+mines+vs+rocks) to detect whether an object is a mine or just another boring rock, based on sonar frequency data.

## 📊 Dataset Info

- **Samples:** 208
- **Features:** 60 numeric features (like sonar echo amplitudes)
- **Target:** `'M'` (Mine) or `'R'` (Rock)
- **Source:** UCI ML Repository

## 🚀 Workflow

1. **Load** the data
2. **Preprocess** it (scaling, label encoding)
3. **Train-Test Split**
4. **Train** Logistic Regression
5. **Evaluate** it like a proud parent

## 🛠️ Tech Stack

- Python 🐍
- Logistic Regression (sklearn)
- Numpy, Pandas, Matplotlib, Seaborn
- Jupyter Notebooks

## 📈 Results

Accuracy? Training Accuracy: 83.42%
Test Accuracy: 76.19%
