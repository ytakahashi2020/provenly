# Provenly

_On-chain provenance and royalty tracking for physical goods via NFT tags_

## Summary

Provenly links physical products (art, sneakers, luxury goods) to on-chain NFTs using QR/NFC tags, letting buyers verify authenticity and enabling creators to earn resale royalties automatically. Every resale is recorded on Solana, building a transparent ownership history.

## Target users

Independent artists, small brands, resale marketplaces, and collectors

## Problem

Physical goods lack verifiable provenance, making counterfeiting easy and resale royalties nearly impossible to enforce.

## Solution

Mint an NFT twin for each physical item, tag it with NFC/QR, and enforce royalty splits on every verified resale transaction recorded on-chain.

## MVP features

- Mint NFT twin linked to a physical item via QR/NFC code
- Scan-to-verify authenticity flow for buyers
- On-chain resale marketplace with enforced royalty split
- Ownership history timeline viewable per item
- Brand dashboard to track all issued items and royalties earned

## Chains

Solana

## Tech

Anchor, Metaplex, React, NFC/QR SDK, Node.js, Solana Pay

## Category

Consumer

## Why now

Cheap NFT minting and compressed NFTs on Solana make it economically viable to tag mass-market physical goods, unlike expensive Ethereum minting.

## Roadmap

- Partner with a small fashion or art brand for pilot batch
- Add compressed NFTs to scale to thousands of items cheaply
- Build resale marketplace plugin for Shopify stores
