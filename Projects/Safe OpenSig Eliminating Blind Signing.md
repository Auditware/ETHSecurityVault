---
title: "Safe OpenSig: Eliminating Blind Signing"
project_url: "https://qf.giveth.io/project/safe-opensig:-eliminating-blind-signing"
owner: "Candide Labs"
twitter: "https://twitter.com/candidelabs/"
tags: ["multisig", "wallet-security"]
donation_count: 5
total_usd_donated: 36.68
updates_count: 1
---

# Safe OpenSig: Eliminating Blind Signing

🔗 **Project:** [https://qf.giveth.io/project/safe-opensig:-eliminating-blind-signing](https://qf.giveth.io/project/safe-opensig:-eliminating-blind-signing)
👤 **Owner:** Candide Labs

## Social Media
- 🐦 [Twitter](https://twitter.com/candidelabs/)
- 🐙 [Github](https://github.com/candidelabs/safe-opensig)
- 🌐 [Website](https://www.candide.dev/opensig)

## Donation Addresses
- `0x338be7628b8f2fb3aaa0fc65f4745a000fb833f1`

## Tags
[[Tags/multisig|#multisig]]  [[Tags/wallet-security|#wallet-security]]


## Donations

> **5 donations** · **Total: $36.68 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xe2e1038a6ea0d9857fdd11835c0ee147563c0835]] | Ethereum | TIK | $25.00 | 2026-05-04 |
| [[Donors/0x057ee041647ae4fe26423830c79ca252d27d7ecb]] | Ethereum | TIK | $5.00 | 2026-05-09 |
| [[Donors/0xd2b73492f5fd65ad9ee39788cf51a94f54621a17]] | Ethereum | FINN | $2.36 | 2026-05-06 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | FINN | $2.32 | 2026-05-07 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $2.00 | 2026-05-07 |

## Description

# Safe OpenSig

## Eliminating Blind Signing for Ethereum's Multisig Signers

  


In February 2025, three Bybit signers reviewed a transaction carefully. Each used a hardware wallet. Each approved it. $1.5 billion was gone.

  


They did nothing wrong. Attackers had compromised the frontend interface months earlier, injecting JavaScript that silently replaced the transaction payload. What each signer saw looked correct. What their hardware signed was a delegatecall handing the attacker full control of the implementation contract. Their Ledgers showed two hashes. Hardware wallets cannot decode complex transactions. They faithfully sign whatever calldata they receive.

  


This is blind signing. And it affects every multisig signer on Ethereum.

  


Every major protocol you interact with, Aave, Arbitrum, ENS, GnosisDAO, Optimism, Compound, is managed by elected stewards approving treasury transactions through Safe. So are the corporate and enterprise treasuries entering Ethereum today. Verification is technically possible but requires expertise most signers don't have. The common approaches are circular: simulating via a browser tool or decoding calldata from the same interface means using the potentially compromised interface to verify the potentially compromised interface. On April 1, 2026, Drift Protocol on Solana lost $285 million the same way.

  


Security Council signers blind signed admin key transfer transactions. Hardware wallets rendered the instructions as raw hex. The admin key to the entire protocol was handed to the attacker. Different chain, same root cause.

  


## What Safe OpenSig does

  


Safe OpenSig is a mobile app that runs on your phone, isolated from your desktop and browser, before you touch your hardware wallet.

  


It simulates the transaction locally using a native Rust EVM implementation (REVM), entirely on-device. It verifies onchain state against multiple independent nodes using Merkle Patricia Tree proofs checked locally. And it generates a pixel-accurate reconstruction of what your Ledger screen will display, so you can confirm the hashes match before committing to anything.

  


Three properties make this different from simulation tools that run in the browser:

  


Isolation. The app runs on a separate device. A compromised browser cannot reach it. A malicious Safe UI cannot feed it altered calldata, because the app fetches transaction data independently.

  


Cryptographic proof. State is not taken on faith from a single RPC endpoint. Merkle proofs are verified locally against multiple nodes. If nodes disagree, you see it before signing.

  


  


Hardware parity. You see exactly what your Ledger will show before you touch it. The hashes you verify on screen match the hashes the hardware will present. The moment of signing becomes confirmation, not discovery.

  


  


  


If Bybit's signers had used this workflow, the simulation would have shown: Operation: DELEGATECALL. New implementation: attacker-controlled address. A signing-ending discrepancy. The transaction stops there.

  


Here it is on a [real transaction](https://x.com/candidelabs/status/2044757460569690611) for Frax Finance, $35M Safe multisig, 3-of-5 threshold, one signer pending on a 17k frxUSD transfer. This is what verifying that transaction looks like, without blind signing.

  


## **Why it belongs in the Ethereum security stack**

  


Safe OpenSig is fully open source. The code is on github. The app is free for everyone, available on iOS and Android. We built it with the World Foundation for their signing operations and launched in April 2026. No token. The tool exists because the problem is real and the ecosystem needed it.

  


The app is free. The verification protocol is open source. Anyone can bring their own RPC nodes and run the full stack independently. For teams who want reliable managed node infrastructure without running their own, Candide offers that as a service. That funds ongoing development. The verification layer itself is and will remain free.

  


Your support helps sustain the core: expanded hardware wallet coverage, broader transaction type support, and the independent audit work required to give signers confidence in the tool they are relying on.

  


The people managing Ethereum's most important assets deserve to know what they are signing. This is the tool that makes that possible.
