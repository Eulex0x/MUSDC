# MUSDC:  MUSDC
MUSDC is a yield-generating ERC-20 token designed to integrate with the Aave lending pool. It allows users to deposit USDC, earn yields, and manage their funds seamlessly.

## Features
- ERC-20 standard implementation
- Yield generation via Aave lending pool
- Rebase functionality for distributing profits
- Pausing and emergency withdrawal features for owner control
- Anti-reentrancy protection

## How it Works
1. Users deposit USDC tokens and receive MUSDC tokens.
2. MUSDC tokens accrue yield based on Aave's lending rates.
3. The owner can rebase to distribute profits to MUSDC holders.

## Deployment
- Prerequisites: Node.js, Hardhat, and a configured wallet
- To deploy:
  ```bash
  npx hardhat run scripts/deploy.js --network <network_name>
  ```
