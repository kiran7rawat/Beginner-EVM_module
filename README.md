# Token Creation

This is a simple token creation and desctruction using solidity language as well it stores information about the token
Token Creation This solidity program is used to create our own token with the help of basic functions and conditional statements studied in the solidity programming.

Description This program is a simple contract written in solidity. The contract has three public variables that store the details about the coin. Mapping is used to map an address with a value. This contract contains two functions mint and burn. Mint function is used to increase the totalSupply of our coin and in contrast burn function is used to destroy token.

Getting Started Executing program To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.


## Requirements                                                                                                                                            

1. The token creation contract has 3 public variables are as follows:                                                                                                
   -`tokenName`: It is a string data type reprents the token name.																										    
   -`tokenAbbrev`: It is also a string data type which represents the abbrevation of token																				      
   -`totalSupply`: it is unsignes integer which represents the total supply of token.

## Mapping
The contract has a mapping of addresses to balances:
   - `balances`: A mapping that associates addresses with their corresponding token balances.


### Executing program

`1)For Creation:`                                                                                   
Here for the token creation we create a function call mint which has two parameters as address and value of token. The function then increases the total supply by that number and increases the balance of the address by that amount.

`2)For Destruction:`                                                                             
Here for the token destruction we create a function called as burn which also has same parameter as afor creating the token.It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance.



## License

This project is licensed under the Solidity Assessment License - see the LICENSE.md file for details
