**ERC20 and Vault Contracts**

This repository contains Solidity smart contracts for ERC20 tokens and a Vault.

### ERC20 Contract

The ERC20 contract provided in this repository implements the ERC20 token standard on the Ethereum blockchain. ERC20 is a standard interface for fungible tokens, which means tokens that can be exchanged on a one-to-one basis.

#### Features:

1. **Standard Compliance**: Implements all the mandatory functions specified by the ERC20 standard.
2. **Transfer Functionality**: Allows users to transfer tokens to other addresses.
3. **Approval Mechanism**: Enables users to approve other addresses to transfer tokens on their behalf.
4. **Total Supply Tracking**: Keeps track of the total supply of tokens.
5. **Balance Inquiry**: Provides functions to check the balance of tokens for a given address.

#### Usage:

1. Deploy the ERC20 contract on the Ethereum blockchain.
2. Interact with the contract using standard ERC20 functions to transfer tokens, approve addresses, and check balances.

### Vault Contract

The Vault contract provided in this repository offers a secure way to store ERC20 tokens. It adds an additional layer of security by requiring multiple signatures for token withdrawals.

#### Features:

1. **Multi-Signature Withdrawals**: Requires multiple authorized signatures to withdraw tokens from the vault.
2. **Role-Based Access Control**: Defines roles such as owner and signer for managing the vault.
3. **Token Deposit and Withdrawal**: Allows users to deposit ERC20 tokens into the vault and withdraw them securely.
4. **Event Logging**: Logs all token deposits and withdrawals for transparency.

#### Usage:

1. Deploy the Vault contract on the Ethereum blockchain.
2. Define authorized signers and owners for the vault.
3. Deposit ERC20 tokens into the vault using the provided function.
4. Withdraw tokens securely by obtaining multiple signatures from authorized 
