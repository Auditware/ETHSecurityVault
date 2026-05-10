---
title: "soldb - Open-Source Solidity Debugger"
project_url: "https://qf.giveth.io/project/soldb-open-source-solidity-debugger"
owner: "Roman Mazur"
owner_twitter: "romanmazur"
twitter: "https://x.com/walnut_dev"
tags: ["solidity-tooling", "evm"]
categories: ["computer science", "infrastructure", "tech"]
donation_count: 5
total_usd_donated: 56.92
updates_count: 1
---

# soldb - Open-Source Solidity Debugger

🔗 **Project:** [https://qf.giveth.io/project/soldb-open-source-solidity-debugger](https://qf.giveth.io/project/soldb-open-source-solidity-debugger)
👤 **Owner:** Roman Mazur
🐦 **Twitter:** [@romanmazur](https://x.com/romanmazur)

## Social Media
- 🐦 [Twitter](https://x.com/walnut_dev)
- 🐙 [Github](https://github.com/walnuthq)
- 🌐 [Website](https://walnut.dev/)

## Donation Addresses
- `0x1225588117f705b36175f440c4bdff61319f9847`

## Tags
[[Tags/solidity-tooling|#solidity-tooling]]  [[Tags/evm|#evm]]


## Donations

> **5 donations** · **Total: $56.92 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x14f18a92d6ba49b9fbe1223a861493a38dd38576]] | Ethereum | FINN | $23.45 | 2026-05-03 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | FINN | $11.47 | 2026-05-07 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | TIK | $11.00 | 2026-05-06 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.00 | 2026-05-03 |
| Anonymous | Ethereum | TIK | $10.00 | 2026-05-10 |

## Categories
**Tags:** computer science, infrastructure, tech
**Main:** Economics & Infrastructure, Technology

## Description

**What.** An open-source, CLI-based debugger for Solidity, inspired by lldb. Built as a foundation other tools plug into — Foundry, Hardhat, Tenderly, block explorers. We're already in discussions with most of those teams.

  


  


**Why.** [Solidity Surveys](https://www.soliditylang.org/survey-2025/) consistently flag debugging as the ecosystem's biggest gap. Despite being the most-used smart contract language, Solidity has no canonical CLI debugger the broader tooling can integrate. soldb fills that.

  


**Who.** Walnut — three years building blockchain compilers and debuggers:

  * Working with Argot on ETHDebug integration into solc, the canonical Solidity compiler. That uniquely positions us to build the client that consumes solc's debug info.
  * Starkware partnership: walnut.dev, a web-based transaction debugger and simulator
  * Miden partnership: midenc compiler and CLI debugger
  * Offchain Labs: stylusdb, the debugger for Stylus



  


**Where.** The Solidity / EVM ecosystem — usable on Ethereum L1 and every EVM L2.

  


**How.** soldb consumes ETHDebug-format debug info from solc and exposes a stable CLI other tools wrap. Open-source, integration-first, no lock-in.

  


**What's next.**

  * **Foundry integration (Q2 2026)** — soldb usable directly from forge workflows.
  * **Tenderly proof-of-concept** — early discussions underway on how Tenderly can integrate soldb.
  * **lldb-inspired feature work:** conditional breakpoints, storage watchpoints, pretty-printers for mappings/structs/arrays, multi-contract stepping across delegatecall, and Debug Adapter Protocol (DAP) support — so any DAP-compatible IDE (VS Code, Neovim, etc.) gets soldb for free.
