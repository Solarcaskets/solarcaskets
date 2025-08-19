<div align="center">

# 📦 Solarcaskets

**Solarcaskets is a hybrid token protocol implementing the Helios400 token standard on Solana, featuring SPL token-to-NFT conversion mechanisms with Orao Oracle integration for verifiable on-chain gambling**

<br/>

[![Website](https://img.shields.io/badge/Website-solarcaskets.io-0066CC?style=flat-square)](https://solarcaskets.io)
[![Documentation](https://img.shields.io/badge/Documentation-docs.solarcaskets.io-28a745?style=flat-square)](https://docs.solarcaskets.io)
[![Twitter](https://img.shields.io/badge/Twitter-@solar_caskets-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/solar_caskets)
[![Solscan](https://img.shields.io/badge/View%20on%20Solscan-FFB800?style=flat-square)](https://solscan.io/token/fUGa7swLiTr8RwsZChfPXEX15N6H3WseEDPSDKVpump)

<br/>

<img src="https://i.imgur.com/zZlvBme.png" alt="Solarcaskets Banner" width="600"/>

</div>

---

## 📚 Table of Contents

- [Why was solarcaskets created](#why-was-solarcaskets-created)
- [What is Helios400?](#what-is-helios400)
- [How Helios400 works](#how-helios400-works)
- [The casket collection](#the-casket-collection)
- [Flowerpoker gambling](#flowerpoker-gambling)
- [Feature comparison](#feature-comparison)
- [Technical architecture](#technical-architecture)
- [Getting started](#getting-started)

---

## Why Was Solarcaskets Created?

Solarcaskets was created in response to the evolving ERC404 landscape. Rather than copying Ethereum's limitations, we sought to leverage **Solana's advantages**: ultra-fast transaction speeds and near-zero minting fees.

We designed the **Helios400** standard from the ground up to align with Solana’s architecture. The result? A pioneering hybrid asset protocol that:

- Enables **instant, on-chain conversion** between tokens and NFTs
- Embeds a **native gambling mechanic** with **verifiable randomness**
- Utilizes **Orao Oracles** to ensure security and fairness

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
  <img src="https://i.imgur.com/MZrUoQ0.png" alt="Helios400 Diagram" width="600"/>
</div>

---

## How Helios400 Works

Helios400 utilizes a two-contract system with a secure vault and oracle-linked randomness to provide seamless swaps and safe gameplay.

### Getting Your NFT

1. Connect to the Solarcaskets dashboard  
2. Swap 200,000 tokens to mint a randomized NFT  
3. Tokens are held in the Helios400 vault  
4. Orao Oracle determines your NFT’s rarity (Diamond, Platinum, Gold, or Wooden)  
5. NFT is sent to your wallet

### Converting Back to Tokens

- Burn your casket NFT via the dashboard  
- Receive exactly 200,000 SOLARCASKETS tokens back from the vault  
- No slippage, no fees, 1:1 exchange guaranteed

### Playing FlowerPoker

- Visit the Solarspace gambling dashboard  
- Stake your NFT to create or join a challenge  
- The winner receives both NFTs  
- Outcomes are verified by Orao randomness

### Vault System

Every NFT minted is fully backed by 200,000 SOLARCASKETS tokens held securely in a vault.

- Guarantees **recoverability**  
- Ensures **1:1 backing** for every NFT  
- Simplifies asset management for the user

<div align="center">
  <img src="https://i.imgur.com/I1EH2s7.png" alt="Minting Diagram" width="600"/>
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

- Requires 200,000 Solarcasket tokens to mint  
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

<div align="center">
  <img src="https://i.imgur.com/If0tCDf.png" alt="FlowerPoker Diagram" width="600"/>
</div>

---

## Feature Comparison

<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>SPL Token</th>
      <th>NFT</th>
      <th>Hybrid (ERC404-style)</th>
      <th><strong>SOLARCASKETS</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Token Fractionalization</td>
      <td align="center">✅</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>NFT Protocol Interoperability</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Native Liquidity</td>
      <td align="center">✅</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>SPL Compatibility</td>
      <td align="center">✅</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Non-Fungible Properties</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>On-Chain Gambling Integration</td>
      <td align="center">❌</td>
      <td align="center">❌</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Orao Oracle Support</td>
      <td align="center">❌</td>
      <td align="center">❌</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Fast Transactions (&lt;400ms)</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Minting Costs &lt;$0.01</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Dynamic NFT Generation</td>
      <td align="center">❌</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
      <td align="center">✅</td>
    </tr>
    <tr>
      <td>Automatic Token↔NFT Conversion</td>
      <td align="center">❌</td>
      <td align="center">❌</td>
      <td align="center">❌</td>
      <td align="center">✅</td>
    </tr>
  </tbody>
</table>

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
- Orao Oracle for randomness  
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

