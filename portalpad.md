# PortalPad — Case Study

> **Multi-Chain Web3 Launchpad with Deterministic Bonding Curve Mechanics**
>
> 🔒 *Source code is private under client NDA.*
> 📹 *Live demonstrations available upon request.*

## Overview

**PortalPad** is a comprehensive multi-chain Web3 platform for launching tokens across **NEAR Protocol** and **EVM-compatible chains** using deterministic bonding curve mechanics.

**Role:** Lead Full-Stack Engineer & Smart Contract Architect

## Architecture

```
Frontend (Next.js)  ←→  Backend (Node.js/Docker)  ←→  NEAR Rust Contracts
     ↑                         ↑                           ↑
Indexer/Subgraph  ←→  NovaSpire Telegram Bot  ←→  Launchpad Contracts
```

## Tech Stack

- **Frontend:** Next.js, TypeScript, Tailwind CSS, Zustand
- **Backend:** Node.js, Express, PostgreSQL, Prisma ORM, Docker
- **Contracts:** Rust (NEAR SDK), AssemblyScript
- **Indexing:** Custom subgraph-like indexer

## Key Features

- Deterministic bonding curves with automated price discovery
- Multi-chain support (NEAR + EVM)
- Vesting schedules with cliff periods and linear unlocks
- Real-time analytics dashboard
- NovaSpire Telegram trading integration
- Multi-wallet support (NEAR, MetaMask, WalletConnect)

## Metrics

- ~298 commits across 7 integrated repositories
- 2 blockchain ecosystems supported
- Sub-second price updates via custom indexer
- Zero-downtime deployments via Docker
