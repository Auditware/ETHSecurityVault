---
title: "SCAR: AI Retrieval for Smart Contract Security"
project_url: "https://qf.giveth.io/project/scar:-ai-retrieval-for-smart-contract-security"
owner: "Farseen Shaikh"
owner_twitter: "LifeHodlr"
twitter: "https://x.com/LifeHodlr"
tags: ["ai-security", "auditing"]
categories: ["computer science", "public-goods", "research", "science-tools-infra", "scientific-research"]
donation_count: 7
total_usd_donated: 592.21
updates_count: 1
---

# SCAR: AI Retrieval for Smart Contract Security

🔗 **Project:** [https://qf.giveth.io/project/scar:-ai-retrieval-for-smart-contract-security](https://qf.giveth.io/project/scar:-ai-retrieval-for-smart-contract-security)
👤 **Owner:** Farseen Shaikh
🐦 **Twitter:** [@LifeHodlr](https://x.com/LifeHodlr)

## Social Media
- 🐦 [Twitter](https://x.com/LifeHodlr)
- 🐙 [Github](https://github.com/FarseenSh/scar)
- 📱 [Telegram](https://t.me/FarseenS)
- 🌐 [Website](https://huggingface.co/datasets/Farseen0/scar-corpus)

## Donation Addresses
- `0x79671f637a70e0ef7472c037eee020f6ab01a3c7`
- `6gP82dKDRXToU5L8JzqxVkCzWdB5mUchjogWgM57zSyq`

## Tags
[[Tags/ai-security|#ai-security]]  [[Tags/auditing|#auditing]]


## Donations

> **7 donations** · **Total: $592.21 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x1babb042ddcca9064eb01a054bcdbf5ceb102592]] | Ethereum | ETH | $468.23 | 2026-05-10 |
| [[Donors/0xd203fd64b3cc755a9ff13c7a32aa9070ad2f30fb]] | Ethereum | USDC | $99.99 | 2026-05-08 |
| [[Donors/0x45656eaa07d95bf60d6fbd98cf68a36256cebbe0]] | Ethereum | TIK | $5.00 | 2026-05-07 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $2.00 | 2026-05-07 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.00 | 2026-05-03 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| Anonymous | Arbitrum | USDC | $15.00 | 2026-05-09 |

## Categories
**Tags:** computer science, public-goods, research, science-tools-infra, scientific-research
**Main:** Community, DeSci, Technology

## Description

TL;DR — **SCAR** is an open-source AI retrieval system that helps smart contract auditors (and the AI tools they use) find relevant vulnerability precedents in 114 milliseconds. R@10 = 0.901 across 232,000 real Ethereum contracts. Independent research. Apache 2.0. Built for Ethereum security.

  


## 🎯 The Problem

Balancer: **$128M**. Cetus: **$223M**. Drift: **$285M**. Smart contract exploits drained **$1.2B+ from DeFi in 2025 alone** — and most involved vulnerability patterns that had been caught before in past audits, if only auditors could surface them fast enough.

When an auditor sees a suspicious pattern, they need to know: _has this vulnerability class been caught before? Where? How?_ Existing retrieval tools fail here. BM25 keyword search doesn't know that "price oracle manipulation" maps to getReserves() and swap() calls. Dense embeddings like CodeBERT score barely above random (R@10 = 0.109) on real audit findings.

  


## 🛡️ What SCAR Does

SCAR is a sparse latent retriever that lets auditors semantically search the full body of past Ethereum audit findings. Given a natural-language query, it returns ranked vulnerable contracts from a corpus of 232,000 real Solidity contracts in **114ms**.

It introduces **SAE-LoRA** , the first published application of low-rank adaptation to Sparse Autoencoder encoder weights — a novel technique that transforms reconstruction-oriented SAE features into retrieval-discriminative ones.

  * **R@10 = 0.901** on full 232,000-contract corpus retrieval (BM25 collapses to **0.308**)
  * **Validated on EVMBench** (OpenAI + Paradigm + OtterSec, 2026) — hybrid beats BM25 on all three metrics
  * **Trained on 7,552 real auditor findings** from Trail of Bits, OpenZeppelin, Sherlock, Code4rena (via Solodit)
  * **6× faster** than dense retrieval · **Interpretable** : 7 of top 10 features map to security-critical Solidity patterns (transfer, call, owner, auth, burn, lock)



  


## ⚡ Why SCAR ≠ another audit AI

AI audit tools are shipping fast in 2026. They share the same weakness: their AI reasons about vulnerabilities in a vacuum, producing hallucinated findings disconnected from real precedent. **SCAR is the retrieval infrastructure underneath** — the component that grounds AI-assisted audits in the 7,552 audit findings already out there. SCAR doesn't compete with audit AIs; it's what makes them stop hallucinating.

  


## 🔬 Why this funding matters right now

The paper is complete. The system works. What separates research from infrastructure audit firms adopt is second-backbone validation on the models that just released:

  * **Qwen 3.5-8B** (Alibaba, Feb 2026) — outperforms the previous-gen 30B on most benchmarks
  * **Gemma 4 26B** (Google DeepMind, April 2026) — built on Gemini 3 research



Validating SAE-LoRA on both proves generalization across architectures (dense → MoE) and labs. This is the #1 reviewer concern — and I've exhausted my self-funded compute budget (~$280 on Modal plus 800$ on pre-runs and pipeline configs) after the initial training runs. **This is the exact gap funding closes.**

  


## 💰 Where your donation goes

Cumulative tiers — higher unlocks broader work. Everything stays **Apache 2.0**.

  * **Under $5K** — Qwen 3.5-8B validation, arXiv preprint, full weights release on HuggingFace
  * **$5K–$10K** — Above + Gemma 4 26B A4B validation, reviewer-requested ablations
  * **$10K–$25K** — Above + production API + CLI for audit firms, Slither/Mythril integration
  * **$25K–$50K** — Above + multi-chain expansion (Arbitrum Stylus, Solana, Move)
  * **$50K+** — Above + 6–12 months sustained research, audit firm partnerships (Trail of Bits, OtterSec, OpenZeppelin)



  


## 🔗 Links

  * **Dataset (live):** <https://huggingface.co/datasets/Farseen0/scar-corpus>
  * **GitHub:** <https://github.com/FarseenSh/scar>
  * **Paper:** EMNLP 2026 submission in ARR, available on demand
  * **Contact:** [farseenshaikh20@gmail.com](mailto:farseenshaikh20@gmail.com)



  


Built by **Farseen Shaikh** , independent researcher. No institutional affiliation. No company. No monetization plans. Just research the Ethereum security community can freely build on.

**The round runs April 21 – May 12, 2026. Donate now →**
