# BetBetBet — MVP (Base Mainnet)

**BetBetBet** is a mobile-first Web3 sports betting dApp focused on a single **Game of the Day**.  
One game. Two picks. One transaction.

This repo contains the full MVP implementation designed for:
- Base mainnet
- USDC-only betting
- Minimal infrastructure
- Extremely simple daily operations

---

## 🧠 Core Concept

- Users connect a wallet, pick a side, see live odds, and place a bet.
- Only **one game** is shown at a time.
- Odds are always refreshed right before a bet is placed.
- Winnings are claimed directly inside the same screen with one tap.

No accounts. No dashboards. No clutter.

---

## 🏗️ Tech Stack

- **Next.js (App Router)**
- **TypeScript**
- **Tailwind CSS**
- **wagmi + viem + RainbowKit**
- **Overtime Markets (SportsAMMV2)**
- **Base Mainnet (chainId 8453)**

No database. No Firebase. No backend services.

---

## 🌐 Network & Currency

- **Network:** Base Mainnet  
- **Currency:** USDC only  
  - Address: `0x833589fCD6eDb6E08f4c7C32D4f71b54bdA02913`
  - Decimals: 6
- **SportsAMMV2 (Base):**  
  `0x76923cDDE21928ddbeC4B8BFDC8143BB6d0841a8`

---

## 📅 Game of the Day (Daily Ops)

### How to update the daily game (no code, no terminal)

1. Open:
