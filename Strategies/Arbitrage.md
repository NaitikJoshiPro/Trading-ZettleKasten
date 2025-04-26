Arbitrage is **risk-free or near-risk-free trading** where traders exploit **price differences** between markets or instruments to make a profit.

It relies on **speed**, **capital**, and **market inefficiencies**.

---

# 1. **Types of Arbitrage**

- **Spatial Arbitrage**: Same asset priced differently across two exchanges.
  - Example: BTC is $30,000 on Exchange A, $30,050 on Exchange B → Buy A, Sell B.

- **Triangular Arbitrage**: Currency mispricing across forex pairs.
  - Example: USD → EUR → GBP → USD, ending up with more USD than you started.

- **Statistical Arbitrage**: Using algorithms to identify short-term mean reversion or correlations.
  - Example: Pairs trading — if two correlated stocks diverge, long one, short the other.

- **Risk Arbitrage (Merger Arbitrage)**: Profiting from merger/acquisition deals.
  - Example: Buy the stock of a company being acquired, short the acquirer.

- **Latency Arbitrage**: Exploiting slight time differences (millisecond level) between price updates. [[Latency Arbitrage]]

- **Regulatory Arbitrage**: Taking advantage of different regulatory treatments across markets.

---

# 2. **Requirements for Successful Arbitrage**

- **Low latency execution**.
- **Access to multiple liquidity venues**.
- **Reliable pricing feeds**.
- **Algorithmic execution speed**.
- **Capital to cover position sizing across venues**.

---

# 3. **Arbitrage Risks**

- **Execution Risk**: Prices move before trades fill.
- **Counterparty Risk**: One side of the trade fails.
- **Latency Risk**: You are slower than someone else.
- **Regulatory Risk**: Rules change making arb illegal or unprofitable.
- **Liquidity Risk**: Slippage can eat away arb profits.

---

# 4. **Examples**

| Type                  | Example |
|------------------------|---------|
| Crypto Arbitrage       | Buy BTC cheap on Kucoin, sell expensive on Binance. |
| Forex Triangular Arb    | Exploit mispricing in EUR/USD, USD/GBP, and EUR/GBP. |
| ETF Arbitrage          | Arbitraging discrepancies between ETF price and its NAV. |
| Futures-Cash Arbitrage | Price difference between a futures contract and its underlying asset. |

---

# 5. **Modern Arbitrage Challenges**

- Most pure arbitrage opportunities are **arbed away instantly** by HFTs.
- Arbitrage now is about **being faster** or **being smarter** (exotic instruments, complex spreads).

---

### Backlinks:
[[Latency Arbitrage]] [[Execution Algos]] [[Smart Order Routing]] [[Liquidity Providers]] [[Order Flow]]