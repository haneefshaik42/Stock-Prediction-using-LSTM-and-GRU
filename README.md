# 📈 Stock Price Forecasting using LSTM and GRU

## 🧠 Objective
This project aims to predict stock prices for major companies using deep learning models — **LSTM (Long Short-Term Memory)** and **GRU (Gated Recurrent Units)**. These models are well-suited for time-series forecasting due to their ability to capture sequential dependencies and trends.

## 📊 Data Collection
- **Source:** [Yahoo Finance](https://finance.yahoo.com/) via the `yfinance` Python library  
- **Tickers Analyzed:** `LMT`, `AAPL`, `GD`, `BA`  
- **Date Range:** January 1, 2010 – May 13, 2025  
- **Feature Used:** Closing Prices (`Close`)  
- Each stock's data is saved as an individual CSV file.

## 🧰 Technologies Used
- Python
- Jupyter Notebook
- `yfinance` for data retrieval
- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualization
- `tensorflow` / `keras` for deep learning models
- `scikit-learn` for preprocessing and metrics

## 📦 Installation
```bash
pip install yfinance
pip install statsmodels
pip install tensorflow
```

## 📁 Project Structure
```
.
├── data/                   # CSV files for each ticker
├── 602_True_Final_Version_5_1.ipynb  # Main notebook
└── README.md               # Project documentation
```

## 🔍 Key Highlights
- Preprocessing of historical stock prices.
- Comparison of LSTM vs GRU models on prediction accuracy.
- Visualization of model performance.
- Forecasting and plotting future stock price trends.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```
2. Install the required packages.
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook 602_True_Final_Version_5_1.ipynb
   ```

## 📌 Notes
- Make sure to have an active internet connection to fetch the latest data from Yahoo Finance.
- Modify ticker symbols or date ranges in the notebook to experiment with other stocks.

## 📬 Contact
For questions or suggestions, feel free to reach out via [GitHub Issues](https://github.com/yourusername/your-repo-name/issues).
