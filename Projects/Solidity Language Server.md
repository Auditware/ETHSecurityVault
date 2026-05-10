---
title: "Solidity Language Server"
project_url: "https://qf.giveth.io/project/solidity-language-server"
owner: "Meek Msaki"
owner_twitter: "msakiart"
twitter: "https://x.com/solidity_lsp"
tags: ["solidity-tooling"]
categories: ["computer science", "public-goods", "research", "tech"]
donation_count: 14
total_usd_donated: 297.75
updates_count: 1
---

# Solidity Language Server

🔗 **Project:** [https://qf.giveth.io/project/solidity-language-server](https://qf.giveth.io/project/solidity-language-server)
👤 **Owner:** Meek Msaki
🐦 **Twitter:** [@msakiart](https://x.com/msakiart)

## Social Media
- 🐦 [Twitter](https://x.com/solidity_lsp)
- 🐙 [Github](https://github.com/mmsaki/solidity-language-server)
- 📱 [Telegram](https://t.me/soliditylsp)
- 🌐 [Website](https://solidity-language-server-docs.pages.dev/)

## Donation Addresses
- `0x04655832bcb0a9a0be8c5ab71e4d311464c97af5`

## Tags
[[Tags/solidity-tooling|#solidity-tooling]]


## Donations

> **14 donations** · **Total: $297.75 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xdcb9bfb38e60d0d03a4b20b78fc25e9298a56faa]] | Ethereum | ETH | $230.66 | 2026-04-24 |
| [[Donors/0x806164c929ad3a6f4bd70c2370b3ef36c64deaa8]] | Ethereum | ETH | $11.43 | 2026-04-28 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | TIK | $11.00 | 2026-05-06 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $10.00 | 2026-05-08 |
| [[Donors/0xf8a025b42b07db05638fe596cce339707ec3cc71]] | Base | ETH | $5.87 | 2026-05-06 |
| [[Donors/David Dada]] | Base | ETH | $5.00 | 2026-04-27 |
| [[Donors/0x79d9f3f6b046c375470588a896b43f23372356d5]] | Ethereum | TIK | $5.00 | 2026-05-03 |
| [[Donors/j stcz]] | Ethereum | DAI | $5.00 | 2026-04-29 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| Anonymous | Ethereum | USDC | $5.10 | 2026-04-25 |
| Anonymous | Ethereum | FINN | $2.34 | 2026-04-29 |
| Anonymous | Ethereum | FINN | $2.26 | 2026-04-30 |
| Anonymous | Ethereum | USDC | $2.00 | 2026-04-29 |
| Anonymous | Ethereum | TIK | $1.00 | 2026-05-03 |

## Categories
**Tags:** computer science, public-goods, research, tech
**Main:** Community, Technology

## Description

# 👋 Hi, Solidity devs,

[Solidity Language Server](https://github.com/mmsaki/solidity-language-server) is an open-source public good language server that supports over 20+ LSP methods accross all text editors i.e. Vim, Neovim, Helix, Zed, VS Code / Cursor, Opencode, Claude Code and maintains low latency in largest solidity/foundry projects.

  


Our 2026 LSP benchmarks found that existing Solidity LSPs struggle with large projects and often break across different editors and AI tools. We built this Language Server at Asyncswap Labs to support our own development, and have since open-sourced it to fill a critical gap in smart contract developer tooling.

  


## How can we contribute to Ethereum security?

Smart contract security doesn't start at audit time. It starts in the editor while developers are writing, navigating, and reviewing code.

  


We want solidity developers to jump to definitions, trace references, and reason about your contracts with confidence whether you're building, reviewing, or using AI-assisted tooling. Ship faster and catch mistakes before they hit the chain.

  


## The Features

1\. Diagnostics

> ** _Diagnostics_** _show you Solidity warnings, lints, and errors._

  


2\. Semantic Tokens

> ** _Semantic tokens_** _allow your editor to understand what each symbol represents so it can apply the correct colors for your editor's theme._

  


3\. Go to Definition / Declaration

  


>  _The_** _Go to Definition_** _feature lets you or your AI agent jump to the location where a variable or user-defined type is declared._

  


4\. Implementation

>  _Have you ever tried to find where IERC20(token).transfer(...) is defined and landed on the interface function instead of the actual code?_**_Go to Implementation_** _skips the interface declaration and jumps straight to the contract that inherits it where the function body lives. This works when the contract inherits the IERC20 interface and overrides the method, which_ _is how the LSP resolves the implementation location._

  


5\. Hover

> ** _Hover_** _surfaces everything you need to know about a symbol without leaving the line. Just hover over a function, variable, or contract to see NatSpec documentation, 4-byte selectors, storage layout locations, contract deployment costs, and function gas estimates — all inline._

  


6\. References

> ** _Find References_** _shows every usage of a variable, function, or user-defined type across your entire project_ _contracts, tests, scripts, and library dependencies. This is more accurate than manual searching to understand how a symbol is used throughout your codebase._

  


7\. Completion

> ** _Completion_** _suggests types, variables, functions, and Solidity identifiers as you type — helping you write contracts faster and with fewer typos._

  


8\. Signature Help

> ** _Signature Help_** _shows parameter hints as you fill in function arguments, emit events, or access mappings. Triggered_ _automatically when you type ( for functions and events, or [ for mapping lookups — so you always know what comes next._

  


9\. Rename

> ** _Rename_** _lets you rename variables, functions, parameters, contracts, aliases, and user-defined types — updating every reference across your project in one action._

  


10\. Document Symbol

> ** _Document Symbols_** _lists every symbol in a file — contracts, functions, variables, events, errors — in a nested hierarchy. Use it with your editor's outline view to quickly navigate large files._

  


11\. Formating

> ** _Formatting_** _keeps your Solidity code clean and consistent. You can format automatically on save or manually on demand._

  


12\. Inlay Hint

> ** _Inlay Hints_** _display parameter names inline at function call sites and event emissions — so you can read what each argument means without jumping to the definition._

  


13\. CodeAction

> ** _Code Actions_** _offer quick fixes right where you need them — like removing unused imports — with more actions being added over time._

  


14\. Will Create Files

> ** _File Templates_** _scaffold new Solidity contracts, tests, and scripts with the right boilerplate — so you can start writing code immediately._

  


15\. Will Rename Files

> ** _File Rename_** _automatically updates all import paths across your project when you rename a file — no broken imports to chase down._

  


16\. Incoming / Outgoing Calls

> ** _Incoming Calls_** _shows every place a function is called from across your project._**_Outgoing Calls_** _shows every external call a function makes. Together, they let you trace the full call chain in either direction without reading through files manually._

  


## Why now?

Solidity editor tooling is still below the standard required for security-critical software development. Many existing language servers — Juan Blanco's VS Code LSP, Nomic Foundation's LSP, and solc's built-in LSP — work inside narrow, editor-specific workflows but break down or degrade significantly in environments like Neovim, Vim, Helix, Zed, Emacs, and Sublime.

  


This matters because Solidity developers are increasingly moving toward other IDEs and AI coding assistants. AI tools like Claude Code and Opencode are beginning to consume language server infrastructure directly, without a traditional editor user interfaces. If Solidity language servers are breaking outside of one editor, they will no meet the needs of the broader ecosystem.

  


More importantly, the Solidity team has stated the Solc LSP is effectively abandoned as development ceased before it became stable, with no plans to revive it ([solidity#16124](argotorg/solidity#16124)). This leaves Ethereum without upstream ownership of a critical layer of Solidity LSP development tooling. Developers, reviewers, and AI systems rely on to understand smart contract code before it reaches production.

  


There is also a growing supply-chain security problem around developer tooling itself. Public reporting has shown that malicious editor extensions and packages can steal data, install backdoors, and target crypto developers specifically. Solidity LSP tooling must not only be fast and capable, but trustworthy in how it is built and distributed.

  


We believe language server infrastructure for Ethereum should be open-source, auditable, and verifiable, not another opaque attack surface in the developer workflow.

  


## Why this project

Across benchmarks against the Solidity language servers currently known to us i.e. Nomicfoundation, Solc, Quang, and Juan Blanco, our results show stronger overall performance, broader feature support, and faster lsp responses. Our benchmarks are reproducible, and we welcome scrutiny and comparison from anyone building language tooling, because transparent measurement helps the entire ecosystem improve.

  


## Who I am

My name is Meek Msaki. I am a software developer, educator, and founder building on Ethereum.

  


Over the last several years I have worked across smart contract development, developer education, and open-source tooling.

  


A few milestones from my journey:

\- 2021: Graduated from the University of Minnesota fintech bootcamp

\- 2022: First hackathon win at ETHGlobal

\- 2023: Consulted with Extropy via Encode Club across 7+ blockchain cohorts covering Solidity, the EVM, zero-knowledge proofs, and Solana

\- 2023: Attended the Science of Blockchain conference at Stanford

\- 2024: Independent consulting at Lifeworld

\- 2025-present: Co-founder at AsyncSwap Labs, working on AMM transaction ordering and swap intents

  


Alongside that work, I teach workshops and build open-source developer tools for Ethereum.

Relevant links:

  


\- X: [@msakiart](https://x.com/msakiart/)

\- Project: [solidity-language-server](https://github.com/mmsaki/solidity-language-server)

\- Other project: [huff.nvim](https://github.com/mmsaki/huff.nvim), a Neovim plugin for developing Huff contracts

  


## What funding will support

Support from this round will help fund any of these causes:

  1. continued feature development and maintenance
  2. performance and indexing improvements
  3. better code navigation, references, and analysis tooling
  4. stronger interoperability across editors and nontraditional clients
  5. continued AI-native LSP support currently available in OpenCode
  6. benchmark infrastructure and reproducibility
  7. testing, regression prevention, and release engineering
  8. security hardening, and verifiable distribution



  


## Donation impact

Your support helps fund preventative security infrastructure for Ethereum.

  


Example impact levels:

\- $1,000 supports maintenance, issue triage, and continual development

\- $2,000 improves compatibility across Solidity versions, editors, and AI-native tooling

\- $5,000 accelerates major features, performance, and other contributor-driven improvements

\- $10,000+ hardening LSP security.

  


## Community signals

Developers are already feeling the gap in Solidity tooling and the value of better editor support:

\- “Actually it’s the only thing that made solidity usable on zed so thanks.” — clandestine.eth

\- “my former colleagues will surely appreciate to have a better lsp.” — badfalafel

\- “zed's bad solidity support always annoys me... if you'd like a contributor I'm happy to help” — kakashi

  


## We need your support.

If you believe Ethereum security starts where smart contracts are written, in the editor, in code navigation, and in the tools developers and AI systems rely on to understand code, please support the Solidity Language Server.

  


Donate $1, $5, $100, $200 or $5,000 :). Any donation will make a huge difference. Thank you ❤️.
