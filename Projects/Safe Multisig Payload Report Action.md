---
title: "Safe Multisig Payload Report Action"
project_url: "https://qf.giveth.io/project/safe-multisig-payload-report-action"
owner: "Gosuto Inzasheru"
owner_twitter: "go__su__to"
twitter: "https://x.com/maxyz_xyz"
tags: ["multisig", "governance-security"]
categories: ["computer science", "public-goods", "research", "tech"]
donation_count: 11
total_usd_donated: 178.72
updates_count: 1
---

# Safe Multisig Payload Report Action

🔗 **Project:** [https://qf.giveth.io/project/safe-multisig-payload-report-action](https://qf.giveth.io/project/safe-multisig-payload-report-action)
👤 **Owner:** Gosuto Inzasheru
🐦 **Twitter:** [@go__su__to](https://x.com/go__su__to)

## Social Media
- 🐦 [Twitter](https://x.com/maxyz_xyz)
- 🐙 [Github](https://github.com/maxyz-xyz)
- 🌐 [Website](https://maxyz.xyz)

## Donation Addresses
- `0xdd386bac33370b75a17dc32a6048949a5a29920c`

## Tags
[[Tags/multisig|#multisig]]  [[Tags/governance-security|#governance-security]]


## Donations

> **11 donations** · **Total: $178.72 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x200550cad164e8e0cb544a9c7dc5c833122c1438]] | Ethereum | WETH | $57.66 | 2026-04-24 |
| [[Donors/0x21cb963bb4a32158cb8694dfe46e25a5f20b8d33]] | Ethereum | FINN | $11.48 | 2026-04-29 |
| [[Donors/0xbeefd2772b7e80eaced1ccf10ef69d27b98c43cc]] | Ethereum | ETH | $5.79 | 2026-04-24 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | FINN | $2.32 | 2026-05-07 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $2.00 | 2026-05-07 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| Anonymous | Ethereum | USDC | $49.99 | 2026-04-24 |
| Anonymous | Ethereum | USDC | $25.00 | 2026-04-24 |
| Anonymous | Ethereum | ETH | $17.39 | 2026-04-25 |
| Anonymous | Gnosis | XDAI | $5.00 | 2026-04-24 |
| Anonymous | Polygon | USDC | $1.00 | 2026-04-24 |

## Categories
**Tags:** computer science, public-goods, research, tech
**Main:** Community, Technology

## Description

We MAXYZ are a service provider for DAOs, specialising in onchain operations. A big part of that is multisig transactions, especially in the form of building and reviewing Safe multisig payload JSONs.

  


While working for Balancer DAO, we have developed and battletested a reliable method to review such payloads: before posting them to the Safe UI, we PR them on GitHub. A JSON file lends itself perfectly for being reviewed as _code_, before looking at it in a human interface such as app.safe.global.

  


Besides having a chance to look at the payload line by line, we also have a GitHub workflow that reads the JSON, simulates it onchain and decodes it into human readable input. This gives considerably more information then even the Safe UI, given we can do things such as implement custom decodings and inject personal addresses for labelling.

  


We believe many other DAOs would benefit from this method. An experimental version is currently already being used in private by Ombrello Group; an EVM security service review service: [https://ombrello.group/](https://ombrello.group).

  


Continuing development on this project, taking it out of alpha and making it public is the goal here. Such a publicly accessible GitHub action would be a great addition to the public security tooling currently out there!

  


See the report live in production for example here: <https://github.com/balancer/multisig-ops/pull/2768>

  


A proof-of-concept repository can be found here: <https://github.com/ombrello-group/payload-report-action>
