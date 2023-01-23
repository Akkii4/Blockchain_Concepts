# 🚨Attention all Ethereum developers!🚨

## A comprehensive list of target EVM versions and the compiler-relevant changes introduced at each stage.

From Homestead to Paris, this list provides an in-depth look at the updates and changes made to the Ethereum Virtual Machine 
this list is a must-read for anyone looking to stay current with the latest developments in the Ethereum ecosystem. 
Stay ahead of the curve and check out the list now! 

### Ethereum EVM versions and relevant changes:

#### 1. Homestead (14 Mar 2016): ```Oldest version```


#### 2. Tangerine Whistle (18 Oct 2016): 
```
Gas cost for access to other accounts increased, all gas sent by default for external calls. 
All gas sent by default for external calls, previously a certain amount had to be retained.
```
#### 3. Spurious Dragon (22 Nov 2016): 
```
Gas cost for the 'exp' opcode increased relevant for gas estimation and the optimizer
```
#### 4. Byzantium (16 Oct 2017): 
```
Introduction of 'returndatacopy', 'returndatasize' and 'staticcall' opcodes in assembly, 
ability to access dynamic data returned from function call. 
The 'staticcall' opcode is used when calling non-library view or pure functions, 
which prevents the functions from modifying state at the EVM level, i.e., even applies when you use invalid type conversions. 
'revert' opcode introduced to avoid wastage of gas
```
#### 5. Constantinople/Petersburg (28 Feb 2019): 
```
Introduction of 'create2', 'extcodehash', 'shl', 'shr' and 'sar' opcodes in assembly, shifting operators use less gas
```
#### 6. Istanbul (08 Dec 2019): 
```
Introduction of 'chainid' and 'selfbalance' opcodes in assembly
```
#### 7. Berlin (14 Apr 2021): 
```
Increased gas costs for 'SLOAD', 'CALL', 'BALANCE', 'EXT' and 'SELFDESTRUCT', compiler assumes cold gas costs for such operations
```
#### 8. London (05 Aug 2021): 
```
Block's base fee (EIP-3198 and EIP-1559) can be accessed via block.basefee or basefee() in inline assembly.
```
#### 9. Paris (Sep-15-2022): 
```
No changes, however the semantics of the difficulty value have changed (see EIP-4399)
```
