---
title: "Solidity-Wake: VS Code extension"
project_url: "https://qf.giveth.io/project/solidity-wake:-vs-code-extension"
owner: "Michal Převrátil"
owner_twitter: "michprev"
twitter: "https://twitter.com/WakeFramework"
tags: ["solidity-tooling", "static-analysis"]
categories: ["computer science", "research", "tech"]
donation_count: 10
total_usd_donated: 227.73
updates_count: 1
---

# Solidity-Wake: VS Code extension

🔗 **Project:** [https://qf.giveth.io/project/solidity-wake:-vs-code-extension](https://qf.giveth.io/project/solidity-wake:-vs-code-extension)
👤 **Owner:** Michal Převrátil
🐦 **Twitter:** [@michprev](https://x.com/michprev)

## Social Media
- 🐦 [Twitter](https://twitter.com/WakeFramework)
- 🐙 [Github](https://github.com/michprev/solidity-for-vscode)
- 📱 [Telegram](https://t.me/wake_group)

## Donation Addresses
- `0x929ec9ed648a56bdef4dad1ffa03c1faea17f488`

## Tags
[[Tags/solidity-tooling|#solidity-tooling]]  [[Tags/static-analysis|#static-analysis]]

## Related QF Projects
- [[Projects/Verity Formal Verification for Smart Contracts|Verity: Formal Verification for Smart Contracts]]
- [[Projects/Wake Solidity static analysis and fuzzing framework|Wake: Solidity static analysis and fuzzing framework]]


## Donations

> **10 donations** · **Total: $227.73 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x8abf01aaea367e7803ca8c18aaf1a2c2e1181184]] | Ethereum | USDC | $199.98 | 2026-05-08 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | FINN | $11.47 | 2026-05-07 |
| [[Donors/0x2c6635b76871a186255e9bd2a31ac280c5f16313]] | Arbitrum | ETH | $6.92 | 2026-04-24 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $2.00 | 2026-05-07 |
| [[Donors/0x226f786b66617858bf563fdfdb8d8fe75ac10934]] | Optimism | ETH | $1.15 | 2026-05-07 |
| [[Donors/0xde1394471c7531b2d5ebe084b744be6609a8b2d8]] | Base | ETH | $1.13 | 2026-04-29 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x64f0bfcf26fef19b66456ec3ec74a536507d1bef]] | Gnosis | USDC | $1.00 | 2026-04-28 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| Anonymous | Ethereum | USDC | $2.00 | 2026-04-29 |

## Categories
**Tags:** computer science, research, tech
**Main:** Technology

## Description

Solidity (Wake) is a VS Code extension for developing, testing, and securing Solidity smart contracts — powered by the [Wake](https://pypi.org/project/eth-wake/) framework.

  


It brings a Remix-like experience into the editor: compile contracts, deploy them on a local node, interact with functions, fork mainnet or L2s, and work with proxy contracts — all without leaving VS Code. Real-time static analysis runs Wake's vulnerability detectors as you type, surfacing security issues inline and in a dedicated sidebar overview.

  


  


# Features

\- **Local node testing** — compile, deploy, and interact with contracts on an embedded Ethereum node directly in VS Code

\- **Mainnet & L2 forking** — fork any EVM chain to test against real on-chain state and interact with deployed contracts

\- **Proxy contract support** — native detection and interaction through proxy contracts

\- **Real-time vulnerability detection** — Wake's detectors run on every keystroke, showing reentrancy, unsafe delegatecalls, and other issues inline as diagnostics

\- **Security overview sidebar** — aggregated view of all detections across the project, filterable by severity and confidence

\- **Code navigation** — go-to-definition, find references, hover documentation, contract outline, and document links across Solidity files

\- **Code lens** — inline function selectors, reference counts, and detector annotations directly in the source

\- **Graph visualizations** — interactive inheritance graphs, control flow graphs, and import dependency diagrams rendered in-editor

\- **Works with existing setups** — compatible with Hardhat and Foundry projects, auto-imports Foundry remappings

  


  


# Donation objectives

Solidity (Wake) is the most feature-rich open-source Solidity extension for VS Code — combining code intelligence, real-time security analysis, and interactive contract testing in one tool. The donation would fund expanding its capabilities and connecting it to Wake's upcoming AI infrastructure.

## Deliverables

\- **Revm-based engine for Deploy & Interact** — add Wake's built-in Rust EVM core as the primary engine for the Deploy & Interact UI alongside Anvil, making local node testing faster and self-contained with no external process required

\- **AI integration** — bring-your-own-provider AI features powered by Wake's static analysis context: natural-language explanations of detected vulnerabilities with suggested fixes. Users connect their own API key (OpenAI, Anthropic, ...) — no vendor lock-in  

\- **AI-assisted fuzz test generation** — generate Wake fuzz tests from contract code using static analysis context to produce meaningful flows and invariants

\- **Richer graph visualizations** — cross-contract call graphs, token flow diagrams, and access control maps rendered interactively

\- **Ongoing maintenance** — keep pace with VS Code API changes, Wake releases, new Solidity language features, and Foundry/Hardhat ecosystem updates
