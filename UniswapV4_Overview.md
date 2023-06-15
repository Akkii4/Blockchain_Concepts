## 𝗨𝗻𝗶𝘀𝘄𝗮𝗽 𝗟𝗮𝗯𝘀 𝗿𝗲𝗰𝗲𝗻𝘁𝗹𝘆 𝗮𝗻𝗻𝗼𝘂𝗻𝗰𝗲𝗱 𝘁𝗵𝗲 𝗨𝗻𝗶𝘀𝘄𝗮𝗽 𝗩𝟰 🦄🦄🦄🦄

For those who don't know, Uniswap v4 is an non-custodial, non-upgradable permissionless automated market maker facilitating different token swaps on the Ethereum Virtual Machine (EVM) based chains.

#### 𝙏𝙤 𝙨𝙪𝙢𝙢𝙖𝙧𝙞𝙯𝙚,
Uniswap v1 and v2 focused on ERC20 ⇄ ETH and ERC20 ⇄ ERC20 transactions, respectively, using a constant product market maker protocol. 
While 2 years back with Uniswap v3 concentrated liquidity, capital efficiency, active liquidity and range orders were introduced.

#### 𝘽𝙪𝙩 𝙬𝙝𝙮 𝙩𝙝𝙚 𝙣𝙚𝙚𝙙 𝙤𝙛 𝙑4 ?
Uniswap v3 was lacking some latest AMM functionalities and also needed some gas efficiency improvements which wasn't possible without reimplementations of the core protocol 
for e.g. since Uniswap v2, any ETH swaps require it to be first wrapped into an ERC-20 token (WETH), which costs gas.

### 𝙎𝙤𝙢𝙚 𝙤𝙛 𝙩𝙝𝙚 𝙜𝙧𝙤𝙪𝙣𝙙 𝙗𝙧𝙚𝙖𝙠𝙞𝙣𝙜 𝙛𝙚𝙖𝙩𝙪𝙧𝙚𝙨 𝙞𝙩 𝙞𝙣𝙩𝙧𝙤𝙙𝙪𝙘𝙚𝙨 𝙬𝙞𝙩𝙝 𝙞𝙩, 𝙖𝙧𝙚 :
#### 1️⃣ Hooks 
```
The External contracts that allows the possiblity to deploy liquidity pools which supports endless customizable and flexible functionalities to these pools for e.g:
• A time-weighted average market maker (TWAMM)
• Dynamic managing fees based on volatility or other inputs
• Onchain limit orders
• Customized onchain oracles
• Auto compound LP fees back into the LP positions
• Internal MEV profits are distributed back to LPs
```

#### 2️⃣ Singleton
```
A design pattern where all pools are managed by a single contract , resulting in whooping 99% gas reduction.
```

#### 3️⃣ Flash accounting 
```
Instead of transferring tokens in and out of the pools, 
update an internal balance at each operation and only transferring the token's net balance upon completion of a swap which results in efficiency in multi-hop trades.
```

#### 4️⃣ Native ETH support 
```
All ETH swappers and Liquidity providers would benefit from cheaper transactions as no more requirement to wrap ETH.
```

#### 5️⃣ Some misc. improvements 
```
• Support for ERC-1155 token balance accounting.
• Governance controlled swap and withdrawal fees.
• Donate (tip) to in-range liquidity providers.
```
