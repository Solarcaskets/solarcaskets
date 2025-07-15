<div align="center">

# 📦 Solarcaskets  
**A hybrid token-to-NFT protocol on Solana built with the Helios400 standard**  

Seamlessly convert SPL tokens into NFTs with integrated on-chain gambling powered by Switchboard Oracles.

<br/>

[![🌐 Website](https://img.shields.io/badge/Website-Solarcaskets-blue?style=for-the-badge)](https://your-website.com)  
[![📖 Documentation](https://img.shields.io/badge/Docs-Read%20More-green?style=for-the-badge)](https://your-docs-url.com)  
[![🐦 Twitter](https://img.shields.io/badge/Twitter-@Solarcaskets-blue?style=for-the-badge&logo=twitter)](https://twitter.com/yourhandle)  
[![🔍 View on Solscan](https://img.shields.io/badge/Solscan-View%20Token-yellow?style=for-the-badge)](https://solscan.io/token/YOUR_TOKEN_ADDRESS)

<br/>

<img src="https://i.imgur.com/J4j5QmA.png" alt="Solarcaskets Banner" width="800">

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
- [Contributing](#contributing)
- [License](#license)

---

## ❓ Why Was Solarcaskets Created?

Solarcaskets emerged as a response to the limitations of Ethereum's hybrid token standards like ERC404. With Solana’s faster block times and lower fees, we built a protocol that not only replicates those concepts but pushes them further using Solana-native tools like Switchboard Oracles.

Unlike other implementations, **Solarcaskets is the first project to embed gambling mechanics natively into a token standard**, enabling verifiable, secure, and on-chain randomness for games like **FlowerPoker**.

---

## ⚙️ What Is Helios400?

Helios400 is a custom Solana token standard that merges the liquidity of SPL tokens with the uniqueness of NFTs, enabling assets to fluidly switch between these states.

Key features:
- 1:1 token-to-NFT and NFT-to-token conversion
- Vault-secured backing for every NFT
- Oracle-based randomness for fair outcomes
- Seamless and low-cost transactions on Solana

<div align="center">
  <img src="https://i.imgur.com/tpjER3U.png" alt="Helios400 Diagram" width="800">
</div>

---

## 🔄 How Helios400 Works

The system operates through two smart contracts that manage token swaps, NFT minting, and oracle integrations, all accessible via the **Solarcaskets dashboard**.

### 🧾 Convert Tokens → NFT

- Deposit 200,000 SOLARCASKETS tokens
- Oracle generates randomness
- Receive a randomized casket NFT (Diamond, Platinum, Gold, or Wooden)
- Tokens are stored in a secure vault

### 🔁 Convert NFT → Tokens

- Burn your NFT via the dashboard
- Retrieve your exact 200,000 tokens from the vault

### 🎮 Play FlowerPoker

- Stake your NFT in a 1v1 game
- Oracle determines the winner
- Winner receives both NFTs

<div align="center">
  <img src="https://i.imgur.com/6NYO1CW.png" alt="Helios400 Process" width="800">
</div>

---

## ⚰️ The Casket Collection

Each NFT represents a tier of rarity and utility:

| Casket Type | Quantity | Rarity        |
|-------------|----------|---------------|
| 💎 Diamond   | 4        | Ultra Rare    |
| 🔷 Platinum  | 1,278    | Extremely Rare|
| 🟡 Gold      | 1,536    | Rare          |
| 🪵 Wooden    | 2,182    | Common        |

- **Mint Requirement**: 200,000 SOLARCASKETS tokens
- **Use Case**: Required to play FlowerPoker

---

## 🌸 FlowerPoker Gambling

Inspired by RuneScape’s classic minigame, FlowerPoker lets players bet NFTs in a 1v1 format where flowers are randomly generated using the oracle.

### 🎲 Flower Probabilities

| Flower | Probability |
|--------|-------------|
| Orange | 15.39%      |
| Blue   | 15.3%       |
| Yellow | 14.65%      |
| Mixed  | 14.66%      |
| Red    | 14.08%      |
| Assorted | 10.78%    |
| Purple | 14.84%      |
| ⚫ Black | ~0.2%     |
| ⚪ White | ~0.1%     |

### 🏆 Hand Rankings (Best → Worst)

1. **5-of-a-kind**
2. **4-of-a-kind**
3. **Full House**
4. **3-of-a-kind**
5. **2 Pair**
6. **No Pair**

<div align="center">
  <img src="https://i.imgur.com/G57gBzv.png" alt="FlowerPoker Gameplay" width="800">
</div>

---

## 🔍 Feature Comparison

| Feature / Compatibility      | SPL Tokens | Metaplex NFTs | Traditional Hybrids | **SOLARCASKETS (Helios400)** |
|-----------------------------|------------|---------------|----------------------|-------------------------------|
| Fractionalization           | ✅         | ❌            | ✅                   | ✅                            |
| NFT Protocol Interoperability | ❌         | ✅            | ✅                   | ✅                            |
| Native Liquidity            | ✅         | ❌            | ✅                   | ✅                            |
| Token Interoperability      | ✅         | ❌            | ✅                   | ✅                            |
| Non-fungible Properties     | ❌         | ✅            | ✅                   | ✅                            |
| Solana-verified Gambling    | ❌         | ❌            | ❌                   | ✅                            |
| Oracle Integration          | ❌         | ❌            | ❌                   | ✅                            |
| Fast (<400ms) Transactions  | ✅         | ✅            | ✅                   | ✅                            |
| Low Minting Cost (<$0.01)   | ✅         | ✅            | ✅                   | ✅                            |
| Dynamic NFT Generation      | ❌         | ❌            | ✅                   | ✅                            |
| Auto Token↔NFT Conversion   | ❌         | ❌            | ❌                   | ✅                            |

---

## 🛠 Technical Architecture

### Tokenomics

- **Total Token Supply**: 1,000,000,000 $CASKET
- **Max NFT Supply**: 5,000 caskets
- **Swap Rate**: 200,000 tokens = 1 NFT
- **Oracle Fee**: 0.005 SOL per randomness request

### Security Features

- PDA-based contract accounts
- Vault-secured 1:1 token backing
- Atomic transactions
- Verifiable randomness via Switchboard
- Smart contract-based NFT escrow

---

## 🚀 Getting Started

### Requirements

- A Solana-compatible wallet (Phantom, Solflare, etc.)
- 200,000 $CASKET tokens
- SOL for gas (~0.005 SOL per transaction)

### Quick Steps

1. Connect your wallet at the [Solarcaskets Dashboard](https://your-website.com)
2. Acquire 200,000+ $CASKET
3. Swap for a random NFT
4. Join a FlowerPoker game
5. Swap back to tokens anytime

