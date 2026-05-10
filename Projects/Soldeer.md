---
title: "Soldeer"
project_url: "https://qf.giveth.io/project/soldeer"
owner: "m4rio eth"
owner_twitter: "mario_eth"
tags: ["solidity-tooling", "infrastructure"]
categories: ["tech"]
donation_count: 22
total_usd_donated: 276.58
updates_count: 1
---

# Soldeer

🔗 **Project:** [https://qf.giveth.io/project/soldeer](https://qf.giveth.io/project/soldeer)
👤 **Owner:** m4rio eth
🐦 **Twitter:** [@mario_eth](https://x.com/mario_eth)

## Social Media
- 🐙 [Github](https://github.com/mario-eth/soldeer)
- 🌐 [Website](https://soldeer.xyz)

## Donation Addresses
- `0xc8e2806a97413b5496a1ba6050b517cc98d0efca`

## Tags
[[Tags/solidity-tooling|#solidity-tooling]]  [[Tags/infrastructure|#infrastructure]]


## Donations

> **22 donations** · **Total: $276.58 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/duha duha]] | Ethereum | TIK | $50.00 | 2026-05-04 |
| [[Donors/0x59bc675d46fb47d9ddde2305af78da268b931998]] | Ethereum | FINN | $42.69 | 2026-05-05 |
| [[Donors/Dyma Budorin]] | Ethereum | ETH | $23.76 | 2026-05-05 |
| [[Donors/0x4badcd537b675812787f77075cdc0e1e82f7f8f5]] | Ethereum | USDC | $15.62 | 2026-05-08 |
| [[Donors/0x6f97cb7e130d6c56c0bc7cf35fcea07e33afac83]] | Ethereum | TIK | $15.00 | 2026-05-05 |
| [[Donors/john ChainSecurity]] | Ethereum | USDC | $12.50 | 2026-05-04 |
| [[Donors/Gosuto Inzasheru]] | Gnosis | GNO | $12.24 | 2026-04-24 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | TIK | $11.00 | 2026-05-06 |
| [[Donors/0x9cea0b05eedb18cdeb041a7832646a139cf8a990]] | Ethereum | TIK | $10.00 | 2026-05-09 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $10.00 | 2026-05-08 |
| [[Donors/devtooligan]] | Base | USDC | $10.00 | 2026-05-06 |
| [[Donors/0xc189271ecfa140ccc6ab23a280f6f0ea10316048]] | Ethereum | FINN | $9.26 | 2026-05-09 |
| [[Donors/0x57d8610ca8e1a6d04ec9dbdc7fc4f32424ca1125]] | Ethereum | FINN | $5.45 | 2026-04-28 |
| [[Donors/0x89f0f5f13208a89499e0b2f01427df044d51ee1d]] | Ethereum | USDC | $5.00 | 2026-04-24 |
| [[Donors/0x9cea0b05eedb18cdeb041a7832646a139cf8a990]] | Ethereum | FINN | $2.32 | 2026-05-09 |
| [[Donors/Cotabe Moral]] | Optimism | USDGLO | $2.00 | 2026-04-23 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x5f88129df411429e5dc15b8fa5ce5cac87eeaecb]] | Gnosis | WETH | $1.02 | 2026-04-29 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.00 | 2026-05-03 |
| Anonymous | Ethereum | USDC | $20.00 | 2026-05-08 |
| Anonymous | Ethereum | FINN | $11.62 | 2026-04-29 |
| Anonymous | Ethereum | USDC | $5.00 | 2026-04-29 |

## Categories
**Tags:** tech
**Main:** Technology

## Description

Soldeer is a lightweight package manager for Solidity that focuses on fixing one of the most painful and underdeveloped parts of the ecosystem: dependency management.

  


Today, most Solidity projects depend on a mix of Git submodules, manual imports, or npm-based setups. In practice, that leads to brittle builds, unclear versioning, and a lot of time wasted debugging dependency issues instead of writing contracts. Soldeer introduces a clean, native approach to handling dependencies in a way that actually fits how smart contracts are built and deployed.

  


With Soldeer, developers can install and manage dependencies in a deterministic way. For example, instead of adding a Git submodule for a library like OpenZeppelin and hoping everyone on the team keeps it in sync, you can simply declare it as a dependency and lock its version. That means every developer and every CI run uses the exact same code, eliminating “it works on my machine” issues.

  


It also supports pulling dependencies from multiple sources. You can install a package from a registry, a GitHub repository, or even a zipped release. For instance, if you want to depend on a specific commit of a protocol, you can pin that exact version and be confident it won’t change underneath you. Updating is just as straightforward — bump the version, review the diff, and move forward without manually reconfiguring your repo.

  


Another key improvement is reproducibility. Soldeer introduces proper lockfiles, so builds are deterministic by default. This is especially important in smart contract environments, where even small changes in dependencies can have security or financial implications.

  


The tool is written in Rust and integrates seamlessly with Foundry, so it fits naturally into existing workflows without adding overhead. You don’t need to switch ecosystems or adopt heavy tooling — it’s designed to stay lightweight while solving a real problem.

  


Overall, Soldeer brings structure and reliability to Solidity dependency management. Instead of relying on ad-hoc Git setups and implicit assumptions, it gives developers a clear, consistent way to define, share, and reproduce their dependencies — closer to what mature ecosystems already take for granted.
