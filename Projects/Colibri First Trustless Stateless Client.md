---
title: "Colibri: First Trustless Stateless Client"
project_url: "https://qf.giveth.io/project/colibri:-first-trustless-stateless-client"
owner: "Jork Leonhardt"
twitter: "https://x.com/CorpusCoreHQ"
tags: ["infrastructure"]
categories: ["computer science", "infrastructure", "tech"]
donation_count: 26
total_usd_donated: 304.97
updates_count: 1
---

# Colibri: First Trustless Stateless Client

🔗 **Project:** [https://qf.giveth.io/project/colibri:-first-trustless-stateless-client](https://qf.giveth.io/project/colibri:-first-trustless-stateless-client)
👤 **Owner:** Jork Leonhardt

## Social Media
- 🐦 [Twitter](https://x.com/CorpusCoreHQ)
- 🐙 [Github](https://github.com/corpus-core/colibri-stateless)
- 🌐 [Website](https://corpuscore.tech/)
- 🔗 [Youtube](https://www.youtube.com/@colibri.stateless)

## Donation Addresses
- `0xed12b99fad334abf7eb787b7760b20a84c179887`

## Tags
[[Tags/infrastructure|#infrastructure]]


## Donations

> **26 donations** · **Total: $304.97 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x057ee041647ae4fe26423830c79ca252d27d7ecb]] | Ethereum | TIK | $50.00 | 2026-05-09 |
| [[Donors/0xb046a5eac49c09f17a71ffb46085680f87d8f923]] | Ethereum | ETH | $32.36 | 2026-04-27 |
| [[Donors/0x4ebf46c3deb18d3c9e979452a4d711549855020f]] | Ethereum | TIK | $20.00 | 2026-05-09 |
| [[Donors/0x057ee041647ae4fe26423830c79ca252d27d7ecb]] | Ethereum | FINN | $11.38 | 2026-04-28 |
| [[Donors/Yabir Benchakhtir]] | Optimism | USDC | $10.00 | 2026-04-23 |
| [[Donors/0x64f0bfcf26fef19b66456ec3ec74a536507d1bef]] | Gnosis | USDC | $10.00 | 2026-04-28 |
| [[Donors/Sem 🐝]] | Gnosis | GNO | $7.24 | 2026-04-23 |
| [[Donors/0x6c6afa2a66586f534c635ae50f14a75855e19d50]] | Ethereum | ETH | $7.13 | 2026-05-05 |
| [[Donors/Lauren Luz]] | Gnosis | GIV | $5.89 | 2026-04-28 |
| [[Donors/0xdcb3448b6537cf31e86a718386c86cdf7cd2907f]] | Ethereum | FINN | $5.78 | 2026-04-25 |
| [[Donors/0x07e995f06149352015bde16530169cab76ef58fe]] | Ethereum | TIK | $5.00 | 2026-05-03 |
| [[Donors/Steffen Kux]] | Ethereum | DAI | $5.00 | 2026-04-25 |
| [[Donors/0x36299441f882b7c6945f4680c00599066f86c564]] | Optimism | ETH | $4.73 | 2026-05-05 |
| [[Donors/0x2446303b80c71b28030dd4e2b8c8f35dd80dd679]] | Ethereum | ETH | $4.64 | 2026-04-27 |
| [[Donors/Cotabe Moral]] | Optimism | USDGLO | $2.00 | 2026-04-23 |
| [[Donors/0xf576bd230d13293f1ea2d7d154b1c08643b1271c]] | Ethereum | USDC | $1.50 | 2026-04-27 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/Rajesh Kushwah]] | Base | USDC | $1.10 | 2026-05-07 |
| [[Donors/0x477ed01c077c99acec44657cadeb1b2da36e1264]] | Optimism | ETH | $1.01 | 2026-05-07 |
| [[Donors/Open Sauce]] | Optimism | GIV | $1.00 | 2026-05-01 |
| [[Donors/Eduardo Vega-Patiño]] | Gnosis | XDAI | $1.00 | 2026-05-06 |
| [[Donors/0xbea26de685ef828b60ca53b40ecc9bab35645fdf]] | Optimism | USDC | $1.00 | 2026-04-26 |
| Anonymous | Ethereum | ETH | $94.45 | 2026-05-04 |
| Anonymous | Ethereum | FINN | $9.68 | 2026-04-24 |
| Anonymous | Ethereum | FINN | $6.98 | 2026-05-09 |
| Anonymous | Ethereum | USDC | $5.00 | 2026-04-29 |

## Categories
**Tags:** computer science, infrastructure, tech
**Main:** Economics & Infrastructure, Technology

## Description

# TL;DR

Colibri is a trustless, stateless, ultra-light Ethereum client that enables applications to verify blockchain data locally — without trusting RPC providers. It brings proof-based verification to mobile, web, IoT, and AI systems.

  


  


# The Problem

Most applications access blockchain data through centralized RPC providers. While the blockchain itself is decentralized, the access layer is not.

A compromised RPC provider can manipulate, censor, or withhold data. Applications cannot verify responses, leading to risks such as incorrect balances, manipulated contract state, unsafe transaction simulations, and undetectable attack vectors. This problem becomes critical for wallets, DeFi applications, IoT devices, and autonomous systems.

In recent years, multiple sophisticated **supply-chain attacks** have proven that this is not a theoretical risk.

A malicious/compromised provider can:

  * Return **fake balances** or **outdated state** ,
  * manipulate transaction data before signing to redirect assets to attacker-controlled addresses,
  * Manipulate smart contract reads (e.g., lending apps or governance votes),
  * Silence or censor certain accounts or regions.



For end users, this means:

  * **Wallets showing false information** ,
  * **Transactions being hijacked or front-run** ,
  * **IoT devices granting unauthorized access** ,
  * **AI systems making wrong autonomous decisions**.



In addition, all blockchain interactions begin with reads. These reads expose user intent and metadata through centralized infrastructure, creating privacy risks that are not addressed today.

  


  


# What Colibri Does

Colibri replaces trust with cryptographic verification.

It verifies:

  * execution data (balances, storage, logs, transaction outcomes)
  * consensus validity (ensuring data originates from the canonical chain)



This is done statelessly — without sync, without stored state, and without trusting any data source.

Colibri extends this into application-level security:

  * Verified Transaction Simulation
  * Transactions can be simulated locally based on proofs before signing, ensuring correctness and preventing manipulation between simulation and execution.
  * Agentic Scam Analysis
  * Verified data can be analyzed to detect inconsistencies or suspicious patterns before users or automated systems act on it.
  * Human-Readable Simulation Translation
  * Simulation results can be translated into understandable explanations, improving user awareness and decision-making.
  * Pragmatic Adaptive Privacy (PAP)
  * Colibri introduces a privacy-aware read layer that reduces metadata leakage and protects user intent during blockchain interactions.



  


[MetaMask with Standalone colibri client]

  


[dApp with remote colibri proofer]

  


[dApp with local colibri proofer]

  


# Colibri’s architecture

  * **C-based core:** ultra-light, fast, portable, runs on mobile, web, and embedded devices
  * **SDK bindings:** JS/TS/WASM, Python, Dart/Flutter, Swift, and Kotlin/Java — making integration into wallets, browsers, or backend systems straightforward.
  * **zk-proof aggregation:** recursively aggregates sync committee transitions into a single compact proof, minimizing bandwidth and compute needs
  * **Local Transaction simulation** : Next to on-chain data verification, all transaction data can be simulated locally before signing based on proofs. (offered as SDK library function)



This means that even a **sensor, phone, or AI agent** can verify the Ethereum state independently — without syncing or trusting any third party.

  


[Video showing colibri in the standalone case as RPC node within Metamask]

  


[Proofer Infrastructure Dashboard]

  


# Roadmap

## Q2 2026 — Production Expansion & zk Baseline

### Core Client

  * Production-ready Ethereum verifier (execution + consensus proofs) (completed)
  * Production-ready Gnosis support
  * MVP support for OP Stack (Optimism, Base)
  * Hardened verifier across platforms (mobile, web, embedded)



### Prover Infrastructure (vRPC)

  * Production-ready prover architecture:
  * Local Prover / Hybrid Prover
  * Proxy Prover
  * vRPC (remote prover)
  * Packaged deployments for different environments (local, hosted, provider)
  * Proof delivery (execution + consensus) at scale



### zk-Proofs (Consensus)

  * zk-consensus proofs production ready
  * Compression of sync committee transitions into single proofs



### Multichain (Phase I)

  * Production support:
  * Ethereum mainnet
  * Gnosis
  * Testnets (Sepolia, Chiado)
  * MVP:
  * OP Stack (Optimism, Base)



### Developer Ecosystem

  * Stable bindings: JS/TS, Python, Swift, Kotlin/Java, Dart/Flutter
  * Developer documentation (integration-first)
  * Reference integrations:
  * Wallet (verified reads + simulation)
  * dApp 



### Deliverables

  * Trustless reads (balances, storage, logs,...) in production
  * Local transaction simulation on verified state
  * End-to-end: Request → Proof → Verification → Execution



## Q3 2026 — Scaling, Privacy Layer &

## Architecture Consolidation

### Prover Infrastructure

  * Scaling of prover architecture across all types:
  * Local Prover (optimization for constrained environments)
  * Proxy Prover (delegation patterns, hybrid verification)
  * vRPC (remote prover, provider-facing)
  * Standardized deployment models (local, hybrid, provider-operated)
  * Historical proof support



### Multichain (Phase II)

  * Additional L1s / L2s
  * Standardization of proof formats across chains



### Privacy Layer (PAP)

  * PAP MVP (Pragmatic Adaptive Privacy)
  * Transport privacy strategies (multi-endpoint, routing)
  * Content privacy strategies (query shaping, batching)
  * Integration into client and bindings



### Transaction Security

  * Concept and architecture of Transaction Security Agent
  * Pre-signature verification model
  * Simulation-based intent validation
  * Integration points (wallet, SDK)



### Developer Ecosystem

  * Additional bindings: C++, Rust, Go
  * SDKs for wallet and IoT integration
  * Testnet environments and reproducible setups



### Deliverables

  * Unified prover architecture (local / proxy / vRPC)
  * Privacy-aware, verifiable data access (PAP MVP)
  * Defined architecture for transaction security layer



## Q4 2026 — Product Integration &

## Ecosystem Rollout

### zk-Proofs

  * zk-consensus proofs fully integrated (completed)
  * Stabilization and optimization of zk verification pipeline



### Prover Infrastructure

  * Advanced batching and aggregation strategies
  * Cost-optimized proof generation
  * Mature deployment patterns across:
  * Local Prover
  * Proxy Prover
  * vRPC (provider-operated)



### Multichain (Phase III)

  * Broad L1 / L2 coverage
  * Stable multi-chain abstraction



### Transaction Security

  * Transaction Security Agent (MVP)
  * Integration into wallet environments
  * LLM-based transaction analysis
  * Detection of anomalies and unexpected behavior
  * Pre-signature verification pipeline



### Ecosystem Integration

  * Integration into wallet stacks (e.g. Kohaku-like SDKs)
  * Integration into IoT / embedded prototypes



### Privacy Layer (PAP)

  * Extended PAP capabilities
  * Configurable privacy profiles (T×C model)



### Deliverables

  * First production-ready transaction security layer
  * Integrated zk-based verification pipeline
  * Multi-chain proof system in real applications



## 2027 — Adoption, Standardization &

## New Verticals

### Infrastructure & Network

  * Mature prover ecosystem (multiple independent operators)
  * vRPC as a deployable standard for RPC providers



### Standardization

  * Contribution to Ethereum Statelessness roadmap
  * Alignment with client teams on proof formats
  * Open standards for proof delivery



### Product Layer Expansion

  * Transaction Security Agent (production)
  * Advanced simulation analysis
  * Automated risk detection
  * Integration into wallets and dApps



### Privacy (PAP)

  * Full PAP release
  * Privacy as default layer in SDKs



### New Verticals

  * IoT SDKs (device integration, access control, payments)
  * AI agents (trustless data access + verifiable actions)



### Real-World Adoption

  * Multiple production integrations:
  * Wallets
  * IoT systems
  * Web applications



### Deliverables

  * Trustless data access as deployable standard
  * Privacy + verification combined at protocol layer
  * Adoption beyond early ecosystem (wallets → devices → agents)



  


  


# Strategic Positioning

### Trust Model

  * No reliance on RPC correctness
  * Proof-based verification for all data access



### Architecture

  * Stateless client (no sync, no state)
  * Execution proofs + consensus proofs as primitives



### Core Principle

  * Request → Proof → Verification → Execution



### Target Environments

  * Mobile
  * Web
  * IoT / Embedded
  * AI Agents



### Objective

  * Replace trusted RPC access with verifiable, privacy-aware infrastructure



  


# The Future with Colibri

Applications can detect manipulated inputs, inconsistent state, or unexpected execution paths before any action is taken. This fundamentally reduces one of the largest attack surfaces in Web3 today. Also, read privacy is available while maintaining full verification. 

  


**In Web3**

Colibri directly improves the security and reliability of existing wallets and dApps.

Applications no longer rely on centralized RPC providers for critical reads. Balances, contract state, logs, and simulation results can be verified locally before being used.

Transaction simulations become provable instead of assumed. Users no longer sign based on UI representations or RPC responses, but on verified execution outcomes.

This closes one of the most critical gaps in Web3 today: the ability to manipulate data between read, simulation, and signing. Wallets and dApps can now detect inconsistencies or manipulated inputs before any transaction is executed.

In practice, this means:

  * safer wallet interactions
  * verifiable DeFi operations
  * reduced attack surface for frontends and bots
  * more reliable automation systems



  


Colibri can be integrated incrementally, acting as a drop-in verification layer without requiring new infrastructure or full nodes.

  


**In IoT**

Devices such as smart locks, meters, vehicles, and industrial systems can independently verify blockchain state.

They no longer rely on cloud services or gateways to interpret blockchain data. Instead, they validate permissions, payments, and state transitions locally, enabling secure machine-to-machine interactions without trusted intermediaries.

  


**In AI and Agentic Systems**

Autonomous agents increasingly act on blockchain data — executing trades, managing assets, or coordinating actions.

Colibri ensures that these systems operate only on verified inputs. Agents can validate state, simulate outcomes, and detect inconsistencies before acting.

This creates a foundation for reliable, autonomous systems that are resistant to manipulation, incorrect data, and hidden trust assumptions.

  


**Across Systems**

Colibri introduces a new standard: verification replaces trust at every interaction point.

Blockchain is no longer only trustless at the core — it becomes trustless at the edge, where applications, devices, and users actually interact with it.

  


###   


# Conclusion

Colibri transforms blockchain access from _trust-based_ to _proof-based_.

It is a foundational layer that ensures correctness, security, and independence for applications interacting with blockchain systems.

It is the missing piece in Ethereum’s journey toward full statelessness and decentralization — an infrastructure layer that guarantees verifiable truth at every endpoint.

By making trustless verification possible on any device, Colibri expands the reach, security, and resilience of Web3 — ensuring that every wallet, every sensor, and every agent can independently verify the world it interacts with.

  


  


# How we plan to use funding

<$5k

  * Hardening of the verifier (execution + consensus proof validation)
  * Hardening and extension of existing bindings (Java/Kotlin, Swift, Dart/Flutter, Python, JS/WASM) and addition of new language support
  * Developer documentation and integration guides (wallet / dApp integration)
  * Integration examples (verified reads, transaction simulation on verified state)



$5k–$10k

  * Performance improvements (verification latency on mobile/web)
  * Extension of verifier infrastructure (vRPC, proxy verifier, hybrid and local verifier modes)
  * Foundations for Pragmatic Adaptive Privacy (PAP) for verifiable, privacy-preserving reads
  * Testing against real attack scenarios (manipulated RPC data, incomplete or inconsistent state)



$10k–$25k

  * Production-ready integration patterns for wallets and dApps (verification-first architecture)
  * Integration of Pragmatic Adaptive Privacy (PAP) for verifiable, privacy-preserving reads
  * Local Transaction simulation and evaluation 
  * vRPC (Verifyable RPC) specification and reference implementation



$25k–$50k

  * Expansion to additional EVM L1/L2 networks
  * Robust prover infrastructure (vRPC, hybrid/local/proxy)
  * Deeper integrations (wallet SDKs, IoT and agent environments)
  * Foundation for Transaction Security Agent (AI based Transaction simulation and evaluation)



$50k+

  * End-to-end proof-based access stack (data + proofs as default, replacing RPC trust)
  * Full integration of Pragmatic Adaptive Privacy (PAP):
  * transport privacy (multi-provider routing, unlinkable requests)
  * content privacy (aggregation and abstraction of reads)
  * Privacy Abstraction Layer (PAL) for developers (privacy without breaking verification)
  * Advanced transaction security layer:
  * simulation on verified state
  * detection of manipulated calldata and malicious patterns
  * Human understandable Txs
  * Standardization of proof-based interfaces for wallets, dApps, and agents



**Core principle across all tiers**

The goal is to remove RPC trust as a security assumption by making proof-based verification practical in real applications—especially wallets, where most attacks occur today. Adding privacy for read access without compromising verification on protocol level.
