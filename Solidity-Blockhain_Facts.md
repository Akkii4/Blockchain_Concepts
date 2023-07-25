### Random Solidity-Blockchain related quick facts

```
1. block.timestamp doesn't gives the time when the contract function is initiated but that of
when the transaction is mined with the block it is included in.

2. In Blockchain, Mining of new blocks can takes place even without any transaction be included in it,
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

7. Use of pragma version does not change the version of the compiler. It also does not enable or disable features of the compiler.
It just instructs the compiler to check whether its version matches the one required by the pragma.
If it does not match, the compiler issues an error.

8.You can force send ETH to a Smart Contract even if it have no payable function, fallback, receive function or
even if it can revert the receiving eth.
By creating another contract with a selfdestruct function, send ether to the target contract through it.

9. A function call from one contract to another does not create its own transaction,
it is a message call as part of the overall transaction.

10. After solidity v0.8, being a function external or public does not matter,
rather gas cost reduction is caused by use of input arguments as calldata instead of memory

11. Solidity compiler's by default optimize the contract assuming it is called 200 times across its lifetime (each opcode is executed around 200 times).
For the initial contract deployment to be cheaper and the later function executions to be more expensive, set optimize-runs=1.
Otherwise for many transactions and not caring for higher deployment cost and output size, set optimize-runs to a high number.
Changing optimiser's parameter effects :

  - the size of the binary search in the function dispatch routine

  - the way constants like large numbers or strings are stored

12. All data necessary for view/pure function call can be fetched from the provider itself (Infura or your locally running node) 
which does all calculations off-chain without need to broadcast a transaction to the network resulting in no gas consumption, 
as long as they are called externally and not from another contract or anonther state changing function.

13. Ethereum's Block Gas limit is of 30 million gas as of 2023.

14. There's no difference between an internal function and a private function remains once the contract is compiled.
```

_New points are added whenever something interesting strikes_
