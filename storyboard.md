
## 🧠 Midas Touch

**Learning** to trade Gold Futures

#### King Midas

King Midas was a legendary king granted a wish that everything he touched would turn to gold.
At first delighted, he soon realized the gift was a curse when food, drink, and even his daughter turned to gold.
The myth serves as a warning about greed and the unintended consequences of valuing wealth over human life.




##  💹 Steps to trading Gold Futures

1. Collect Data and analyze
2. 

#### King Midas






# 🧩 Solution Template

#### A modular, AI first solution scaffold  

> Created by **ThriveAI  ...      Joe Eberle**  
> 🗓️ Started: April 18, 2025 
> 📫 Contact: [josepheberle@outlook.com](mailto:josepheberle@outlook.com)  
> 🔗 GitHub: [JoeEberle](https://github.com/JoeEberle/)






## 🟡 Top Data Points for Evaluating Gold Futures

1. **Spot Gold Price** — The **current cash market price** of gold, which anchors futures contracts and reflects immediate supply and demand.
2. **Futures Curve (Contango/Backwardation)** — Shows how **future delivery prices** compare to spot, indicating storage costs, interest rates, and market expectations.
3. **U.S. Dollar Index (DXY)** — Gold is priced in dollars, so a **stronger dollar** usually puts downward pressure on gold prices.
4. **Real Interest Rates** — **Rising real yields** make non-yielding assets like gold less attractive, while falling real rates support higher gold prices.
5. **Inflation Expectations** — Gold often rises when investors **expect inflation to erode** the purchasing power of fiat currencies.
6. **Central Bank Gold Purchases** — **Large-scale buying or selling by central banks** significantly affects global demand and long-term price trends.
7. **COMEX Open Interest** — Measures **how many gold futures contracts are active**, signaling speculative and hedging interest in the market.
8. **ETF Gold Holdings (e.g., GLD)** — Inflows and outflows from gold **ETFs** reflect institutional and retail **investor sentiment toward gold**.
9. **Geopolitical Risk Index** — Wars, sanctions, and **global instability** increase safe-haven demand for gold.
10. **Mining Supply and Production Costs** — Changes in **gold output and extraction costs** affect long-term supply and price floors.





## What are gold ETF's 

**Gold ETFs (Exchange-Traded Funds)** are investment funds that let you buy and sell exposure to the price of gold on the stock market without having to physically own or store gold.

They work by either holding physical **gold in vaults (like GLD or IAU)** or by holding gold futures contracts, and each share represents a fractional claim on that gold or its price movement.
Gold ETFs make it easy for investors to **trade gold like a stock**, use it for **inflation protection**, portfolio diversification, or as a **safe-haven** asset during economic uncertainty.





# 💰 Spot Gold Price 🪙

The **spot gold price** is the **current market price** for immediate delivery of gold, reflecting real-time supply and demand in global bullion markets. It is reported continuously by major commodity exchanges and data providers such as the London Bullion Market Association (LBMA), COMEX, and financial platforms like Bloomberg, Reuters, and major market websites.

import yfinance as yf

gold = yf.Ticker("XAUUSD=X")
price = gold.history(period="1d")["Close"].iloc[-1]

print(f"Spot Gold Price (USD/oz): {price}")




