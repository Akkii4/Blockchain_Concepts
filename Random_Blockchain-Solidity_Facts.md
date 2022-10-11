### Random Blockchain related quick facts

```
1. block.timestamp doesn't gives the time when the contract function is initaited but that of 
when the transaction is mined with the block it is included in. 

2. In Blockchain, Mining of new blocks can takes place even without any transaction be included in it , 
as mining of block will eventually lead to new Coin genereation as miners reward.

3. Deploying a smart contract, is merely an Ethereum transaction 
containing the compiled code of the smart contract without specifying any recipient.

4.Time Complexity in Solidity data types :
  - Mappings: Constant time search (Same amount of time despite number of elements)
  - Array: Linear time search (takes time depending on number of elements)
  
5. EWASM (Ethereum Web Assembly Machine) : Is a proposed replacement for EVM as it aims for 
faster computation (converts solidity code to bytecode faster) and also more High Level Support.

6. Sending Ether or messages to addresses that doesn't exists : Ethereum cannot and does not validate 
recipient addresses in a transaction. 
Any 20-byte value is corresponds to an address w/wo private key,contract is considered valid.
```
*Will write more whenever something interesting strikes*

