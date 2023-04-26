# EthProof_Solidity

# MyToken
MyToken is a Solidity smart contract that implements a simple token with the ability to mint and burn tokens.

# Features
Public variables that store the details about the token: Token Name, Token Abbrv., and Total Supply
- A mapping of addresses to balances (address => uint) to keep track of token balances
- A mint function that increases the total supply by a specified amount and increases the balance of the sender address by that amount
- A burn function that decreases the total supply by a specified amount and decreases the balance of the sender address by that amount
- Conditionals in the burn function to ensure that the balance of the sender is greater than or equal to the amount that is supposed to be burned

# Usage
To use this contract, you can deploy it on the Ethereum network using Remix or another Solidity development environment. Once the contract is deployed, you can interact with it using the following functions:

# mint
The mint function allows you to create new tokens and add them to the balance of a specific address. It takes two parameters: the address to add the tokens to, and the number of tokens to add.

# burn
The burn function allows you to destroy tokens and subtract them from the balance of a specific address. It takes two parameters: the address to subtract the tokens from, and the number of tokens to subtract. This function also includes conditionals to ensure that the balance of the sender is greater than or equal to the amount that is supposed to be burned.

# Public Variables
The following public variables are available to provide information about the token:

- TokenName (string): The name of the token.
- TokenAbbrv (string): The abbreviation of the token.
- TotalSupply (uint): The total supply of the token.
# Mapping
 The following mapping variable is used to keep track of the balances of each address:

- balances (mapping): A mapping of addresses to their respective balances.

# License
This code is released under the MIT License.
