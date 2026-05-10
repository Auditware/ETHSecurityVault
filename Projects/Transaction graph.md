---
title: "Transaction graph"
project_url: "https://qf.giveth.io/project/transaction-graph"
owner: "Tas Nak"
owner_twitter: "ProgrammerSmart"
twitter: "https://x.com/ProgrammerSmart"
tags: ["on-chain-investigation"]
categories: ["computer science", "education-tech", "public-goods", "research", "tech"]
donation_count: 8
total_usd_donated: 40.88
updates_count: 1
---

# Transaction graph

🔗 **Project:** [https://qf.giveth.io/project/transaction-graph](https://qf.giveth.io/project/transaction-graph)
👤 **Owner:** Tas Nak
🐦 **Twitter:** [@ProgrammerSmart](https://x.com/ProgrammerSmart)

## Social Media
- 🐦 [Twitter](https://x.com/ProgrammerSmart)
- 🐙 [Github](https://github.com/t4sk/tx-graph)
- 🌐 [Website](https://tx-graph-eight.vercel.app/)

## Donation Addresses
- `0x27c616d7f90e9a2be28d46f359470f06c41a38f5`

## Tags
[[Tags/on-chain-investigation|#on-chain-investigation]]


## Donations

> **8 donations** · **Total: $40.88 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/duha duha]] | Ethereum | FINN | $18.89 | 2026-05-04 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | FINN | $11.47 | 2026-05-07 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.20 | 2026-05-03 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| [[Donors/0x1ca30326f0ab9ab8f30435d32ea39c275c660d9e]] | Arbitrum | ETH | $0.23 | 2026-04-27 |
| Anonymous | Ethereum | USDC | $5.00 | 2026-04-29 |
| Anonymous | Ethereum | USDC | $2.00 | 2026-04-28 |

## Categories
**Tags:** computer science, education-tech, public-goods, research, tech
**Main:** Community, Education, Technology

## Description

# Project Overview

tx-graph is a transaction visualizer for EVM-compatible chains that converts a transaction hash into an interactive graph, making complex contract interactions easy to explore and understand.

  


# What problem does it solve?

Transactions on EVM chains are difficult to trace and interpret, especially when they involve multiple contract interactions. While existing tracers provide low-level execution details, they require significant time and effort to piece together how contracts are connected and interact.

  


# Solution

The solution is to combine tracer with a graph that maps out how contracts interact within a transaction.

  


## Additional features

  * One click download all the contract codes that were executed in a transaciton
  * [Foundry](https://www.getfoundry.sh/) integration
  * A smart contract developer or a security engineer can execute a Foundry test and see the execution using this tool. This will help them quickly understand how a protocol is structured.



  


# Existing Solutions

While existing tools such as [tracerflow.xyz](tracerflow.xyz) provide graph-based views of transaction traces, they are optimized for low-level execution detail rather than high-level understanding. By representing each function call as a separate node, they produce fragmented graphs that obscure the relationships between contracts. This limits their usefulness for quickly understanding transaction structure, highlighting the need for a more intuitive, contract-centric visualization approach.

  


In addition, existing solutions lack Foundry integration.

  


# How does it aid security?

It aids security by helping developers and security researchers understand what the transaction did.

For example, [Balancer hack in 2025](https://etherscan.io/tx/0x53fe7ef190c34d810c50fb66f0fc65a1ceedc10309cf4b4013d64042a0331156) has over 1700 calls to contracts, involving almost 100 contracts. As you can imagine, this transaction is difficult to understand and time consuming to manually draw out on a white board.

  


tx-graph instantly graphs out the transaction, helping a security researcher quickly understand how an exploit was executed.

  


# How does it aid Ethereum ecosystem?

The tool can also be used for educational purpose. If an user wants to learn how a protocol works, the user can paste a transaction hash that is relevant to the protocol to see how the protocol works.

It enables anyone to learn how protocols function by exploring real transactions,

  


# Proof of Work

  * Website is hosted [here](https://tx-graph-eight.vercel.app/)
  * [Example of Foundry integration](https://x.com/ProgrammerSmart/status/2024094673292116223)
  * [Graph of a hack with 2843 calls](https://x.com/ProgrammerSmart/status/2013234464017567779)



  


# Use of Funds

Funds will primarly cover infrastructure costs (database and RPC services). Remaining funds will support continued development and feature improvements. The project is currently maintained by myself.

With or without funding, I will continue developement as it serves as a core tool in my workflow.
