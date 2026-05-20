# Zend Bot — Case Study

> **AI Automation Platform for Zend Money Fintech**
>
> 🔒 *Source code is private under client confidentiality.*

## Overview

**Zend Bot** is a multi-platform AI automation system built for **Zend Money**, a fintech company.

**Role:** Lead Bot Developer

## Architecture

```
Telegram Bot  ←→  Discord Bot  ←→  API Gateway  ←→  Dashboard (Web)
```

## Tech Stack

- **Telegram Bot:** Node.js, TypeScript, Grammy.js
- **Discord Bot:** Node.js, Discord.js
- **API Gateway:** Express.js, Redis
- **Dashboard:** Next.js, Tailwind CSS
- **Database:** PostgreSQL

## Key Features

- Automated KYC onboarding flow via chat
- Real-time balance checks and peer-to-peer transfers
- Transaction alerts (deposits, withdrawals, payments)
- Multi-language support (English, Yoruba, Pidgin)
- Admin dashboard with real-time metrics

## Metrics

- ~84 commits
- 24/7 uptime via Docker + PM2
- 3 languages supported
