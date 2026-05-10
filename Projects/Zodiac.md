---
title: "Zodiac"
project_url: "https://qf.giveth.io/project/zodiac"
owner: "Auryn Macmillan"
owner_twitter: "auryn_macmillan"
twitter: "https://twitter.com/zodiaceco"
tags: ["governance-security", "multisig"]
categories: ["computer science", "research", "tech"]
donation_count: 14
total_usd_donated: 51.81
updates_count: 1
---

# Zodiac

🔗 **Project:** [https://qf.giveth.io/project/zodiac](https://qf.giveth.io/project/zodiac)
👤 **Owner:** Auryn Macmillan
🐦 **Twitter:** [@auryn_macmillan](https://x.com/auryn_macmillan)

## Social Media
- 🐦 [Twitter](https://twitter.com/zodiaceco)
- 🐙 [Github](https://github.com/gnosisguild/zodiac)
- 🌐 [Website](https://zodiac.eco)

## Donation Addresses
- `0x12beef35025841efccb77d6ee40df86400fdb4bb`

## Tags
[[Tags/governance-security|#governance-security]]  [[Tags/multisig|#multisig]]


## Donations

> **14 donations** · **Total: $51.81 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xee0b53ac9578cbc6e0cee0ac6e18cfb7118b5cb3]] | Ethereum | ETH | $10.02 | 2026-05-04 |
| [[Donors/0xc7cbea8f72d1062efa7f397d098448b0016cc1ac]] | Ethereum | TIK | $7.00 | 2026-05-07 |
| [[Donors/0xf44217a8b6b3f258bffead635c226528aa516aea]] | Gnosis | XDAI | $5.00 | 2026-05-04 |
| [[Donors/0x07e995f06149352015bde16530169cab76ef58fe]] | Ethereum | TIK | $5.00 | 2026-05-03 |
| [[Donors/Ethical Ash]] | Optimism | DAI | $3.00 | 2026-05-08 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | FINN | $2.32 | 2026-05-07 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | FINN | $2.32 | 2026-05-07 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $2.00 | 2026-05-07 |
| [[Donors/0x8fda1daa6a674c1726d1896e3054b9a82d123f12]] | Base | ETH | $1.16 | 2026-05-01 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.00 | 2026-05-03 |
| [[Donors/validator .eth]] | Ethereum | USDC | $1.00 | 2026-05-01 |
| [[Donors/validator .eth]] | Ethereum | USDC | $1.00 | 2026-05-01 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| Anonymous | Ethereum | TIK | $10.00 | 2026-05-10 |

## Categories
**Tags:** computer science, research, tech
**Main:** Technology

## Description

## 🛡️ Zodiac: Open-Source Security Infrastructure for Onchain Entities

  


### 👥 Who We Are

Zodiac is an open-source project developed by Gnosis Guild, a team of smart contract engineers and DAO tooling practitioners building composable, non-custodial infrastructure for onchain organizations. Our work sits at the intersection of Ethereum security and decentralized operations. We build the permissioning primitives that DAOs, protocols, and treasury management teams rely on to stay secure while executing at scale. The Zodiac protocol is already trusted by some of the most consequential organizations in the Ethereum ecosystem, including Safe, ENS DAO, Balancer, Gnosis DAO, and kpk, collectively securing several billion dollars worth of onchain assets.

  


### 🔩 What We've Built

Zodiac is a collection of open-source smart contracts and tooling built according to a composable open standard, freely available at [github.com/gnosisguild/zodiac](https://github.com/gnosisguild/zodiac). It extends systems like Safe with **modular permissions** , **security controls** , and **governance execution** , without sacrificing security or custody.

The core components of the open standard include:

  * **Roles Modifier** — Fine-grained, role-based access control enforced entirely onchain. Defines exactly which contracts can be called, which functions can be invoked, and what parameter constraints apply. Permissions are checked by the smart contract at execution time, not by operational trust or an off-chain service.
  * **Delay Modifier** — Enforces a configurable time delay between when a module initiates a transaction and when it executes, providing a critical window for intervention in the event of a compromised key or malicious proposal.
  * **Scope Guard** — Limits the set of addresses and functions that a module or signer can interact with, preventing unauthorized or out-of-scope transactions at the contract level.
  * **Bridge, Reality, Governor, and Exit Modules** — A suite of governance execution modules enabling cross-chain control, Snapshot-based on-chain execution, OpenZeppelin-style governance, and rage-quit mechanics, all built to the open Zodiac standard.



The library has 481 GitHub stars, 114 forks, and over 608 commits. It is licensed under LGPL-3.0 and has been independently audited by the G0 Group.

  


### ❓ Why It Matters for Ethereum Security

The dominant threat model for DAO and protocol treasuries isn't a smart contract exploit: it's operational risk. Multisigs with overly broad signer access, undocumented delegation practices, and a lack of onchain accountability are responsible for a significant share of value lost and governance failures across the ecosystem. When teams grow, when operations get routine, when signers become bottlenecks, the pressure to expand access increases. And expanded access without constraints means an expanded attack surface.

Zodiac's open-source permissioning layer addresses this directly. By encoding access rules as verifiable, auditable, onchain policies rather than relying on social trust or off-chain systems, Zodiac reduces the risk profile of complex treasury operations without requiring teams to sacrifice efficiency or decentralization. **Security enforced by code is security that can be verified, audited, and trusted by anyone.**

This is foundational Ethereum security infrastructure, protecting more than $2 billion in onchain assets. It is the kind of work that is easy to overlook when nothing goes wrong, and catastrophically visible when something does.

  


### 🌍 Where We Operate

Zodiac contracts are deployed across all major EVM-compatible networks where Safe is supported, including Ethereum Mainnet, Arbitrum, Optimism, Base, Polygon, and Gnosis Chain. As an open standard, the protocol is framework-agnostic and can be used with any programmable account that implements the IAvatar interface, not just Safe. The tooling is permissionlessly available to any developer or organization in the ecosystem.

  


### ⚙️ How Funds Will Be Used

Support through TheDAO Security Fund's ETH Security grant will directly help sustain and extend Zodiac's open-source security infrastructure: continued maintenance of core contracts and SDKs, security audits for Roles and new modules, stronger developer documentation and integration support, and grants for external builders extending the standard.

  


### 📅 When — Status and Roadmap

The Zodiac library is live, audited, and in active production use. Near-term development focus includes expanded parameter constraint tooling in the Roles Modifier, additional audit coverage for new modules, and deeper integration support for teams building on the standard.

**👉 Support open, auditable infrastructure for secure onchain operations.**

_Source code:_[_github.com/gnosisguild/zodiac_](https://github.com/gnosisguild/zodiac) _| Community:_[_discord.gnosisguild.org_](https://discord.gnosisguild.org/)
