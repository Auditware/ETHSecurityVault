---
title: "Verifereum"
project_url: "https://qf.giveth.io/project/verifereum"
owner: "Benny Lada"
twitter: "https://x.com/Verifereum"
tags: ["formal-verification", "smart-contract"]
categories: ["computer science", "research", "tech"]
donation_count: 23
total_usd_donated: 211.79
updates_count: 1
---

# Verifereum

🔗 **Project:** [https://qf.giveth.io/project/verifereum](https://qf.giveth.io/project/verifereum)
👤 **Owner:** Benny Lada

## Social Media
- 🐦 [Twitter](https://x.com/Verifereum)
- 🐙 [Github](https://github.com/verifereum/verifereum)
- 🌐 [Website](https://verifereum.org/)

## Donation Addresses
- `0x65fe89a480bdb998f4116daf2a9360632554092c`

## Tags
[[Tags/formal-verification|#formal-verification]]  [[Tags/smart-contract|#smart-contract]]

## Related QF Projects
- [[Projects/Vyper|Vyper]]


## Donations

> **23 donations** · **Total: $211.79 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/pcaversaccio 🫡]] | Ethereum | DAI | $49.98 | 2026-04-27 |
| [[Donors/0x2e2da2428469c48e14e3c11d53f8b4ea078da939]] | Ethereum | TIK | $25.00 | 2026-05-06 |
| [[Donors/0x59aa8eea9bec5b00640f73cf169f05ff00459b9f]] | Ethereum | TIK | $20.00 | 2026-05-05 |
| [[Donors/Pietro Carta ChainSecurity]] | Ethereum | USDC | $20.00 | 2026-05-04 |
| [[Donors/Hubert  ChainSecurity]] | Ethereum | USDC | $20.00 | 2026-05-05 |
| [[Donors/0x12846be7b801c745cb62ac41423894b2d97185d0]] | Ethereum | TIK | $16.00 | 2026-05-08 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | FINN | $11.47 | 2026-05-07 |
| [[Donors/0xee0b53ac9578cbc6e0cee0ac6e18cfb7118b5cb3]] | Ethereum | ETH | $10.02 | 2026-05-04 |
| [[Donors/0x8103e115deac098104c40c0a669d626830158304]] | Ethereum | USDC | $5.00 | 2026-05-07 |
| [[Donors/0x7c41489e78f6b690eb6eb08fe43ab2bf3d017462]] | Ethereum | FINN | $4.63 | 2026-04-27 |
| [[Donors/Cotabe Moral]] | Optimism | USDGLO | $3.00 | 2026-04-23 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | FINN | $2.32 | 2026-05-07 |
| [[Donors/0x1177aba531463cadd9c505d97fc4149fa693045e]] | Ethereum | USDC | $2.00 | 2026-04-24 |
| [[Donors/0x0b5f8b66e1ed03b465af5b94802a1a233cf42baa]] | Ethereum | USDC | $1.50 | 2026-04-24 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.20 | 2026-05-03 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0xbea26de685ef828b60ca53b40ecc9bab35645fdf]] | Optimism | USDC | $1.00 | 2026-04-26 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| [[Donors/0x1ca30326f0ab9ab8f30435d32ea39c275c660d9e]] | Arbitrum | ETH | $0.23 | 2026-04-27 |
| Anonymous | Ethereum | USDC | $5.10 | 2026-04-25 |
| Anonymous | Ethereum | FINN | $4.70 | 2026-05-06 |
| Anonymous | Ethereum | ETH | $4.55 | 2026-04-28 |
| Anonymous | Ethereum | USDC | $2.00 | 2026-04-28 |

## Categories
**Tags:** computer science, research, tech
**Main:** Technology

## Description

## Mathematically Verified Ethereum Smart Contracts

Verifereum is an open-source project that brings mathematical rigour to [Ethereum](https://ethereum.org/) smart contract verification. Using the [HOL4 theorem prover](https://hol-theorem-prover.org/), we’re building tools to prove the correctness of smart contracts and eliminate entire classes of vulnerabilities.

  


### Why Verifereum Matters

  * **Beyond Traditional Auditing** : While audits can find bugs, mathematical verification proves the absence of entire classes of vulnerabilities
  * **High Stakes, Higher Standards** : With billions of dollars secured by smart contracts, formal verification offers the strongest security guarantees possible
  * **Perfect Fit** : Ethereum’s deterministic execution model, where additionally code is expensive so applications are small, makes it an ideal candidate for formal verification



###   


### Technical Focus Areas

We’re currently working on three main tracks:

  1. **EVM Base Layer**


  * Refining our formal EVM specification
  * Implementing precompiles (ecRecover, etc.)
  * Optimizing execution in logic
  * Ensuring test suite compliance


  1. **Decompilation Pipeline**


  * Building Hoare/Separation logic for EVM bytecode
  * Creating verification examples
  * Developing decompilation automation


  1. **Vyper Verification**


  * Formalizing Vyper semantics
  * Implementing compiler frontend in logic
  * Building verification infrastructure



##   


### Our Approach

  * **Foundation** : Formal model of the EVM in HOL4 (Higher-Order Logic)
  * **Methodology** : Operational semantics via definitional interpreter
  * **Validation** : Complete EVM test suite compliance
  * **Verification** : Program logic for smart contract correctness proofs
  * **Implementation** : Focus on decompilation and compiler verification
