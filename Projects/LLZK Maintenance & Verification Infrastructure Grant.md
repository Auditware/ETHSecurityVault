---
title: "LLZK Maintenance & Verification Infrastructure Grant"
project_url: "https://qf.giveth.io/project/llzk-maintenance-verification-infrastructure-grant"
owner: "Kostas Ferles"
twitter: "https://x.com/VeridiseInc"
tags: ["zk-security", "formal-verification"]
categories: ["computer science", "research", "tech"]
donation_count: 12
total_usd_donated: 317.69
updates_count: 1
---

# LLZK Maintenance & Verification Infrastructure Grant

🔗 **Project:** [https://qf.giveth.io/project/llzk-maintenance-verification-infrastructure-grant](https://qf.giveth.io/project/llzk-maintenance-verification-infrastructure-grant)
👤 **Owner:** Kostas Ferles

## Social Media
- 🐦 [Twitter](https://x.com/VeridiseInc)
- 🐙 [Github](https://github.com/veridise)
- 💼 [Linkedin](https://www.linkedin.com/company/veridise/)
- 🌐 [Website](https://veridise.com/)

## Donation Addresses
- `0x99abf99d5cc97a0d3507b0d6af2d63447d98d353`

## Tags
[[Tags/zk-security|#zk-security]]  [[Tags/formal-verification|#formal-verification]]


## Donations

> **12 donations** · **Total: $317.69 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x63b540193d0a411fa710f5138412a561322914ae]] | Ethereum | FINN | $23.55 | 2026-05-06 |
| [[Donors/0x12846be7b801c745cb62ac41423894b2d97185d0]] | Ethereum | TIK | $16.00 | 2026-05-08 |
| [[Donors/0x02437eb276e9c931f91ef4e24e327f81db46cfc3]] | Ethereum | FINN | $11.76 | 2026-05-04 |
| [[Donors/0x02437eb276e9c931f91ef4e24e327f81db46cfc3]] | Ethereum | FINN | $11.33 | 2026-04-30 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | TIK | $11.00 | 2026-05-06 |
| [[Donors/0x63b540193d0a411fa710f5138412a561322914ae]] | Ethereum | FINN | $9.45 | 2026-05-04 |
| [[Donors/0x63b540193d0a411fa710f5138412a561322914ae]] | Ethereum | FINN | $9.40 | 2026-05-04 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $2.00 | 2026-05-07 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0xd39dc38225e642f09eb964d76c85b32ef097bb0d]] | Base | USDC | $0.10 | 2026-05-06 |
| Anonymous | Ethereum | TIK | $220.00 | 2026-05-04 |
| Anonymous | Ethereum | USDC | $2.00 | 2026-04-28 |

## Categories
**Tags:** computer science, research, tech
**Main:** Technology

## Description

## **Project Overview**

LLZK is an open-source compiler framework for zero-knowledge (ZK) circuits that enables analysis, optimization, and formal verification across multiple ZK ecosystems. Built on top of MLIR, LLZK provides a modular intermediate representation that supports multiple frontends (e.g., Circom, Halo2, Plonky3) and multiple verification backends (e.g., PCL, Lean, R1CS).

  


The project is publicly available at: <https://github.com/project-llzk>

  


LLZK is designed not just for circuit construction, but for security-critical reasoning about circuits, including determinism, soundness, and constraint correctness.

  


## **Existing Functionality and Usage**

LLZK is already a working system with the following capabilities:

  * **Frontends:** Circom, Halo2, and Plonky3 circuits can be translated into LLZK
  * **Backends:** LLZK can lower circuits into:
  * PCL (for determinism verification via Picus)
  * Lean-based verification representations (including zkLean)
  * R1CS
  * **Analysis & Optimization Passes:**Degree lowering
  * Interval analysis
  * Unconstrained signal detection
  * Redundant constraint elimination



###   


### **Real-World Usage**

LLZK is actively used internally at Veridise as part of our verification pipeline:

  * We use LLZK + Picus to analyze circuits from zkVM systems such as:
  * RISC Zero (SP1)
  * Other zkVM-style architectures
  * LLZK serves as the intermediate layer enabling these circuits to be checked for **determinism and soundness properties**
  * We also run custom static analyses over LLZK representations to detect circuit-level issues



  


## **Ecosystem Adoption and Contributions**

LLZK is beginning to see adoption and contributions beyond its original authors, reflecting its role as emerging shared infrastructure for ZK circuit verification.

  * **Galois** has contributed support for a Lean-based verification backend (zkLean), enabling integration with formal verification workflows in the Lean ecosystem.
  * The **Noir** ecosystem is actively developing a frontend from Brillig (Noir’s intermediate representation) into LLZK.



These contributions indicate that LLZK is evolving into a common intermediate layer for interoperability and verification across ZK frameworks, rather than a project tied to a single toolchain.

##   


## **Motivation**

Modern Ethereum scaling systems (zk rollups, zkVMs) rely on increasingly complex ZK circuits. However:

  * Circuit implementations span multiple frameworks (Circom, Halo2, Plonky3, emerging zkVM IRs)
  * There is no unified infrastructure for verification across these ecosystems
  * Subtle bugs (e.g., underconstrained circuits, nondeterminism) can lead to critical security vulnerabilities



  


LLZK addresses this gap by providing a common compilation and verification layer, enabling:

  * Translation of circuits into formal verification backends (PCL, Lean)
  * Application of uniform analysis passes across ecosystems
  * Reuse of verification tooling across different proving systems



##   


## **Scope of This Grant (Maintenance Focus)**

  


This proposal focuses on maintenance, stabilization, and ecosystem integration of LLZK—not new project creation.

  


The goal is to make LLZK a usable, reliable public good for Ethereum security researchers and developers.

###   


### **Priority Areas**

  * **Stabilization & Usability (Primary)**Improve documentation and onboarding
  * Provide clear workflows for verification use cases
  * Package existing functionality into accessible interfaces
  * **Verification & Analysis Improvements**Maintain and extend existing analysis passes
  * Improve support for real-world circuits encountered in audits and research
  * **Infrastructure Hardening and Issue Resolution** Expand the testing infrastructure for LLZK, especially the core analysis passes.
  * Resolve open issues in the public issue tracker, particularly technical debt tasks and bugs.
  * Upgrade MLIR/LLVM versions for LLZK to take advantage of upstream changes — SMT dialects in MLIR 21.



##   


## **Deliverables**

### **1\. End-to-End Verification Pipelines**

We will deliver fully documented, runnable verification workflows for ZK circuits, along with a unified interface for executing them. While many of the underlying components already exist, end-to-end pipelines have not yet been fully integrated, stress-tested, or made easily usable by external developers, and current documentation is limited.

  


This effort will focus on building complete workflows that take circuits from supported frameworks (e.g., Circom, Halo2, and zkVM-style systems) through LLZK and into verification backends such as PCL/Picus and Lean. In addition, we will provide a unified CLI and supporting scripts to ingest circuits, run LLZK passes, and export verification artifacts in a consistent and user-friendly manner.

  


Comprehensive documentation and tutorials will accompany these workflows, enabling users to reproduce results and apply LLZK to their own circuits with minimal setup.

  


**Artifacts:**

  * Public repo examples with step-by-step instructions
  * One-command or scripted execution of pipelines
  * Tagged releases with working tooling



  


**Timeline/Cost**

  * 8 weeks, $80,000



###   


### **2\. Expanded Verification Backends**

We will extend LLZK’s verification support to better match real-world needs:

  * Bitvector-based SMT encodings for circuits over small primes
  * Finite field–aware encodings
  * Improvements to current integer-based encodings



  


**Artifacts:**

  * New SMT lowering passes which use different encodings: bitvector, finite field, optimized integers.
  * An evaluation of the lowering on real world benchmarks, demonstrating that users can leverage SMT solvers to check properties of their circuits out-of-the-box.



  


**Timeline/Cost**

  * 3 weeks, $30,000



  


### 3\. Core Infrastructure Hardening & Issue Resolution

We will systematically address open issues in LLZK to improve the correctness, stability, and usability of the framework. This includes resolving bugs in dialect implementations and lowering passes, strengthening validation of IR invariants, and ensuring reliable translation across supported frontends and backends.

This work will be guided by and transparently tracked through the project’s public issue tracker: <https://github.com/project-llzk/llzk-lib/issues>.

  


In parallel, we will improve the developer experience by refining error reporting, simplifying APIs, and reducing friction when integrating LLZK into external tooling. We will also expand test coverage and CI workflows to prevent regressions and ensure the reliability of end-to-end verification workflows.

  


**Timeline/Cost:**

  * 8 weeks, $80,000



##   


## **Importance**

This project directly strengthens Ethereum’s security ecosystem by:

  * Providing shared infrastructure for verifying ZK circuits across frameworks
  * Enabling detection of critical bugs such as nondeterminism and underconstrained signals
  * Supporting auditing of zk rollups and zkVMs, which are central to Ethereum scaling
  * Lowering the barrier for applying formal verification techniques to real-world circuits



##   


## **About the Team**

Veridise is a blockchain security firm specializing in the analysis of smart contracts and ZK systems, with deep expertise in formal methods and verification.

  


We have audited critical infrastructure including zkVMs, rollups, and DeFi protocols (e.g., RISC Zero, Linea, Succinct, Mina), and have developed internal tools such as Picus for circuit verification.

  


LLZK builds on this experience to provide general-purpose verification infrastructure for the ecosystem.
