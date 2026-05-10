---
title: "OWASP Smart Contract Security Framework by CredShields"
project_url: "https://qf.giveth.io/project/owasp-smart-contract-security-framework-by-credshields"
owner: "CredShields Official"
owner_twitter: "credshields.com"
twitter: "https://x.com/credshields"
tags: ["standards", "smart-contract"]
categories: ["tech"]
donation_count: 14
total_usd_donated: 90.31
updates_count: 1
---

# OWASP Smart Contract Security Framework by CredShields

🔗 **Project:** [https://qf.giveth.io/project/owasp-smart-contract-security-framework-by-credshields](https://qf.giveth.io/project/owasp-smart-contract-security-framework-by-credshields)
👤 **Owner:** CredShields Official
🐦 **Twitter:** [@credshields.com](https://x.com/credshields.com)

## Social Media
- 🐦 [Twitter](https://x.com/credshields)
- 🌐 [Website](https://credshields.com)

## Donation Addresses
- `0x61243ca2ad339edf3e44fa60f2341f1fb89c6d3e`

## Tags
[[Tags/standards|#standards]]  [[Tags/smart-contract|#smart-contract]]


## Donations

> **14 donations** · **Total: $90.31 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xb53460f73b5cedf6345108cba73f32b9da09172c]] | Arbitrum | USDC | $49.99 | 2026-05-01 |
| [[Donors/0x21cb963bb4a32158cb8694dfe46e25a5f20b8d33]] | Ethereum | FINN | $11.48 | 2026-04-29 |
| [[Donors/0x083447a493c455a284da5ef9eb8751252fb6113f]] | Ethereum | FINN | $6.83 | 2026-04-28 |
| [[Donors/SunSec]] | Polygon | USDT | $5.00 | 2026-04-29 |
| [[Donors/0x63b540193d0a411fa710f5138412a561322914ae]] | Ethereum | FINN | $4.71 | 2026-05-06 |
| [[Donors/0x07e995f06149352015bde16530169cab76ef58fe]] | Ethereum | FINN | $2.33 | 2026-04-24 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | FINN | $2.32 | 2026-05-07 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $2.00 | 2026-05-07 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/Kresimir Katusic]] | Optimism | GIV | $1.07 | 2026-04-24 |
| [[Donors/Alexandre  Melo]] | Ethereum | USDC | $1.00 | 2026-04-29 |
| Anonymous | Ethereum | TIK | $1.50 | 2026-05-04 |
| Anonymous | Polygon | USDC | $1.00 | 2026-04-24 |
| Anonymous | Polygon | USDC | $0.00 | 2026-05-04 |

## Categories
**Tags:** tech
**Main:** Technology

## Description

CredShields is the creator of **OWASP SCS Framework** , an open source risk-prioritization framework built from real-world exploits observed across Ethereum and EVM chains in 2025.

  


## OWASP Smart Contract Top 10 | CredShields Open Source Project

The [OWASP Smart Contract Top 10 2026](https://scs.owasp.org/sctop10/) is an authoritative standard awareness document for smart contract risk. Published under CC BY-NC-SA 4.0 as a sub-project of the OWASP Smart Contract Security (OWASP SCS) initiative, it gives every Ethereum developer, auditor, and protocol team a free, community-owned reference for the vulnerabilities actually causing losses on-chain.

  


We led the structured incident aggregation and impact-weighted pattern analysis behind the 2026 ranking, powered by our exploit intelligence platform Web3HackHub and our AI-powered auditing platform SolidityScan. The 2026 edition is anchored in 134 deduplicated smart contract incidents from 2025, representing ~3.6B in on-chain losses, the most data-driven edition of the Top 10 ever released.

  


## **SCWE (Smart Contract Weakness Enumeration)**

A catalog of common security and privacy weaknesses in smart contracts, modeled after MITRE's CWE and acting as the bridge between SCSVS controls and SCSTG tests. Each weakness is categorized under SCSVS control groups and documents an overview, impact, modes of introduction, and mitigations with the important distinction that a weakness is a condition that can contribute to vulnerabilities, not a vulnerability itself.

  


<https://scs.owasp.org/SCWE/>

  


## **SCSVS (Smart Contract Security Verification Standard)**

The requirements standard: a list of specific security requirements and tests for Solidity/EVM smart contracts used by architects, developers, auditors, and tool vendors to define and verify secure dApps and DeFi protocols. It is organized into 11 control groups covering the most critical areas of the smart contract attack surface.

  


<https://scs.owasp.org/SCSTG/>

  


## **SCSTG (Smart Contract Security Testing Guide)**

The testing counterpart to SCSVS: a methodology manual for developers, auditors, and security professionals that describes technical processes for verifying the controls listed in the SCSVS through the weaknesses defined by the SCWE, with detailed detection methods, examples of common flaws, and remediation strategies. Together, SCSVS defines _what_ to verify, SCWE defines _what can go wrong_ , and SCSTG defines _how to test it_.

  


<https://scs.owasp.org/SCSVS/>

  


  


## Why This Matters for Ethereum Security

Most Ethereum and L2 exploits in 2025 weren't novel, they were variants of failure classes the community already knew about but hadn't standardized against.

  


The OWASP Smart Contract Top 10 closes that gap by turning real breach data into a shared vocabulary the entire ecosystem can align on, and it sits on top of a deeper stack: the SCSVS (verification standard - 11 control groups covering architecture, access control, oracles, bridges, DeFi logic, etc.), the SCWE (weakness enumeration - the smart-contract analogue of MITRE's CWE, with ~150 catalogued weakness classes), and the SCSTG (testing guide - concrete methodology to verify each SCSVS control through the weaknesses SCWE defines).

  


The 2026 Top 10 introduced Proxy & Upgradeability Vulnerabilities as a new category and elevated Business Logic Vulnerabilities to #2, changes that directly reflect where Ethereum capital is actually being lost, and that flow through into corresponding SCSVS controls (ARCH-2, GOV) and SCWE entries (e.g., [SCWE-099 Storage Layout Collision on Upgrade](https://scs.owasp.org/SCWE/SCSVS-ARCH/SCWE-099/), [SCWE-101 Flash-Loan-Fueled Governance Manipulation](https://scs.owasp.org/SCWE/SCSVS-GOV/SCWE-101/)).

  


## The Feedback Loop We Operate

Every exploit logged in Web3HackHub (a dataset of on-chain incidents going back to 2011) feeds OWASP's methodology, which in turn shapes SolidityScan's 700+ detectors scanning Ethereum and every major EVM chain (Arbitrum, Optimism, Base, zkSync, and more). That loop **real-world exploits → Web3HackHub → OWASP categorization → detector coverage → developer workflows** is what makes the Top 10 a living standard.

  


The framework is designed to be used alongside the OWASP SC Weakness Enumeration (SCWE), the OWASP SCS Checklist, and the [Alternate Top 15: Web3 Attack Vectors](https://scs.owasp.org/sctop10/Web3-Attack-Vectors-Top15/) together forming a layered defense for Ethereum builders.

  


The Top 10 is free, open-source, and used by auditors, enterprises, and solo devs around the world. Supporting this round supports the public-good layer of Ethereum security: the taxonomies, datasets, and standards everyone else builds on top of.

  


**Framework, methodology, and data sources:** [scs.owasp.org/sctop10](https://scs.owasp.org/sctop10/)

  


## CredShields: An Overview

[**CredShields**](https://giveth.io/project/16943/credshields.com) is a security company specializing in blockchain and traditional security headquartered in Singapore, founded in 2021 by Indranil Roy and Shashank. [**SolidityScan**](https://solidityscan.com/) is CredShields' flagship product an automated auditing and vulnerability scanning platform built specifically for Solidity, Ethereum's native smart contract language. It ships with 700+ vulnerability detectors and delivers an average scan time of just 6 seconds, making it one of the fastest automated auditing tools in the Ethereum ecosystem. SolidityScan has done over 7M+ scans so far.

  


[**QuickScan**](https://solidityscan.com/quickscan)**** is a specialized free-to-use security tool designed for the rapid analysis of deployed smart contracts to identify vulnerabilities and potential "rug pull" scams. ****

  


[**Web3HackHub**](https://solidityscan.com/web3hackhub) is CredShields' exploit intelligence platform a curated collection of past and present Web3 security incidents designed to help developers, researchers, and security teams learn from real-world attacks.
