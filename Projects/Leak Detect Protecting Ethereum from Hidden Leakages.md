---
title: "Leak Detect: Protecting Ethereum from Hidden Leakages"
project_url: "https://qf.giveth.io/project/leak-detect:-protecting-ethereum-from-hidden-leakages"
owner: "Manu Gupta"
owner_twitter: "manusheel"
twitter: "https://x.com/manusheel"
tags: ["static-analysis", "smart-contract"]
categories: ["financial-services", "industry-and-innovation", "public-goods", "scientific-research", "tech"]
donation_count: 4
total_usd_donated: 4.22
updates_count: 1
---

# Leak Detect: Protecting Ethereum from Hidden Leakages

🔗 **Project:** [https://qf.giveth.io/project/leak-detect:-protecting-ethereum-from-hidden-leakages](https://qf.giveth.io/project/leak-detect:-protecting-ethereum-from-hidden-leakages)
👤 **Owner:** Manu Gupta
🐦 **Twitter:** [@manusheel](https://x.com/manusheel)

## Social Media
- 🐦 [Twitter](https://x.com/manusheel)
- 💬 [Discord](https://discord.gg/FqsarW8t)
- 🔗 [Facebook](https://www.facebook.com/manusheel)
- 🔗 [Farcaster](https://warpcast.com/seeta)
- 🐙 [Github](https://github.com/LeakDetectAI)
- 🔗 [Instagram](https://www.instagram.com/manusheelg)
- 💼 [Linkedin](https://www.linkedin.com/in/manusheelgupta/)
- 📱 [Telegram](t.me/leakdetectai)
- 🌐 [Website](https://tickervalue.com)
- 🔗 [Youtube](https://www.youtube.com/@aspiringdemos)

## Donation Addresses
- `0x856c29e91eb30b8d9154a74a543dcc8d970d5d15`
- `BsqkwQq678azDXvmAM5LrJCACyQPwn742yBsifxuxagD`
- `gcokvpom4r7cpbktsfxd3kg6dpsumqgahwfnopa6blztivbqhnmfyass`

## Tags
[[Tags/static-analysis|#static-analysis]]  [[Tags/smart-contract|#smart-contract]]


## Donations

> **4 donations** · **Total: $4.22 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xde1394471c7531b2d5ebe084b744be6609a8b2d8]] | Base | ETH | $1.13 | 2026-04-29 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.00 | 2026-05-03 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |

## Categories
**Tags:** financial-services, industry-and-innovation, public-goods, scientific-research, tech
**Main:** Community, DeSci, Economics & Infrastructure, Finance, Technology

## Description

## The Problem No One Is Watching

Ethereum security today focuses on visible threats—smart contract exploits, phishing, and wallet hacks.

But a more subtle and dangerous risk is being overlooked.

Even when systems behave correctly, they may leak sensitive information through:

  * Transaction timing
  * Gas usage patterns
  * Signing behavior
  * Cross-chain execution



These signals can be analyzed by adversaries to infer private keys, predict decisions, or reconstruct internal state, **without exploiting a single bug**.

This class of attacks is not theoretical.

It builds on **years of research in side-channel analysis and cryptographic leakage detection** , already demonstrated in real-world systems (e.g., TLS padding oracle attacks like Bleichenbacher).

As AI agents begin managing funds and interacting autonomously, this risk becomes urgent.

**Ethereum isn’t just vulnerable to what breaks, it’s vulnerable to what it unintentionally reveals.**

  


## What LeakDetect Does

LeakDetect is an open-source framework to **detect, measure, and simulate hidden information leakage** in Ethereum wallets, AI agents, and multi-chain systems.

It enables developers to:

  * Simulate real adversaries observing their systems
  * Capture execution signals (timing, gas, API patterns)
  * Apply machine learning to infer potential secrets
  * Quantify leakage using formal security metrics



This introduces a new paradigm:

**Security under observation, not just correctness under execution**

  


## Background Research

LeakDetectAI is built on:

  * **3+ years of active open-source development** conducted at _Research Center Trustworthy Data Science and Security, Ruhr-Universität Bochum (Germany)_
  * **5+ years of foundational research** in AI, cryptography, and security _Software Innovation Campus Paderborn (SICP, Germany)_



This work reflects **PostDoc-level research rigor** by our research lead, Dr. Pritha Gupta, now being translated into **Ethereum-native security tooling**.

  


## Proven Foundations & Open-Source Work

Core repositories:

  * <https://github.com/LeakDetectAI/deep-learning-sca>
  * <https://github.com/LeakDetectAI/AutoMLQuantILDetect>
  * <https://github.com/LeakDetectAI/automl-qild-experiments>



These demonstrate:

  * AI-driven side-channel analysis
  * Automated vulnerability detection
  * Neural Architecture Search (NAS) for attack optimization
  * Large-scale experimental pipelines



Supporting research, demos, and publications:

[ https://tinyurl.com/leakdetectai](https://tinyurl.com/leakdetectai) and <https://sites.google.com/view/sovralabs>

  


## Real-World Alignment & Deployment

This work is aligned with and builds upon **existing, deployed open-source security efforts**.

Example:

**AutoSCA (Automated Side-Channel Analysis Tool)**

  * <https://github.com/achelos/AutoSCA>
  * <https://www.achelos.de/en/>
  * [https://www.youtube.com/watch?v=-ljLPgrw-DY&t=388s](https://www.youtube.com/watch?t=388s&v=-ljLPgrw-DY)



Based on ACM AISec research:

_“Automated Detection of Side Channels in Cryptographic Protocols: DROWN the ROBOTs!”_

AutoSCA:

  * Detects **Bleichenbacher-style TLS side-channel vulnerabilities**
  * Uses **machine learning for cryptographic attack detection**
  * Demonstrates real-world feasibility of leakage-based attacks



LeakDetect extends this direction into:

**Ethereum, wallets, AI agents, and multi-chain systems**

  


## Why This Matters Now

Ethereum is evolving rapidly:

  * AI agents are signing transactions
  * Apps are becoming multi-chain
  * Autonomous systems manage real assets



But current tools **cannot measure what systems leak**.

Our research already shows:

  * Leakage attacks are **feasible today**
  * Even modest compute can exploit them
  * Advanced attackers can significantly amplify risk



LeakDetect fills this gap **before it scales ecosystem-wide**.

  


## Our Progress So Far

  * Large-scale leakage detection experiments using deep learning
  * AutoML/NAS pipelines for automated vulnerability discovery
  * Real-world adversarial inference simulations
  * Benchmarks across GPU clusters and consumer hardware
  * Ongoing security analysis of multi-chain deployments (incl. ERC-20 ecosystems across 13+ chains)



  


## What We Will Build With This Funding

**1\. Production-Ready Open Source Toolkit**

  * CLI + SDK
  * Wallet + agent integrations
  * Plug-and-play leakage testing



**2\. Public Benchmarks & Datasets**

  * Standardized leakage datasets
  * Cross-chain environments
  * Reproducible pipelines



**3\. Ecosystem Integrations**

  * Wallet providers
  * AI agent frameworks
  * Multi-chain dApps



**4\. Security Metrics Standardization**

  * Vulnerability Score (VS)
  * Key Recovery Probability (KRP)
  * Information Leakage Rate (ILR)
  * Stealth Leakage Index (SLI)



**5\. Community & Education**

  * Docs, tutorials, workshops
  * Awareness of leakage-based attacks



  


## Why Donors Should Care

This is a **public goods problem** :

  * Leakage vulnerabilities affect everyone
  * They are hard to detect and widely ignored
  * Fixing them benefits the entire ecosystem



Your support helps:

  * Protect user funds from next-gen attacks
  * Secure AI-driven Ethereum applications
  * Strengthen long-term protocol resilience
  *   




## Why Quadratic Funding Matters

  * Small contributions ($1–$10) matter
  * More unique donors to more matching
  * Early support increases visibility and impact



 Your signal helps surface an **under-recognized but critical risk**

  


## Open Source Commitment

LeakDetect is fully open:

  * Public code, datasets, benchmarks
  * Reproducible research
  * Built for ecosystem collaboration



  


## The Bigger Vision

We aim to redefine blockchain security:

From:

**“Is this system safe to run?”**

To:

**“Is this system safe to observe?”**

Because in Ethereum:

**Anything observable can eventually be exploited**

  


## Call to Action

Support LeakDetect in the Ethereum Security QF round:

  * Help surface a critical blind spot
  * Enable next-generation security tooling
  * Protect the future of AI + Ethereum



Even a small contribution helps secure the ecosystem.

  


##
