---
title: "Simbolik: Security Toolkit for Solidity"
project_url: "https://qf.giveth.io/project/simbolik:-security-toolkit-for-solidity"
owner: "Raoul Schaffranek"
owner_twitter: "RaoulSaffron"
twitter: "https://x.com/rv_inc/"
tags: ["solidity-tooling", "static-analysis"]
categories: ["infrastructure", "public-goods", "tech"]
donation_count: 16
total_usd_donated: 444.44
updates_count: 1
---

# Simbolik: Security Toolkit for Solidity

🔗 **Project:** [https://qf.giveth.io/project/simbolik:-security-toolkit-for-solidity](https://qf.giveth.io/project/simbolik:-security-toolkit-for-solidity)
👤 **Owner:** Raoul Schaffranek
🐦 **Twitter:** [@RaoulSaffron](https://x.com/RaoulSaffron)

## Social Media
- 🐦 [Twitter](https://x.com/rv_inc/)
- 💬 [Discord](https://discord.com/invite/CurfmXNtbN)
- 🐙 [Github](https://github.com/runtimeverification/simbolik-vscode)
- 💼 [Linkedin](https://linkedin.com/company/runtime-verification)
- 📱 [Telegram](https://t.me/rv_simbolik)
- 🌐 [Website](https://www.simbolik.dev/)

## Donation Addresses
- `0xec0d8cff3e3e5870db55a82ba4d36bfe3123451d`

## Tags
[[Tags/solidity-tooling|#solidity-tooling]]  [[Tags/static-analysis|#static-analysis]]

## Related QF Projects
- [[Projects/Sourcify|Sourcify]]


## Donations

> **16 donations** · **Total: $444.44 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x8abf01aaea367e7803ca8c18aaf1a2c2e1181184]] | Ethereum | USDC | $199.99 | 2026-05-08 |
| [[Donors/0x9471f70f2518846f7a076636d64e5a22787da105]] | Ethereum | ETH | $23.82 | 2026-05-05 |
| [[Donors/0x0413f6e30e990a8942e88851de2c5ce721f81536]] | Gnosis | GNO | $21.26 | 2026-05-06 |
| [[Donors/0xe212716bbf9968f22d4f8c6dbd6f39006f5cd015]] | Ethereum | USDC | $20.00 | 2026-05-05 |
| [[Donors/0x12846be7b801c745cb62ac41423894b2d97185d0]] | Ethereum | TIK | $16.00 | 2026-05-08 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $15.00 | 2026-05-08 |
| [[Donors/0x8003e06ec13c41415ea9dc427f0ada49f16b0d42]] | Ethereum | USDC | $15.00 | 2026-05-08 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | TIK | $11.00 | 2026-05-06 |
| [[Donors/0xb53460f73b5cedf6345108cba73f32b9da09172c]] | Ethereum | TIK | $10.00 | 2026-05-05 |
| [[Donors/0x63b540193d0a411fa710f5138412a561322914ae]] | Ethereum | FINN | $9.42 | 2026-05-06 |
| [[Donors/0x0c58478a1c2e080a2c04603ee02f5518861fc5f8]] | Ethereum | FINN | $6.97 | 2026-05-07 |
| Anonymous | Optimism | USDC | $41.99 | 2026-05-06 |
| Anonymous | Ethereum | USDC | $19.99 | 2026-05-07 |
| Anonymous | Base | USDC | $14.00 | 2026-05-07 |
| Anonymous | Ethereum | TIK | $10.00 | 2026-05-10 |
| Anonymous | Ethereum | USDC | $10.00 | 2026-05-09 |

## Categories
**Tags:** infrastructure, public-goods, tech
**Main:** Community, Economics & Infrastructure, Technology

## Description

Simbolik is a [VSCode](https://marketplace.visualstudio.com/items?itemName=RuntimeVerification.simbolik) and [Cursor](https://open-vsx.org/extension/RuntimeVerification/simbolik) extension that brings engineering tools for smart-contract security and quality assurance into the IDE, including:

  


**Test explorer**

  


See all your Foundry tests at a glance, run them individually or in batches. The test explorer makes it easy to understand your test suite's structure and quickly iterate on complex test scenarios.

  


  


  


**Test coverage**

  


Understand exactly which lines of your code are covered by tests, and which aren't. Systematically improve your test coverage and ensure that critical edge cases are not overlooked.

  


  


  


**Static analysis**

  


Simbolik continuously runs Foundry's native static analysis detectors on your code, surfacing warnings and potential issues right in your editor as you type.

  


  


  


Simbolik is built and maintained by [Runtime Verification](https://runtimeverification.com/), the team behind [KEVM](https://github.com/runtimeverification/evm-semantics) — the formal specification of the EVM, maintained continuously since 2017 — and [Kontrol](https://kontrol.runtimeverification.com/)[,](https://kontrol.runtimeverification.com/\),) our Foundry-native formal verification engine. Simbolik is in daily use across hundreds of individual developers, protocol teams, and security researchers.

  


For transparency, we note that Simbolik also includes a proprietary Solidity debugger that is only partially open source. None of the raised funds is used for closed-source development or operations. All work funded by this round ships under BSD-3 to our [public GitHub](https://github.com/runtimeverification/simbolik-vscode) repository.

  


## Roadmap

  


The five deliverables below ship *consecutively, in priority order*, as funding accumulates. Each ships with marketplace distributions of the VSCode and Cursor extensions, and published documentation. Anything funded ships in full; anything underfunded does not start. Budgets cover engineering, documentation, and release operations.

  


**1\. Kontrol formal verification, integrated — $0 - $15,000**

  


[Kontrol](https://kontrol.runtimeverification.com/) _(_ Runtime Verification’s Foundry-native formal verification engine) becomes a built-in Simbolik feature. Where a Foundry test exercises only random inputs, a Kontrol proof exercises every possible input the path condition admits, surfacing nuanced bugs and providing stronger guarantees.

  


In Simbolik, the test explorer gains a “Prove” action that runs symbolic execution on any test, with results reported alongside conventional pass/fail status. Because proofs do not always terminate quickly, timeout and partial-proof states are reported explicitly rather than hidden behind an indefinite spinner; when a property fails, the offending input is shown as a concrete counterexample. A tutorial accompanies the integration, walking developers from “I write Foundry tests” to “I write formal specifications” through a sequence of working examples.

  


**2\. Stack-too-deep detector with auto-fix — $15,000 - $25,000**

  


Stack-too-deep is one of Solidity’s oldest and most-criticized rough edges; the annual Solidity developer surveys have repeatedly ranked it among the language’s top compiler frustrations. The error occurs when a function’s local variable footprint exceeds the EVM’s 16-slot stack window.

  


A new static analysis detector flags the condition in realtime as code is being written, with quick-fix actions for the standard refactors, so the rewrite happens at design time rather than at deadline.

Importantly, this allows tools such as code coverage and debuggers that rely on disabled gas optimizations to run without manual refactoring of the codebase.

  


**3\. AI-assisted, coverage-guided test synthesis — $25,000 - $40,000**

  


Simbolik gains a test-synthesis feature that uses an LLM to generate Foundry tests, informed by its existing test coverage reports. Simbolik renders line coverage in the editor gutter today; the new “Generate test” action prompts the LLM with an uncovered code path and the existing test suite as context, then validates each test candidate against the current code.

  


The deliverable is regression prevention: a generated test pin current behavior as the baseline, so its value compounds in the *next* edit rather than the present one. A growing share of Solidity is now produced by agentic workflows, where developers iterate alongside a coding agent rather than writing each line themselves; the result ships faster but is often under-tested, and the next agent-driven edit has nothing to push back against. A coverage-pinned test suite, generated alongside the code, captures an executable specification of what the contract is supposed to do, reducing the rate at which subsequent agent edits silently introduce regressions.

  


**4\. Web-hosted Simbolik for browser-based source review — $40,000-$55,000**

  


A hosted, browser-based Simbolik makes any on-chain-verified contract or transaction auditable directly from a URL, with sources resolved via Sourcify and no local installation required.

  


Two entry points are supported: by contract address (`simbolik.dev/contract/<chain>/<address>`) and by transaction hash (`simbolik.dev/tx/<chain>/<tx-hash>`). The transaction-hash entry point loads every verified contract touched by the transaction into a single workspace: an auditor pastes a suspicious tx hash and sees, in seconds, every contract that participated, opened together — replacing the multi-step manual reassembly through a block explorer that this workflow currently requires. For deeper analysis, a clone-to-disk action in the desktop VSCode and Cursor extensions pulls the verified source into a standard Foundry project layout, so the auditor can keep editing locally with the full toolchain available.

  


**5\. Interactive symbolic execution — $55,000+**

  


Kontrol already exposes the full internal state of a proof, but only through a terminal UI and only at the level of raw KEVM configurations — word stacks, memory regions, 256-bit storage keys, path conditions over symbolic words. For developers fluent in Solidity, that is a steep barrier between writing a specification and understanding why it does or does not go through.

  


This milestone closes the gap on two axes: the TUI is replaced by a graphical interface in the Simbolik test explorer, with breakpoints, single-step and step-over controls, and call-stack navigation; and every paused state is lifted from KEVM back to its Solidity meaning — storage slots as their declared mappings and arrays, packed bytes as struct fields, the symbolic word stack as named locals, path conditions as predicates over Solidity expressions. The engineer reasoning about a proof sees the contract they wrote, not the bytecode it compiled to.

  


This milestone is also where any excess funding lands. Because the final round size is unknown, we are not committing to a specific scope here: every dollar above $55,000 goes toward this deliverable, in priority order — graphical interface first, then progressively wider Solidity-level state lifting. What ships is determined by what is raised; nothing in this section is promised in full.
