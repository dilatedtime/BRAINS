# BRAINS

BRAINS stands for Bayesian Ranking and Analysis of Investment Strategies. This repository is the shared submission hub for a Stamatics IIT Kanpur summer project on probability, market data, trading rules, and backtesting.

The folders are organised by student and week. Most submissions are Jupyter notebooks with code, charts, and written explanations.

## Work covered so far

### Week 1: Python and market foundations

- Downloading and exploring stock data with `yfinance`
- Candlestick and price charts
- Simple returns, log returns, and volatility
- Basic probability and expected-value exercises
- First trading-strategy implementations

### Week 2: Signals, risk, and backtesting

- Position sizing and capital use
- Static and trailing stop-loss rules
- Probabilistic checks for candlestick patterns
- Heikin-Ashi candles, Supertrend, Money Flow Index, and ATR
- Entry and exit rules, backtests, and common failure cases

## Finding a submission

Folder names usually contain the week, roll number, or student name. For example:

- `Week1_230219/Assignment1_Brains_AryanRaj(230219).ipynb`
- `Week2_BRAINS_230219_AryanRaj/Assignment2_Brains_AryanRaj(230219).ipynb`
- `Week_2_220920_rudraksh/Rudraksh_Assignment2.ipynb`

The repository contains many independent notebooks rather than one program. Open the notebook you want in Jupyter or Google Colab and install the libraries imported by that submission. Common dependencies include `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `mplfinance`, `scipy`, and `yfinance`.

```bash
git clone https://github.com/dilatedtime/BRAINS.git
cd BRAINS
python -m pip install jupyter pandas numpy matplotlib seaborn plotly mplfinance scipy yfinance
jupyter notebook
```

Some notebooks download current market data, so results may differ from the saved output. Treat every strategy as coursework and test it carefully before drawing conclusions about real trading performance.

Project resources: [BRAINS mentee notes](https://www.notion.so/BRAINS_MENTEES-1fb06a7d803b80aeab86e88d03a36e58)

This repository is a fork of [optimusprimeg/BRAINS](https://github.com/optimusprimeg/BRAINS).
