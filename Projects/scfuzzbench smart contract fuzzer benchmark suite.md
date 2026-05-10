---
title: "scfuzzbench: smart contract fuzzer benchmark suite"
project_url: "https://qf.giveth.io/project/scfuzzbench:-smart-contract-fuzzer-benchmark-suite"
owner: "Antonio Viggiano"
owner_twitter: "aviggiano"
tags: ["fuzzing", "smart-contract"]
donation_count: 31
total_usd_donated: 610.00
updates_count: 1
---

# scfuzzbench: smart contract fuzzer benchmark suite

🔗 **Project:** [https://qf.giveth.io/project/scfuzzbench:-smart-contract-fuzzer-benchmark-suite](https://qf.giveth.io/project/scfuzzbench:-smart-contract-fuzzer-benchmark-suite)
👤 **Owner:** Antonio Viggiano
🐦 **Twitter:** [@aviggiano](https://x.com/aviggiano)

## Social Media
- 🐙 [Github](https://github.com/scfuzzbench/scfuzzbench)
- 🌐 [Website](https://scfuzzbench.com)

## Donation Addresses
- `0x20f4614a502d61d119a461fb6e320f6f54953adc`

## Tags
[[Tags/fuzzing|#fuzzing]]  [[Tags/smart-contract|#smart-contract]]


## Donations

> **31 donations** · **Total: $610.00 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x674a1634ccd3bec188898201095776257beef2e9]] | Arbitrum | USDC.e | $220.00 | 2026-04-29 |
| [[Donors/0xc6308909a83fad9e5de9df883e1d8a3b7141d90a]] | Ethereum | USDC | $99.98 | 2026-05-09 |
| [[Donors/0xc5ce30688aa9e0556bb3e4f7c2f8623bc2f1f96b]] | Optimism | ETH | $61.02 | 2026-04-30 |
| [[Donors/0x1ffa24febecf764daff68507113ad6aff16acd08]] | Ethereum | FINN | $11.44 | 2026-05-01 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $10.00 | 2026-05-08 |
| [[Donors/0x8ea0e7015877064bce6372b3f95d0b7259566750]] | Ethereum | USDC | $10.00 | 2026-04-24 |
| [[Donors/0xc189271ecfa140ccc6ab23a280f6f0ea10316048]] | Ethereum | FINN | $9.26 | 2026-05-09 |
| [[Donors/0x89f0f5f13208a89499e0b2f01427df044d51ee1d]] | Ethereum | USDC | $5.00 | 2026-04-24 |
| [[Donors/0x440f05c6e359e3a4ab8765e492d9ae2d66c913b4]] | Ethereum | USDC | $5.00 | 2026-04-24 |
| [[Donors/0x83eccb05386b2d10d05e1baea8ac89b5b7ea8290]] | Gnosis | USDC | $5.00 | 2026-04-24 |
| [[Donors/0xf5034f28b3f0cec6c108d5cdf8f21c4f24492a6c]] | Gnosis | XDAI | $2.50 | 2026-05-07 |
| [[Donors/0xff3eb1ce0f105a01445384c6eb8f7ef6f1c902c9]] | Arbitrum | USDC.e | $1.85 | 2026-04-29 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $1.50 | 2026-05-07 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/Alexandre  Melo]] | Ethereum | USDC | $1.00 | 2026-04-29 |
| [[Donors/0x92ac69308b8794ececffa804278b252dc77982c0]] | Ethereum | FOX | $0.32 | 2026-05-07 |
| [[Donors/0xb53460f73b5cedf6345108cba73f32b9da09172c]] | Arbitrum | USDC | $0.00 | 2026-05-04 |
| Anonymous | Ethereum | TIK | $50.00 | 2026-05-06 |
| Anonymous | Ethereum | TIK | $27.00 | 2026-05-05 |
| Anonymous | Ethereum | FINN | $14.35 | 2026-05-06 |
| Anonymous | Ethereum | USDC | $14.00 | 2026-05-02 |
| Anonymous | Ethereum | FINN | $11.75 | 2026-04-26 |
| Anonymous | Ethereum | TIK | $10.00 | 2026-05-10 |
| Anonymous | Ethereum | USDC | $10.00 | 2026-05-07 |
| Anonymous | Ethereum | USDC | $5.10 | 2026-04-25 |
| Anonymous | Ethereum | USDC | $5.00 | 2026-05-07 |
| Anonymous | Ethereum | USDC | $5.00 | 2026-04-28 |
| Anonymous | Base | ETH | $5.00 | 2026-04-24 |
| Anonymous | Ethereum | FINN | $4.51 | 2026-04-30 |
| Anonymous | Ethereum | FINN | $2.33 | 2026-04-24 |
| Anonymous | Ethereum | USDC | $1.00 | 2026-04-30 |

## Description

**scfuzzbench** is a benchmark suite for evaluating smart contract fuzzers.

  


# **Who**

We are security researchers, protocol engineers, and open-source contributors focused on improving the safety of blockchain applications. The project is led by experienced practitioners in smart contract security and fuzz testing, with strong roots in real-world protocol auditing and vulnerability research. The core maintainer is [Antonio Viggiano](https://github.com/aviggiano), and the project has received valuable contributions from [Gustavo Grieco](https://github.com/gustavo-grieco), [alpharush](https://github.com/0xalpharush), [Rappie](https://github.com/rappie), and [Alex The Entreprenerd](https://github.com/GalloDaSballo).

  


# **What**

**scfuzzbench** provides a standardized benchmark suite and methodology to measure the effectiveness of smart contract fuzzers, especially for **stateful invariant testing** , one of the most important techniques for discovering complex multi-transaction vulnerabilities in DeFi protocols and blockchain infrastructure. The platform allows researchers and tool builders to compare fuzzers using reproducible runs, shared datasets, transparent methodology, and publicly accessible results. As of now, we support Aave v4, Superform v2 periphery, Liquity v2 Governance, and Nerite as benchmark targets.

  


# **Why**

Today, the blockchain ecosystem secures billions of dollars in assets, yet security tooling is still fragmented and difficult to compare fairly. Different fuzzers report results using different metrics, environments, and assumptions, making it hard for researchers, developers, and auditors to know which tools actually perform best. **scfuzzbench** solves this by creating an objective benchmark that drives scientific progress, improves transparency, and accelerates the discovery of vulnerabilities before attackers do.

  


# **Where**

The project is fully open source and publicly accessible online at [scfuzzbench.com](https://scfuzzbench.com), with benchmark definitions, methodology, and results available to the community. It is currently in the beta stage and is being constantly peer-reviewed before official benchmark results can be shared with the world.

  


# **How**

Donations directly support cloud infrastructure for benchmark runs, expansion of benchmark datasets, integration of new fuzzing tools, reproducibility pipelines, result dashboards, and research collaborations with the broader blockchain security community.

  


# **When**

Funding now will help us scale benchmark coverage in 2026, onboard additional open-source fuzzers, and establish **scfuzzbench** as the reference benchmark for smart contract security tooling.

By supporting **scfuzzbench** , donors help strengthen the security foundations of Web3 and protect users, protocols, and ecosystems from catastrophic vulnerabilities.

  


  


_Sample result, not ready for publication_
