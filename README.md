# Provenly
![Provenly logo](assets/logo.png)

On-chain provenance and royalty tracking for physical goods via NFT tags.

## Overview

Provenly links physical products such as art, sneakers, and luxury goods to on-chain NFTs using QR or NFC tags. Buyers can verify authenticity instantly, and creators earn resale royalties automatically. Every resale is recorded on Solana, building a transparent, permanent ownership history for each item.

## Problem

Physical goods lack verifiable provenance. This makes counterfeiting easy and makes it nearly impossible for creators and brands to enforce resale royalties once an item leaves the primary sale.

## Solution

Provenly mints an NFT twin for each physical item and tags it with a QR code or NFC chip. Every verified resale transaction is recorded on-chain, and royalty splits are enforced automatically, so creators keep earning long after the first sale.

## Features (MVP)

- Mint an NFT twin linked to a physical item via QR/NFC code
- Scan-to-verify authenticity flow for buyers
- On-chain resale marketplace with enforced royalty split
- Ownership history timeline viewable per item
- Brand dashboard to track all issued items and royalties earned

## Tech Stack

- Anchor (Solana smart contracts)
- Metaplex (NFT minting and metadata)
- React (frontend)
- NFC/QR SDK (tag scanning)
- Node.js (backend services)
- Solana Pay (payments)

## How It Works

```
[Physical Item] --tagged with--> [QR/NFC]
        |
        v
[NFT Twin Minted on Solana] <--Anchor + Metaplex
        |
        v
[Buyer Scans Tag] --> [Verify Authenticity + Ownership History]
        |
        v
[Resale Transaction] --> [On-chain Royalty Split Enforced]
        |
        v
[Brand Dashboard: Items + Royalties]
```

1. A brand or artist mints an NFT twin for a physical item and attaches a QR/NFC tag.
2. A buyer scans the tag to verify authenticity and view the item's full ownership history.
3. When the item is resold, the marketplace records the transaction on Solana and enforces the royalty split defined at mint time.
4. Brands track all issued items and royalties earned through a dashboard.

## Roadmap

- Partner with a small fashion or art brand for a pilot batch
- Add compressed NFTs to scale to thousands of items cheaply
- Build a resale marketplace plugin for Shopify stores

## Pitch

- Slides: [docs/pitch.pdf](docs/pitch.pdf)
- Script: [docs/pitch-script.md](docs/pitch-script.md)

## Team

- [Name] — Role
- [Name] — Role
- [Name] — Role

Built for the Colosseum hackathon.

---

🎬 Pitch video: [docs/pitch-video.mp4](docs/pitch-video.mp4)
