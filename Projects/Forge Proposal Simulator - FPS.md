---
title: "Forge Proposal Simulator - FPS"
project_url: "https://qf.giveth.io/project/forge-proposal-simulator-fps"
owner: "Elliot Friedman"
owner_twitter: "Elliot0x"
twitter: "https://x.com/soliditylab"
tags: ["governance-security", "auditing"]
categories: ["computer science", "financial-services", "infrastructure", "public-goods", "tech"]
donation_count: 10
total_usd_donated: 31.74
updates_count: 1
---

# Forge Proposal Simulator - FPS

🔗 **Project:** [https://qf.giveth.io/project/forge-proposal-simulator-fps](https://qf.giveth.io/project/forge-proposal-simulator-fps)
👤 **Owner:** Elliot Friedman
🐦 **Twitter:** [@Elliot0x](https://x.com/Elliot0x)

## Social Media
- 🐦 [Twitter](https://x.com/soliditylab)
- 🐙 [Github](https://github.com/solidity-labs-io/forge-proposal-simulator)
- 🌐 [Website](https://docs.soliditylabs.io)

## Donation Addresses
- `0x1d107d157a44e360d6f06cf27e58497e7f72ffa7`

## Tags
[[Tags/governance-security|#governance-security]]  [[Tags/auditing|#auditing]]


## Donations

> **10 donations** · **Total: $31.74 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | FINN | $11.47 | 2026-05-07 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $8.00 | 2026-05-08 |
| [[Donors/0x45656eaa07d95bf60d6fbd98cf68a36256cebbe0]] | Ethereum | TIK | $5.00 | 2026-05-07 |
| [[Donors/Cotabe Moral]] | Optimism | USDGLO | $2.00 | 2026-04-23 |
| [[Donors/donny lewis]] | Optimism | ETH | $1.18 | 2026-05-05 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.00 | 2026-05-03 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| [[Donors/Kresimir Katusic]] | Optimism | USDC | $0.00 | 2026-04-24 |
| Anonymous | Base | USDC | $1.00 | 2026-04-24 |

## Categories
**Tags:** computer science, financial-services, infrastructure, public-goods, tech
**Main:** Community, Economics & Infrastructure, Finance, Technology

## Description

Forge Proposal Simulator (FPS) is an open-source framework built on top of Foundry that gives developers and signers a standardized way to simulate governance proposals before they touch the chain. It covers the full proposal lifecycle: deployment scripts, calldata generation, proposal simulation throughout the governance lifecycle, and post proposal state validation. The framework runs your existing test suite against the post-proposal state of the protocol, catching bugs that unit tests and auditors miss. When governance proposals contain bugs, protocols break. Funds get locked, markets get frozen, users experience cascading liquidations on healthy positions. The Compound V2 WETH incident is a perfect example of this: the governance proposal was not tested against the live state of the protocol before execution.

  


FPS supports four governance models out of the box: OpenZeppelin Timelock Controller, Gnosis Safe multisig, Compound Governor Bravo, and OpenZeppelin Governor. The architecture is loosely coupled. If your protocol uses a different governance model, FPS is flexible enough to accommodate it.

OlympusDAO made FPS mandatory for all governance proposals. Other top rollups and DeFi protocols use concepts this tool pioneered to secure their governance process. This tool has been used in production, helping govern protocols with a combined TVL of over a billion dollars.

  


This project is the culmination of years spent building smart contracts for DAOs and watching governance security be treated as an afterthought. I have deployed, written, reviewed, and debugged proposals that broke in production. Almost every protocol I worked with had the same blind spot: there wasn’t a standardized way to test a governance action and contract deployment against the real state of the system before it executed. FPS was born from years of direct exposure to the problem, building with teams that needed this tool and didn't have it. At DeFi Security Summit (DSS 2024), we presented how FPS can be used to find hard-to-catch bugs in deployment scripts ([https://www.youtube.com/watch?v=UU4wkD4hXUY).](https://www.youtube.com/watch?v=UU4wkD4hXUY%29.)

  


The framework is MIT licensed, free to use, and has been open source since 2023. It is a public good. There is no token, no revenue model, and no paywall.

  


Funding tiers are cumulative, with each funding level enabling us to do more to secure the ecosystem:

  


Under $5k: Ongoing maintenance. Bug fixes, Foundry version compatibility, triaging GitHub issues from teams integrating FPS. This would enable me to survey users, and understand their pain points.

  


$5k–$10k: Better documentation and onboarding. Dedicated guides for each governance model, video walkthroughs, a standalone project site, more mainnet examples covering Uniswap Governor, Aave governance, and a migration guide including intuition for teams currently testing proposals with bespoke tooling. At this level, I would prioritize implementation of features identified in the user survey.

  


$10k–$25k: Community outreach and adoption. A dedicated FPS Twitter/X account, regular content, integration case studies, regular conference workshops on governance testing, a library of real governance bugs FPS would have caught, and a Tenderly integration for visualizing simulation output. CI integration runner and an expanded set of features to enable seamless onchain verification of governance proposals within CI.

  


$25k–$50k: Feature development. A proposal diffing feature that shows exactly what state changes a proposal will make in human-readable format. FPS already has parts of this, but it could be a lot more ergonomic and communicate storage slot changes in a human-readable format. At this level of funding, I would dig in and figure out native support for L2-specific governance patterns like cross-chain proposals and L1-to-L2 timelocks. I would also host a small prize pool at EthGlobal to have hackers try FPS and give feedback.
