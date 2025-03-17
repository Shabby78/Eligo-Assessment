# **FINAL REPORT : AG News CLassification**

## **1. Objective:**
This project classifies news article into 4 categories:
1. World
2. Sports
3. Business
4. Sciece/Tech

## **2. Data Processing:**
- Loaded AG News dataset from **Hugging Face**.
- Text cleaning was applied.
- Splitted into **train (80%) & test (20%)**

## **3. Exploratory Data Analysis (EDA):**
- **Visualizations:**
  - **Category distribution** (imbalanced dataset).
  - **Text length analysis** (Business & World categories have longer articles).
  - **Word cloud** (common words in dataset).

## **4. Model Training & Evaluation**
- **Count Vectorizer + Logistic Regression**:
  - Accuracy: **90%**
  - Precision, Recall, & F1-score.
