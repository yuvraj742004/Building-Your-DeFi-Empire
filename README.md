# Building-Your-DeFi-Empire

## Introduction

Welcome to the repository housing two Solidity smart contracts: `ERC20.sol` and `vault.sol`. These contracts serve as the backbone for managing ERC-20 tokens, providing functionalities for basic token operations and secure storage.

## Contracts Overview

- **ERC20.sol**: This contract lays the foundation for an ERC-20 compliant token. It includes essential functions like transfer, approve, mint, and burn.

- **vault.sol**: The vault contract acts as a secure storage solution for ERC-20 tokens. It facilitates depositing and withdrawing tokens while overseeing the overall token supply and individual balances.

## Getting Started with Remix

### Prerequisites:

1. **Remix IDE**: Install Remix IDE on your web browser.
2. **Ethereum Wallet**: Ensure compatibility with an Ethereum wallet (e.g., MetaMask) for interacting with contracts on the Ethereum blockchain.

### Steps:

1. **Open Remix IDE**:
   - Go to the Remix IDE in your web browser.

2. **Import Contracts**:
   - Copy the contents of `ERC20.sol` and `vault.sol`.
   - Create new files named `ERC20.sol` and `vault.sol` in Remix.
   - Paste the contents into the respective files.

3. **Compile Contracts**:
   - Access the "Solidity" tab in Remix.
   - Choose the appropriate Solidity compiler version (e.g., ^0.8.17).
   - Click "Compile" to compile the contracts.

4. **Deploy Token Contract**:
   - Switch to the "Deploy & Run Transactions" tab.
   - Select `ERC20.sol` in the contract dropdown.
   - Click "Deploy" to deploy the ERC-20 token contract.

5. **Copy Token Address**:
   - After deployment, copy the token contract address from the Remix console.

6. **Deploy Vault Contract**:
   - Choose `vault.sol` in the contract dropdown.
   - Paste the ERC-20 token contract address into the constructor parameter for Vault.
   - Click "Deploy" to deploy the vault contract.

### Interact with Contracts:

- Once deployed, interact with the contracts using the provided functions.
- Connect your EVM Subnet to Remix for transaction execution.

## Authors

- yuvraj742004

## License:

This project is licensed under the MIT License. Refer to the LICENSE file for details.
- - -
