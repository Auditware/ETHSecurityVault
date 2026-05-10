---
title: "Roundabout: Static Analysis for Solidity"
project_url: "https://qf.giveth.io/project/roundabout:-static-analysis-for-solidity"
owner: "Seth Hallem"
owner_twitter: "seth_certora"
twitter: "https://x.com/Certora"
tags: ["static-analysis", "solidity-tooling"]
categories: ["computer science", "infrastructure", "public-goods", "tech"]
donation_count: 4
total_usd_donated: 124.99
updates_count: 1
---

# Roundabout: Static Analysis for Solidity

🔗 **Project:** [https://qf.giveth.io/project/roundabout:-static-analysis-for-solidity](https://qf.giveth.io/project/roundabout:-static-analysis-for-solidity)
👤 **Owner:** Seth Hallem
🐦 **Twitter:** [@seth_certora](https://x.com/seth_certora)

## Social Media
- 🐦 [Twitter](https://x.com/Certora)
- 🐙 [Github](https://github.com/Certora/wala-solidity)
- 💼 [Linkedin](https://www.linkedin.com/company/certora)
- 🌐 [Website](https://certora.com)
- 🔗 [Youtube](https://www.youtube.com/live/1KR0GnxhNz4?si=PqzpyvBNtUMzGVQt)

## Donation Addresses
- `0x339effebdd8b80e6b1877ac4e8d23ee877d825d9`

## Tags
[[Tags/static-analysis|#static-analysis]]  [[Tags/solidity-tooling|#solidity-tooling]]


## Donations

> **4 donations** · **Total: $124.99 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x046f1453ff5b4dbbd951b6d49713d06f9a700e23]] | Ethereum | DAI | $9.99 | 2026-05-07 |
| [[Donors/0x45656eaa07d95bf60d6fbd98cf68a36256cebbe0]] | Ethereum | TIK | $5.00 | 2026-05-07 |
| Anonymous | Ethereum | TIK | $100.00 | 2026-05-06 |
| Anonymous | Ethereum | TIK | $10.00 | 2026-05-10 |

## Categories
**Tags:** computer science, infrastructure, public-goods, tech
**Main:** Community, Economics & Infrastructure, Technology

## Description

Certora is building an open source static analysis tool based for Solidity. Our goal is to use syntax tree analysis and abstract interpretation to build a series of inter-procedural, flow sensitive static analyses that detect common security vulnerabilities in Solidity smart contracts. Our first target is rounding errors, and we have released the Roundabout tool here: <https://github.com/Certora/wala-solidity>

  


Unlike code scanners and other syntax tree analyzers, Roundabout is based on the concept of abstract interpretation. Abstract interpretation guarantees that the static analyzer collects a safe approximation of actual program behavior. The result is a precise and sound analysis, meaning it can report false positives but it will not miss bugs.

  


Such a tool is ideal for detecting security vulnerabilities where even a single missed bug can lead to a financial disaster. Roundabout detects inconsistent rounding directions, and clearly illustrates to a developer the rounding direction of each fixed point value used within a Solidity smart contract. We have already built a simple, local HTML-based UI for analyzing results and Claude skills to ease the adoption of Roundabout.

  


Certora would like to extend this open source tool to include new analyzers that build on top of our work with Roundabout. Such analyzers could include a static analysis for unit conversion errors, an analyzer for access control checks, and more. All funds raised through the DAO vehicle would be used directly to build out this tool for the community.

  


You can learn more about how roundabout works from our co-founder and Chief Scientist, Mooly Sagiv's, presentation at EthCC: <https://www.youtube.com/live/1KR0GnxhNz4?si=PqzpyvBNtUMzGVQt>
