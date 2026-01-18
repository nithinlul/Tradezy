
**Tradezy** is a cloud-hosted, interactive web application designed to provide **data-driven financial insights** for retail and intermediate investors. It integrates **fundamental stock analysis**, **risk modeling**, and **time-series forecasting** into a single, intuitive platform built using **Python** and **Streamlit**.

The system follows a **client–server architecture**, where user inputs are processed through modular backend services that handle data retrieval, analytics, and prediction pipelines before returning visualized outputs to the client UI .


* **Real-Time Stock Analysis**

  * Fetches historical and fundamental stock data via external APIs.
  * Displays key risk metrics such as volatility, Sharpe ratio, and beta.
  * Interactive charts and visualizations.

* **Risk Modeling using CAPM**

  * Computes expected returns based on the **Capital Asset Pricing Model (CAPM)**.
  * Allows dynamic tuning of market parameters for personalized analysis.
  * Provides theoretical benchmarks for asset performance .

* **Time-Series Forecasting (ARIMA)**

  * Implements a statistical ARIMA pipeline for short-term stock price prediction.
  * Performs stationarity checks, differencing, and parameter tuning.
  * Outputs forecasts with confidence intervals for uncertainty visualization .

* **Interactive Web Interface**

  * Built using Streamlit for rapid deployment and usability.
  * Fully browser-based; no local installation required.

---

## 🧱 System Architecture

Tradezy uses a **modular client–server design**:

* **Client Layer**: Streamlit-based UI for user interaction.
* **Server Layer**: Business logic modules for data processing, CAPM computation, and forecasting.
* **Data Layer**: External financial data APIs (e.g., yfinance).

This separation of concerns enables **scalability**, **maintainability**, and easy deployment on cloud platforms .

---

## 🛠 Tech Stack

* **Frontend / UI**: Streamlit
* **Backend**: Python
* **Data Processing**: Pandas, NumPy
* **Visualization**: Plotly
* **Forecasting**: Statsmodels (ARIMA)
* **APIs**: yfinance
* **Deployment**: Streamlit Cloud

---

## 🎯 Project Goals

The goal of Tradezy is to bridge the gap between **basic stock charting tools** and **institution-grade analytics platforms** by offering:

* Quantitative decision support
* Transparent modeling
* Accessible cloud-based deployment
* Modular, extensible design

---

