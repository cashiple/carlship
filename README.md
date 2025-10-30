# Wheel Strategy Trading Simulator<<<<<<< HEAD

﻿# Wheel Strategy Trading Simulator

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

[![Streamlit](https://img.shields.io/badge/streamlit-1.28+-red.svg)](https://streamlit.io/)[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)[![Streamlit](https://img.shields.io/badge/streamlit-1.28+-red.svg)](https://streamlit.io/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A web-based training simulator for practicing the wheel options trading strategy using historical market data.

A web-based training simulator for practicing the wheel options trading strategy using historical market data.

## 🎯 Overview

##  Overview

This simulator allows you to practice the wheel strategy on 11 blue-chip stocks using 3 years of historical data. Options premiums are calculated using the Black-Scholes model with historical volatility.

This simulator allows you to practice the wheel strategy on 11 blue-chip stocks using 3 years of historical data. Options premiums are calculated using the Black-Scholes model with historical volatility.

## 📈 Stocks Included

##  Stocks Included

- **AAPL** (Apple)

- **MSFT** (Microsoft)- **AAPL** (Apple)

- **JNJ** (Johnson & Johnson)- **MSFT** (Microsoft) 

- **KO** (Coca-Cola)- **JNJ** (Johnson & Johnson)

- **XOM** (Exxon Mobil)- **KO** (Coca-Cola)

- **V** (Visa)- **XOM** (Exxon Mobil)

- **BRK.B** (Berkshire Hathaway)- **V** (Visa)

- **GOOG** (Google)- **BRK.B** (Berkshire Hathaway)

- **AXP** (American Express)- **GOOG** (Google)

- **WMT** (Walmart)- **AXP** (American Express)

- **PG** (Procter & Gamble)- **WMT** (Walmart)

- **PG** (Procter & Gamble)

## 🚀 Quick Start

##  Quick Start

1. **Clone the repository**

   ```bash1. **Clone the repository**

   git clone https://github.com/cashiple/carlship.git   `ash

   cd carlship   git clone https://github.com/[username]/wheel-strategy-simulator.git

   git checkout WheelSimulator   cd wheel-strategy-simulator

   ```   `



2. **Install dependencies**2. **Install dependencies**

   ```bash   `ash

   pip install -r requirements.txt   pip install -r requirements.txt

   ```   `



3. **Run the simulator**3. **Run the simulator**

   ```bash   `ash

   python run.py   python run.py

   ```   `



4. **Open your browser** and go to: http://localhost:85014. **Open your browser** and go to: http://localhost:8501



## 🎮 How to Use##  How to Use



The web interface provides an intuitive dashboard with:The web interface provides an intuitive dashboard with:



- **📊 Market Overview** - Interactive charts showing current prices and volatility- ** Market Overview** - Interactive charts showing current prices and volatility

- **💰 Portfolio Status** - Visual tracking of your cash, positions, and P&L- ** Portfolio Status** - Visual tracking of your cash, positions, and P&L

- **📋 Option Chains** - Easy-to-read tables with strike prices and premiums- ** Option Chains** - Easy-to-read tables with strike prices and premiums

- **⚡ Trading Interface** - Point-and-click trading for puts and calls- ** Trading Interface** - Point-and-click trading for puts and calls

- **⏰ Time Controls** - Simple buttons to advance through trading days- ** Time Controls** - Simple buttons to advance through trading days

- **📈 Performance Charts** - Visual P&L tracking over time- ** Performance Charts** - Visual P&L tracking over time



## 🔄 The Wheel Strategy##  The Wheel Strategy



The wheel is an income-generating options strategy:The wheel is an income-generating options strategy:



1. **Sell cash-secured puts** on stocks you want to own1. **Sell cash-secured puts** on stocks you want to own

   - Collect premium   - Collect premium

   - If assigned, you buy the stock at your chosen strike price   - If assigned, you buy the stock at your chosen strike price



2. **Sell covered calls** on your stock positions2. **Sell covered calls** on your stock positions  

   - Collect more premium   - Collect more premium

   - If assigned, your stock is sold at the strike price   - If assigned, your stock is sold at the strike price



3. **Repeat** the cycle to continuously generate income3. **Repeat** the cycle to continuously generate income



## ✨ Features##  Features



- **🌐 Web-Based Interface**: Modern, intuitive Streamlit dashboard- ** Web-Based Interface**: Modern, intuitive Streamlit dashboard

- **📊 Interactive Charts**: Visual market data and performance tracking- ** Interactive Charts**: Visual market data and performance tracking

- **📚 Historical Data**: Real market data from the past 3 years- ** Historical Data**: Real market data from the past 3 years

- **🧮 Black-Scholes Pricing**: Realistic option premiums based on historical volatility- ** Black-Scholes Pricing**: Realistic option premiums based on historical volatility

- **📍 Position Tracking**: Monitor all your trades and positions- ** Position Tracking**: Monitor all your trades and positions

- **📈 P&L Analysis**: Track your performance over time with charts- ** P&L Analysis**: Track your performance over time with charts

- **🎯 Multiple Stocks**: Practice on 11 different blue-chip stocks- ** Multiple Stocks**: Practice on 11 different blue-chip stocks



## ⚙️ Configuration##  Configuration



Edit `src/wheel_simulator/config.py` to customize:Edit src/wheel_simulator/config.py to customize:

- Initial capital- Initial capital

- Risk-free rate- Risk-free rate

- Available expiration cycles- Available expiration cycles

- Display settings- Display settings



## 📁 Project Structure##  Project Structure



````

wheel-strategy-simulator/wheel-strategy-simulator/

├── src/ src/

│   └── wheel_simulator/    wheel_simulator/

│       ├── core/           # Core simulation logic        core/           # Core simulation logic

│       ├── models/         # Data models and calculations        models/         # Data models and calculations

│       ├── ui/             # Streamlit web interface        ui/             # Streamlit web interface

│       └── config.py       # Configuration settings        config.py       # Configuration settings

├── tests/                  # Unit tests tests/                  # Unit tests

├── docs/                   # Documentation docs/                   # Documentation

├── requirements.txt        # Python dependencies requirements.txt        # Python dependencies

└── README.md              # This file README.md              # This file

````



## 💡 Tips for Training##  Tips for Training



1. Start with one stock to learn the mechanics1. Start with one stock to learn the mechanics

2. Try different strike prices and expirations2. Try different strike prices and expirations

3. Observe how volatility affects premiums3. Observe how volatility affects premiums

4. Practice during different market conditions (bull, bear, sideways)4. Practice during different market conditions (bull, bear, sideways)

5. Compare your results against buy-and-hold5. Compare your results against buy-and-hold

6. Use the visual charts to understand market trends6. Use the visual charts to understand market trends



## 🤝 Contributing##  Contributing



Contributions are welcome! Please feel free to submit a Pull Request.Contributions are welcome! Please feel free to submit a Pull Request.



## 📄 License##  License



This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## ⚠️ Disclaimer##  Disclaimer



This is a training tool only. Past performance does not guarantee future results. Always do your own research before trading with real money.This is a training tool only. Past performance does not guarantee future results. Always do your own research before trading with real money.



## 🐛 Issues##  Issues



If you encounter any problems or have suggestions, please [open an issue](https://github.com/cashiple/carlship/issues).If you encounter any problems or have suggestions, please [open an issue](https://github.com/[username]/wheel-strategy-simulator/issues).

=======
### 👋 Hi, I'm Carl Shipley  

I'm a Principal Technical Program Manager driving Azure Fundamentals across a portfolio of cloud services. While my day job centers on strategy and program delivery, I work hands-on with:  

- **Kusto queries** for surfacing insights and improving operational health  
- **Dashboards & reporting** that reduce ambiguity and accelerate decision-making  
- **AI-assisted workflows** (GitHub Copilot, automation scripts) to improve service health and resilience  

My GitHub activity is mostly private due to the nature of my work, but I use this space to:  
- Experiment with AI and Copilot in VS Code  
- Build learning projects that strengthen my query and automation skills  
- Explore ways to combine data, visualization, and automation for business impact  

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/carlkshipley/) for my professional story.  
>>>>>>> 8d47b0761849f66a69cd67d7894a396aceab939e
