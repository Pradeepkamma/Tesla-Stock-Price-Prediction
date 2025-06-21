# 📄 Full Research Paper
**Title:** Analysing Tesla Stock Prices Using Machine Learning Algorithm  
**Published in:** IJISRT, Volume 8, Issue 4, April 2023  
**Link:** [Read Online](https://ijisrt.com/analysing-tesla-stock-prices-using-machine-learning-algorithm)

---

## 🧠 Abstract

Long-term research has focused heavily on the prediction of stock values. Predicting stock prices has been one of the biggest concerns in recent years. Making a prediction about the stock market involves attempting to anticipate the future value of a company’s stock or another financial instrument traded on a stock exchange.

Machine learning techniques are frequently used. This paper uses supervised and unsupervised machine learning to predict Tesla stock price direction based on historical and sentiment-based data.

---

## 🔍 Introduction

Tesla Inc., an American automaker, was established in 2003. It developed electric vehicles for the consumer market. In early 2019, Tesla’s stock price declined, influencing the used car market significantly.

With limited post-sale service availability and high dependency on market sentiment, predicting stock trends became vital for customers and investors. This paper studies Tesla’s stock behavior and presents ML-driven forecasting.

---

## ⚙️ Technology Used

- **Machine Learning**: Both supervised and unsupervised
- **Libraries**: NumPy, Pandas, Scikit-learn, Matplotlib
- **Platform**: Jupyter Notebook
- **Model**: Linear Regression
- **Language**: Python

---

## 📊 Algorithm Used: Linear Regression

Linear regression models the relationship between dependent (stock price) and independent variables (Open, High, Low, Volume). The output shows the line of best fit and coefficient values, enabling prediction.

---

## 🛠️ Functional & Non-Functional Requirements

### Functional:
- Load dataset
- Preprocess data
- Apply regression model
- Evaluate output

### Non-Functional:
- Usability
- Efficiency
- Accuracy
- Portability

---

## 📉 Existing System

Existing systems rely on sentiment analysis, using Elon Musk’s tweets and public reactions to forecast price changes. Though innovative, these methods require heavy data and have limited accuracy due to emotional bias and computational costs.

---

## 🚀 Proposed System

We propose using predictive modeling with regression techniques. It uses historical Tesla stock data (Open, High, Low, Volume, Close) to train and predict outcomes with visualizations and performance metrics.

Expected accuracy:
- 69% in-sample
- 37% out-of-sample

---

## 🧱 Architecture

The system involves:
1. Data Collection
2. Preprocessing
3. Model Training
4. Prediction
5. Evaluation
6. Visualization

---

## 📦 Dataset

Collected from public repositories (e.g., Kaggle), stored in CSV format. Data is split:
- 80% Training
- 20% Testing

---

## 🧪 Results

Model evaluation using:
- Mean Absolute Error
- Mean Squared Error
- Root Mean Squared Error

Predicted vs Actual graphs confirm trend matching with acceptable error rates.

---

## ✅ Conclusion

ML can effectively predict Tesla’s stock prices. With clean data and proper modeling, even simple algorithms like Linear Regression deliver insightful results. Future work could explore deep learning and real-time market data.

---

## 📚 References

[1] M. Usmani et al., “Stock Market Prediction Using ML Techniques,” ICCOINS, 2016  
[2] K. Raza, “Stock Market ML Performance,” ICIEECT, 2017  
[3–9] Other IEEE conference citations
