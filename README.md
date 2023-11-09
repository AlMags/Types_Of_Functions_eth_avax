# Project Title

Types of Functions - ETH + AVAX - Assessment Submission

## Description

We were tasked to create our own ERC20 token and have it be deployed using either Remix or HardHat.
Metamask test accounts from Hardhat were then used in order to interact with the ERC20 contract.
It must have the following features: mint tokens, burn tokens, and transfer tokens.

## Getting Started

The program was created using Solidity. The tools used were Remix and Hardhat in order to interact
with the contract. 

### Installing

* Import the files from the repository to your remix IDE
* Before running go to your VSCode and launch a GitBash terminal:
   - Run this command: npm i
   - If necessary, you may need to run: npm audit fix --force
* Now spin up your HardHat node: npx hardhat node
* Deploy the ERC20 contract
* You may have your test account addresses ready for ease of use


### Executing program

* How to run the program
```
With the ERC20 contract and your account addresses:
 - approve:
    - paste each address with an amount of tokens to be approved
 - burn:
    - input a value to be burned
 - mint
    - input an address and a value to be minted to
    - must be:
      - address approved in the contract
      - value msut be within the approved amount
 - transfer
    - input an address and a value to be transferred
    - must be:
      - address approved in the contract
      - value msut be within the approved amount
 - balanceOf: input an address to display its balance
 - decimals: outputs the number of decimals in the contract
 - name: displays the name of the token (MEVToken)
 - owner: displays the address of the owner of the contract
 - symbol: displays the symbol of the token (MEV)
 - totalSupply: displays the total supply for the contract

```

## Authors

Alkier Magallanes
magallanesalkier@gmail.com


