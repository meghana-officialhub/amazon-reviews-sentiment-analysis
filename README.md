# 📊 Sentiment Analysis on Product Reviews

## 📌 Project Overview

This project focuses on analyzing customer reviews from an e-commerce platform to determine overall sentiment. The goal is to classify reviews as **Positive, Negative, or Neutral** and extract meaningful insights to understand customer satisfaction.

---

## 🎯 Problem Statement

E-commerce platforms receive thousands of reviews daily, making manual analysis inefficient. This project automates sentiment classification using Natural Language Processing (NLP) techniques.

---

## 📂 Dataset

* Source: Amazon Fine Food Reviews (Kaggle)
* Total records used: **5000**
* Key columns:

  * `Text` → Review content
  * `Score` → User rating (1–5)

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* TextBlob
* Matplotlib
* Seaborn
* Jupyter Notebook (VS Code)

---

## ⚙️ Project Workflow

### 1. Data Loading & Exploration

* Loaded dataset using Pandas
* Explored structure, columns, and data types

### 2. Data Cleaning

* Removed null and empty reviews
* Removed duplicate entries
* Selected relevant columns

### 3. Sentiment Analysis

* Used TextBlob to calculate polarity scores
* Classified reviews into:

  * Positive
  * Negative
  * Neutral

### 4. Data Visualization

* Bar chart → Sentiment count
* Pie chart → Sentiment distribution
* Rating vs Sentiment → Analytical comparison

---

## 📊 Key Insights

* Majority of reviews are **positive**, indicating strong customer satisfaction
* Negative reviews highlight issues like **product quality and packaging**
* Some mismatch observed between ratings and sentiment

---

## 💡 Business Recommendation

Improving product quality and packaging can significantly reduce negative feedback and enhance customer experience.

---

## 📁 Project Structure

```
├── analysis.ipynb
├── Reviews_5000.csv
├── summary.pdf
├── charts/
```

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas textblob matplotlib seaborn
   ```
3. Open `analysis.ipynb` in Jupyter/VS Code
4. Run all cells

---

## 👩‍💻 Author

**Meghana M**
