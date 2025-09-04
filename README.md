📈 Stock Analyst Agent (Real Data + AutoGen)

This is a Stock Analysis App built using Streamlit, yFinance, TA (technical indicators), and OpenAI AutoGen.
It fetches real stock data, calculates technical & fundamental indicators, and uses an AI agent to recommend BUY / HOLD / SELL.


---

🚀 Features

📊 Real-time stock data via yFinance

🔎 Technical Indicators:

Moving Averages (20, 50, 200)

RSI (Relative Strength Index)

MACD (Moving Average Convergence Divergence)

Volume trends


💰 Fundamental Ratios:

PE Ratio

PB Ratio

Dividend Yield

Market Cap


🤖 AI-powered analysis with OpenAI AutoGen

🎨 Interactive dashboard with Streamlit

JSON-based recommendation 

---


🔑 API Key Setup

1. Get your API key from OpenAI API Keys


2. Create a file named .env in the project root directory


3. Add your API key inside:

OPENAI_API_KEY=sk-your_api_key_here




---

▶ Run the App

Start the Streamlit app with:

streamlit run stock.py

Then open your browser at:
👉 http://localhost:8501


---

📦 Requirements

Main libraries used:

numpy

pandas

yfinance

streamlit

python-dotenv

ta

pyautogen[openai]

tiktoken



---

⚠ Disclaimer

This project is for educational purposes only.
It does not provide financial advice. Use responsibly.
