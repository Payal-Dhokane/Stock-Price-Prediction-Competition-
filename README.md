# 📈 Stock Price Predictor (Kaggle Competition)

🔗 **Kaggle Competition Link:**  
https://www.kaggle.com/competitions/stock-price-predictor

---

## 🧠 Overview
This repository contains the dataset and supporting materials for the **Stock Price Predictor** Kaggle competition.

The goal of this competition is to help learners practice **time-series analysis and binary classification** by predicting whether a stock’s **next-day closing price** will go **up or down** based on historical price data.

This competition is designed **purely for learning and experimentation**.  
There are **no prizes or medals**.

---

## 🎯 Problem Statement
Given historical daily stock price data, participants must predict:

- `1` → Stock price goes **up** the next day  
- `0` → Stock price goes **down or stays the same**

This helps beginners understand:
- Feature engineering on time-series data
- Model training for classification tasks
- Kaggle submission and evaluation workflow

---

## 📂 Dataset Description
The dataset is derived from **Yahoo Finance** and contains the following columns:

- `date` – Trading date  
- `open` – Opening price  
- `high` – Highest price of the day  
- `low` – Lowest price of the day  
- `close` – Closing price  
- `target` – Binary label indicating next-day price movement  

### Files Included
- `StockTrends.zip` - All files
- `train.xlsx` – Training data with target column  
- `test.xlsx` – Test data without target  
- `sample_submission.csv` – Example submission format  



## 📊 Evaluation Metric
Submissions are evaluated using **Accuracy**.

Accuracy measures how often the predicted direction (up/down) matches the actual movement.

---



⭐ If you find this useful, consider giving the Kaggle competition an upvote!
