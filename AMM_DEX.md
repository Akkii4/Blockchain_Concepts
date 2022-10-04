# Components of Decentralised Exchange's (aka DeX) Explained

### 1️⃣ What are Automated Market Makers ?
```
An Automated Market Maker (AMM) is a fully decentralized exchange that relies on liquidity pools and liquidity providers, and not on order book mechanism (buyers-sellers price matching). The tokens in the liquidity pools are priced by an algorithm that automates price changes depending on market demand while also reducing slippage.
```
### 2️⃣ What are liquidity pools?
```
AMM uses liquidity pools (LPs). LPs are two unique tokens locked into a smart contract to provide traders with liquidity. The tokens in the LP will need to be of equivalent total value - for eg., 50% ETH & 50% USDC in the ETH-USDC pool.
```
### 3️⃣ Who is a liquidity provider?
```
A liquidity provider is the one who supplies their tokens to a liquidity pool. In return, they will receive liquidity pool tokens that represent their share of the pool. Every time a trade happens that utilises in a liquidity pool, traders pay a small fee for access. That fee then gets distributed among liquidity providers according to their weightage share in the pool.
```
### 4️⃣ How do liquidity pools work?
```
The most common formula that Uniswap and other AMMs use a simple formula x*y=k (aka Constant Product), where x and y represent unique tokens, and k remains constant. When the balances of x and y changes, they will need to adjust to maintain k. Otherwise, this will create an arbitrage opportunity.
```
### 5️⃣ What is impermanent loss?
```
Providing liquidity to an AMM exposes LPs to “impermanent loss”. LPs lose money when they withdraw their assets relative to what they actual provided. Impermanent loss occurs due to the change in price of the assets in the pool. The more price deviates, the higher the loss.

But why "impermanent" ? It's because as the distribution of tokens within the LP can change it back to what they were, it becomes permanent only if being withdrawn at a moment when one token has significantly changed in value compared to when entered.
```
### Examples of AMMs :
```
1. Curve
2. Uniswap
3. Balancer
4. Kyber
```
