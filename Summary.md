# Feature Selection Summary

## Credit & Risk Sentiment Indicators

### Credit Spread (Baa - Aaa) 
Measures the yield difference between lower-grade investment bonds (Baa) and higher-grade (Aaa). A widening spread suggests investors are demanding higher compensation for taking on more credit risk — a sign of growing financial stress or risk aversion. A rising credit spread may precede spikes in volatility.
### Junk Bond Spread (High-Yield OAS)
Captures the yield premium investors demand on non-investment grade (high-yield) corporate bonds compared to Treasuries. It's a sensitive proxy for market fear — when investors expect defaults or economic slowdown, this spread increases. A sharp rise typically signals worsening credit conditions and a likely increase in VIX.
### Corporate Bond Spread (Baa - 10Y Treasury)
Tracks the difference between medium-grade corporate bond yields and the risk-free rate. Reflects the cost of capital for firms and systemic risk. If this spread widens, it indicates deteriorating confidence in corporate solvency and economic outlook — a red flag for future volatility.

## Commodities

### Crude Oil (WTI) 
Oil is both an input to economic production and a geopolitical asset. A sharp drop in oil prices may signal weakening demand or global growth concerns, both of which can contribute to rising uncertainty. Sudden spikes can also indicate geopolitical shocks. Either direction — if large and rapid — may lead to VIX increases.
### Gold 
Considered a safe-haven asset. Investors often flock to gold during financial crises or geopolitical uncertainty. A sharp rise in gold prices may indicate underlying fear in the markets, making it a useful early warning indicator for a rising VIX.

## Interest Rates & Yield Curve

### DGS2 (2-Year Treasury Yield) 
Short-term interest rates reflect expectations about Fed policy and near-term inflation. Falling 2Y yields may indicate flight to safety or rate cut expectations — both linked to rising volatility.
### DGS10 (10-Year Treasury Yield) 
Long-term yields reflect expectations of economic growth and inflation over the next decade. A falling 10Y yield, especially when paired with a flat or inverted yield curve, often precedes recessions or market fear. 
### T10Y3M Spread
The difference between the 10Y and 3M Treasury yields — a widely-used recession predictor. Negative values (inversions) have historically preceded economic downturns. An inverted curve often leads to rising volatility as markets price in economic uncertainty.
### SOFR 
The Secured Overnight Financing Rate is the successor to LIBOR. It reflects the cost of borrowing in the overnight repo market and is now the benchmark for many derivatives. Changes in SOFR are closely tied to liquidity stress and short-term funding pressure.
### EFFR (Effective Fed Funds Rate) 
The rate at which banks lend reserves overnight. It's a direct signal of Fed policy and short-term liquidity. Sharp movements can indicate shifts in monetary policy stance — often influencing risk sentiment and volatility expectations. 

## Equities & Global Markets

### S&P 500 Returns (Lagged) 
Used cautiously due to simultaneity with VIX. Lagged S&P returns provide directional clues — sharp declines often precede spikes in implied volatility. Including it as a lag ensures temporal causality and avoids using contemporaneous data.
### EEM (MSCI Emerging Markets ETF)
Tracks performance of emerging markets, which are more sensitive to global risk, interest rates, and commodity prices. A drop in EEM often signals broader risk-off sentiment, which may soon appear in U.S. volatility.
### Nikkei 225 (Japan)
A proxy for Asian market sentiment. Given time zone differences, it can provide clues about global market dynamics before U.S. markets open. Overnight risk aversion in Asia often bleeds into global volatility pricing.

## Macro & Currency

### CPI (Consumer Price Index) 
Measures inflation. While it’s monthly, it’s a key macro signal. Persistent inflation or sudden spikes raise uncertainty about Fed policy, which can increase VIX. CPI is forward-filled to align with daily frequency.
### EPU (Economic Policy Uncertainty Index) 
Derived from newspaper coverage of economic and political uncertainty. A rising EPU indicates market-wide anxiety over regulation, elections, trade wars, or fiscal/monetary policy — all known drivers of implied volatility.
### USD Index 
Measures the strength of the U.S. dollar against a basket of currencies. A rapidly rising dollar can signal global stress or capital flight into safety — conditions that often precede spikes in VIX. A weakening dollar, on the other hand, might indicate loosening financial conditions.