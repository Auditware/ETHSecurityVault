---
title: "Wake: Solidity static analysis and fuzzing framework"
project_url: "https://qf.giveth.io/project/wake:-solidity-static-analysis-and-fuzzing-framework"
owner: "Michal Převrátil"
owner_twitter: "michprev"
twitter: "https://twitter.com/WakeFramework"
tags: ["static-analysis", "fuzzing", "solidity-tooling"]
categories: ["computer science", "research", "tech"]
donation_count: 16
total_usd_donated: 243.11
updates_count: 1
---

# Wake: Solidity static analysis and fuzzing framework

🔗 **Project:** [https://qf.giveth.io/project/wake:-solidity-static-analysis-and-fuzzing-framework](https://qf.giveth.io/project/wake:-solidity-static-analysis-and-fuzzing-framework)
👤 **Owner:** Michal Převrátil
🐦 **Twitter:** [@michprev](https://x.com/michprev)

## Social Media
- 🐦 [Twitter](https://twitter.com/WakeFramework)
- 🐙 [Github](https://github.com/michprev/wake)
- 📱 [Telegram](https://t.me/wake_group)

## Donation Addresses
- `0xd8393ea15c2c17864f483aa4d6a0b709d46bf98e`

## Tags
[[Tags/static-analysis|#static-analysis]]  [[Tags/fuzzing|#fuzzing]]  [[Tags/solidity-tooling|#solidity-tooling]]


## Donations

> **16 donations** · **Total: $243.11 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x8abf01aaea367e7803ca8c18aaf1a2c2e1181184]] | Ethereum | USDC | $199.99 | 2026-05-08 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | FINN | $11.47 | 2026-05-07 |
| [[Donors/0x2c6635b76871a186255e9bd2a31ac280c5f16313]] | Arbitrum | ETH | $10.38 | 2026-04-24 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $8.00 | 2026-05-08 |
| [[Donors/0x237d7367daf1b337e1753a5177c95dd525777406]] | Ethereum | FINN | $2.34 | 2026-04-29 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.20 | 2026-05-03 |
| [[Donors/0x7a6eee7bae30ddbde6777c6f02ef478437e47d99]] | Ethereum | ETH | $1.17 | 2026-05-07 |
| [[Donors/0x4799b6ffa163dd67adcb8faaed9eadec32b7246a]] | Arbitrum | ETH | $1.14 | 2026-05-07 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x66e1bffb4515f9fb15ee16dc17831a587d13ad7f]] | Base | ETH | $1.03 | 2026-05-04 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| [[Donors/bilal ali kaya]] | Optimism | GIV | $0.05 | 2026-04-26 |
| [[Donors/Kresimir Katusic]] | Optimism | USDC | $0.00 | 2026-04-24 |
| [[Donors/0x43276b383f95b163b617c91787a4d76c0d4ce9f6]] | Optimism | USDC | $0.00 | 2026-04-24 |
| Anonymous | Ethereum | FINN | $2.26 | 2026-04-30 |
| Anonymous | Ethereum | USDC | $2.00 | 2026-04-28 |

## Categories
**Tags:** computer science, research, tech
**Main:** Technology

## Description

[Wake](https://pypi.org/project/eth-wake/) is a development framework for Solidity smart contracts that combines testing, fuzzing, static analysis, and IDE tooling in a single Python-based toolkit — helping developers write safer contracts, faster.

  


  


# Features

\- **Testing framework** based on [pytest](https://docs.pytest.org/en) — write clean, readable tests with familiar Python tooling

\- **Property-based fuzzing** — automatically generate diverse inputs to uncover hidden bugs

\- **Manually-guided fuzzing (MGF)** — combine automated fuzzing with human insight to target specific contract behaviors and edge cases

\- **Rust EVM core** — high-performance chain simulation via [revm](https://github.com/bluealloy/revm), with call tracing, coverage tracking, and mainnet forking built in

\- **Vulnerability detectors** — catch reentrancy, unsafe delegatecalls, unchecked return values, and more out of the box

\- **Extensible static analysis** — write custom detectors and printers in Python to enforce project-specific rules

\- **Rich code intelligence** — fully typed intermediate representation of Solidity code with control flow graphs, cross-reference resolution, storage layout analysis, and state change tracking — a foundation ready to power AI-driven security tooling

\- **Deployments & mainnet interactions** — send transactions and deploy contracts on major chains

  


  


  


# Donation objectives

Wake's static analysis engine produces rich, structured representations of Solidity code — typed IR, control flow graphs, cross-references, storage layouts, and state change tracking. Today, this powers detectors and IDE features. The donations would fund exposing this intelligence to AI agents, unlocking a new class of AI-driven security and development tooling.

  


## Deliverables

\- **MCP server for static analysis** — expose Wake's code intelligence (definitions, references, type hierarchy, control flow, storage layout, state changes) as an [MCP](https://modelcontextprotocol.io/) server, giving AI agents structured, queryable access to Solidity codebases instead of raw source text

\- **AI-native fuzzing interface** — provide an agent-friendly API for autonomous fuzz testing: AI agents define flows, invariants, and test strategies, then launch and monitor fuzzing campaign outputs

\- **Agent-oriented documentation and examples** — reference implementations showing AI agents using Wake's MCP tools for end-to-end security analysis: from code understanding through fuzz testing to vulnerability reporting

\- **Ongoing revm core maintenance** — keep Wake's Rust EVM core up to date with revm releases and upcoming Ethereum hardforks, ensuring tests and fuzzing always run against the latest EVM semantics

\- **New vulnerability detectors** — expand the built-in detector suite with coverage for additional vulnerability classes, including detectors for known Solidity compiler bugs that silently generate incorrect bytecode
