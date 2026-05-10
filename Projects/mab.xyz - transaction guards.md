---
title: "mab.xyz - transaction guards"
project_url: "https://qf.giveth.io/project/mabxyz-transaction-guards"
owner: "Martin Monperrus"
owner_twitter: "martinmonperrus"
tags: ["smart-contract", "monitoring"]
categories: ["computer science", "research", "tech"]
donation_count: 16
total_usd_donated: 196.00
updates_count: 1
---

# mab.xyz - transaction guards

🔗 **Project:** [https://qf.giveth.io/project/mabxyz-transaction-guards](https://qf.giveth.io/project/mabxyz-transaction-guards)
👤 **Owner:** Martin Monperrus
🐦 **Twitter:** [@martinmonperrus](https://x.com/martinmonperrus)

## Donation Addresses
- `0xe0f27ddbed2a0165b683b8dacd293887badd4625`

## Tags
[[Tags/smart-contract|#smart-contract]]  [[Tags/monitoring|#monitoring]]


## Donations

> **16 donations** · **Total: $196.00 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x777777526f0acd7acabe2f40021008edc8293d7b]] | Ethereum | USDC | $102.10 | 2026-05-01 |
| [[Donors/0x4f89104a09355086513b282640df0b6c3dab8863]] | Ethereum | ETH | $23.41 | 2026-05-04 |
| [[Donors/0x2ee228ce8c3eb8ca11fcb829373bf162391b19b2]] | Ethereum | ETH | $11.56 | 2026-05-09 |
| [[Donors/0x3ec2f869066a8b4a30a5f10fc9c63be4dfbbd2b4]] | Ethereum | FINN | $11.52 | 2026-05-01 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $10.00 | 2026-05-07 |
| [[Donors/0x76c13c0bb17d233aab44b91342b3eb0989681079]] | Ethereum | USDC | $5.00 | 2026-05-07 |
| [[Donors/0xece039bd21e3910187af408909b6529c629ec8e5]] | Gnosis | XDAI | $5.00 | 2026-05-02 |
| [[Donors/0x4b9c01a9e7731300b66d60e62ca38fa5992af37c]] | Ethereum | USDC | $5.00 | 2026-05-06 |
| [[Donors/0x239029c61aa9b8bf33ebf15d50d8b2b3ccb3c087]] | Ethereum | USDC | $5.00 | 2026-05-05 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | FINN | $2.32 | 2026-05-07 |
| [[Donors/0xeeab375f1d46842df7934dd648b63858e3a442f3]] | Ethereum | ETH | $1.18 | 2026-05-04 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x239029c61aa9b8bf33ebf15d50d8b2b3ccb3c087]] | Ethereum | USDC | $1.00 | 2026-05-05 |
| Anonymous | Ethereum | FINN | $5.81 | 2026-04-29 |
| Anonymous | Ethereum | ETH | $5.00 | 2026-05-02 |
| Anonymous | Arbitrum | USDC | $1.00 | 2026-05-05 |

## Categories
**Tags:** computer science, research, tech
**Main:** Technology

## Description

This project is being developed by mab.xyz, a Web3 security company rooted in crypto security research from KTH Royal Institute of Technology. The intended users are Ethereum wallet teams, transaction simulation providers, smart contract wallet builders, and ultimately everyday blockchain users who rely on wallet previews to understand what a transaction will do before signing it.

  


What?

The project proposes Transaction Guard Contracts for Ethereum: a mechanism that turns simulated transaction outcomes into enforceable on-chain guarantees. Today, wallets can simulate a transaction and show the user expected effects such as token transfers or balance changes, but the blockchain only enforces the raw transaction input, not the displayed outcome. This project closes that gap by wrapping a transaction in a one-shot guard contract that checks whether the actual side effects match the simulated ones. If the outcome deviates beyond allowed tolerance, the entire transaction reverts.

  


Why?

The project addresses the simulation-execution gap, a major weakness in current Ethereum UX and security. A user may approve a swap, approval, lending action, or governance interaction based on a safe simulation, only for conditions to change before the transaction lands on-chain. That creates exposure to front-running, oracle manipulation, governance changes, upgradeable contract abuse, and other state-dependent attacks. Existing defenses such as slippage and deadlines only cover narrow cases. Transaction Guard Contracts aim to protect users by ensuring they receive what they approved, not merely what they were shown.

  


Where?

The solution is designed for the Ethereum ecosystem and broadly for DeFi, wallet infrastructure, account abstraction systems, and transaction simulation pipelines. It sits between wallet simulation and on-chain execution, making it relevant anywhere users interact with smart contracts under changing blockchain state. It also complements standards such as EIP-7730, which helps users understand what they are signing, by adding guarantees about what they will actually get.

  


How?

The flow has three steps: simulate the transaction, capture the important side effects, and encode them into a temporary guard contract that executes the original call and verifies the resulting balance or state changes atomically. The mechanism supports configurable tolerances, so it can allow small acceptable deviations such as AMM rounding or modest price movement while still blocking harmful divergences. Because verification happens on-chain, the model avoids extra off-chain trust during enforcement. In practice, this means a swap that was simulated to return around 2,000 USDC can be protected so that if manipulation reduces the result below an acceptable threshold, the transaction fails instead of silently succeeding with a bad outcome.

  


When?

This project is timely because Ethereum users increasingly depend on simulation-driven wallet UX, while MEV, adversarial reordering, proxy upgrades, and fast-changing protocol state make pre-signing previews less trustworthy on their own. As wallets become clearer about transaction intent, the next step is to guarantee execution integrity as well. Transaction Guard Contracts are positioned as that next layer: a practical security improvement for current Ethereum usage and a strong fit for the future of safer wallet infrastructure.
