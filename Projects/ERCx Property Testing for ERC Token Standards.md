---
title: "ERCx: Property Testing for ERC Token Standards"
project_url: "https://qf.giveth.io/project/ercx:-property-testing-for-erc-token-standards"
owner: "Palina Tolmach"
twitter: "https://x.com/rv_inc"
tags: ["standards", "smart-contract"]
categories: ["computer science", "financial-services", "public-goods", "research", "tech"]
donation_count: 8
total_usd_donated: 263.73
updates_count: 1
---

# ERCx: Property Testing for ERC Token Standards

🔗 **Project:** [https://qf.giveth.io/project/ercx:-property-testing-for-erc-token-standards](https://qf.giveth.io/project/ercx:-property-testing-for-erc-token-standards)
👤 **Owner:** Palina Tolmach

## Social Media
- 🐦 [Twitter](https://x.com/rv_inc)
- 💬 [Discord](https://discord.gg/CurfmXNtbN )
- 🐙 [Github](https://github.com/runtimeverification)
- 💼 [Linkedin](https://www.linkedin.com/company/runtime-verification/)
- 🌐 [Website](https://runtimeverification.com/)
- 🔗 [Youtube](https://www.youtube.com/channel/UCZeDdn8F5ARtK5LmRngiLnA)

## Donation Addresses
- `0xe0497d748522582a277d3ecbd87eb41b475202f2`

## Tags
[[Tags/standards|#standards]]  [[Tags/smart-contract|#smart-contract]]


## Donations

> **8 donations** · **Total: $263.73 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/0x8abf01aaea367e7803ca8c18aaf1a2c2e1181184]] | Ethereum | USDC | $199.99 | 2026-05-08 |
| [[Donors/0x4d022f677ffffd5d0cec0722d71407d82636ff62]] | Ethereum | TIK | $15.00 | 2026-05-08 |
| [[Donors/0x8003e06ec13c41415ea9dc427f0ada49f16b0d42]] | Ethereum | USDC | $15.00 | 2026-05-08 |
| [[Donors/0xb8efa90ea762deaa667ee103f4b7230eb456b0f7]] | Ethereum | TIK | $11.00 | 2026-05-06 |
| [[Donors/Lauren Luz]] | Gnosis | GIV | $5.42 | 2026-05-06 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $5.00 | 2026-05-07 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | FINN | $2.32 | 2026-05-07 |
| Anonymous | Ethereum | TIK | $10.00 | 2026-05-10 |

## Categories
**Tags:** computer science, financial-services, public-goods, research, tech
**Main:** Community, Finance, Technology

## Description

ERCx is a free, open-source library of handcrafted Foundry tests for ERC token standards. It checks smart contracts against an extensive property-based test suite, measuring conformance, security properties, and behavioral risks for token implementations. Any developer can install it with forge install, point it at their source code or a deployed contract address, and get a detailed report of how well their token conforms to the standard in minutes.

  


ERCx currently covers ERC-20, ERC-721, ERC-1155, and ERC-4626, with over 900 individual tests across standard conformance, security properties, and implementation features. Each test suite is available in "Light" (fixed addresses) and "Heavy" (fuzzed addresses) versions for different levels of assurance, all open-sourced under <https://github.com/runtimeverification/ercx-tokens>.

  


**Why this matters**

Token standards are the most fundamental building blocks of the Ethereum ecosystem, since every DeFi protocol, vault, NFT marketplace depends on tokens behaving as the standard says they should. But ERC specifications are written in natural language, and implementations routinely deviate in subtle ways (see [d-xo/weird-erc20](https://github.com/d-xo/weird-erc20)), potentially breaking composability and enabling exploits. 

  


ERCx helps catch those issues automatically, using the test suites they are written by hand by engineers who have spent hundreds of hours reading EIP specifications, and then validated [using mutation testing](https://cnandi.com/docs/icst24-cr.pdf) to ensure the tests actually catch the bugs they claim to catch.

  


**How ERCx has been used**

ERCx is used by token developers for pre-deployment testing, by auditors as a first-pass conformance check, and by protocol teams evaluating tokens for integration. For example, Rheo (formerly Size Credit) [uses](https://github.com/rheo-xyz/very-liquid-vaults/tree/e356a70cffe5912618488ff79562db7ce48633b4/test/property/rv) ERCx's ERC-4626 test suite alongside other test suites to test their Very Liquid Vaults. The[ test library](https://github.com/runtimeverification/ercx-tests) is designed to be imported directly into any Foundry project as a dependency, and a[ VSCode extension](https://ercx.runtimeverification.com/ide) provides inline results in the IDE. In addition, it is used by the [ERCx web interface](https://ercx.runtimeverification.com/) that allows anyone to test deployed tokens by address or paste in source code for evaluation.

  


**What's next**

The immediate priorities are maintenance and responsiveness to user feedback: merging community contributions, fixing issues reported by users, and keeping the test suites current with Foundry updates. Beyond that, extending coverage to additional ERC standards and expanding the depth of existing test suites. Longer-term, we see significant potential in AI integration: building AI skills and MCP tooling that let developers and AI agents run ERCx checks as part of automated security workflows, interpret results in context, and get actionable guidance on how to fix failing tests.

  


**Why your support matters**

Every token that ships without proper conformance testing is a composability risk for every protocol that integrates it. ERCx makes it trivial to check token conformance using the free and easy to integrate test suites. Funding keeps them maintained, expanding, and increasingly automated.

  


**Funding breakdown  **

  


All donations fund open-source ERCx Test Token Library development. The library is and will remain freely available under its open-source license. No portion of donations will support commercial services.

  


**$0 - $5,000:** Maintenance and community contributions. Merging [pending contributions](https://github.com/runtimeverification/ercx-tests/pulls), addressing [issues](https://github.com/runtimeverification/ercx-tests/issues) reported by users, keeping test suites compatible with the latest Foundry releases, and general upkeep. This tranche funds the baseline work that keeps ERCx reliable for the teams already using it.

  


**$5,000 - $15,000:** Extending test coverage. Deepening the existing test suites by introducing more security properties, better edge case coverage, expanded heavy (fuzzed) versions for standards beyond ERC-20, and improving documentation and onboarding for developers integrating ERCx.

  


**$15,000 - $30,000:** Supporting additional ERC standards. This tranche funds development of test suites for new standards based on ecosystem demand, with candidates including ERC-2612 (permit), ERC-3525 (semi-fungible tokens), and other standards seeing growing adoption. 

  


**$30,000+:** AI integration and automated workflows. Building AI skills and MCP tooling that enable developers and AI agents to run ERCx as part of automated security workflows: running conformance checks, interpreting results in context, and surfacing actionable fixes. This turns ERCx from a library you run manually into a tool that can be woven into CI pipelines and agentic coding workflows.
