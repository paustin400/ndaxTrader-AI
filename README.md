# 📈 NdaxTrader-AI

**NdaxTrader-AI** is a fully automated cryptocurrency trading bot designed to eliminate **manual trading inefficiencies**. The bot leverages **technical indicators** and **machine learning models** to make real-time trading decisions. Users receive trade recommendations via text messages and can **confirm orders** before execution. The bot supports cryptocurrencies based on the **user’s selection**, provided they are available on the **NDAX platform**.

---

## 🚀 Features

- 🤖 **Automated Cryptocurrency Trading** – No manual intervention needed.
- 📊 **Technical Indicator Analysis** – Uses RSI, MACD, and other key indicators for precision trading.
- 📡 **Real-Time Market Data** – Fetches up-to-date market conditions to optimize decisions.
- 📩 **Text Message Trade Confirmations** – Users receive a brief analysis and confirm orders via SMS.
- 🔒 **Risk Management** – Includes stop-loss, position sizing, and order limits.
- ⚙️ **User-Customizable Strategies** – Users can adjust parameters to suit their preferences.
- ⌨️ **CLI-Based Interface** – Simple and efficient command-line interactions.

---

## 📂 Project Structure

```
📦 ndaxTrader-AI
 ┣ 📂 app
 ┃ ┣ 📜 main.py        # Entry point for trading logic
 ┃ ┣ 📜 models.py      # Database models for trade records
 ┃ ┣ 📜 routes.py      # API routes for trade execution
 ┃ ┣ 📜 utils.py       # Helper functions (indicators, risk management)
 ┣ 📂 static           # CLI-based logs or reports (if applicable)
 ┣ 📂 database
 ┃ ┗ 📜 schema.sql     # User-provided database schema (if warranted)
 ┣ 📜 README.md        # Project documentation
 ┣ 📜 requirements.txt # Required dependencies
 ┣ 📜 .gitignore       # Git ignored files
 ┗ 📜 LICENSE          # License information
```

---

## 🛠️ Technologies Used

| Category    | Technology |
|------------|------------|
| **Backend** | Python |
| **Trading API** | NDAX API |
| **Indicators & Analysis** | TA-Lib, NumPy, Pandas |
| **Machine Learning** | Scikit-learn (if needed) |
| **Messaging** | Twilio API for SMS confirmations |
| **Database** | User-provided database for trade logs (if warranted) |

---

## 🏗️ Installation & Setup

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/yourusername/ndaxTrader-AI.git
cd ndaxTrader-AI
```

### 2️⃣ **Set Up Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

### 3️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 4️⃣ **Configure NDAX API Credentials**
- Obtain API credentials from NDAX.
- Store them in a `.env` file or a secure method of your choice.

### 5️⃣ **Run the Bot**
```bash
python app/main.py
```

---

## 📌 Workflow & API Endpoints *(Planned)*

| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/market-data` | Fetches real-time market data |
| GET | `/trade-signals` | Analyzes market trends and indicators |
| POST | `/execute-trade` | Sends trade for confirmation via SMS |
| POST | `/confirm-trade` | Confirms trade and executes order |

---

## 🎯 Future Enhancements

✅ Expand AI-based trading models  
✅ Optimize risk management strategies  
✅ Add more NDAX-supported cryptocurrencies  
✅ Develop a web-based UI for improved visualization  

---

## 🤝 Contributing

Interested in contributing? Please follow these steps:

1. **Fork the repository**
2. **Create a new branch** (`git checkout -b feature-name`)
3. **Commit your changes** (`git commit -m "Add new feature"`)
4. **Push to GitHub** (`git push origin feature-name`)
5. **Submit a Pull Request**

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

