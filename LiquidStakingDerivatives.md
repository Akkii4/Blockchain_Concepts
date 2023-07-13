# Unlocking the Magic of LSD: An In-Depth Look at Liquid Staking Derivatives

Staking, we all might have heard about it when it comes to finance, NOT! but I bet you would have heard about Fixed Deposits, Term Deposits or time deposits or Bonds 📜 all are basically the same, the finance instruments offered by Banks 🏦 which gives investors the yields over their deposited money; similarly when it comes to the world of crypto, the terms changes to Staking, as crypto community likes spinning off with traditional finance terminologies 🤭🤫 so staking is one of the most popular ways to earn passive income 💸 over your crypto tokens by locking them up for a specific duration and is quite popular in the Decentralised Finance space for quite some time.

But from past 2-3 years a new term is brewing up in the crypto space and is grabbing quite serious attention 👀 all the way from Blockchain developers, miners, institutions, Crypto OG's and even retail investors. Any guesses 🤔

Hint: It's a way to stake your tokens and still enjoy the benefits of liquidity, flexibility, and composability?

Pat your back 👏 if you said Liquid Staking Derivatives.

Liquid staking derivatives (LSDs) are becoming increasingly popular among cryptocurrency investors, as they offer a way to earn rewards from staking without the need to become a validator in POS chains ⛓️. In this article, we will deep dive into every aspect of Liquid Staking.

## TL;DR, What are Liquid Staking Derivatives?

Liquid Staking Derivatives are the tokens that are issued in exchange ⇋ for staking Ethereum or other chain's native currency respectively. Protocols allow users to stake native currency of supported Proof of Stake(POS) based chains e.g. Ethereum without having to run a validator node 👨🔧 or lock up their 32 ETH for a longer period. The idea actually first introduced in a paper from a Cosmos team member in 2019, but then it was called "Delegation Vouchers". But since the Ethereum began its transition form Proof of Work to Proof of Stake Consensus and on December 2020, Beacon Chain went live, since then these protocols have gained massive popularity in the Ethereum community, with players emerging like Lido Finance, Rocket Pool, Frax Ether, Stader Labs etc.

## How does Liquid Staking work?

When a user stakes their assets much goes Behind the Scene, as:
```
1. Deposit ETH
2. User receives a special liquid tokens 🪙 representing underlying stake
3. Staking Protocol delegate this ETH to its own selected validator nodes
4. These node further deposit into ETH deposit contract
5. Validator node starts accruing yields over it
6. Liquid token too accrues value
7. User can redeem 🎟️ its underlying ETH against this liquid token along any yield generated on top of it.
```

### Breaking down the ETH staking rewards

You might wonder 🧐, how rewards yields for the staked Ether in the first place, actually there are many factors accumulating them:

- Consensus Rewards:
  - New ETH being minted(aka inflation) for each new block forged ⛏️
  - Validators attesting, participating in sync committees
  
- Transactions Rewards:
  - Accumulating transaction's priority gas fees
  - Extracting the Maximal extractable value (MEV) 💰

Note: Each POS chains is currently at different stages of the evolution and thus relatively newer chains ⛓ incentivizes stakers by giving them higher yield percentages ﹪. 
Also, users on-chain activity across a blockchain plays a major factor toward yield percentage as more the activity generates higher transactions fees.

## Liquid Tokens explained

When a user stakes Ethereum, they receive staking protocol's native ERC-20 token, similar to the LP tokens issued by a liquidity pools of DEX 🏦, known as "liquid tokens".

### There are 3 types of Liquid Reward Tokens models:

1. Rebasing Token:
```
A rebasing token is one which adjusts its supply periodically to reflect the changes in its value.

e.g. Lido’s stETH that represents staked ETH. As Lido staked ETH starts generating staking rewards,
      the supply of stETH increases proportionally 📈, so each stETH represents one ETH plus the accrued rewards 💸.

Advantage of a rebasing token is that it is easier to track the rewards,
while disadvantage being its complex architecture 🤨 and difficult to be supported on some DeFi protocols that relies on fixed supply.
```
2. Value-accruing Token:
```
These type of token increases 📈 in value over time without any change in their supply.

e.g. Swell’s swETH is a value-accruing token whose value increases relative to ETH,
so each swETH represents one ETH plus the accrued rewards.

This is the most widely used model while being compatible with all DeFi protocols.
But it abstracts out the intuitiveness of tracking rewards as need an oracle 🔮 to determine its exchange rate.
```
3. Two-token System:
```
As the name suggests it's a system that uses two tokens to represent staked assets and rewards separately.

e.g. Frax’s sfrxETH is a two-token system that consists of sfrxETH and sfrxCRV. sfrxETH is a token that is pegged to ETH and represents staked ETH
while sfrxCRV is a token that varies in price depending on the staking rewards and can be traded or used in DeFi.

Its advantage is that it offers more flexibility 💪 and options for users
while being disadvantage for some as it may be more complex and cumbersome to manage two tokens instead of one.
```

### Uses of liquid tokens:

1. Primary use case is to seamlessly redeem underlying asset without any slippage
2. Get the liquid token to work on DeFi protocols/strategies to earn extra yield 🤑 via farming, lending, staking, etc.
3. Benefiting from arbitrage opportunity caused by liquidity discount or slippage on different markets 🏦


## Why liquid staking?

How liquid staking is making noise 💥 in the space, overshadowing all other staking alternatives, via:

- **Security 🔒:** Increase the security and decentralization of the network by incentivizing more users to stake their tokens. This reduces the concentration of power among large validators or exchanges and makes the network more resilient to attacks or censorship 🤬.
- **Flexibility 💪:** Give users more options and control over their staked assets. Users can choose between different LSDs based on their risk-reward preferences, governance rights, and fee structures.
- **Permissionless** and transparent 🔍 nature
- **Bringing down the 32 ETH staking requirement** encourages capital efficiency and brings more user on board
- **Liquidity 💰:** Enable users to access the liquidity of their staked assets without having to wait for long lockup periods or withdrawal queues
- **Composability 🔗:** LSDs enhance the composability of DeFi by creating new use cases and value streams for staked assets. Users can leverage their LSDs to participate in various DeFi activities, such as lending, borrowing, trading, farming, or insurance. This creates a positive feedback loop that increases the demand and utility of both the underlying assets and the LSDs.

## Risks ⚠️

As they say, it's not all roses 🌹, liquid staking comes with its own trade-offs and some significant challenges involved with it like:

- **Smart contract 📜 & Counterparty risk:** LSDs rely on several smart contracts ranging from manage the liquid tokens, token deposit contracts or 3rd party DeFi protocols to enhance yields. These smart contracts may contain bugs 🐞 or vulnerabilities that could result in the loss of funds or malfunction of the protocol. Liquid Staking Protocols too possess a degree of risk that they may fail to deliver on their promises, act maliciously, or be compromised by external factors.
- **Validators Risks 👨🔧:** Validator at any time can increase their reward fees, or any Inactive 😴 or malicious validator nodes can get their stake getting slashed ✂︎
- **Token Depegging risks:** Slashing can cause lesser yields being generated, which could result in liquid token depegs from underlying assets and can cause cascading liquidations if being used on lending platforms.
- **Liquidity issue:** Withdrawing Stake time can vary from days to even weeks, which can cause Liquid tokens price manipulation or, in the case of weaker liquidity of the liquid token, can encounter serious slippage resulting in loss of user's months of their accumulated yield.
- **Regulatory risk 👨⚖️:** Regulatory uncertainty or scrutiny in some jurisdictions, especially if they are considered securities by law. Also, users should be aware that rewards from staking can attract taxes to them.

## Conclusion

Liquid staking derivatives are an innovative and exciting 🤩 development in the DeFi space, offering a new way to unlock the potential of staked assets without having to worry about validator technicalities. However, they also come with some risks ⛔️ and trade-offs that users should be aware of and mitigate accordingly. As the Ethereum ecosystem evolves, we can expect to see more innovation in the liquid staking space, and it will be interesting to see how these products develop in the coming years 📆.
