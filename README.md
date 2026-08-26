# Algorithmic Trading with Python

Notes, code, and projects from a specialized program on algorithmic trading, covering
quantitative finance fundamentals, statistical & machine learning modeling, and
strategy backtesting — all implemented in Python.

The program combines financial theory, Python programming, and methodologies used by
quantitative funds to build reproducible, decision-oriented models. 64 academic hours,
live format, structured in 3 modules of 8 sessions each.

## Structure

The program follows three complementary stages:

| Stage | Module | Focus |
|-------|--------|-------|
| Fundamentals | [`01-quant-finance-fundamentals`](modules/01-quant-finance-fundamentals) | Markets, asset classes, financial data with Python, return/risk metrics, applied regression & time series |
| Development | [`02-quant-modeling-ml`](modules/02-quant-modeling-ml) | Market microstructure, stochastic processes & volatility (GBM, OU, GARCH), supervised ML, feature engineering & validation |
| Application | [`03-algo-trading-backtesting`](modules/03-algo-trading-backtesting) | Backtesting engine design, mean reversion strategies, out-of-sample evaluation, capstone project |

Each module folder has its own README with a per-class progress checklist. Each
`class-XX/` folder holds the instructor's slides (`resources/`), my notes (`notes.md`),
and any code for that session.

```
modules/
├── 01-quant-finance-fundamentals/
│   └── class-01 … class-08/
│       ├── resources/     # instructor's slides for that session
│       ├── notes.md       # my notes
│       └── *.ipynb / *.py # code for that session
├── 02-quant-modeling-ml/
└── 03-algo-trading-backtesting/
```

Reusable code (data helpers, risk metrics, backtesting engine) lives in [`src/`](src),
shared across classes instead of being duplicated notebook to notebook. Finished,
polished work — like the Module 3 capstone strategy — graduates into [`projects/`](projects).

## Progress

- [x] Module 1 — Quantitative Finance Fundamentals & Python (in progress: class 2/8)
- [ ] Module 2 — Quantitative Modeling & Machine Learning
- [ ] Module 3 — Algorithmic Trading & Backtesting

## Tech stack

Python · Jupyter Notebook · pandas · NumPy · SciPy · Statsmodels · scikit-learn ·
yfinance · vectorbt · Backtrader · Matplotlib · Plotly

## Setup

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## About

This repository serves two purposes: a running log of coursework for a specialized
algorithmic trading program, and a portfolio piece demonstrating applied quantitative
finance and machine learning skills in Python.
