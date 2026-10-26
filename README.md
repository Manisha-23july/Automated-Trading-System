# 🚀Automated-Trading-System 
A simple Python-based algorithmic trading bot that implements a Moving Average Crossover Strategy using historical stock data fetched via yfinance.

This project is designed as an introductory quantitative trading backtester to evaluate how a simple trend-following strategy performs against a buy-and-hold market return.

---

## 📋Table of Contents 

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites & Installation](#prerequisites-&-installation)
- [How to Run](#how-to-run)
- [Configuration](#configuration)
- [Future Improvements](#future-improvements)

---

## 📌Introduction 
Algorithmic trading leverages computer programs to execute trading decisions based on predefined mathematical rules and historical trends. This repository provides an end-to-end quantitative backtesting pipeline that automates historical data retrieval, technical indicator calculations, signal generation, trade simulation, and performance visualization.

---

## ✨Features
- **Automated Data Ingestion**: Seamlessly downloads historical stock market pricing and volume data via yfinance.

- **Technical Indicator Calculations**: Computes short-term and long-term Simple Moving Averages (SMAs) using pandas rolling windows to filter market noise.

- **Crossover Signal Generation**: Automatically establishes buy and sell signals based on trend intersections.

- **Trade Simulation**: Implements position lagging (shifting signals) to prevent look-ahead bias during backtesting.

- **Visual Analytics**: Plots comprehensive stock pricing, moving averages, and cumulative strategy growth versus market returns using matplotlib.

---

## 🛠Prerequisites & Installation
### **System Requirements**
- [ ] Python 3.8+

### **Installation Steps**
1.  **Clone the repository**
```bash
   git clone [https://github.com/Manisha-23july/Automated-Trading-System.git](https://github.com/Manisha-23july/Automated-Trading-System.git)
   cd Automated-Trading-System


