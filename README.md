# Crypto–Traditional Portfolio Optimization

This repository implements a hybrid framework combining the Markowitz mean‑variance optimizer with a GARCH–Vine‐copula model to allocate assets across three portfolios: traditional (stocks, gold, commodities), cryptocurrencies (e.g. Bitcoin, Ethereum), and a blended portfolio of both. A 30‑day rolling window is used to forecast returns and time‑varying volatility via an ARMA(1,1)–GARCH(1,1) model, then capture inter‑asset dependencies with R‑, C‑, and D‑vine copulas.

## Installation

Clone this repository and install the required Python packages via:
```bash
git clone https://github.com/yourusername/portfolio‑optimization.git
cd portfolio‑optimization
pip install -r requirements.txt
