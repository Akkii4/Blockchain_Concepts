# Make your *Smart Contracts* even more smarter π via Automation : 
## Triggers certain functions in the contract automatically.



### Want to know secret trait of good programmer π€«

Good programmer are really lazy species π₯± , they can spend hours to create a code which automates even if the same can be done manually within minutes.


### Problem: Smart Contracts Cannot Auto-Execute ?

### But whyβ: 
Actually they are deterministic programs that run on blockchains but their code will not run and make state changes on a blockchain until triggered by an on-chain transaction.


Even Auto liquidation of under-collateralised loans π in lending protocols aren't actually automatic but triggered by liquidators(basically relies on user interactions to trigger them).


But this can also done via custom bots running, and maintaining to service these contracts require a substantial amount of time & usually leads to the development team becoming the central point of failure within their system.


Also who wants to maintain a server π


So basically we want our smart contract to be triggered based on time (e.g. trigger x function every day at π) or events based (e.g. trigger y function only when the assetβs price reaches below a certain threshold).

### Popular Solutions :

π₯ **Gelato** : Most easy to use but only major Drawback being Canβt edit task once created.

π₯ **OpenZeppelin Defender** : 

β’ Has Notification functionality π
β’ Supports multiple chains β
β’ Best in class private key management for security π

π₯ **Chainlink Automation** : They have "Keepers" that are externally owned accounts that are incentivised to trigger the execution of smart contracts based on predefined conditions .

π’ Advantages :
β’ low-cost off-chain computation
β’ easy to set up

π΄ Disadvantages :
β’ Need $LINK to fund Keepers
β’ Need to custom build contracts with Chainlink interfaces.
β’ Limited Blockchain Support
