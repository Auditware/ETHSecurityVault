---
title: "CuEVM: Accelerate EVM execution on GPUs"
project_url: "https://qf.giveth.io/project/cuevm:-accelerate-evm-execution-on-gpus"
owner: "Minh Ho"
owner_twitter: "minhhn2910"
twitter: "https://x.com/minhhn2910"
tags: ["evm", "fuzzing"]
categories: ["computer science", "research", "science-tools-infra", "scientific-research", "tech"]
donation_count: 1
total_usd_donated: 11.47
updates_count: 1
---

# CuEVM: Accelerate EVM execution on GPUs

🔗 **Project:** [https://qf.giveth.io/project/cuevm:-accelerate-evm-execution-on-gpus](https://qf.giveth.io/project/cuevm:-accelerate-evm-execution-on-gpus)
👤 **Owner:** Minh Ho
🐦 **Twitter:** [@minhhn2910](https://x.com/minhhn2910)

## Social Media
- 🐦 [Twitter](https://x.com/minhhn2910)
- 🐙 [Github](https://github.com/minhhn2910)
- 📱 [Telegram](https://t.me/nminh_ho)
- 🌐 [Website](https://minhhn2910.github.io/)

## Donation Addresses
- `0xf7011eeb6974fcc4ab58b485b470be9ecd1f9a4d`

## Tags
[[Tags/evm|#evm]]  [[Tags/fuzzing|#fuzzing]]

## Sub-projects
### [medusa-cuevm](https://github.com/minhhn2910/medusa-cuevm)
Integration of CuEVM with Medusa fuzzer for GPU-accelerated fuzzing.


## Donations

> **1 donations** · **Total: $11.47 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | FINN | $11.47 | 2026-05-07 |

## Categories
**Tags:** computer science, research, science-tools-infra, scientific-research, tech
**Main:** DeSci, Technology

## Description

## CuEVM

  


CuEVM is a CUDA implementation of the Ethereum Virtual Machine that uses GPU parallelism to execute transactions at millions of TPS. Since my presentation on the preliminary results of CuEVM v1 at Devcon SEA (see link below), the project has progressed significantly to CuEVM v2, which now reaches over 8 million TPS on a single NVIDIA RTX 5000 (ERC-20 transfers). We originally aimed it for fuzzing to test thousands of transactions in parallel. Other potential use cases include large-scale parallel transaction testing, or customized L2 with proper concurrency control.

  


**Current State:**

  * Support Shanghai EVM, and multi-GPU execution.
  * Passed ~96% of eth-tests (ethereum/tests/GeneralStateTests)
  * We achieved up to 8 millions TPS on a single Nvidia GPU device and 13 million TPS on two GPUs (ERC20 transfer workload).
  * Show case fuzzing use case with in-house fuzzer and a fork from Medusa fuzzer from Crytic.



  


**Project Plan (long term development and maintenance):**

  * Upgrade to support new GPUs and new EVM (Pectra)
  * Maintain the codebase and review PRs from open-source contributors
  * Fix bugs and corner cases
  * In the long term we hope to be included in the official ethereum github.



  


**Talk at Devcon SEA :**<https://app.devcon.org/schedule/PQBKHF>

  


**Project Links:**

  * <https://github.com/sbip-sg/CuEVM> (existing repository)
  * <https://github.com/minhhn2910/CuEVM> (personal fork - future maintenance and syncs)
  * <https://github.com/minhhn2910/medusa-cuevm> (fuzzing tool interfacing CuEVM)



  


**Core Developers:**

  * <https://github.com/minhhn2910> (active)
  * Previous developers <https://github.com/sdcioc> and <https://github.com/cassc>



  


Disclosure: The project was part of the Ethereum Foundation Research Grant "Massively Parallel Smart Contract Fuzzing on GPUs" and ETH Ranger project "Enhancing CuEVM: GPU-Accelerated EVM".
