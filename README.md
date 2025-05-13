
# Algorithmic_Trading

An algorithmic trading project focused on collecting, analyzing, and visualizing stock market data using Python. This project implements quantitative trading strategies such as Momentum and Mean Reversion for paper trading, backtesting, and analysis.

## Project Overview

This project aims to:
- Collect historical stock data using the `yfinance` API
- Perform preprocessing and exploratory analysis
- Visualize price movements and indicators
- Implement trading strategies (Momentum & Mean Reversion)
- Generate buy/sell signals
- Prepare for paper trading and backtesting

## Project Structure

```
Algorithmic_Trading/
├── DataCollection.ipynb   # Notebook for data collection, preprocessing, and visualization
├── strategies/            # (Planned) Python scripts for implementing trading strategies
├── data/                  # (Planned) Stored historical data (CSV or Pickle format)
└── README.md              # Project documentation
```

## Data

- **Source**: Yahoo Finance via `yfinance`
- **Tickers**: `AAPL`, `MSFT`, `AMZN`, `GOOG`
- **Time Period**: Past 2 years (automatically calculated)
- **Frequency**: Daily price data

## Strategies

Planned strategies to be implemented:

1. **Momentum Strategy**
   - Focuses on identifying trends and following them
   - Buy when returns exceed a threshold over a recent window

2. **Mean Reversion Strategy**
   - Assumes prices revert to their historical average
   - Buy when prices are below the moving average (and vice versa)

These strategies will output **buy/sell signals** and support **backtesting** for evaluation.

## Dependencies

The project uses the following Python libraries:

```python
yfinance
pandas
numpy
matplotlib
datetime
os
logging
warnings
```

You can install the necessary dependencies using:

```bash
pip install yfinance pandas numpy matplotlib
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Algorithmic_Trading.git
   cd Algorithmic_Trading
   ```

2. Open `DataCollection.ipynb` in Jupyter Notebook or your IDE.

3. Run the cells to download and visualize historical stock data.

4. (Work in progress) Explore the `strategies/` folder as strategy implementations are added.

## Sample Output

*Visualizations include:*
- Line plots of closing prices
- Moving averages (planned)
- Strategy entry/exit signals (planned)

## Future Work

- Complete implementation of trading strategies
- Backtesting framework
- Paper trading simulation
- Parameter optimization
- Integration with broker APIs for live trading (optional)

## License

This project is licensed under the **GNU General Public License v3.0**.  
See the [LICENSE](https://www.gnu.org/licenses/gpl-3.0.en.html) file for more details.

---

*This project is under active development. Contributions, feedback, and suggestions are welcome!*
