# market-cortex-public

<!-- release-manager:download -->
[![Download Market Cortex 1.0.2](https://img.shields.io/badge/Download-v1.0.2-005FB8?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/jean-knapp/market-cortex-public/releases/download/v1.0.2/MarketCortex-win-Setup.exe)

[MarketCortex-win-Setup.exe](https://github.com/jean-knapp/market-cortex-public/releases/download/v1.0.2/MarketCortex-win-Setup.exe) · Windows installer, version 1.0.2
<!-- /release-manager:download -->

<!-- release-manager:about -->
Market Cortex is a Windows desktop application that manages a quantitative long-only equity strategy on B3, the Brazilian stock exchange. It turns a neural-network model's daily signals, filtered by momentum, insider-selling activity, and a market-rally detector, into concrete buy and sell orders for the next trading session. Beyond the strategy itself, it tracks the investor's actual holdings, cash, fixed income, and income tax obligations, so the model's suggestions and the real account can be followed side by side.

## Features
- Converts daily model signals into round-lot and fractional buy/sell orders for a fixed universe of B3 stocks
- Applies a 252-day relative-momentum gate, an insider-selling block, and an Ibovespa rally detector before suggesting a trade
- Imports holdings, trades, loans, and corporate events from the B3 broker statement, including automated login and sync
- Tracks fixed-income positions (Tesouro Direto, CDBs, LCIs/LCAs, private credit) and brokerage cash across multiple accounts
- Calculates monthly capital-gains tax on stock sales, including the DARF amount, exemption threshold, and loss carryforward
- Runs a historical paper-trading backtest of the strategy against CDI, Ibovespa, and IPCA
- Reports realized performance such as returns, dividends, and trades, kept separate from deposits and withdrawals
- Shows a 3D visualization of the portfolio and the underlying neural network through an embedded browser view
<!-- /release-manager:about -->

Releases of Market Cortex
