# Make your *Smart Contracts* even more smarter 😎 via Automation : 
## Triggers certain functions in the contract automatically.



### Want to know secret trait of good programmer 🤫

Good programmer are really lazy species 🥱 , they can spend hours to create a code which automates even if the same can be done manually within minutes.


### Problem: Smart Contracts Cannot Auto-Execute ?

### But why❓: 
Actually they are deterministic programs that run on blockchains but their code will not run and make state changes on a blockchain until triggered by an on-chain transaction.


Even Auto liquidation of under-collateralised loans 📉 in lending protocols aren't actually automatic but triggered by liquidators(basically relies on user interactions to trigger them).


But this can also done via custom bots running, and maintaining to service these contracts require a substantial amount of time & usually leads to the development team becoming the central point of failure within their system.


Also who wants to maintain a server 😅


So basically we want our smart contract to be triggered based on time (e.g. trigger x function every day at 🕙) or events based (e.g. trigger y function only when the asset’s price reaches below a certain threshold).

### Popular Solutions :

🥇 **Gelato** : Most easy to use but only major Drawback being Can’t edit task once created.

🥈 **OpenZeppelin Defender** : 

• Has Notification functionality 🔔
• Supports multiple chains ⛓
• Best in class private key management for security 🔒

🥉 **Chainlink Automation** : They have "Keepers" that are externally owned accounts that are incentivised to trigger the execution of smart contracts based on predefined conditions .

🟢 Advantages :
• low-cost off-chain computation
• easy to set up

🔴 Disadvantages :
• Need $LINK to fund Keepers
• Need to custom build contracts with Chainlink interfaces.
• Limited Blockchain Support
