---
title: "Tool Against Price Manipulation Attacks in DeFi on EVM"
project_url: "https://qf.giveth.io/project/tool-against-price-manipulation-attacks-in-defi-on-evm"
owner: "Martin Derka"
owner_twitter: "dr_zircuit"
twitter: "https://x.com/dr_zircuit"
tags: ["defi-security", "smart-contract"]
categories: ["computer science", "financial-services", "research", "tech"]
donation_count: 26
total_usd_donated: 1038.95
updates_count: 1
---

# Tool Against Price Manipulation Attacks in DeFi on EVM

🔗 **Project:** [https://qf.giveth.io/project/tool-against-price-manipulation-attacks-in-defi-on-evm](https://qf.giveth.io/project/tool-against-price-manipulation-attacks-in-defi-on-evm)
👤 **Owner:** Martin Derka
🐦 **Twitter:** [@dr_zircuit](https://x.com/dr_zircuit)

## Social Media
- 🐦 [Twitter](https://x.com/dr_zircuit)
- 🐙 [Github](https://github.com/FlashSyn-Artifact/FlashSyn-Artifact-ICSE24)
- 💼 [Linkedin](https://www.linkedin.com/company/quantstamp)
- 🌐 [Website](https://www.quantstamp.com)

## Donation Addresses
- `0x755c8e96ebca19874be4ea713f15003d4b0fa8ff`

## Tags
[[Tags/defi-security|#defi-security]]  [[Tags/smart-contract|#smart-contract]]


## Donations

> **26 donations** · **Total: $1,038.95 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x3ec2f869066a8b4a30a5f10fc9c63be4dfbbd2b4]] | Ethereum | FINN | $82.97 | 2026-05-01 |
| [[Donors/0xc348905ee15e9ae4a0c10aef703818c434e6ab8e]] | Ethereum | USDC | $74.99 | 2026-04-29 |
| [[Donors/0xc348905ee15e9ae4a0c10aef703818c434e6ab8e]] | Ethereum | USDC | $74.97 | 2026-04-29 |
| [[Donors/0x3a24cddca03912ed1970b3c9c0a9bc6d3e1a8665]] | Ethereum | ETH | $49.93 | 2026-05-01 |
| [[Donors/0x8d596e7f916fe815b4efd4b1dce50c895d4ab9f2]] | Ethereum | USDC | $31.99 | 2026-04-30 |
| [[Donors/0xabdb288d4d2da081ac8e24ab6658e9f42ed66084]] | Ethereum | USDC | $24.99 | 2026-04-24 |
| [[Donors/Anny Edge]] | Arbitrum | ETH | $11.27 | 2026-04-29 |
| [[Donors/0x5b36fc8ccf927c136d48bf745dc991d3e0786859]] | Ethereum | ETH | $10.01 | 2026-05-04 |
| [[Donors/0xc07db3f37185599da355bdcdd11350a8bad93bb9]] | Base | USDC | $10.00 | 2026-04-30 |
| [[Donors/0x9cea0b05eedb18cdeb041a7832646a139cf8a990]] | Ethereum | TIK | $6.00 | 2026-05-09 |
| [[Donors/Lauren Luz]] | Optimism | GIV | $5.66 | 2026-04-23 |
| [[Donors/Jake  Schumacher]] | Polygon | WETH | $5.06 | 2026-04-23 |
| [[Donors/0x45656eaa07d95bf60d6fbd98cf68a36256cebbe0]] | Ethereum | TIK | $5.00 | 2026-05-07 |
| [[Donors/0x45a2809685dd871af6104fc261e17f82f87ac7d0]] | Ethereum | USDC | $5.00 | 2026-04-30 |
| [[Donors/0x9cea0b05eedb18cdeb041a7832646a139cf8a990]] | Ethereum | FINN | $2.32 | 2026-05-09 |
| [[Donors/Kamrul Hasan]] | Base | ETH | $1.14 | 2026-05-08 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x5090bb37446f5fb8779777732e0ab679870eeab0]] | Ethereum | USDC | $1.00 | 2026-05-02 |
| Anonymous | Base | USDC | $499.87 | 2026-04-30 |
| Anonymous | Base | USDC | $99.96 | 2026-04-30 |
| Anonymous | Base | ETH | $11.38 | 2026-05-08 |
| Anonymous | Ethereum | USDC | $10.00 | 2026-04-30 |
| Anonymous | Ethereum | USDC | $10.00 | 2026-04-30 |
| Anonymous | Ethereum | FINN | $2.33 | 2026-04-24 |
| Anonymous | Optimism | USDC | $1.00 | 2026-04-29 |
| Anonymous | Base | USDC | $1.00 | 2026-05-04 |

## Categories
**Tags:** computer science, financial-services, research, tech
**Main:** Finance, Technology

## Description

## Automated Price Manipulation and Flash Loan Attack Discovery for Composable DeFi Systems

 _Prepared and submitted by Martin Derka, Head of New Initiatives @ Quantstamp and Co-Founder @ Zircuit, ETH Security Badge #29._

  


Most DeFi attacks no longer exploit isolated bugs, but behaviors emerging across protocol compositions. Exploits driven by asset price manipulation, with or without flash loans, are a prominent cause of losses arising from carefully orchestrated interactions between lending markets, AMMs, and oracles.

This proposal aims to advance the state of DeFi security by modernizing and making accessible to the broader Ethereum community [FlashSyn (2024, Z. Chen et al.)](https://arxiv.org/abs/2206.10708), a research tool developed at the University of Toronto that has already demonstrated strong effectiveness in discovering real-world flash loan exploits.

  


We propose to improve its usability and reliability by addressing the currently known drawbacks that prevent FlashSyn from wider adoption, extend it into a continuous monitoring system for EVM-compatible chains, and release the result as an open-source tool for the ecosystem.

###   


### Motivation

  


Modern DeFi exploits are increasingly compositional: attackers construct multi-step strategies that span multiple protocols and exploit assumptions that only break under composition.

  


A canonical attack pipeline looks as follows:

  1. An attacker enters with capital, potentially obtained via a flash loan
  2. Manipulate price or liquidity in one protocol
  3. Exploit mispriced collateral or accounting in another
  4. Extract back the capital, possibly repay the flash loan, and extract profit



  


Each step is valid in isolation; the protocols operate as they are intended to, but the systemic vulnerability emerges only when actions are composed.

  


This shift is well documented and relevant for Ethereum in 2026:

  * Industry data confirms the trend: flash loan and manipulation attacks account for a _large share of DeFi losses_ , often involving multiple protocols: <https://www.halborn.com/reports/top-100-defi-hacks-2025>
  * Ethereum alone saw _92 incidents and ~$470M in losses in H1 2025_ , many tied to pricing and logic flaws in composable systems: <https://thedefiant.io/news/research-and-opinion/ethereum-hit-by-most-security-incidents-in-h1-2025-slowmist>
  * FlashSyn models attacks explicitly as _"sequences of actions across DeFi protocols"_ : <https://arxiv.org/abs/2206.10708>
  * Prior work shows flash loan attacks rely on _atomic composability and cross-protocol interactions_ →[ https://arxiv.org/abs/2003.03810](https://arxiv.org/abs/2003.03810)
  * Recent examples such as [KiloEx (April 2025)](https://www.coindesk.com/markets/2025/04/15/dex-kiloex-loses-usd7m-in-apparent-oracle-manipulation-attack), Moonwell (November 2025), and [Silo Finance (June 2025)](https://www.certora.com/blog/silo-incident-report-contract-exploit) reinforce that these exploits often rely on cross-protocol price manipulation and liquidity feedback loops.



  


The ecosystem has responded to smart contract security threats primarily by embedding audits into the development process. Yet the numbers demonstrate that audits can fail to surface vulnerabilities of this kind. This is precisely where automated tooling can close the gap.

  


### Background: FlashSyn in Practice

  


FlashSyn is an open-source research tool, released under the Apache 2.0 license, developed by [Z. Chen et al](https://arxiv.org/abs/2206.10708). at the University of Toronto. It is the first automated end-to-end program synthesis tool for detecting flash loan attack vulnerabilities.

  


FlashSyn models potential exploits as parameterized sequences of actions across multiple DeFi protocols, where each action represents a valid interaction (e.g., swaps, borrows, approvals) with placeholder parameters. It systematically generates and executes combinations of these actions, identifying sequences that do not revert and produce measurable changes in the attacker's balance.

  


To efficiently search this space, FlashSyn approximates the resulting profit as a multivariate polynomial function over the action parameters using sampled executions. It then analyzes this approximation to find profitable extrema and validates them through concrete EVM execution, confirming whether a true exploit exists.

  


Using FlashSyn requires several expert steps, primarily: extracting relevant protocol actions, defining pricing relationships, and occasionally mocking infrastructure dependencies. The tool's authors and Quantstamp (also the current maintainers of the repository) have proceduralized these steps. Quantstamp actively uses FlashSyn in its security offering, and it has successfully and reliably rediscovered exploits including bZx, Eminence, Harvest, Value DeFi, CheeseBank, Warp, Yearn, InverseFi, bEarnFi, AutoShark, ElevenFi, ApeRocket, WDoge, Novo, OneRing, and Euler.

  


See the following resources for more details:

  * [Automated Flash Loan Attack Synthesis (DeFi Security Summit, 2023)](https://www.youtube.com/watch?v=e6VR7Rv-jiY)
  * [FlashSyn: Flash Loan Attack Synthesis via Counter Example Driven Approximation](https://arxiv.org/abs/2206.10708)



  


### Proposed Work

  


Despite the apparent strength of the tool and its open-source license, community-wide adoption remains limited. We believe this is caused by the following shortcomings:

  * Manual, expert-heavy action definition to guide the search
  * Non-trivial setup and protocol-specific configuration



  


We propose to transform FlashSyn into a practical, automated, and extensible security tool for the broader Ethereum community.

  


#### 1\. AI-Augmented Action Extraction

The overhead that necessitates expert use is primarily action extraction and protocol setup. We believe that an LLM can effectively substitute an expert by inferring actions from the codebase, ABIs, transaction history, test suite, and documentation. It can also iteratively refine those actions based on execution feedback from subsequent steps.

  


#### 2\. Tooling, Optimization, and Usability

The goal is to refactor FlashSyn into a clean codebase with a simple interface and smooth developer experience, targeting a workflow as straightforward as:

  


git clone ...

flashsyn run ...

  


#### 3\. Continuous Monitoring

To date, FlashSyn has only been used for one-time analyses of protocols. The techniques it employs are, however, well-suited for continuous post-deployment monitoring. This opens up valuable new directions: detecting vulnerabilities triggered by changes in protocol integrations or configurations, and alerting to risks introduced by shallow liquidity pools. These directions have not been explored in prior work.

  


#### 4\. Reusable Protocol Artifacts

Using FlashSyn for protocol analyses inherently produces reusable artifacts, including protocol deployment configurations and action definitions. We intend to collect these artifacts in the repository and make them available for future reuse and more advanced analyses across the community.
