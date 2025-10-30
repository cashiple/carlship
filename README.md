# Wheel Strategy Trading Simulator

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/streamlit-1.28+-red.svg)](https://streamlit.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A web-based training simulator for practicing the wheel options trading strategy using historical market data.

## Overview

This simulator allows you to practice the wheel strategy on 11 blue-chip stocks using 3 years of historical data. Options premiums are calculated using the Black-Scholes model with historical volatility.

## Stocks Included

- **AAPL** (Apple)
- **MSFT** (Microsoft)
- **JNJ** (Johnson & Johnson)
- **KO** (Coca-Cola)
- **XOM** (Exxon Mobil)
- **V** (Visa)
- **BRK.B** (Berkshire Hathaway)
- **GOOG** (Google)
- **AXP** (American Express)
- **WMT** (Walmart)
- **PG** (Procter & Gamble)

## Quick Start

1. **Clone the repository**
   `ash
   git clone https://github.com/cashiple/carlship.git
   cd carlship
   git checkout WheelSimulator
   `

2. **Install dependencies**
   `ash
   pip install -r requirements.txt
   `

3. **Run the simulator**
   `ash
   python run.py
   `

4. **Open your browser** and go to: http://localhost:8501

## How to Use

The web interface provides an intuitive dashboard with:

- **Market Overview** - Interactive charts showing current prices and volatility
- **Portfolio Status** - Visual tracking of your cash, positions, and P&L
- **Option Chains** - Easy-to-read tables with strike prices and premiums
- **Trading Interface** - Point-and-click trading for puts and calls
- **Time Controls** - Simple buttons to advance through trading days
- **Performance Charts** - Visual P&L tracking over time

## The Wheel Strategy

The wheel is an income-generating options strategy:

1. **Sell cash-secured puts** on stocks you want to own
   - Collect premium
   - If assigned, you buy the stock at your chosen strike price

2. **Sell covered calls** on your stock positions
   - Collect more premium
   - If assigned, your stock is sold at the strike price

3. **Repeat** the cycle to continuously generate income

## Features

- **Web-Based Interface**: Modern, intuitive Streamlit dashboard
- **Interactive Charts**: Visual market data and performance tracking
- **Historical Data**: Real market data from the past 3 years
- **Black-Scholes Pricing**: Realistic option premiums based on historical volatility
- **Position Tracking**: Monitor all your trades and positions
- **P&L Analysis**: Track your performance over time with charts
- **Multiple Stocks**: Practice on 11 different blue-chip stocks

## Configuration

Edit src/wheel_simulator/config.py to customize:
- Initial capital
- Risk-free rate
- Available expiration cycles
- Display settings

## Project Structure

`
wheel-strategy-simulator/
 src/
    wheel_simulator/
        core/           # Core simulation logic
        models/         # Data models and calculations
        ui/             # Streamlit web interface
        config.py       # Configuration settings
 tests/                  # Unit tests
 docs/                   # Documentation
 requirements.txt        # Python dependencies
 README.md              # This file
`

## Tips for Training

1. Start with one stock to learn the mechanics
2. Try different strike prices and expirations
3. Observe how volatility affects premiums
4. Practice during different market conditions (bull, bear, sideways)
5. Compare your results against buy-and-hold
6. Use the visual charts to understand market trends

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This is a training tool only. Past performance does not guarantee future results. Always do your own research before trading with real money.

## Issues

If you encounter any problems or have suggestions, please [open an issue](https://github.com/cashiple/carlship/issues).
