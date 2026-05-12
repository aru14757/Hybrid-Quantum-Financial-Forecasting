# Hybrid-Quantum-Financial-Forecasting

This repository contains the dataset and trained models associated with the research paper:

**"Hybrid Quantum-Classical Neural Architectures for Financial Time-Series Forecasting"**

The study investigates classical deep learning models, quantum neural networks, and hybrid quantum-classical architectures for forecasting the S&P 500 index using binary classification, multiclass classification, and regression-based approaches.

---

## Repository Contents

### Dataset

The repository includes processed S&P 500 financial time-series data from 2021 to 2025 with technical indicators:

- Open
- High
- Low
- Close
- Volume
- SMA_50
- SMA_200
- RSI
- MACD
- Signal
- Momentum

### Trained Models

Included trained models:

- LSTM+QNN
- GRU+QNN
- QENN
- QSVM
- QLSTM
- QGRU
- BiLSTM
- CNN+QNN
- CNN+LSTM+QNN
- CNN+GRU+QNN
- CNN+GRU+Attention+QNN

---

## Data Source

Historical S&P 500 market data from 2021–2025 were obtained from Yahoo Finance using the yfinance API.

---

## Study Summary

The experimental results demonstrate that hybrid quantum-classical architectures outperform purely quantum and classical baseline models in financial time-series forecasting tasks.

The LSTM+QNN model achieved the best regression performance with:

- R² = 0.9407
- RMSE = 112.77
- MAE = 78.67
- MAPE = 1.32%

The study also shows that regression-based forecasting is more suitable for trading-oriented financial applications than classification-based approaches.

---

## Authors

- Alibek Barlybayev
- Aruzhan Tazhibay
- Aizhan Nazyrova
- Alua Turginbayeva
- Nurgul Uzakkyzy
- Gulmira Shakhmetova
- Zhanar Lamasheva

Institute of Digital Sciences and Artificial Intelligence  
L.N. Gumilyov Eurasian National University  
Astana, Kazakhstan

---

## License

This repository is released under the MIT License.

---

## Citation

If you use this dataset or trained models in your research, please cite the associated publication.
