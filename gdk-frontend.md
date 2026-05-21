# GDK Frontend — Case Study

## Overview

Frontend interface for the GDK staking and DeFi protocol. A Web3 dashboard enabling users to stake assets, track rewards, and participate in governance across the GDK ecosystem.

**Category:** Web3 / DeFi  
**Role:** Frontend Developer  
**Status:** Live  
**Repository:** [gdk](https://github.com/Ajemark/gdk) (private)

## Challenge

DeFi protocols need intuitive, secure frontends that abstract blockchain complexity while maintaining full transparency. Users need real-time staking data, reward calculations, and governance voting without compromising security.

## Solution

Built a comprehensive TypeScript/React frontend with:

- **Staking Dashboard**: Real-time staking positions, APY calculations, and lock period management
- **Rewards Tracking**: Visual reward accumulation with claim functionality
- **Governance Interface**: Proposal viewing and voting mechanisms
- **Wallet Integration**: Multi-wallet support for seamless Web3 interactions

## Architecture

```
React Frontend (TypeScript)
    ↓
Web3 Provider (Ethers/Wagmi)
    ↓
GDK Smart Contracts
    ↓
Blockchain (EVM)
```

## Technologies

- **TypeScript** — Type-safe frontend development
- **React** — UI framework
- **Wagmi / Ethers.js** — Web3 interactions
- **Tailwind CSS** — Styling

## Key Features

1. **Real-time Staking Data**: Live APY, TVL, and personal position tracking
2. **One-Click Staking**: Simplified staking flow with gas estimation
3. **Reward Visualization**: Charts and graphs for reward history
4. **Governance Voting**: Delegation and proposal voting UI

## Metrics

- **Language:** TypeScript
- **Type:** DeFi Dashboard
- **Ecosystem:** GDK Protocol

## Links

- **Related:** [GDK Contracts](https://github.com/Ajemark/case-studies/blob/main/gdk-contracts.md) — Smart contract layer

---

*Built by [Ajemark](https://github.com/Ajemark) · Part of the [GDK ecosystem](https://github.com/Ajemark/case-studies/blob/main/gdk-contracts.md)*
