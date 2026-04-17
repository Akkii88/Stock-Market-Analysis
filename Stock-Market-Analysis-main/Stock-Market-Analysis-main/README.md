# 📈 Stock Market Financial Analysis Dashboard

> An interactive data analytics project combining **Python (Pandas)** for data engineering and **Tableau** for visual storytelling — analyzing historical stock data of top tech giants: **Apple, Google, Nvidia, Tesla, Facebook, and Twitter**.

---

## 🚀 Live Demo

🔗 **[View the Interactive Tableau Dashboard](https://public.tableau.com/app/profile/rohan.verma4805/viz/Stock_Market_Dashboard/Dashboard1?publish=yes)**

---

## 📌 Project Overview

This project performs an in-depth **financial analysis of major tech company stocks** using historical market data sourced from Kaggle. The workflow involves:

1. **Data Engineering** with Python & Pandas to compute key technical indicators
2. **Exploratory Data Analysis (EDA)** in a Jupyter Notebook
3. **Interactive Dashboard** built with Tableau for visual insights

---

## 🏢 Companies Analyzed

| Company | Ticker |
|---------|--------|
| 🍎 Apple | AAPL |
| 🔍 Google | GOOGL |
| 🟢 Nvidia | NVDA |
| 🚗 Tesla | TSLA |
| 📘 Facebook (Meta) | META |
| 🐦 Twitter | TWTR |

---

## 🔧 Technical Indicators Engineered

Using **Pandas**, the following new columns were computed from the raw stock data:

| Feature | Description |
|---------|-------------|
| `MA50` | 50-Day Moving Average |
| `MA200` | 200-Day Moving Average |
| `Change in Price` | Daily price delta |
| `% Change in Price` | Daily price percentage change |
| `Change in Volume` | Daily volume delta |
| `% Change in Volume` | Daily volume percentage change |
| `Previous Day Close Price` | Lag-1 close price for comparison |

---

## 📂 Project Structure

```
Stock-Market-Analysis/
│
├── 📓 Stock_Market_Financial_Analysis.ipynb   # Data processing & EDA notebook
├── 📊 Stock_Market_Dashboard.twbx             # Tableau packaged workbook
├── 📊 Stock_Market_Dashboard.twb              # Tableau workbook
│
├── 📁 Data (CSV Files)
│   ├── Apple.csv
│   ├── Google.csv
│   ├── Nvidia.csv
│   ├── Tesla.csv
│   ├── Facebook.csv
│   └── Twitter.csv
│
└── README.md
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) | Data processing & feature engineering |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) | Data manipulation |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) | Exploratory data analysis |
| ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white) | Interactive visualization dashboard |

---

## ⚙️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/Sabina-Sheoran/Stock-Market-Analysis.git
cd Stock-Market-Analysis
```

### 2. Install Dependencies
```bash
pip install pandas jupyter
```

### 3. Run the Notebook
```bash
jupyter notebook Stock_Market_Financial_Analysis.ipynb
```

### 4. Open the Dashboard
- Open `Stock_Market_Dashboard.twbx` in **Tableau Desktop**, or
- Visit the **[live Tableau Public dashboard](https://public.tableau.com/app/profile/rohan.verma4805/viz/Stock_Market_Dashboard/Dashboard1?publish=yes)**

---

## 📊 Dashboard Features

The Tableau dashboard provides:

- 📉 **Closing Price Over Time** — Historical price trends for all 6 companies
- 📊 **50-Day & 200-Day Moving Averages** — Trend identification via MA crossovers
- 🔁 **Daily % Price Change** — Volatility comparison across companies
- 📦 **Volume Traded Over Time** — Market activity and liquidity insights
- 🔍 **Cross-Company Comparison** — Side-by-side analysis of all tech giants

---

## 📁 Data Source

- **Dataset**: [Stock Market Dataset – Kaggle](https://www.kaggle.com/datasets/jacksoncrow/stock-market-dataset)
- **Coverage**: Historical daily OHLCV data for major tech companies

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-analysis`)
3. Commit changes (`git commit -m 'Add new indicator'`)
4. Push and open a Pull Request

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Sabina Sheoran**
- GitHub: [@Sabina-Sheoran](https://github.com/Sabina-Sheoran)

---

⭐ **If you found this project useful, please give it a star!**
