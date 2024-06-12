# MyToken Smart Contract

This repository contains the implementation of a simple Ethereum-based token contract. The contract provides basic functionalities for minting and burning tokens.

## Contract Details

The smart contract, written in Solidity, has the following features:

- Public variables that store details about the coin: Token Name, Token Abbreviation, and Total Supply.
- A mapping that tracks balances of addresses.
- A `mint` function to create new tokens and assign them to an address.
- A `burn` function to destroy tokens from an address.

## Requirements

1. The contract contains public variables to store:
   - Token Name
   - Token Abbreviation
   - Total Supply

2. The contract has a mapping of addresses to balances.

3. The `mint` function:
   - Takes two parameters: an address and a value.
   - Increases the total supply by the given value.
   - Increases the balance of the specified address by the given value.

4. The `burn` function:
   - Takes two parameters: an address and a value.
   - Decreases the total supply by the given value.
   - Decreases the balance of the specified address by the given value.
   - Ensures the balance of the specified address is greater than or equal to the amount to be burned.

## Getting Started

### Prerequisites

To work with this contract, you need:

- [Solidity](https://docs.soliditylang.org/en/v0.8.18/installing-solidity.html) - The Solidity Compiler
- [Remix IDE](https://remix.ethereum.org/) or any other Solidity development environment

### Creator
- [Ravinder Singh](https://www.linkedin.com/in/ravinder-singh-7708761b7/)
