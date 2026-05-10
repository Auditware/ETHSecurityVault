---
title: "Canon Guard"
project_url: "https://qf.giveth.io/project/canon-guard"
owner: "Wonderland"
owner_twitter: "wonderland"
twitter: "https://x.com/wonderland"
tags: ["multisig", "governance-security"]
categories: ["financial-services", "infrastructure", "public-goods", "tech"]
donation_count: 21
total_usd_donated: 446.29
updates_count: 1
---

# Canon Guard

🔗 **Project:** [https://qf.giveth.io/project/canon-guard](https://qf.giveth.io/project/canon-guard)
👤 **Owner:** Wonderland
🐦 **Twitter:** [@wonderland](https://x.com/wonderland)

## Social Media
- 🐦 [Twitter](https://x.com/wonderland)
- 🐙 [Github](https://github.com/defi-wonderland/canon-guard)
- 🌐 [Website](https://docs.canon.wonderland.xyz/)

## Donation Addresses
- `0x640a1f341bbd33e93c3b311e2bee92d6b4e07cee`

## Tags
[[Tags/multisig|#multisig]]  [[Tags/governance-security|#governance-security]]


## Donations

> **21 donations** · **Total: $446.29 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x41b9d1643bd66f04adb7cab38ca4f7c05420a86a]] | Ethereum | ETH | $100.00 | 2026-05-06 |
| [[Donors/0x064fced6ffb0d98be3ff5d6659fc2ff01e6329be]] | Ethereum | TIK | $25.00 | 2026-05-04 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $15.00 | 2026-05-08 |
| [[Donors/0xf1dd032dbb5c507b592a3f22b4a7cb2bebf54607]] | Polygon | USDT | $5.01 | 2026-05-07 |
| [[Donors/0x71ffd1ddf272114bc16e9bff7db179671c384ad7]] | Base | USDC | $5.00 | 2026-05-08 |
| [[Donors/0x9c2b07dd951edae10fbf58bb98a1448cde417f58]] | Ethereum | USDC | $5.00 | 2026-05-07 |
| [[Donors/0x9df582f558f2994e6c7bd1c8c39097a160bea072]] | Base | USDC | $5.00 | 2026-05-07 |
| [[Donors/0x58c8a648bfdde299d5730d7433c7f6de6e4f9ccc]] | Optimism | USDT | $4.00 | 2026-05-08 |
| [[Donors/0x064fced6ffb0d98be3ff5d6659fc2ff01e6329be]] | Ethereum | FINN | $2.32 | 2026-04-23 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $2.00 | 2026-05-07 |
| [[Donors/0x8fda1daa6a674c1726d1896e3054b9a82d123f12]] | Base | ETH | $1.16 | 2026-05-01 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x1409a9ef3450d5d50aad004f417436e772fbf8fc]] | Gnosis | XDAI | $1.00 | 2026-05-08 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.00 | 2026-05-03 |
| [[Donors/0xfd22df44ab8637c4b772c694226f8869c5147bda]] | Optimism | USDC | $1.00 | 2026-05-08 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| Anonymous | Ethereum | WETH | $102.38 | 2026-05-08 |
| Anonymous | Ethereum | USDC | $99.99 | 2026-05-10 |
| Anonymous | Ethereum | USDC | $49.99 | 2026-05-05 |
| Anonymous | Ethereum | FINN | $14.35 | 2026-05-06 |
| Anonymous | Ethereum | USDC | $5.00 | 2026-04-29 |

## Categories
**Tags:** financial-services, infrastructure, public-goods, tech
**Main:** Community, Economics & Infrastructure, Finance, Technology

## Description

>  _Multisig treasuries can't verify the off-chain data they depend on. Canon Guard moves it onchain so they can._

  


Safe's signing flow has a gap: transaction proposals live off-chain. Payloads can change between review and execution. Signers might approve different versions of the same transaction without realising it. External UIs and coordination layers become attack surfaces. Reviewer fatigue only makes the process worse.

# What Canon Guard does

Canon Guard is an open-source security layer for Safe that moves all transaction intent onchain, removing the off-chain blind spots that put multisig treasuries at risk.

At the core are _Actions_ : immutable onchain contracts that encode the exact call data and value of a Safe transaction. Once an _Action_ is queued, it cannot be altered. Anyone can simulate it, fork-test, and verify that what signers approved is what will execute. No more trusting off-chain blobs.

Every transaction faces a mandatory time delay before execution. Pre-approved, low-risk operations (e.g. routine token transfers) take a short path. Novel or higher-risk proposals face longer delays, giving reviewers time to scrutinise and cancel.

Owners approve Safe transaction hashes directly onchain against specific payloads, creating a shared source of truth, clear audit trails, and coercion resistance through timelocks.

If something goes wrong, a designated trigger can restrict execution to an emergency caller only. Owners can still propose and approve, so governance continues, but outflows pause until the situation is resolved.

# Design philosophy

Canon Guard assumes worst-case scenarios will happen. Three rules:

  1. Reusable vetting: routine operations are reviewed thoroughly once, then safely reused.
  2. Universal timelocks: every transaction faces a delay. No exceptions.
  3. Constrained delegation: _DELEGATECALL_ is blocked (except for multisend batching), and all coordination happens onchain.



# Why donate?

Canon Guard is a public good. It is fully open-source (MIT Licensed) and free to use. Donations support continued development, security audits, new chain deployments, and maintenance.

If your organisation uses a Safe, Canon Guard makes it harder for things to go wrong, and gives you real options when they do.
