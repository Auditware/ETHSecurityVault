---
title: "Rescue-Lifeboat"
project_url: "https://qf.giveth.io/project/rescue-lifeboat"
owner: "Kane Mayfield"
owner_twitter: "kanemayfield"
twitter: "https://x.com/KaneMayfield"
tags: ["wallet-security", "incident-response"]
categories: ["art", "culture", "grassroots", "public-goods", "victims' services"]
donation_count: 12
total_usd_donated: 119.52
updates_count: 2
---

# Rescue-Lifeboat

🔗 **Project:** [https://qf.giveth.io/project/rescue-lifeboat](https://qf.giveth.io/project/rescue-lifeboat)
👤 **Owner:** Kane Mayfield
🐦 **Twitter:** [@kanemayfield](https://x.com/kanemayfield)

## Social Media
- 🐦 [Twitter](https://x.com/KaneMayfield)
- 🐙 [Github](https://github.com/KaneMayfield/Rescue-Lifeboat)
- 🌐 [Website](https://kanemayfield.com/)

## Donation Addresses
- `0x56241059e5c3fda10762fc3ac128112c623a94d6`

## Tags
[[Tags/wallet-security|#wallet-security]]  [[Tags/incident-response|#incident-response]]


## Donations

> **12 donations** · **Total: $119.52 USD** (ETH Security QF Round)

| Donor | Network | Currency | USD Value | Date |
|-------|---------|----------|-----------|------|
| [[Donors/sub terranean]] | Ethereum | ETH | $50.01 | 2026-05-04 |
| [[Donors/0xf7f9ff731a18627fbde7ff310138d31aff40d8c4]] | Ethereum | ETH | $47.17 | 2026-05-05 |
| [[Donors/0xc7cbea8f72d1062efa7f397d098448b0016cc1ac]] | Ethereum | TIK | $7.00 | 2026-05-07 |
| [[Donors/0x45656eaa07d95bf60d6fbd98cf68a36256cebbe0]] | Ethereum | TIK | $5.00 | 2026-05-07 |
| [[Donors/0x3265da8751c13a184b3fde54d42156dd958705d9]] | Ethereum | TIK | $5.00 | 2026-05-07 |
| [[Donors/0x8fda1daa6a674c1726d1896e3054b9a82d123f12]] | Base | ETH | $1.16 | 2026-05-01 |
| [[Donors/freshelle]] | Optimism | USDC | $1.10 | 2026-04-29 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | TIK | $1.00 | 2026-05-03 |
| [[Donors/0x9905dd283a9373fd21727eae40518969741c352e]] | Ethereum | FINN | $0.99 | 2026-05-01 |
| [[Donors/0xd39dc38225e642f09eb964d76c85b32ef097bb0d]] | Base | USDC | $0.10 | 2026-05-06 |
| [[Donors/0xbb3883f7178c4ce73e85ee281f21d62262c3b5d9]] | Base | AZUSD | $0.00 | 2026-05-07 |
| Anonymous | Base | USDC | $1.00 | 2026-04-27 |

## Categories
**Tags:** art, culture, grassroots, public-goods,  victims' services
**Main:** Art & Culture, Community

## Description

**Operation Rescue - Lifeboat**

**Free, Open-Source NFT Rescue Tool for Compromised Wallets**

  


In February 2026, my MetaMask wallet got compromised. A sweeper bot was deployed on the address, monitoring it 24/7, draining any ETH the moment it arrived. My NFTs were still there. I could see them. But I couldn't move them because every attempt to fund gas got swept before the transaction landed. I was watching my collection through a glass wall I couldn't break through.

  


Every "whitehat" recovery service I found wanted thousands of dollars to even look at the problem. So I built what I wished had existed, tested it on myself, and rescued 413 NFTs across Ethereum mainnet, Polygon, and Base, plus my Manifold creator contract and my ENS domain. The compromised wallet was drained to zero. The bot had nothing left to take.

  


Operation Lifeboat is the tool that made that happen, now open-source and free for anyone in the same situation.

  


It's a local application. Not a website, not a browser extension. You download a folder, double-click a launcher, and your browser opens to localhost:3000. Your private keys never leave your machine. On Ethereum mainnet, transactions route through MEV Blocker so the sweeper bot never sees the funding or transfers in the mempool. The bot doesn't know you're there until your NFTs are already gone.

The tool scans compromised wallets across Ethereum, Polygon, Base, Optimism, and Avalanche. It estimates gas per token individually, which matters because flat gas limits fail on roughly 20% of non-standard contracts. It scans and sweeps ERC-20 tokens. It shows native balances across all chains. It handles Manifold contract transfers. And it has a scan-only mode so you can assess a compromised wallet without entering any keys. Just look before you commit.

  


Every feature in this tool exists because I hit that wall during a real rescue, at 2am, under real pressure. The gas estimation logic, the MEV protection, the session persistence so you don't lose progress if your browser crashes mid-rescue, the burn button that wipes your keys from memory when you're done. None of this was theoretical. It was all tested live on 413 real tokens with a real bot watching.

  


Nobody should have to go through this without a tool built for exactly this scenario. Free. No catch. No percentage. Just help.

  


Funding would go directly toward continued development. Solana support is next, which is essentially a second engine since it's a completely different architecture. Beyond that: improved UX around gas funding so the tool better explains what to do when the compromised wallet is empty, public address read-only scanning so people can assess a situation before touching any keys, and better documentation for non-technical users who are finding this tool at the worst moment of their crypto experience. Everything stays open-source. Everything stays free.

  


Not from a business... im a neighbor.
