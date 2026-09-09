# SUGR Community Treasury — Technical Verification

## Current Official Treasury

**Network:** Cardano Mainnet

**Address**

`addr1wx8m0ykl983j099ulp93z6q2tm5v4uwu63h209vfujjr4mc4cu408`

The current treasury is a Shelley-era **enterprise script address** with a script-controlled payment credential and no staking credential.

## Payment Script

**Script Hash**

`8fb792df29e32794bcf84b11680a5ee8caf1dcd46ea79589e4a43aef`

**Threshold:** 2-of-3

Authorized public payment key hashes:

1. `2f28e297c33f7fa481c46d78393d8c2ac38ed9d1d074575d9b62509e`
2. `32c2051a1366250ea0f478794cb0e89f88a51c0484a4b76412d6dcf6`
3. `bd230768ac17d7d58c7d96deebc4daa3bf06712c67e058bad230022a`

The canonical public representation is [`payment-script.json`](./payment-script.json).

These are public cryptographic identifiers. This repository intentionally does not map them to individual signer identities.

## Independent Script Verification

The native script was independently reconstructed and checked against the treasury address.

Expected payment script hash:

`8fb792df29e32794bcf84b11680a5ee8caf1dcd46ea79589e4a43aef`

The treasury address exposes the same payment script credential.

## Mainnet Operability Test

Before migrating treasury assets, a real Mainnet spend was performed from the replacement treasury.

**Funding UTxO**

`90b9b8e7871dfe28353a91a37e31a1859ee2320c08c9b641d138ebee7fe4c909#0`

**Spend TXID**

`a154f3abab3530a241c64fbe5e117b651cfd258e92edea545a2a979d9c3b660d`

Verified result:

- consumed 5.000000 ADA
- paid a 0.174301 ADA network fee
- produced a 4.825699 ADA output
- satisfied the 2-of-3 native script with two independent vkey witnesses
- confirmed successfully on Cardano Mainnet

## Legacy Treasury Migration

**Retired treasury**

`addr1x8r7229fv0yvzxu6ehdh6mlfqzfm72n6sjuctw4ee5pz3r8mxz70nxpx89ztkptddveudu82mgp72qrpx8ps5awnyr4snrd9uc`

**Migration TXID**

`eed7c76d78e5d59240ff6bb715daeadc6a4a85c5c58f09f60d3ccedf716d9bd7`

**Block:** `13906298`  
**Confirmed:** 2026-09-06 22:21:52

On-chain verification showed:

- retired treasury spent 3.072004 ADA
- retired treasury spent 22,000,000 SUGR
- current treasury received 2.890883 ADA
- current treasury received 22,000,000 SUGR
- network fee was 0.181121 ADA

The replacement treasury became the operational SUGR Community Treasury after the successful spend test and asset migration.

## SUGR Asset

**Policy ID**

`766fce8055f39d40fcfc19721677b3deb2e7846950ae08dce757f1e7`

**Asset Name Hex**

`53554752`

**Asset Name**

`SUGR`

## Public / Private Boundary

This verification record documents public cryptographic evidence only.

It does not publish private keys, seed/recovery phrases, wallet backups, signer identity-to-key-hash mappings, or private operational configuration.

## Historical Evidence

Retired treasury records are preserved under [`history/`](./history/) for audit/history only. They must not be interpreted as identifying the current official treasury.
