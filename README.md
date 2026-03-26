# 📈 Multi-Agent Trading System

An AI-powered multi-agent trading system built using CrewAI that simulates collaboration between financial experts (Analyst & Trader) to analyze stocks and generate trading decisions using real-time data.

---

## 🚀 Features

- Multi-agent architecture using CrewAI  
- LLM-powered reasoning (Groq - LLaMA 3)  
- Real-time stock data using yfinance  
- Task-based workflow (Analysis → Decision)  
- Modular, scalable, and maintainable structure  

---

## 📁 Project Structure

multi-agent-trading-system/
│
├── agents/
│   ├── analyst_agent.py
│   └── trader_agent.py
│
├── tasks/
│   ├── analyse_task.py
│   └── trade_task.py
│
├── tools/
│   └── stock_research_tool.py
│
├── crew.py
├── main.py
├── requirements.txt
├── .env
└── .gitignore

---

## ⚙️ Installation

1. Clone the repository  
git clone https://github.com/HamzaAnsari8/multi-agent-trading-system.git  
cd multi-agent-trading-system  

2. Create virtual environment  
python -m venv venv  

3. Activate virtual environment  
Windows: venv\Scripts\activate  
Mac/Linux: source venv/bin/activate  

4. Install dependencies  
pip install -r requirements.txt  

---

## 🔑 Environment Variables

Create a `.env` file in the root directory and add:  

GROQ_API_KEY=your_api_key_here  

---

## ▶️ Usage

Run the application:  

python main.py  

Enter a stock symbol when prompted (e.g., AAPL, TSLA, MSFT).

---

## 🧠 How It Works

1. Analyst Agent  
- Fetches real-time stock data using yfinance  
- Performs trend and performance analysis  
- Generates structured insights  

2. Trader Agent  
- Consumes analyst insights  
- Makes BUY / SELL / HOLD decisions  
- Provides reasoning based on data  

3. Crew Execution  
- Agents collaborate sequentially  
- Tasks are executed in pipeline format  
- Final output is a trading recommendation  

---

## 🛠️ Tech Stack

Python  
CrewAI  
Groq (LLaMA 3)  
yfinance  
python-dotenv  

---

## 📌 Example Output

Stock: TSLA  

Analysis:  
- Current Price: $250  
- Daily Change: +2.5%  
- Trend: Bullish  

Recommendation:  
- Action: BUY  
- Reason: Strong upward momentum and positive indicators  

---

## 📊 Key Highlights

- Multi-agent AI system simulating real-world financial roles  
- Real-time data processing and analysis  
- Modular architecture for scalability  
- End-to-end automation of trading workflow  
- Demonstrates practical use of LLMs in finance  

---

## ⚠️ Disclaimer

This project is for educational purposes only and does not provide financial advice. Always do your own research before making investment decisions.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.
