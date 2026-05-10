---
title: "AgnopraxLab"
project_url: "https://qf.giveth.io/project/agnopraxlab"
owner: "Tim Fan"
twitter: "https://x.com/realagnopraxlab"
tags: ["fuzzing", "infrastructure"]
categories: ["computer science", "research", "tech"]
donation_count: 6
total_usd_donated: 114.44
updates_count: 2
---

# AgnopraxLab

🔗 **Project:** [https://qf.giveth.io/project/agnopraxlab](https://qf.giveth.io/project/agnopraxlab)
👤 **Owner:** Tim Fan

## Social Media
- 🐦 [Twitter](https://x.com/realagnopraxlab)
- 🐙 [Github](https://github.com/AgnopraxLab)
- 🌐 [Website](https://www.agnopraxlab.net)

## Donation Addresses
- `0x3ba64750f4a23c3791b7f0975000142554e921a9`

## Tags
[[Tags/fuzzing|#fuzzing]]  [[Tags/infrastructure|#infrastructure]]


## Donations

> **6 donations** · **Total: $114.44 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0xc896e7c0ad9a8f9c787b5bbedceeba259c912d72]] | Polygon | USDC.e | $87.98 | 2026-05-07 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.20 | 2026-05-03 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| Anonymous | Base | USDC | $11.80 | 2026-05-07 |
| Anonymous | Base | ETH | $11.37 | 2026-04-28 |

## Categories
**Tags:** computer science, research, tech
**Main:** Technology

## Description

> **Our Vision**

> Making Ethereum’s communication system safer, stronger, and more trustworthy.

## Why This Matters

Ethereum is not only a blockchain. It is also a living network of computers constantly talking to each other.

If this communication is unreliable or vulnerable, the whole system can suffer:

  * nodes may crash
  * messages may be misunderstood
  * attackers may find hidden weaknesses
  * the stability of the network may be put at risk



Today, most security testing looks at only **one part of this communication system at a time**. But in reality, problems often appear **between different parts working together**. These “in-between” gaps are exactly where dangerous issues can remain unnoticed.

**If the network is not safe, the protocol is not truly safe.**

  


## What We Want To Do

We want to build a new security testing framework that looks at Ethereum’s network communication in a more complete and realistic way.

Instead of checking isolated pieces one by one, our approach will simulate how a peer behaves over time:

  * how it joins the network
  * how it exchanges messages
  * how it reacts to changing conditions
  * how different communication layers affect each other



This helps us find problems that traditional tools are likely to miss.

  


## Why This Is Important

Our goal is simple:

### Find hidden weaknesses earlier

Before attackers or real-world failures expose them.

### Test the system more like the real world

Because real networks are dynamic, messy, and full of interactions—not neat isolated steps.

### Protect the broader Ethereum ecosystem

A stronger network layer benefits:

  * client teams
  * node operators
  * developers
  * users
  * the long-term reliability of Ethereum itself



  


## What This Project Will Deliver

### Open-Source Security Tooling

We will release an open-source toolkit that others can use, extend, and integrate into their own testing workflows.

### Practical Security Improvements

We will work with client teams to help turn findings into real fixes, patches, and improvements.

### Public Knowledge for the Ecosystem

The project will also produce:

  * research publications
  * vulnerability advisories
  * public writeups that help the wider community learn and improve



  


## What Makes This Project Different

Most existing efforts check only limited parts of the network.

Our project focuses on the **whole communication journey** , not just isolated moments.

That means we are not only asking:

> “Can this single message break something?”

We are also asking:

> “What happens when many steps unfold together over time, the way they do in the real network?”

That broader perspective is where many important security problems can be discovered.

  


## Early Proof That This Works

We are not starting from zero.

Our earlier work already produced:

  * a working security-testing prototype
  * real bug discoveries in major Ethereum clients
  * direct engagement with development teams
  * a strong engineering foundation for this next step



This gives us confidence that the new project can create practical value for the ecosystem.

  


## Codebase

  * **GitHub Repository:**  [AgnopraxLab / D2PFuzz](https://github.com/AgnopraxLab/D2PFuzz)



## Selected Bugs We Found

  


  * [go-ethereum issue #31471](https://github.com/ethereum/go-ethereum/issues/31471)
  * [reth issue #15255](https://github.com/paradigmxyz/reth/issues/15255)
  * [erigon issue #13931](https://github.com/erigontech/erigon/issues/13931)
  * [besu issue #8445](https://github.com/hyperledger/besu/issues/8445)
  * [besu issue #8339](https://github.com/hyperledger/besu/issues/8339)



##   


## What We Will Do With Funding

Our current work has built a strong foundation in testing Ethereum’s network layer — the part of the system that allows nodes to communicate, exchange messages, and stay connected.

With funding, we want to take the next step: moving from testing how Ethereum nodes **talk** to testing how they **agree**.

This is important because Ethereum’s security does not depend on communication alone. At its core, Ethereum relies on many independent nodes maintaining a shared view of the chain and reaching agreement under complex, changing conditions. If this agreement process fails, the consequences can be far more serious than a simple networking error.

From a technical perspective, this means extending our fuzzing framework from network-layer behavior into **consensus-state and consensus-algorithm testing**. Compared with network message fuzzing, consensus fuzzing is more demanding because it must reason about:

  * how protocol state evolves over time
  * how different clients handle the same sequence of events
  * how edge cases affect agreement, finality, and fork choice
  * how unexpected inputs or timing conditions may expose hidden implementation differences



The funding will be used primarily for two core needs:

  * **Engineer salaries**
  * To support the research, development, implementation, testing, and maintenance required to extend the framework from network-layer fuzzing to consensus-focused fuzzing.
  * **Server rental and computing infrastructure**
  * To run large-scale fuzzing campaigns, long-duration experiments, multi-client validation, regression testing, and continuous security testing workflows.



##
