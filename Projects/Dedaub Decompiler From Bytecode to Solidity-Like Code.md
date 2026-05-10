---
title: "Dedaub Decompiler: From Bytecode to Solidity-Like Code"
project_url: "https://qf.giveth.io/project/dedaub-decompiler:-from-bytecode-to-solidity-like-code"
owner: "Ivan Bermejo"
owner_twitter: "Ibermejocatalan"
twitter: "https://x.com/dedaub"
tags: ["evm", "static-analysis"]
categories: ["research", "tech"]
donation_count: 21
total_usd_donated: 261.12
updates_count: 1
---

# Dedaub Decompiler: From Bytecode to Solidity-Like Code

🔗 **Project:** [https://qf.giveth.io/project/dedaub-decompiler:-from-bytecode-to-solidity-like-code](https://qf.giveth.io/project/dedaub-decompiler:-from-bytecode-to-solidity-like-code)
👤 **Owner:** Ivan Bermejo
🐦 **Twitter:** [@Ibermejocatalan](https://x.com/Ibermejocatalan)

## Social Media
- 🐦 [Twitter](https://x.com/dedaub)
- 💼 [Linkedin](https://www.linkedin.com/company/dedaub/posts/?feedView=all)
- 🌐 [Website](https://dedaub.com/)
- 🔗 [Youtube](https://www.youtube.com/@web3-security-dedaub)

## Donation Addresses
- `0xf5da01d6affef5af0e326bff01b6a1c2bd93c046`

## Tags
[[Tags/evm|#evm]]  [[Tags/static-analysis|#static-analysis]]

## Related QF Projects
- [[Projects/SCAR AI Retrieval for Smart Contract Security|SCAR: AI Retrieval for Smart Contract Security]]


## Donations

> **21 donations** · **Total: $261.12 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xd6b66609e5c05210be0a690ab3b9788ba97afa60]] | Ethereum | ETH | $116.74 | 2026-05-04 |
| [[Donors/Pietro Carta ChainSecurity]] | Ethereum | USDC | $20.00 | 2026-05-04 |
| [[Donors/0x2e2da2428469c48e14e3c11d53f8b4ea078da939]] | Ethereum | TIK | $15.00 | 2026-05-06 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | FINN | $11.47 | 2026-05-07 |
| [[Donors/0xdfef68b86eff06691e3edfaebf620c84eb86f0e3]] | Arbitrum | USDC | $10.04 | 2026-05-07 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $10.00 | 2026-05-08 |
| [[Donors/0x63b540193d0a411fa710f5138412a561322914ae]] | Ethereum | FINN | $9.42 | 2026-05-06 |
| [[Donors/0x14f18a92d6ba49b9fbe1223a861493a38dd38576]] | Ethereum | FINN | $9.38 | 2026-05-03 |
| [[Donors/0xbcbc63d0841811f403fbb04cfa164806bf189051]] | Ethereum | ETH | $7.21 | 2026-05-07 |
| [[Donors/0x9cea0b05eedb18cdeb041a7832646a139cf8a990]] | Ethereum | TIK | $5.00 | 2026-05-09 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $5.00 | 2026-05-07 |
| [[Donors/Simon  ChainSecurity]] | Ethereum | USDC | $5.00 | 2026-05-09 |
| [[Donors/0x9df582f558f2994e6c7bd1c8c39097a160bea072]] | Base | USDC | $5.00 | 2026-05-07 |
| [[Donors/0x63b540193d0a411fa710f5138412a561322914ae]] | Ethereum | FINN | $4.72 | 2026-05-04 |
| [[Donors/0xd2b73492f5fd65ad9ee39788cf51a94f54621a17]] | Ethereum | FINN | $4.71 | 2026-05-06 |
| [[Donors/0xf9aa490e4581a4029762a170e9b16959f846afcf]] | Polygon | USDC | $3.00 | 2026-05-04 |
| [[Donors/0x9cea0b05eedb18cdeb041a7832646a139cf8a990]] | Ethereum | FINN | $2.32 | 2026-05-09 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | FINN | $2.32 | 2026-05-07 |
| [[Donors/0xd39dc38225e642f09eb964d76c85b32ef097bb0d]] | Base | USDC | $0.10 | 2026-05-06 |
| Anonymous | Ethereum | TIK | $10.00 | 2026-05-10 |
| Anonymous | Ethereum | FINN | $4.70 | 2026-05-06 |

## Categories
**Tags:** research, tech
**Main:** Technology

## Description

# Dedaub Decompiler: From Bytecode to Solidity-Like Code

Free EVM bytecode decompilation infrastructure for Ethereum security research.

## The problem

In the last 12 months, approximately 83M smart contracts deployed across Ethereum, Binance, Base, Arbitrum, Polygon, Avalanche, Optimism, and Blast, have no verified source code.

When one of these contracts holds value, is exploited, or interacts with another project, the only way to understand what it actually does is to decompile its bytecode.

**Why this matters for Ethereum security**  

A large portion of onchain activity relies on contracts with no publicly available source code, creating blind spots in security and risk assessment. Understanding behavior and responding to exploits, therefore, depends on analyzing raw bytecode rather than developer-provided sources.

**Hack response.** This becomes critical during exploits. Every time a major hack happens, researchers need to inspect the attacker’s contracts immediately. Attackers usually do not publish source code, so decompilation is often the only way to understand the exploit path, identify copied infrastructure, and support real-time incident response.

**Bots and MEV.** The same constraint applies beyond hacks. Bots and MEV strategies are routinely deployed without verified source code, often deliberately to obscure behavior. As a result, assessing risk, detecting malicious patterns, and understanding interactions in real time also depend on reading and decompiling bytecode.

## How Dedaub Decompiler addresses this security visibility issue

Because understanding smart contract logic without source code is critical for security, the Dedaub Decompiler has become widely used over the years. It enables researchers to reconstruct and analyze contract behavior directly from bytecode at scale.

Today, the Dedaub Decompiler has over 12,000 registered users. Any registered user, including free users, can search smart contracts deployed on Ethereum, Binance, Base, Arbitrum, Polygon, Avalanche, Optimism, Blast, and visualize a Solidity-like version to understand the logic.

**Fast and comprehensive.** Contracts are indexed and decompiled within minutes across major chains.

**High-quality reconstruction.** Recovers most contract logic, enabling meaningful analysis without source code.

**Accessible and real-time.** Free access removes friction during incidents and supports immediate investigation.

The Dedaub decompiled smart contract database spans back to the very early days of the Ethereum ecosystem. The oldest block in the database is **47205** , timestamped **7 August 2015 at 08:26:34 UTC**. Just 8 days after the Ethereum mainnet genesis block (30 July 2015). See the decompiled view: <https://app.dedaub.com/ethereum/address/0xc669eaad75042be84daaf9b461b0e868b9ac1871/decompiled-yul> and the corresponding Etherscan page: <https://etherscan.io/address/0xc669eaad75042be84daaf9b461b0e868b9ac1871>

**Sustaining an Almost Public Good: Ongoing R &D and Infrastructure Investment**

Although the Dedaub Decompiler operates as an almost public good with free access for any registered user, the cost of sustaining the service is completely self-funded. Maintaining and improving it requires continuous investment in both research and infrastructure, with an estimated annual cost of around $500K, including researcher support and the infrastructure needed to host and maintain the database. 

Over the years, Dedaub has advanced EVM decompilation through a combination of peer‑reviewed research and production engineering.

Core areas include:

**Core EVM decompiler research in progress:** improvements to reconstruction quality and scalability.

**Static analysis algorithms:** Contributions to function boundary reconstruction and EVM‑tuned context sensitivity (e.g., _The Incredible Shrinking Context… in a Decompiler Near You_ <https://dl.acm.org/doi/10.1145/3728935>).

**Storage layout recovery.** Precise static identification of Ethereum storage variables (e.g., _Precise Static Identification of Ethereum Storage Variables_ <https://arxiv.org/abs/2503.20690>).

**Engineering features: AI-based** source reconstruction, additional representations such as Yul, and continuous expansion to new networks.

Because reconstructing contract logic without source code is critical, the Dedaub Decompiler is widely relied upon across the ecosystem. If Dedaub were to stop operating, access to large-scale decompiled data could disappear; community funding helps reduce this risk.

## Technical strengths of Dedaub’s decompilation approach

The EVM exposes only low-level bytecode with no explicit functions, types, or structured control flow, making reliable reconstruction inherently hard. Traditional decompilers rely on symbolic execution, which does not scale to real-world contracts due to path explosion and compiler optimizations, resulting in low coverage.

Dedaub takes a different approach: advanced static analysis that over-approximates all executions while remaining scalable through context sensitivity. Its core innovation, introduced in Gigahorse and formalized in Elipmoc, treats calls and returns asymmetrically, recording context on entry and discarding it on exit, achieving precision without exponential blowup.

Elipmoc enables recovery of function boundaries, control flow, and storage layout at scale, delivering significantly higher accuracy than prior tools. The result is a near-complete reconstruction of deployed contract logic, enabling dependable analysis even when no source code exists.

  * If you want to go deeper, check out: <https://dedaub.com/blog/gigahorse-thorough-declarative-decompilation-of-smart-contracts/>
  * <https://dedaub.com/blog/elipmoc-advanced-decompilation-of-ethereum-smartcontracts/>
  * [**https://youtu.be/fZUzBGA37Hs**](https://youtu.be/fZUzBGA37Hs)** **



## Why are we asking for your support?

We have submitted a funding request via Giveth (giveth.io) under the umbrella of The DAO Fund (thedao.fund) to do even more for the community. With proper financial support, we can expand the Dedaub decompiler database both vertically and horizontally. 

**Expand chain coverage.** Increase the number of supported chains from 8 (Ethereum, Binance, Base, Arbitrum, Polygon, Avalanche, Optimism, Blast) to cover up to 95% of EVM activity, including for instance Monad, Hyperliquid, and Tron.

**Extract more information from bytecode.** Expand the use of AI to reconstruct cleaner, more readable Solidity-like representations from decompiled output, reducing low-level artifacts and bringing them closer to developer-intended logic.

**Connect the dots between smart contracts.** Expand the ML-powered “find similar public function” feature to help security researchers identify similar behavior across contracts using LLM-based function-level pattern detection.

## What donations fund

Delivering the three expansions below over 12 months adds approximately $100,000 to $150,000 to the infrastructure Dedaub already runs. Dedaub continues investing its own resources throughout.

### Under $25k: Remove AI analysis limits.

Scales the LLM-assisted analysis layer, raising or removing the current cap on daily contract analysis for free users. Researchers can run full AI-assisted inspections across large contract sets without interruption, including during active incidents.

### $25k to $75k: Full coverage for more chains

Funds infrastructure to onboard additional EVM chains: indexing pipelines, storage, and continuous analysis. Brings mainnet-level decompilation and static analysis to L2 ecosystems where exploits are increasingly concentrated.

### $75k+: Similarity analysis at ecosystem scale

Expands the ML-based “find similar” feature across all contracts and supported chains. Detects reused code patterns, forks, and previously exploited logic at scale using LLM-derived embeddings over decompiled bytecode.

## Commitments

The free tier at app.dedaub.com remains free for the duration of the funded period and beyond. No previously free feature will be paywalled. If the community demonstrates clear backing, Dedaub will open-source components of the decompiler codebase. A public retrospective on fund allocation and measurable outcomes will be published within 60 days of the round closing.

## The Platform
