**💼 Financial Analyst Multi-Agentic Playground**
A modular and extensible environment designed to simulate and deploy collaborative AI agents focused on financial analysis and real-time decision-making using LLMs, APIs, and search tools.

**🧠 Overview**
This playground simulates multiple collaborative AI agents that:

1. 📈 Analyze real-time stock market data
2. 🌐 Conduct web-based financial research
3. 💼 Offer personalized portfolio insights
4. ⚡ Automate decision-making workflows

Agents leverage Groq, yFinance, DuckDuckGo, and other tools to perform tasks intelligently and independently.

**🔍 Agents**
**Financial Agent**- Uses LLMs and financial APIs to perform stock analysis, portfolio insights, and trend forecasting.

**Web Search Agent**- Augments analysis with real-time data, news, and external financial information using search APIs.

**⚙️** **Features**
1. Multi-agent collaboration
2. Stock market research
3. Portfolio advisory logic
4. Integration with real-time APIs
5. LLM-powered reasoning
6. Modular code for easy extension

**🧩 Tech Stack**
1. Python
2. Phi framework (for agents)
3. Groq / LLaMA3 (LLM backend)
4. YFinance API
5. DuckDuckGo Search API

**📌 Goals**
1. To explore how multi-agent systems can assist in:
   
     a). Financial decision-making
   
     b). Market insights
   
     c). AI-driven investment advisory

**⚙️ Setup Instructions**

**1. Clone the Repository**
git clone https://github.com/your-username/financial-analyst-multi-agentic-playground.git
cd financial-analyst-multi-agentic-playground

**2. Install Dependencies**
pip install -r requirements.txt

**3. Configure Environment Variables**
Create a .env file in the root directory with the following:

a)- GROQ_API_KEY=your_groq_key

b)- PHI_API=your phidata api key

(Optional: Include other API keys like OPENAI_API_KEY if needed by dependencies.)

**4. Run the Application**
python main.py

**🚀 Use Cases**

📊 Portfolio management simulations

📰 Real-time financial reporting

🤖 Research automation for traders and analysts

🧠 Building agentic financial advisory systems

📌 **Notes**
1. Ensure API keys are valid and within rate limits.
2. Built using the open-source Phi Agent Framework.
3. Easily extend or swap agents and tools for new workflows or verticals.

