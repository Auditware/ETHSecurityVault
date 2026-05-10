---
title: "Self-Custodial Agent Authorization for Ethereum"
project_url: "https://qf.giveth.io/project/self-custodial-agent-authorization-for-ethereum"
owner: "Gabby Vorbeck"
owner_twitter: "gabbyvorbeck"
twitter: "https://x.com/FunctorNetwork"
tags: ["ai-security", "wallet-security"]
categories: ["financial-services", "infrastructure", "tech"]
donation_count: 25
total_usd_donated: 379.24
updates_count: 1
---

# Self-Custodial Agent Authorization for Ethereum

🔗 **Project:** [https://qf.giveth.io/project/self-custodial-agent-authorization-for-ethereum](https://qf.giveth.io/project/self-custodial-agent-authorization-for-ethereum)
👤 **Owner:** Gabby Vorbeck
🐦 **Twitter:** [@gabbyvorbeck](https://x.com/gabbyvorbeck)

## Social Media
- 🐦 [Twitter](https://x.com/FunctorNetwork)
- 🐙 [Github](https://github.com/functornetwork)
- 🌐 [Website](https://functor.sh/)

## Donation Addresses
- `0xd402016dbccc874002d8b1b9b9cc21485ec52e8d`
- `Gk7uSqD2G9GqfDLGMkrHSw6eFdfp6JYpYeoqFNWG98K5`

## Tags
[[Tags/ai-security|#ai-security]]  [[Tags/wallet-security|#wallet-security]]


## Donations

> **25 donations** · **Total: $379.24 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xcd32111c1ea7ddfb1d02fa26e1bb23381c369d88]] | Ethereum | USDC | $100.01 | 2026-05-07 |
| [[Donors/0xb98a13c39fc4efb98f25785f433ce23e70659bad]] | Arbitrum | USDC | $59.99 | 2026-05-02 |
| [[Donors/Lighthouse Labs]] | Optimism | OP | $41.25 | 2026-05-08 |
| [[Donors/0x5d36a202687fd6bd0f670545334bf0b4827cc1e2]] | Ethereum | SKALE | $23.96 | 2026-05-04 |
| [[Donors/0x1ddc50a8b8ef07c654b4ace65070b0e7acff622b]] | Base | ETH | $23.54 | 2026-05-04 |
| [[Donors/James (jkm.eth)]] | Base | USDC | $20.00 | 2026-05-08 |
| [[Donors/0xab97b372dd33c8a449a8475d82470f5124915cd5]] | Arbitrum | USDC | $20.00 | 2026-05-04 |
| [[Donors/0xc86f7ccee8aad2efc0b25759aa153d5220d341ec]] | Polygon | USDT | $20.00 | 2026-05-07 |
| [[Donors/0x6e20f1b46d4164d707e8342f941302b2197bbe47]] | Base | USDC | $10.00 | 2026-05-04 |
| [[Donors/0x0a08c6196d1fdbad710f64799f06332be6b92937]] | Base | USDC | $5.00 | 2026-04-24 |
| [[Donors/0x7a9e7a1fe90e483b4b60c569068912cbd9879d12]] | Base | ETH | $3.48 | 2026-04-23 |
| [[Donors/Blossom Labs]] | Optimism | ETH | $2.33 | 2026-04-23 |
| [[Donors/0x91c6ed9df457172b4731b7bc17f4d71ccdc85ebd]] | Ethereum | ETH | $2.28 | 2026-05-08 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| [[Donors/Kresimir Katusic]] | Optimism | USDC | $0.00 | 2026-04-29 |
| [[Donors/0x0afbea5597875c33047ab0004575f636e652c49e]] | Ethereum | LINK | $0.00 | 2026-05-06 |
| Anonymous | Arbitrum | USDC | $10.00 | 2026-04-27 |
| Anonymous | Base | USDC | $10.00 | 2026-04-24 |
| Anonymous | Arbitrum | USDC | $7.00 | 2026-05-04 |
| Anonymous | Base | USDC | $5.00 | 2026-04-27 |
| Anonymous | Ethereum | USDC | $5.00 | 2026-04-28 |
| Anonymous | Base | USDC | $5.00 | 2026-05-07 |
| Anonymous | Ethereum | FINN | $2.33 | 2026-04-24 |
| Anonymous | Ethereum | USDC | $1.00 | 2026-05-05 |

## Categories
**Tags:** financial-services, infrastructure, tech
**Main:** Economics & Infrastructure, Finance, Technology

## Description

## **TLDR**

Self-custodial authorization for agentic workflows that move capital onchain. Building a keystore layer: one signer registry anchored to Ethereum. Programmable permissions. Global revocation. Native account recovery. Works across every L2, no bridges, no redeployments per chain. GPL-3, open source.

  


## **The Problem**

Wallets have always forced a trade-off: you can have security, or you can have self-custody. Not both.

  * **One key controls everything.** Lose it, the funds are gone. Expose it, there is no revocation, no fallback, no way to limit the damage. The only escape is handing control to a custodian.
  * **No scope, no hierarchy.** A $10 transfer and a $50M protocol deposit go through the exact same signing process. There is no way to assign different roles or permissions to different signers, the way a Google Workspace admin can grant an employee edit access without giving them ownership.
  * **No native recovery for self-custodial accounts.** Lose your keys and you lose your wallet. The infrastructure to attach guardians, rotate credentials, and recover access has never existed for accounts you fully own. Until now.
  * **And it affects agentic workflows too.** AI agents moving funds onchain have no way to operate under scoped, revocable permissions that live outside the agent. The same security gap that affects human wallet holders blocks every agentic workflow that touches onchain capital.



  


Functor introduces a security hierarchy for self-custodial wallets: multiple signers, programmable permissions, native recovery, and instant revocation, without giving up custody.

  


## **What We're Building**

Functor is the [keystore layer](https://functor.sh/architecture) for Ethereum: a dedicated signer network with a single source of truth anchored to Ethereum, readable by any chain. It’s self-custodial authorization that agentic workflows need to move onchain capital: humans retain control, agents execute under scoped permissions.

The core idea is separating "who can act" from "where the assets are." Instead of each chain storing its own copy of who can sign, all chains reference one source of truth. This means:

  * **Multiple signers per wallet.** Add a passkey, a hardware key, a guardian. Each with its own permissions and scope.
  * **Programmable permissions.** Spend limits, time windows, contract restrictions, set once and enforced everywhere.
  * **Native account recovery.** Attach guardians and recover access the way you would reset a forgotten password, without trusting a custodian.
  * **Global revocation.** Rotate a compromised key once. It reflects across every chain instantly.



  


It works across all wallet types: smart contract wallets, EOAs, multisigs, and keystore-native wallets. Signature schemes can include passkeys, hardware keys, and other standards, so teams are not locked into a single signing method. 

Functor directly addresses 5 of 6 UX pain points identified in Ethereum's[ 1TS initiative](https://ethereum.org/trillion-dollar-security/#ux):

  * **Key management**
  * **Permission management**
  * **Fragmentation**
  * **Blind signing**
  * **Compromised web interfaces**



  


Demo: ERC-7579 smart account with native multi-passkey recovery via Functor Keystore: <https://www.loom.com/share/daf68134cd46458c965fbaad136cb28d>

Docs: <https://docs.functor.sh>

  


## **Who Benefits**

  * **Power users and individuals:** Add multiple devices as signers on one wallet. Lose your phone, revoke that signer, keep using your laptop. No seed phrase. No starting over.
  * **Teams and asset managers:** Assign different permissions per team member, set programmable execution rules, and maintain a clear audit trail across chains.
  * **Agent wallets and agentic workflows:** Give agents scoped permissions, set spending limits, restrict which contracts they can touch, and revoke access instantly if a key is compromised.
  * **Wallet and smart account infrastructure:** Any team building on ERC-7579 can integrate Functor to offer unified signer management and native recovery to their users, without per-chain redeployment.



  


## **How Funds Are Used**

Security audit of the Functor Keystore. The protocol is fully open source and the audit is a prerequisite for public release, so the ecosystem can build on it reliably.

**In QF, every unique donor increases the matching pool allocation. If this infrastructure matters to you, a small donation has real weight.**

**Thank you for supporting open-source Ethereum security.**
