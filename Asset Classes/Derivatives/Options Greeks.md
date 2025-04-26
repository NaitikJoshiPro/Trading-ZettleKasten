Options Greeks are risk measures that tell you how an option’s price will change based on different factors.  
If you trade options without understanding Greeks, you’re basically gambling.

## The Main Greeks

- **Delta** → Measures sensitivity to **price movement**.  
  - Delta 0.5 = Option moves $0.50 if asset moves $1.
  - Calls have positive delta. Puts have negative delta.

- **Gamma** → Measures the **rate of change of Delta**.  
  - Higher Gamma = Delta changes faster.
  - Close to expiration, Gamma is bigger = more unstable.

- **Theta** → Measures **time decay**.  
  - Options lose value as time passes even if asset doesn’t move.
  - Short options (selling) make money from Theta.

- **Vega** → Measures sensitivity to **implied volatility (IV)**.  
  - Higher Vega = More sensitive to IV changes.
  - Big before earnings → dies after → IV Crush.

- **Rho** → Measures sensitivity to **interest rates**.  
  - Not a big deal for short-term trades.
  - Matters in longer-term options (LEAPS).

## Why Greeks Matter

- Greeks let you **quantify your risk**.
- You know how much time, volatility, or price move you’re exposed to.
- Every smart options strategy (hedging, spreads, straddles) is built around Greeks.

## Quick Visual

| Greek  | Meaning | Risk To Watch |
|:-------|:--------|:--------------|
| Delta  | Price Move | Direction |
| Gamma  | Delta Change | Volatility near expiry |
| Theta  | Time Decay | Holding time |
| Vega   | Volatility Change | News Events |
| Rho    | Interest Rate Changes | Longer term options |

## Real-World Tip

- High Theta decay? Close your options faster.
- High Gamma? Be ready for violent swings.
- High Vega before earnings? Be ready for IV Crush.
