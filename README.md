# SOLARCASKETS

SOLARCASKETS is an innovative hybrid token protocol implementing the Helios400 standard on Solana, featuring dynamic SPL token-to-NFT conversion mechanisms with Switchboard Oracle integration for verifiable on-chain gambling
<div align="center">
  <img src="https://i.imgur.com/J4j5QmA.png" alt="Banner" width="800">
</div>

## Table of Contents

- [Why was Solarcaskets created?](#why-was-solarcaskets-created)
- [What is Helios400?](#what-is-helios400)
- [How Helios400 works](#how-helios400-works)
- [The casket collection](#the-casket-collection)
- [Flowerpoker gambling](#flowerpoker-gaming)
- [Feature comparison](#feature-comparison)
- [Technical architecture](#technical-architecture)
- [Getting started](#getting-started)

---

## Why Was SOLARCASKETS Created?

Solarcaskets was created in response to a notable trend in the past in the ERC404 project landscape. After careful evaluation of existing token standards and their limitations on Ethereum, we recognized that Solana's infrastructure offered superior advantages for our vision. The blockchain's fast transaction speeds and minimal minting costs made it the ideal platform for our ambitious token-to-NFT hybrid protocol.

Rather than simply porting existing ERC404 concepts to Solana, we developed our custom Helios400 standard from the ground up. This innovative approach allows us to leverage Solana's unique architecture while building upon the foundational token-to-NFT mechanics that inspired the crypto community.

Solarcaskets stands out as the first project on Solana to introduce native gambling functionality directly into the token standard. This is not just any gambling mechanism but a meticulously designed system that leverages Switchboard Oracle integration for verifiable randomness. By implementing Switchboard Oracles, we prioritize safety and fairness in the outcomes of our FlowerPoker games, ensuring a secure and transparent gambling experience for users while maintaining Solana's characteristic speed and cost-efficiency.

---

## What is Helios400?

Helios400 is a revolutionary token standard built specifically for Solana that bridges the gap between traditional tokens and NFTs. Unlike regular tokens that can only be traded, or NFTs that can only be collected, Helios400 creates "hybrid assets" that can transform between both states whenever you need them to.

Think of it as having a digital asset that can be liquid like cash when you want to trade it, or unique like a collectible when you want to use it for gaming or show ownership. This flexibility means you're not locked into one form - you can adapt your holdings to whatever opportunity comes up.

The "400" in Helios400 represents Solana's lightning-fast 400-millisecond block times, emphasizing how this standard takes full advantage of Solana's speed and low costs to make these transformations seamless and affordable.

<div align="center">
  <img src="https://i.imgur.com/tpjER3U.png" alt="Diagram1" width="800">
</div>


## How Helios400 Works

Helios400 uses a smart two-contract system on Solana to seamlessly convert between SOLARCASKETS tokens and NFTs through an easy-to-use dashboard interface. The protocol ensures your assets are always safe and recoverable through specialized vault contracts that hold your tokens securely.

### Getting Your NFT (Minting)
Using the SOLARCASKETS dashboard, you simply connect your wallet and use the swap interface to convert your tokens into an NFT. When you initiate the swap, the dashboard automatically handles sending your tokens to the Helios400 contract, which safely stores them in a secure vault. The contract then requests random numbers from the Switchboard Oracle to determine which type of casket NFT you'll receive (Diamond, Platinum, Gold, or Wooden). Your new NFT is created and sent directly to your wallet, while your original tokens stay locked in the vault as backup.

### Converting Back to Tokens (Swapping)
Through the same dashboard interface, you can easily swap your NFT back to tokens. The dashboard handles burning your NFT and the contract releases your original 200,000 tokens from the vault back to your wallet. It's a perfect 1:1 exchange - you always get exactly what you put in.

### Playing FlowerPoker (Gambling)
To gamble, you use the SOLARSPACE platform to create or join challenges. The interface handles all the technical details - your NFT gets escrowed while you play, and the winner automatically receives both NFTs.

### The Vault System
Behind the scenes, a separate vault contract acts like a safety deposit box, holding tokens 1:1 for every NFT that exists. This ensures that even if something unexpected happens, your value is always protected and recoverable. The beauty of this system is that you never have to worry about the technical complexity - just connect your wallet to the dashboard and swap with a few clicks!


<div align="center">
  <img src="https://i.imgur.com/6NYO1CW.png" alt="Diagram1" width="800">
</div>


## The Casket Collection

The SOLARCASKETS collection consists of four distinct types of NFTs, each representing a unique casket tier: Diamond, Platinum, Gold, and Wooden. Upon accumulating the required 200,000 SOLARCASKETS tokens, holders are automatically awarded one of these NFT caskets. These NFTs serve as admission tickets for participating in the decentralized FlowerPoker gambling games on the SOLARSPACE platform.

The rarity distribution of generated caskets is as follows:

- **Diamond Caskets**: 150 NFTs (0.25% - Ultra Rare)
- **Platinum Caskets**: 500 NFTs (0.5% - Extremely Rare)  
- **Gold Caskets**: 1,850 NFTs (30% - Rare)
- **Wooden Caskets**: 2,500 NFTs (69.25% - Common)

Each casket type carries different prestige and potential advantages within the gaming ecosystem, with rarity inversely proportional to the total supply of each tier.

---

## FlowerPoker Gaming

Flowerpoker is Solarcaskets' signature gambling game, inspired by the classic RuneScape minigame. Each player uses their NFT casket to participate in 1v1 matches where the outcome is determined by randomly generated flower combinations via Switchboard Oracle.

### Flower Generation Probabilities
- Orange flowers: 15.39%
- Blue flowers: 15.3%
- Yellow flowers: 14.65%
- Mixed flowers: 14.66%
- Red flowers: 14.08%
- Assorted flowers: 10.78%
- Black flowers: ~0.2% (2 in 1,001) - Ultra Rare
- Purple flowers: [Variable]
- White flowers: [Variable]

### Winning Hand Rankings (Best to Worst)
1. **5-of-a-kind**: Five flowers of the same color
2. **4-of-a-kind**: Four flowers of the same color
3. **Full house**: Three flowers of one color + two of another
4. **3-of-a-kind**: Three flowers of the same color
5. **2 pair**: Two flowers of the same color
6. **No pair**: All unique flower colors

### Available Flower Colors
The game features 9 distinct flower colors: Assorted, Black, Blue, Mixed, Orange, Purple, Red, White, and Yellow. Each color has its own probability of appearing, with Black flowers being the rarest, creating an additional layer of strategy and excitement to each match.


<div align="center">
  <img src="https://i.imgur.com/G57gBzv.png" alt="Diagram3" width="800">
</div>


---

## Feature Comparison

| Feature / Compatibility | SPL Tokens | Metaplex NFTs | Traditional Hybrid Solutions | SOLARCASKETS (Helios400) |
|------------------------|------------|---------------|----------------------------|-------------------------|
| Fractionalization | ✓ | ✗ | ✓ | ✓ |
| NFT Protocol Interoperability | ✗ | ✓ | ✓ | ✓ |
| Native Liquidity | ✓ | ✗ | ✓ | ✓ |
| SPL Token Interoperability | ✓ | ✗ | ✓ | ✓ |
| Non-fungible Properties | ✗ | ✓ | ✓ | ✓ |
| Solana-verified gambling | ✗ | ✗ | ✗ | ✓ |
| Switchboard Oracle support | ✗ | ✗ | ✗ | ✓ |
| High-speed transactions (<400ms) | ✓ | ✓ | ✓ | ✓ |
| Low minting costs (<$0.01) | ✓ | ✓ | ✓ | ✓ |
| Dynamic NFT generation | ✗ | ✗ | ✓ | ✓ |
| Automatic token-to-NFT conversion | ✗ | ✗ | ✗ | ✓ |

---

## Technical Architecture

### Token Economics

- **Total Supply**: 1,000,000,000 Solarcaskets tokens
- **NFT Supply**: 5,000 unique caskets
- **Conversion Rate**: 200,000 tokens = 1 NFT
- **Oracle Fee**: 0.005 SOL per randomness request

### Security Features

- Vault-secured token custody
- Atomic transaction processing
- Oracle-verified randomness
- PDA-based account derivation
- Smart contract escrow for gaming

---

## Getting Started

### Prerequisites

- Solana wallet (Phantom, Solflare, etc.)
- SOL for transaction fees
- Solarcasket tokens for minting

### Quick Start

1. **Connect Wallet**: Visit the SOLARCASKETS dashboard and connect your Solana wallet
2. **Acquire Tokens**: Obtain 200,000+ SOLARCASKETS tokens
3. **Mint NFT**: Use the swap interface to convert tokens to a random casket NFT
4. **Start Gaming**: Use your NFT on SOLARSPACE to play FlowerPoker
5. **Swap Back**: Convert your NFT back to tokens anytime through the dashboard

### Swap Process

```
Tokens → NFT: 200,000 SOLARCASKETS → Random Casket NFT
NFT → Tokens: Casket NFT → 200,000 SOLARCASKETS
Gaming Fee: 0.005 SOL per game
```

---

## Contributing

We welcome contributions to the SOLARCASKETS ecosystem. Please read our contributing guidelines and submit pull requests for any improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Disclaimer**: Gambling involves risk. Please play responsibly and within your means. SOLARCASKETS provides verifiable randomness but cannot guarantee profits or prevent losses.
