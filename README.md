# 📊 Stock Market Prediction with Exogenous Variables using ML & DL Models

This project explores various Machine Learning (ML), Deep Learning (DL), and Hybrid models to predict stock market behavior using exogenous (external) variables. The goal is to estimate a continuous Market Confidence score and classify it into **Bullish**, **Neutral**, or **Bearish** categories.

---

## 🚀 Project Highlights

- Utilizes a rich set of exogenous variables including technical indicators, sentiment scores, and economic signals.
- Implements a wide range of ML, DL, and hybrid models for comparison.
- Converts numerical confidence values into market classes for better interpretability.
- Evaluates each model using multiple metrics including accuracy, MSE, classification report, and confusion matrix.
- Includes tests for data leakage using label shuffling and correlation checks.

---

## 📁 File Descriptions

| File Name                                 | Description |
|-------------------------------------------|-------------|
| `Stock_Prediction.ipynb`                  | Jupyter Notebook with full code: data processing, ML/DL/hybrid models, evaluation, and visualizations. |
| `stock_data_with_exogenous_variables.csv` | Dataset with market-related features and the target variable `Market_Confidence`. |
| `requirements.txt`                        | List of required Python libraries to run the notebook. |
| `README.md`                               | This documentation file describing the project, usage, and structure. |
| `results/performance_summary.csv`         | (Optional) Summary table comparing all model performances. |
| `results/charts/`                         | (Optional) Visual outputs such as confusion matrices and feature importance charts. |

---

## 🧠 Models Implemented

### Machine Learning:
- Linear Regression, Ridge, Lasso, ElasticNet
- Decision Tree, Random Forest
- Gradient Boosting, XGBoost, LightGBM, CatBoost
- Support Vector Regression

### Deep Learning:
- Multilayer Perceptron (MLP)
- CNN (1D)
- LSTM
- GRU
- Transformer

### Hybrid Models:
- MLP + XGBoost
- LSTM + LightGBM
- AutoEncoder + Random Forest
- CNN + CatBoost
- Stacked Ensemble

---

## 📊 Evaluation Metrics

- **Accuracy Score**
- **Mean Squared Error (MSE)**
- **Classification Report** (Precision, Recall, F1-score)
- **Confusion Matrix**

---

## 🧪 Dataset Overview

The dataset includes multiple market-related features such as:

- Technical Indicators (RSI, MACD, ATR, etc.)
- Sentiment Scores
- Economic Flags (Fed Meetings, Core CPI, etc.)
- Volume, Open, Close, and other market metrics

The target column `Market_Confidence` is a float (0 to 1), later mapped to market classes.

---

## 📦 Installation

To install required dependencies:

```bash
pip install -r requirements.txt
```

---

## 📂 How to Run

1. Clone the repository  
2. Open the `Stock_Prediction.ipynb` notebook  
3. Run all cells in order  
4. Review accuracy scores, charts, and model comparisons

---

## 📌 Author

Luv Khati  
Master’s Student in Statistical Data Analytics  
Tampere University, Finland

---

## 📜 License

This project is open-source and free to use for educational and research purposes.
