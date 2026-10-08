# PartForge

_Collect and trade rocket component NFTs, then assemble them into working ships_

## Summary

PartForge treats individual rocket components (engines, tanks, fins) as tradable NFTs with on-chain stats, letting users collect, trade, and combine them into custom rocket builds. The simulator reads each part's NFT metadata to calculate real flight performance, turning part trading into strategic gameplay.

## Target users

Trading card game fans, collectible NFT traders, simulation gamers

## Problem

Existing NFT games rarely let component-level assets meaningfully affect gameplay mechanics in a transparent, verifiable way.

## Solution

Encode each rocket part's stats on-chain so simulation outcomes are provably derived from owned NFTs, making part trading strategically valuable.

## MVP features

- Mint individual rocket parts (engine, tank, fin) as NFTs with stats
- Inventory UI to select owned parts and assemble a rocket
- Simulation engine computes flight results from combined part stats
- Marketplace to buy/sell/trade individual part NFTs
- Rarity tiers affecting part performance and market value

## Chains

Solana

## Tech

Anchor, Metaplex Token Metadata, React, Node.js backend, Phantom Wallet Adapter

## Category

Gaming

## Why now

Composable NFT standards on Solana now make it easy to build gameplay that directly reads and uses on-chain item metadata.

## Roadmap

- Add crafting/fusion mechanic to combine parts into rarer ones
- Launch seasonal part drops and limited edition engines
- Build a leaderboard tying part quality to competitive rankings
