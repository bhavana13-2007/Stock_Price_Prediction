# 📈 Stock Trend Prediction

## 🎯 Overview

**Stock Trend Prediction** is an AI-powered web application that leverages **Long Short-Term Memory (LSTM)** neural networks to analyze historical stock market data and forecast future price trends.

The application provides an interactive web interface where users can:
- 🔍 Enter stock ticker symbols (e.g., AAPL, MSFT, GOOGL)
- 📊 Visualize historical performance via candlestick charts
- 📈 View moving average trend analysis
- 🤖 Generate AI-powered future trend predictions

&gt; ⚠️ **Disclaimer**: This project is for **educational and research purposes only**. Stock market predictions are uncertain and should not be considered financial or investment advice.

---

## 🎬 Live Demo

| Platform | Status | URL |
|----------|--------|-----|
| Hugging Face Spaces | 🟢 Running | [Stock_Price_Prediction](https://huggingface.co/spaces/suryavamshibhavana/STOCKS-PRICES) |

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔍 **Ticker Search** | Search stocks using valid ticker symbols via Yahoo Finance |
| 📊 **Candlestick Charts** | Interactive OHLC visualization with Plotly.js |
| 📈 **Moving Averages** | Trend analysis with configurable MA periods |
| 🤖 **LSTM Predictions** | Deep learning-based future price forecasting |
| 🌐 **Web Interface** | Clean, responsive UI built with HTML5, CSS3, and JavaScript |
| ⚡ **Real-time Data** | Live stock data fetched from Yahoo Finance API |
| 🐳 **Docker Ready** | Containerized deployment support |

---
# Stock Market Prediction Dashboard

AI-powered Yahoo Finance dashboard with multi-language support (Hindi, Tamil), offline-first architecture using Ollama local inference, and BYOK cloud AI fallback. Built for Bharat.

## 🛠️ Technology Stack

### Frontend
| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure |
| CSS3 | Styling & responsive design |
| JavaScript | Client-side interactivity |
| Plotly.js | Interactive candlestick & line charts |

### Backend
| Technology | Purpose |
|------------|---------|
| Python 3.10+ | Core language |
| Flask 3.0 | Web framework & API |
| Gunicorn | Production WSGI server |

### Machine Learning
| Technology | Purpose |
|------------|---------|
| TensorFlow 2.16 | Deep learning framework |
| Keras 3.3 | High-level neural network API |
| LSTM | Time-series prediction model |
| NumPy 1.26 | Numerical computing |
| Pandas 2.2 | Data manipulation |
| Scikit-Learn 1.5 | Preprocessing & metrics |

### Data & Deployment
| Technology | Purpose |
|------------|---------|
| yfinance 0.2.65 | Yahoo Finance data API |
| Docker | Containerization |
| Hugging Face Spaces | Cloud deployment |

---

# Stock Market Prediction Dashboard

AI-powered Yahoo Finance dashboard with multi-language support (Hindi, Tamil), offline-first architecture using Ollama local inference, and BYOK cloud AI fallback. Built for Bharat.

# Stock Market Prediction Dashboard

AI-powered Yahoo Finance dashboard with multi-language support (Hindi, Tamil), offline-first architecture using Ollama local inference, and BYOK cloud AI fallback. Built for Bharat.

## Installation

```bash
# Clone the repository
git clone https://gitlab.com/manognya_r/stockmarket-prediction.git
cd stockmarket-prediction

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Pull Ollama models for offline AI
ollama pull llama3
ollama pull mistral

# Start the application
uvicorn src.main:app --reload
