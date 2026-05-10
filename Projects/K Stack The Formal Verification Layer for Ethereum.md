---
title: "K Stack: The Formal Verification Layer for Ethereum"
project_url: "https://qf.giveth.io/project/k-stack:-the-formal-verification-layer-for-ethereum"
owner: "Palina Tolmach"
twitter: "https://x.com/rv_inc"
tags: ["formal-verification", "smart-contract", "auditing"]
categories: ["computer science", "public-goods", "research", "scientific-research", "tech"]
donation_count: 22
total_usd_donated: 375.89
updates_count: 1
---

# K Stack: The Formal Verification Layer for Ethereum

🔗 **Project:** [https://qf.giveth.io/project/k-stack:-the-formal-verification-layer-for-ethereum](https://qf.giveth.io/project/k-stack:-the-formal-verification-layer-for-ethereum)
👤 **Owner:** Palina Tolmach

## Social Media
- 🐦 [Twitter](https://x.com/rv_inc)
- 💬 [Discord](https://discord.gg/CurfmXNtbN)
- 🐙 [Github](https://github.com/runtimeverification)
- 💼 [Linkedin](https://www.linkedin.com/company/runtime-verification/)
- 🌐 [Website](https://runtimeverification.com/)
- 🔗 [Youtube](https://www.youtube.com/channel/UCZeDdn8F5ARtK5LmRngiLnA)

## Donation Addresses
- `0x3b4f6e0db0082f767b8a13dcf63a533b97006235`
- `0x34d254ac20731ae30731677801986c74be543c03`
- `0x19cae8aeb55935832959264ad8f2223ed2db9dcf`

## Tags
[[Tags/formal-verification|#formal-verification]]  [[Tags/smart-contract|#smart-contract]]  [[Tags/auditing|#auditing]]

## Sub-projects
### [K Framework](https://github.com/runtimeverification/k)
Core rewriting logic framework underlying all K-based tools.

### [Kontrol](https://github.com/runtimeverification/kontrol)
Formal verification of Foundry tests using K semantics.

### [EVM Semantics (KEVM)](https://github.com/runtimeverification/evm-semantics)
Formal semantics of the EVM in K.

## Related QF Projects
- [[Projects/ERCx Property Testing for ERC Token Standards|ERCx: Property Testing for ERC Token Standards]]


## Donations

> **22 donations** · **Total: $375.89 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x8abf01aaea367e7803ca8c18aaf1a2c2e1181184]] | Ethereum | USDC | $199.99 | 2026-05-08 |
| [[Donors/0x12846be7b801c745cb62ac41423894b2d97185d0]] | Ethereum | TIK | $16.00 | 2026-05-08 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $15.00 | 2026-05-08 |
| [[Donors/0x0413f6e30e990a8942e88851de2c5ce721f81536]] | Gnosis | GNO | $13.29 | 2026-05-06 |
| [[Donors/0x1ffa24febecf764daff68507113ad6aff16acd08]] | Ethereum | FINN | $11.44 | 2026-05-01 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | TIK | $11.00 | 2026-05-06 |
| [[Donors/devtooligan]] | Base | USDC | $10.00 | 2026-05-06 |
| [[Donors/0x083447a493c455a284da5ef9eb8751252fb6113f]] | Ethereum | FINN | $6.83 | 2026-04-28 |
| [[Donors/0x89f0f5f13208a89499e0b2f01427df044d51ee1d]] | Ethereum | USDC | $5.00 | 2026-04-24 |
| [[Donors/0xd2b73492f5fd65ad9ee39788cf51a94f54621a17]] | Ethereum | FINN | $2.36 | 2026-05-06 |
| [[Donors/Cotabe Moral]] | Optimism | USDGLO | $2.00 | 2026-04-23 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.00 | 2026-05-03 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| [[Donors/0xb53460f73b5cedf6345108cba73f32b9da09172c]] | Arbitrum | USDC | $0.00 | 2026-05-04 |
| Anonymous | Ethereum | TIK | $27.00 | 2026-05-05 |
| Anonymous | Base | USDC | $14.00 | 2026-05-07 |
| Anonymous | Ethereum | TIK | $10.00 | 2026-05-10 |
| Anonymous | Ethereum | USDC | $10.00 | 2026-05-09 |
| Anonymous | Optimism | USDC | $8.00 | 2026-05-06 |
| Anonymous | Ethereum | FINN | $5.81 | 2026-04-29 |
| Anonymous | Ethereum | USDC | $5.10 | 2026-04-25 |

## Categories
**Tags:** computer science, public-goods, research, scientific-research, tech
**Main:** Community, DeSci, Technology

## Description

[K](https://github.com/runtimeverification/k) is the engine behind Ethereum's most rigorous security tooling. It's a universal semantic framework that lets you define a programming language once, precisely and mathematically, and automatically derive a full suite of analysis tools from that single definition. Built and maintained by Runtime Verification over two decades, K is the foundation of an open-source infrastructure stack that secures Ethereum from the smart contract layer down to the clients and cryptographic libraries that run the network.

K powers [KEVM](https://github.com/runtimeverification/evm-semantics) — the first complete, executable formal semantics of the EVM. KEVM is a public good the ecosystem depends on: the reference point against which client implementations and zkEVM stacks are checked for correctness, and the foundation that makes formal verification of smart contracts possible. It was used to [verify the Ethereum Beacon Chain deposit contract](https://daejunpark.github.io/papers/deposit.pdf) (today holding over 77 million staked ETH), uncovering a subtle compiler bug in the process. More recently, KEVM played a central role in EF-funded zkEVM verification work, proving equivalence with [revm](https://github.com/bluealloy/revm) and the [EVMYul](https://github.com/NethermindEth/EVMYulLean) model of EVM in Lean 4 ([full report](https://github.com/runtimeverification/publications/blob/main/reports/zkvm/zkEVM_Formal_Verification_report.pdf)). KEVM has been actively maintained by RV for over eight years, tracking every major Ethereum upgrade through Pectra. 

[Kontrol](https://github.com/runtimeverification/kontrol) is the developer-facing layer: a free, open-source formal verification tool that lets Solidity developers write formal specifications as Foundry tests, using tools and languages they already know. It is actively used across the Ethereum ecosystem, with production deployments at some of the highest-stakes protocols. Optimism runs [Kontrol proofs](https://github.com/ethereum-optimism/optimism/tree/88cd69c83a01986e98508b4ab9415e45de7415fa/packages/contracts-bedrock/test/kontrol) in CI, verifying Bedrock contract components before every deployment. In the Term Finance engagement, Kontrol proofs [caught loop-related vulnerabilities](https://runtimeverification.com/blog/kontrol-and-term-finance-formal-verification-success-story-working-with-bounded-loops) that fuzzing and manual audits had missed. It has been used for pre-deployment formal verification of critical invariants across [Lido](https://github.com/lidofinance/dual-governance/blob/ba9dfc9213ec888993937a699e2a587a0082720f/test/kontrol/report/DualGovernanceFormalVerificationReport.md), [Zivoe](https://strapi-rv-bucket-01.s3.us-east-2.amazonaws.com/Zivoe_Vault_dd0c6e0a7e.pdf), [Cork Protocol](https://strapi-rv-bucket-01.s3.us-east-2.amazonaws.com/Cork_FV_Summary_Report_967e4b9eaf.pdf), [Levery](https://strapi-rv-bucket-01.s3.us-east-2.amazonaws.com/Levery_Audit_Report_cbbfd502d7.pdf), and other major protocols. 

As of March 2026, Kontrol is used by 70 projects building on Ethereum. As AI tools for bug-hunting advance and make black-hats ever more productive, the only defense is eliminating all bugs at launch, which only formal verification can achieve. For anyone already writing Foundry tests, Kontrol is the lowest-friction path to formal verification available today.

**Beyond the EVM**

[KWasm](https://github.com/runtimeverification/wasm-semantics) provides formal semantics for WebAssembly, which becomes increasingly critical as Arbitrum Stylus, Wasm-based fraud proofs, and Wasm zkVMs become live infrastructure on Ethereum. KWasm is the foundation for [Skribe](https://github.com/runtimeverification/skribe), an open-source property-based testing and fuzzing tool for Arbitrum Stylus contracts.

[KMIR](https://github.com/runtimeverification/mir-semantics) brings formal verification to Rust, the language that Ethereum's consensus clients, cryptographic libraries, and ZK proving systems are written in. KMIR makes a deliberate choice to support all of Rust, including unsafe code. This matters because the most security-critical components, such as cryptographic primitives, memory management, and low-level protocol logic, are precisely where unsafe code lives.

RV collaborates directly with AWS on upstream Rust compiler improvements and on[ stable-mir-json](https://github.com/runtimeverification/stable-mir-json), a tool RV developed that lets any verification tool extract MIR from the rustc toolchain, and toward contributing KMIR to the[ AWS/Rust Foundation initiative to formally verify the Rust standard library](https://github.com/model-checking/verify-rust-std). Improvements to the public MIR interface and to stable-mir-json are public goods that benefit the entire Rust verification ecosystem.

Further down the stack, RV's [KRiscV](https://github.com/runtimeverification/riscv-semantics) semantics for RISC-V brings formal verification to the instruction set underlying many zkVMs.

Every K-based tool shares the same backends, and any improvement to K benefits all of them simultaneously. This economy of effort is why K punches so far above its weight for a largely unfunded infrastructure project, and sustained support would multiply that leverage further.

**A decade of public goods**

All tools in the K stack are fully open source under the BSD-3-Clause license. K-related publications have accumulated thousands of academic citations, and the framework has been used to deliver practical security results for NASA, DARPA, Toyota, and Boeing beyond blockchain. 

RV also maintains [ERCx](https://github.com/runtimeverification/ercx-tests), a free, open-source library of over 900 handcrafted Foundry tests for ERC token standards.

This infrastructure has been largely unfunded relative to its importance. RV maintains it because it underpins not just our own tools, but a significant part of Ethereum's formal verification and security ecosystem. Community support is what would help keep it sustainable long-term.

**What's next**

The immediate priorities are 

  * Keeping KEVM synchronized with Ethereum protocol upgrades
  * AI-assisted workflows for Kontrol that help developers onboard faster and diagnose stuck proofs, and
  * Performance improvements across the stack that benefit both human developers and AI agents driving verification workflows.



Longer-term investments fall into three categories:

  * Strengthening the core: hardening K's [Lean 4 backend](https://github.com/runtimeverification/k/tree/master/pyk/src/pyk/klean) to benefit from the rapid progress in AI-assisted theorem proving, developing a Rust frontend for K (kframework-rs), and coverage-guided greybox fuzzing over K semantics
  * Expanding coverage: bringing KWasm up to date with the Wasm 3.0 specification for Arbitrum Stylus and emerging Wasm-based zkVMs, and expanding KMIR toward Ethereum client and cryptographic library verification, and
  * Scaling through AI: developing agent capabilities for writing K semantics and working with K-based tools, reducing the cost of both building new formal specifications and using existing ones for verification.



**Why your support matters**

Runtime Verification has maintained this infrastructure for over a decade, through every hardfork, every new EVM feature, every shift in the ecosystem. Every Kontrol proof, every zkEVM equivalence check, every hardfork-compatible verification engagement depends on someone keeping this stack correct, complete, and current. That work needs sustained community support, and every donation here goes directly toward it.

**Funding Breakdown**

All donations fund open-source development of RV's formal verification infrastructure. All tools are and will remain freely available under BSD-3-Clause. No portion of donations will support commercial services.

**$0 - $15,000:** AI-assisted onboarding and proof debugging for Kontrol. Building AI skills and tooling that guide teams using Foundry through setting up Kontrol, writing specifications, diagnosing stuck proofs, generating counterexamples, and suggesting concrete next steps, without requiring RV's direct involvement. This tier funds AI capabilities that can unlock teams that are getting started or stalled, and reduce the need for expert hand-holding on routine proof issues.

**$15,000 - $45,000:** KEVM hardfork tracking and core maintenance. Keeping KEVM current with Ethereum protocol upgrades is the single most critical ongoing cost, which amounts to about $150,000/year. This tier covers a substantial portion of 2026 maintenance, keeping the semantics synchronized with the chain for Kontrol's 70+ monthly active users and the broader ecosystem that depends on it.

**$45,000 - $75,000:** Hardening K Framework Lean 4 backend. Making the K-to-Lean extraction pipeline substantially more robust, expanding what can be verified with K-based tools and opening an alternative path for proofs where automated tools hit scalability limits.

**$75,000 - $90,000:** Agent-facing tooling and documentation for K. Bringing more advanced tutorials, onboarding guides, and structured APIs that lower the barrier for new users and AI agents working with K semantics, running proofs, and interpreting results.

**$90,000 - $120,000:** Symbolic execution performance improvements. Targeted engineering work on [K's Haskell backend](https://github.com/runtimeverification/haskell-backend/), focused on metrics that directly affect KEVM, Kontrol, and KWasm. Faster symbolic execution means more teams can run more challenging proofs in CI without prohibitive runtimes.

**$120,000 - $180,000:** KWasm Wasm 3.0 update and scaling. Bringing KWasm in line with the Wasm 3.0 specification, which is critical for Arbitrum Stylus and Wasm-based zkVMs, and scaling it to handle larger programs. Newer stable rustc releases are already emitting post-1.0 Wasm instructions that KWasm doesn't yet support, making this increasingly urgent.

**$180,000 - $210,000:** kframework-rs and greybox fuzzing. A Rust frontend for K modernizes how external tools interact with the framework, replacing the legacy Java frontend with something faster and more ergonomic across every tool in the stack. Coverage-guided greybox fuzzing over K semantics delivers coverage-guided fuzzing across all K language semantics simultaneously.

**$210,000+:** KMIR, AI skills for K, and Rust infrastructure verification. This tier funds upstream rustc improvements and [stable-mir-json](https://github.com/runtimeverification/stable-mir-json) hardening, expanding KMIR's language coverage guided by real verification targets, and introducing further AI agent capabilities for writing K semantics, reducing the cost of building new formal specifications and K-based tools.
