# Birb Minter — Case Study

## Overview

NFT minting platform for the Birb ecosystem. Custom minting mechanics, whitelist management, and launchpad features for Birb NFT collections.

**Category:** Web3 / NFT  
**Role:** Solo Developer  
**Status:** Live  
**Repository:** [birbminter](https://github.com/Ajemark/birbminter) (public)

## Challenge

NFT launches require robust minting infrastructure with fair distribution, gas optimization, and anti-bot protection. Creators need tools to manage whitelists, pricing, and launch phases.

## Solution

Built an NFT minting platform with:

- **Custom Minting**: Flexible minting mechanics (public, whitelist, gated)
- **Whitelist Management**: CSV upload, on-chain verification, snapshot tools
- **Launchpad**: Phased launches with time-based pricing
- **Anti-Bot Protection**: Rate limiting, wallet verification, and Sybil resistance

## Architecture

```
React Frontend
    ↓
Minter API
    ↓
Smart Contracts (Solidity)
    ↓
Blockchain
```

## Technologies

- **TypeScript** — Frontend and backend
- **Solidity** — Smart contracts
- **React** — UI
- **Hardhat** — Contract development

## Key Features

1. **Multi-Phase Minting**: Whitelist → Public → Open phases
2. **Dynamic Pricing**: Time-based or supply-based pricing curves
3. **Reveal Mechanics**: Delayed metadata reveal post-mint
4. **Royalty Enforcement**: EIP-2981 compatible royalty settings

## Metrics

- **Language:** TypeScript / Solidity
- **Type:** NFT Minter
- **Ecosystem:** Birb

## Links

- **GitHub:** [Ajemark/birbminter](https://github.com/Ajemark/birbminter)
- **Related:** [Birb Task](https://github.com/Ajemark/case-studies/blob/main/birb-task.md) — Engagement platform

---

*Built by [Ajemark](https://github.com/Ajemark) · Part of the Birb ecosystem*
