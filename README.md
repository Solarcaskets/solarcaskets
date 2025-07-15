<div align="center">

# 📦 Solarcaskets

**A hybrid token protocol built on Solana using the Helios400 standard**

Dynamic SPL token-to-NFT conversion, native gambling integration, and verifiable randomness via Switchboard Oracle — all wrapped in a seamless, high-speed protocol.

<br/>

[![🌐 Website](https://img.shields.io/badge/Website-solarcaskets.io-blue?style=for-the-badge)](https://solarcaskets.io)
[![📖 Docs](https://img.shields.io/badge/Docs-docs.solarcaskets.io-green?style=for-the-badge)](https://docs.solarcaskets.io)
[![🐦 Twitter](https://img.shields.io/badge/Twitter-@solar_caskets-1DA1F2?style=for-the-badge&logo=twitter)](https://twitter.com/solar_caskets)
[![🔍 Solscan](https://img.shields.io/badge/View%20on-Solscan-yellow?style=for-the-badge)](https://solscan.io/token/YOUR_TOKEN_ADDRESS)

<br/>

<img src="https://i.imgur.com/J4j5QmA.png" alt="Solarcaskets Banner" width="600"/>

</div>

---

## 📚 Table of Contents

- [Why Was Solarcaskets Created?](#why-was-solarcaskets-created)
- [What Is Helios400?](#what-is-helios400)
- [How Helios400 Works](#how-helios400-works)
- [The Casket Collection](#the-casket-collection)
- [FlowerPoker Gambling](#flowerpoker-gambling)
- [Feature Comparison](#feature-comparison)
- [Technical Architecture](#technical-architecture)
- [Getting Started](#getting-started)

---

## Why Was Solarcaskets Created?

Solarcaskets was created in response to the evolving ERC404 landscape. Rather than copying Ethereum's limitations, we sought to leverage **Solana's advantages**: ultra-fast transaction speeds and near-zero minting fees.

We designed the **Helios400** standard from the ground up to align with Solana’s architecture. The result? A pioneering hybrid asset protocol that:

- Enables **instant, on-chain conversion** between tokens and NFTs
- Embeds a **native gambling mechanic** with **verifiable randomness**
- Utilizes **Switchboard Oracles** to ensure security and fairness

No other hybrid protocol on Solana combines speed, utility, and transparent on-chain gaming like Solarcaskets.

---

## What Is Helios400?

**Helios400** is a Solana-native token standard that creates dynamic "hybrid assets" — capable of existing as both SPL tokens and NFTs.

Imagine owning a liquid, tradable token that can be instantly transformed into a unique NFT — then swapped back when needed.

Key benefits:

- **Flexibility**: Switch between token and NFT forms at will
- **Efficiency**: Solana’s 400ms block times make it fast and cheap
- **Utility**: NFTs enable gaming and gamification use cases
- **Liquidity**: Underlying tokens remain fully recoverable

<div align="center">
  <img src="https://i.imgur.com/tpjER3U.png" alt="Helios400 Diagram" width="600"/>
</div>

---

## How Helios400 Works

Helios400 utilizes a two-contract system with a secure vault and oracle-linked randomness to provide seamless swaps and safe gameplay.

### Getting Your NFT

1. Connect to the Solarcaskets dashboard  
2. Swap 200,000 tokens to mint a randomized NFT  
3. Tokens are held in the Helios400 vault  
4. Switchboard Oracle determines your NFT’s rarity (Diamond, Platinum, Gold, or Wooden)  
5. NFT is sent to your wallet

### Converting Back to Tokens

- Burn your casket NFT via the dashboard  
- Receive exactly 200,000 SOLARCASKETS tokens back from the vault  
- No slippage, no fees, 1:1 exchange guaranteed

### Playing FlowerPoker

- Visit the Solarspace gambling dashboard  
- Stake your NFT to create or join a challenge  
- The winner receives both NFTs  
- Outcomes are verified by Switchboard randomness

### Vault System

Every NFT minted is fully backed by 200,000 SOLARCASKETS tokens held securely in a vault.

- Guarantees **recoverability**  
- Ensures **1:1 backing** for every NFT  
- Simplifies asset management for the user

<div align="center">
  <img src="https://i.imgur.com/6NYO1CW.png" alt="Architecture Diagram" width="600"/>
</div>

---

## The Casket Collection

There are four types of NFTs in the Solarcaskets collection, representing different tiers of rarity and status.

| Casket Type  | Quantity | Rarity          |
|--------------|----------|------------------|
| 💎 Diamond    | 4        | Ultra Rare       |
| 🔷 Platinum   | 1,278    | Extremely Rare   |
| 🟡 Gold       | 1,536    | Rare             |
| 🪵 Wooden     | 2,182    | Common           |

- Requires 200,000 $CASKET to mint  
- Distributed randomly via Oracle  
- Required to access FlowerPoker gambling

---

## FlowerPoker Gambling

Inspired by RuneScape’s legendary game, FlowerPoker is a 1v1 NFT-staking minigame where the player with the best flower combination wins both caskets.

### 🎲 Flower Generation Probabilities

| Flower Type   | Chance     |
|---------------|------------|
| Orange        | 15.39%     |
| Blue          | 15.3%      |
| Yellow        | 14.65%     |
| Mixed         | 14.66%     |
| Red           | 14.08%     |
| Assorted      | 10.78%     |
| Purple        | 14.84%     |
| ⚫ Black       | ~0.2%      |
| ⚪ White       | ~0.1%      |

### Winning Hands (Ranked Best → Worst)

1. 5-of-a-kind  
2. 4-of-a-kind  
3. Full House (3 + 2)  
4. 3-of-a-kind  
5. 2 Pair  
6. No Pair

Strategic betting and the rarest flowers (Black, White) introduce both excitement and unpredictability.

<div align="center">
  <img src="https://i.imgur.com/G57gBzv.png" alt="FlowerPoker Diagram" width="600"/>
</div>

---

## Feature Comparison

| Feature                        | SPL Token | NFT | Hybrid (ERC404-style) | **SOLARCASKETS** |
|-------------------------------|-----------|-----|------------------------|------------------|
| Token Fractionalization       | ✅        | ❌  | ✅                     | ✅               |
| NFT Protocol Interoperability | ❌        | ✅  | ✅                     | ✅               |
| Native Liquidity              | ✅        | ❌  | ✅                     | ✅               |
| SPL Compatibility             | ✅        | ❌  | ✅                     | ✅               |
| Non-Fungible Properties       | ❌        | ✅  | ✅                     | ✅               |
| On-Chain Gambling Integration | ❌        | ❌  | ❌                     | ✅               |
| Switchboard Oracle Support    | ❌        | ❌  | ❌                     | ✅               |
| Fast Transactions (<400ms)    | ✅        | ✅  | ✅                     | ✅               |
| Minting Costs <$0.01          | ✅        | ✅  | ✅                     | ✅               |
| Dynamic NFT Generation        | ❌        | ❌  | ✅                     | ✅               |
| Automatic Token↔NFT Conversion| ❌        | ❌  | ❌                     | ✅               |

---

## Technical Architecture

### 📦 Token Economics

- **Total Token Supply**: 1,000,000,000 SOLARCASKETS  
- **Total NFT Supply**: 5,000  
- **Conversion Rate**: 200,000 tokens → 1 NFT  
- **Oracle Fee**: 0.005 SOL per flower generation request

### Security Features

- Program-Derived Addresses (PDAs)  
- Token vaults for custody  
- Atomic transaction design  
- Switchboard Oracle for randomness  
- Smart contract-based escrow during gameplay

---

## Getting Started

### Prerequisites

- A Solana wallet (e.g., Phantom, Solflare)  
- 200,000 SOLARCASKETS tokens  
- A small amount of SOL for gas fees (~0.005)

### Quick Start Guide

1. Connect your wallet at [solar caskets dashboard](https://solarcaskets.io)  
2. Acquire 200,000 SOLARCASKETS tokens  
3. Swap tokens for a randomized NFT casket  
4. Play FlowerPoker via the dashboard  
5. Swap NFT back into tokens at any time

