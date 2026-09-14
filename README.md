# SUGR Community Treasury 🔐

Public verification and transaction records for the **SUGR Community Revival Treasury** on Cardano Mainnet.

## Current Official Treasury

**Network:** Cardano Mainnet  
**Control:** 2-of-3 Cardano native-script multisig  
**On-chain Handle:** `$sugarfactory`

**Treasury Address**

`addr1wx8m0ykl983j099ulp93z6q2tm5v4uwu63h209vfujjr4mc4cu408`

**Payment Script Hash**

`8fb792df29e32794bcf84b11680a5ee8caf1dcd46ea79589e4a43aef`

**Authorized Treasury Signers**

- Nicholas
- IQ
- Akinga

**2 signatures are required to move treasury funds. No single signer controls the treasury.**

### `$sugarfactory` Treasury Handle

The legacy Sugar Factory handle, **`$sugarfactory`**, was recovered together with the Factory assets and transferred to the current 2-of-3 Community Treasury.

The SUGR Community Revival Team is preserving the handle as part of SUGR's on-chain history and using it as the **recognizable on-chain identity of the SUGR Community Treasury**.

The handle does **not** replace the authoritative treasury address.

For verification or material transfers, always verify the full multisig address published in this repository:

`addr1wx8m0ykl983j099ulp93z6q2tm5v4uwu63h209vfujjr4mc4cu408`

## SUGR Asset

**Ticker:** SUGR

**Policy ID**

`766fce8055f39d40fcfc19721677b3deb2e7846950ae08dce757f1e7`

Always verify the Policy ID when identifying SUGR on-chain.

## Treasury Asset Classification

Assets held at the treasury address may have different purposes and should not automatically be treated as unrestricted Community Treasury funds.

Following the legacy Factory recovery, the treasury address holds both:

- **Community Treasury assets** — assets available for treasury purposes subject to governance and disclosure rules
- **Legacy Factory recovery reserve** — recovered SUGR designated for legacy-holder recovery

The recovered Factory reserve is accounted for separately from ordinary Community Treasury funds even though both are secured by the same 2-of-3 multisig.

See [`transactions/`](./transactions/) for the public transaction history and recovery-reserve handover record.

## Verify It Yourself

- [`GOVERNANCE.md`](./GOVERNANCE.md) — treasury control and disclosure rules
- [`payment-script.json`](./payment-script.json) — canonical public payment script
- [`VERIFICATION.md`](./VERIFICATION.md) — technical verification evidence and known Mainnet tests
- [`transactions/`](./transactions/) — completed material treasury transaction records
- [`history/`](./history/) — retired treasury records preserved for audit/history

Current holdings should always be verified directly on Cardano using the official treasury address above.

## Transparency Principle

The blockchain shows **what moved**. Repository records explain **why it moved**.

Material treasury movements may be documented with:

- purpose
- asset and amount
- destination or counterparty where appropriate
- Cardano transaction ID
- related public disclosure or decision

Only completed transactions are recorded as completed.

## Current Treasury Activity

The legacy Sugar Factory recovery payment and Factory reserve handover have been completed and confirmed on Cardano Mainnet.

A total of **46,643,937 SUGR** was recovered from the legacy Factory and transferred to the Community Treasury for legacy-holder recovery.

The recovered reserve is **not general treasury spending money** and is accounted for separately from ordinary Community Treasury assets.

Completed material treasury movements, including the Factory recovery payment and reserve handover, are documented under [`transactions/`](./transactions/).

Legacy-holder reconciliation and the public recovery process are the next phase of the Factory recovery.

## Public / Private Boundary

This repository contains **public verification material only**.

It does **not** contain:

- seed or recovery phrases
- private/signing keys
- wallet backups
- hardware-wallet secrets
- signer identity-to-key-hash mappings
- internal signing procedures
- internal wallet configuration

Never send funds to an address simply because it appears in an old document or because a human-readable handle is displayed.

Always verify the current official treasury address from this README before making a material transfer.

## Official SUGR Resources

**Website:** https://www.sugarcardano.io/  
**Discord:** https://discord.gg/m8dYN6Gx8H  
**X:** https://x.com/Sugr_on_cardano

## Security

See [`SECURITY.md`](./SECURITY.md).

---

**DON'T TRUST THE SQUIRRELS — VERIFY THE SQUIRRELS. 🐿️🔎**
