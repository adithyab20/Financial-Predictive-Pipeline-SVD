# Financial-Predictive-Pipeline-SVD
A data pipeline and predictive modeling system utilizing Singular Value Decomposition (SVD) to filter market noise and forecast stock trends.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Data Science](https://img.shields.io/badge/Domain-Data%20Science%20%26%20Engineering-success)
![SVD](https://img.shields.io/badge/Algorithm-SVD-orange)

## 📌 Overview
Historical stock market data is notoriously volatile and complex, making it difficult to predict future trends. Traditional analysis struggles with the sheer volume of features (open, close, low, high) recorded over extended periods, and random market noise often hides actionable patterns.

This project tackles these challenges by leveraging **Singular Value Decomposition (SVD)**—a mathematical dimensionality reduction technique used to decompose complex matrices into simpler components. By filtering out unwanted noise, this pipeline isolates the key patterns driving stock price changes, ultimately improving predictive classification accuracy and computational efficiency.

## 🚀 Objectives
* **Data Complexity Management:** Process and prepare high-volume stock datasets with multiple time-series features.
* **Noise Reduction:** Implement SVD to filter out random market fluctuations and reveal the underlying behavior of the market.
* **Predictive Modeling:** Apply machine learning classification to forecast market trends based on the cleaned, reduced dataset, creating better models for trading strategies.

## 🧠 Methodology
1. **Data Collection & Preparation:** Aggregated historical stock data and engineered the necessary features for mathematical modeling.
2. **Normalization:** Scaled the financial data to ensure uniform weight across all pricing factors prior to decomposition.
3. **Dimensionality Reduction (SVD):** Decomposed the data matrix to identify key patterns. Analyzed reconstruction metrics (MSE, MAE, R-squared) across different values of *k*.
4. **Classification & Evaluation:** Compared classification models on the raw data versus the SVD-processed data to quantify the improvement in trend prediction.

## 📊 Results & Performance
The application of SVD successfully removed noise without losing critical variance. Evaluation showed that as the number of components (*k*) increased, the F1 score improved until reaching a plateau of efficiency at **k=5**. 

* **Before SVD:** Accuracy = `0.9508` | F1 Score = `0.9559`
* **After SVD:** Accuracy = `0.9549` | F1 Score = `0.9594`

The integration of SVD yielded a leaner dataset, favoring computing efficiency while simultaneously improving both accuracy and F1 classification scores.

## 🛠️ Technical Implementation
* **Data Engineering:** Built pipelines to clean, format, and prepare raw financial datasets for downstream mathematical processing.
* **Model Execution:** Handled the core coding and environment setup for executing SVD algorithms and evaluating the machine learning classification models.

## 📬 Contact
**Adithya Reddy Boravelly**
* **Location:** Birmingham, AL
* **Email:** adithyareddyboravelly@gmail.com
