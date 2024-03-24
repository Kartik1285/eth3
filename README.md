# ERC-20 Token Contract - KARTIKCOIN

This repository contains a simple implementation of an ERC-20 token contract named MEMECOIN. ERC-20 is a widely-used Ethereum token standard that defines a set of functions and events that allow for the creation of fungible tokens on the Ethereum blockchain.

## Overview

- **Token Name**: KARTIKCOIN
- **Symbol**: KRTK
- **Decimals**: 18
- **Total Supply**: 0 (initially, can be minted by the owner)
- **Owner**: The contract deployer

## Functions and Events

- `mint(address account, uint256 amount)`: Allows the owner to mint new tokens and assign them to an account.
- `burn(uint256 amount)`: Allows an account to burn their tokens (reduce their balance) while decreasing the total supply.
- `approve(address spender, uint256 amount)`: Allows token owners to approve allowances for spenders.
- `transfer(address to, uint256 amount)`: Allows token owners to transfer tokens to another address.
- `transferFrom(address from, address to, uint256 amount)`: Allows a spender to transfer tokens on behalf of a token owner, provided they have the necessary allowance.
- `allowance(address tokenOwner, address spender)`: Returns the current allowance set for a spender by a token owner.
- `balanceOf(address tokenOwner)`: Returns the balance of tokens for a specific token owner.

### Events

- `Transfer(address indexed from, address indexed to, uint256 value)`: Logs information when token transfers occur.
- `Approval(address indexed owner, address indexed spender, uint256 value)`: Logs information when allowances are approved.

## License

This contract is provided under the MIT License (SPDX-License-Identifier: MIT), which allows for the use, modification, and distribution of the code with certain restrictions. Users of this contract should review and comply with the terms of the MIT License.

