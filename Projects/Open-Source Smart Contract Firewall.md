---
title: "Open-Source Smart Contract Firewall"
project_url: "https://qf.giveth.io/project/open-source-smart-contract-firewall"
owner: "IVa V"
owner_twitter: "LisVikkk"
twitter: "https://x.com/LisVikkk"
tags: ["smart-contract", "monitoring"]
categories: ["computer science", "financial-services", "industry-and-innovation", "infrastructure", "tech"]
donation_count: 13
total_usd_donated: 71.95
updates_count: 1
---

# Open-Source Smart Contract Firewall

🔗 **Project:** [https://qf.giveth.io/project/open-source-smart-contract-firewall](https://qf.giveth.io/project/open-source-smart-contract-firewall)
👤 **Owner:** IVa V
🐦 **Twitter:** [@LisVikkk](https://x.com/LisVikkk)

## Social Media
- 🐦 [Twitter](https://x.com/LisVikkk)
- 🐙 [Github](https://github.com/ivanvolov/moat/)
- 📱 [Telegram](https://t.me/IVIkkk)
- 🌐 [Website](https://ivanvolov.github.io/moat/)

## Donation Addresses
- `0xf93d6bd233823e8ccb6658da931f694331520e6e`
- `GExPe7kWLBXZAiVym1HvhVfbgkxkcqVELq8yCohMYHha`

## Tags
[[Tags/smart-contract|#smart-contract]]  [[Tags/monitoring|#monitoring]]

## Related QF Projects
- [[Projects/Echidna A Fast Smart Contract Fuzzer|Echidna: A Fast Smart Contract Fuzzer]]


## Donations

> **13 donations** · **Total: $71.95 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x0918e33f6c64c1a34fe08b7a296973d303653349]] | Gnosis | XDAI | $21.00 | 2026-04-28 |
| [[Donors/Lauren Luz]] | Gnosis | GIV | $18.07 | 2026-05-06 |
| [[Donors/0x7bde1c894deede897486ff425c8ad9d2c5795359]] | Ethereum | ETH | $6.87 | 2026-04-27 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $2.00 | 2026-05-07 |
| [[Donors/0x511a926af6181ed4a9e057d12df5d90e53a87278]] | Optimism | ETH | $1.39 | 2026-05-09 |
| [[Donors/0xe20838f254f8ae310da5ea3b534f564df426ef2f]] | Optimism | ETH | $1.14 | 2026-05-08 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0xc3068d66c17b82b0a13db5a65110bb2f332326ff]] | Base | USDC | $1.10 | 2026-05-06 |
| [[Donors/0xd80c03e50a9859a1df3d18bb7cbb011cffdc0d28]] | Arbitrum | ETH | $1.03 | 2026-05-08 |
| Anonymous | Ethereum | TIK | $10.00 | 2026-05-03 |
| Anonymous | Ethereum | USDC | $5.00 | 2026-05-05 |
| Anonymous | Ethereum | FINN | $2.26 | 2026-04-30 |
| Anonymous | Base | USDC | $1.00 | 2026-04-27 |

## Categories
**Tags:** computer science, financial-services, industry-and-innovation, infrastructure, tech
**Main:** Economics & Infrastructure, Finance, Technology

## Description

> If you're generous enough to donate, keep in mind that to unlock part of the [quadratic-funding pool of TheDAO round](https://x.com/Giveth/status/2047339433007915128), you will also need to donate to at least two [other projects](https://qf.giveth.io/qf/ethereum-security) (minimum $1 each) — otherwise the algorithm will not recognize your donation. Thank you so much!

  


[Moat](https://ivanvolov.github.io/moat/) is an open-source, decentralized pre-execution transaction-level firewall for smart contracts.

  


It is for any protocol team that wants to **shrink their attack surface** — especially teams **shipping fast** , teams **too early-stage to afford the audit** they should have before going to production, and teams trying to **convince risk-averse LPs** that their funds are safe.

Moat originated as an internal solution in response to that exact pressure: running a DeFi protocol where security was the core promise and needing a practical way to back it up.

  


## **The Solution**

It sits in front of your critical functions — deposits, withdrawals, swaps, anything you choose — and emulates every incoming transaction before it touches your protocol. If the transaction violates a rule or an invariant defined by your team, it is blocked before execution. A timelock always activates on any rejection, providing the protocol team with a configurable window (e.g., 30 minutes) to do incident response — after which the user can proceed with pushing the transaction through.

  


## **Reality**

Protocols keep getting hacked. The current responses are reactive: frontrun the attack transaction in the mempool, or pause the entire protocol after the fact. The race defenders rarely win. By then, funds are often already gone. Moat addresses the mitigation gap by enforcing the simple invariants the team already understands — protocol-level ones (reserve ratios, solvency, share-price bounds) and economic ones (per-user yield, profit caps) — before state changes occur.

  


The existing solutions are not enough:

  


\- There is no permissively-licensed **day-one** firewall where the protocol team authors the rules and ships them in their own repo.

\- **Hypernative Firewall** is closed-source, proprietary, and enterprise-priced — unavailable to most early teams.

\- **Forta Firewall** and **Ironblocks** ship a custom-rule surface, but the products are built around vendor-managed detection — AI Attesters and compliance filters at Forta, Approved Patterns at Ironblocks — designed for L2s, rollups, and protocols subscribing to a catalog. Neither is a permissively-licensed primitive a lean team can drop in and run with its own simple rules.

  


Lean DeFi teams in 2026 — increasingly shipping with LLM-assisted audits and no firewall budget — are exactly the buyer with nothing to drop in today. Moat fills that gap. Open source, auditable, easy to use at day-one.

  


## **Architecture**

It operates at the intersection of a thin on-chain enforcement layer and an off-chain validator:

  


\- **The on-chain layer is the modifier and the force-through.** A single modifier added to the functions you choose to protect — `withdraw`, `deposit`, anything critical. Routes the call through the firewall, blocks it on the validator's verdict, but still opens a 30-minute force-through timelock. That is the entire on-chain surface — every rule runs in the off-chain validator below.

\- **The protocol team writes the rules.** Two shapes, both natural to the engineers who designed the protocol. _Pre/post-state invariants_ — the same Foundry/Echidna predicates already in your test suite: constant-product, share-price bounds, reserve ratios, solvency. _Statistical bounds_ — limits on aggregate behavior proven via zk-coprocessor (Brevis): per-user yield caps, profit thresholds, TVL anomaly bands. The class of rules that catches the **_one address suddenly earning 1,000,000% APY while every other LP earns 10%_** exit, without any black-box ML. The CTO authors them, ships them in the repo, and can read them out loud to an LP.

\- **Self-hosted backend at v1.** The rules that don't fit on-chain — the full invariant set under state emulation — run on a backend that the team hosts themselves. Early-stage protocols already retain a lot of operational control (admin keys, upgrade powers, the ability to pull liquidity), so a team-hosted validator does not move the centralization needle for v1. The on-chain force-through window keeps the user from ever being permanently censored, regardless.

\- **Moving to an AVS.** As the protocol decentralizes and TVL grows, the validator moves to an EigenLayer / Symbiotic AVS. A set of independent operators runs the same emulation + predicate logic, BLS-aggregates the verdicts, and the team is no longer a trusted operator. This is what makes the firewall credible to LPs at the mature stage.

\- **Users are protected from both attackers and censorship.** Every blocked transaction triggers a 30-minute timelock. After 30 minutes, the user can always push through.

  


## **Composability**

Moat is the floor, not the ceiling. A team integrates it on day one and keeps it. As the protocol matures and TVL grows, enterprise tooling layers on top — Hypernative's threat intel, Forta's attester network, and custom monitoring. Moat persists underneath as the place where the protocol-specific, non-outsourceable rules live: the invariants only the team can write.

  


## **Milestones**

**Milestone 1** — ~10 ETH

On-chain modifier and force-through state machine, self-hosted off-chain validator with the rule runtime for both Foundry-style invariants and Brevis-proven statistical rules, basic rule template set. Implementation is well advanced — the grant covers the final stretch and security review before public release.

> _$300M+ lost to DeFi exploits in 2025 (_[_DeFiLlama_](https://defillama.com/hacks?time=1y) _). Access control failures and code vulnerabilities account for the majority, exactly the class of attacks that pre-execution emulation catches. Any team with M1 deployed is no longer a soft target._

  


**Milestone 2** — ~8 ETH

Decentralized AVS on EigenLayer / Symbiotic. Multiple independent operators, no single backend. Data-feed integrations (ChainSecurity, Chainlink, third-party threat intel), richer rule templates.

> _Removes the last trusted third party, which makes the firewall credible to LPs._

  


**Milestone 3** — ~4 ETH

Preset rule library covering the most common exploits across lending, AMM, vaults, and staking. Pick a template, deploy, done.

> _~95% of teams covered out of the box._

  


## **Conclusion**

It is a transaction-level circuit breaker that any team can drop in today. It is not a replacement for other tools or professional audits. As your protocol matures, grows TVL, and builds out its security practice, you layer those on top. Moat is the floor — something you can have from day one, before you have the budget or the team for anything else.
