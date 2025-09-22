# HRP

## 📌 Overview
This project implements **Hierarchical Risk Parity (HRP)**, a portfolio construction method by Marcos López de Prado.  
HRP uses hierarchical clustering to allocate capital without inverting the covariance matrix, often yielding more **stable** and **diversified** out-of-sample performance than mean–variance optimization.

The notebook demonstrates:
- Fetching NSE stock data (2019-01-01 to 2024-01-01)
- Computing returns, covariance, and correlation matrices
- Performing hierarchical clustering (dendrogram)
- Quasi-diagonalizing the covariance matrix
- Allocating HRP weights via recursive bisection
- Comparing HRP vs Equal-Weight performance

---

## 🛠️ Requirements
```bash
pip install yfinance numpy pandas matplotlib seaborn scipy
