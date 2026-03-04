# Crypto Trading Platform (C++)

C++ simulation of a cryptocurrency exchange with a limit order book, bid/ask matching, and wallet management.
Built as an OOP project to model exchange microstructure.

## Features
- Limit order book (bids/asks)
- Matching engine (trade execution)
- Wallet & balance checks
- CSV-driven market data replay
- Menu-based CLI interface

## Files
- `main.cpp` / `MerkelMain.*` — application entry + menu loop
- `OrderBook.*` — order book + matching logic
- `OrderBookEntry.*` — order model
- `Wallet.*` — balances and order validation
- `CSVReader.*` — CSV parsing
- `20200317.csv` — sample market data

## Build & Run
### macOS / Linux
```bash
g++ -std=c++17 *.cpp -o exchange
./exchange
