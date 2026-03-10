# ◈ DeFi Yield Farming Protocol

Full yield farming protocol — multi-pool staking, MasterChef reward distribution, governance token emissions, and a DApp frontend.

[![Solidity](https://img.shields.io/badge/Solidity-^0.8.20-363636?style=flat-square&logo=solidity)](.)
[![Hardhat](https://img.shields.io/badge/Hardhat-2.x-F7DF1E?style=flat-square)](.)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react)](.)

---

## Features

**Protocol**
- Multi-pool yield farming — stake LP tokens, earn rewards
- MasterChef-style reward distributor
- Per-block emission schedule with halving
- Emergency withdraw — no lock penalty
- Timelock on admin functions for trust

**Frontend DApp**
- Pool overview with live APY
- Deposit / withdraw / harvest UI
- Portfolio dashboard — all positions in one view

## Architecture

```
YieldProtocol
├── MasterChef.sol       — Reward distribution
├── RewardToken.sol      — Governance + reward token
├── Timelock.sol         — Admin delay
└── Frontend (React + Wagmi)
```

---

**Need a DeFi protocol built?**
→ [t.me/oxbobdev](https://t.me/oxbobdev) · [0xbob.vercel.app](https://0xbob.vercel.app)
