# Avalanche-Subnets: ERC20 Token and Vault Smart Contract

## Overview

This repository contains two Solidity smart contracts: `ERC20.sol` and `vault.sol`. The `ERC20.sol` contract implements a standard ERC-20 token, providing key functionalities such as transfer, approval, minting, and burning. Meanwhile, the `vault.sol` contract acts as a secure storage solution for the ERC-20 token, allowing users to deposit and withdraw tokens while managing overall supply and individual balances.

## Getting Started with Remix

### Prerequisites

1. Access to Remix IDE in your web browser.
2. An Ethereum wallet (e.g., MetaMask) for interacting with the deployed contracts on the Ethereum blockchain.

### Steps

1. **Open Remix IDE**:
   - Go to the [Remix IDE](https://remix.ethereum.org).

2. **Import Contracts**:
   - Create two new files named `ERC20.sol` and `vault.sol`.
   - Copy and paste the contents of `ERC20.sol` and `vault.sol` into the respective files.

3. **Compile Contracts**:
   - Navigate to the "Solidity" tab.
   - Select the appropriate Solidity compiler version (e.g., ^0.8.17).
   - Click the "Compile" button to compile the contracts.

4. **Deploy the Token Contract**:
   - Switch to the "Deploy & Run Transactions" tab.
   - Select `ERC20.sol` from the contract dropdown.
   - Click the "Deploy" button to deploy the ERC-20 token contract.

5. **Copy Token Address**:
   - After deployment, copy the token contract address from the Remix console.

6. **Deploy the Vault Contract**:
   - Select `vault.sol` in the contract dropdown.
   - Paste the ERC-20 token contract address into the constructor parameter for Vault.
   - Click the "Deploy" button to deploy the vault contract.

### Interacting with Contracts

Once deployed, you can interact with the contracts using the provided functions. Make sure to connect your EVM Subnet to Remix for executing transactions.

## Authors

- monoliene

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
