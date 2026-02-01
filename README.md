# Event-Driven Trading Engine

A research-grade trading simulation framework built to evaluate strategies under realistic market conditions, including transaction costs, slippage, and walk-forward validation.

---

## What This Is

This project is an event-driven trading research engine designed to separate **signal generation, execution modeling, and risk management**.

The goal is to move beyond toy backtests and instead model the constraints faced by real trading systems.

---

## Results (Planned)

> Quantitative results will be reported once strategies are implemented and evaluated.

- Strategy Sharpe ratio (out-of-sample): _TBD_
- Maximum drawdown: _TBD%_
- Transaction cost impact: _TBD bps_

---

## Demo

> Visualizations and reports will be added as experiments are completed.

- [ ] Backtest performance plots
- [ ] Trade lifecycle visualization
- [ ] Walk-forward evaluation report

---

## How to Run

> Execution instructions will be finalized after the core event loop is implemented.

```bash
# clone repository
git clone https://github.com/<username>/event-driven-trading-engine.git
cd event-driven-trading-engine

# install dependencies
pip install -r requirements.txt

# run sample backtest
python -m engine.run
