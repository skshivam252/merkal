# MERKAL - Minimal Order Book Matching Engine

MERKAL is a simple C++ order book matching engine that simulates basic trading operations. It reads market data from CSV files, processes bids and asks, matches orders, and tracks user balances through wallets.

---

## Features

- Limit order matching (bid/ask)
- CSV-based order data input
- Simulated wallet system
- Modular C++ design
- Easy to extend for educational use

---

## File Structure
main.cpp - Program entry point
MerkelMain.* - Core engine loop
OrderBook.* - Handles order matching
OrderBookEntry.* - Represents individual orders
Wallet.* - Simulates account balances
CSVReader.* - Parses CSV input
20200317.csv - Sample market data


---

## Build Instructions

**Requirements:** C++11 or later

### Compile:

```bash
g++ -std=c++11 main.cpp MerkelMain.cpp OrderBook.cpp \
    OrderBookEntry.cpp Wallet.cpp CSVReader.cpp -o merkal
```

### Run:
```bash
./merkal
```
