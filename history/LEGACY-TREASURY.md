# RETIRED SUGR Treasury — Historical Record

> ⚠️ **RETIRED TREASURY — DO NOT SEND FUNDS TO THIS ADDRESS**
>
> This document is preserved for historical transparency and independent
> on-chain verification.
>
> The current official SUGR Community Revival Treasury is:
>
> `addr1wx8m0ykl983j099ulp93z6q2tm5v4uwu63h209vfujjr4mc4cu408`
>
> Current documentation: [`../README.md`](../README.md)

---

## Retired Treasury

**Network:** Cardano Mainnet

**Retired Address**

`addr1x8r7229fv0yvzxu6ehdh6mlfqzfm72n6sjuctw4ee5pz3r8mxz70nxpx89ztkptddveudu82mgp72qrpx8ps5awnyr4snrd9uc`

This former treasury used a base address with script-controlled payment
and stake credentials.

The address is retired and should not be used for current SUGR treasury
activity.

---

## Retired Payment Script

**Payment Script Hash**

`c7e528a963c8c11b9acddb7d6fe90093bf2a7a84b985bab9cd02288c`

**Stake Script Credential Hash**

`fb30bcf998263944bb056d6b33c6f0eada03e5006131c30a75d320eb`

**Threshold:** 2-of-3

Public payment key hashes:

1. `a455017a5d40ab8c0b494e47bba843294317a641fd1f7b06c943702a`
2. `c6c4a15078df475ce4928f4a888c1725232b5cd69dcb21ffd7e49089`
3. `b6b058b5fa15430c1bc9f396167d6e114f72b41467b43b8994fd5e6d`

The verified historical payment script is preserved as:

[`legacy-payment-script.json`](./legacy-payment-script.json)

These hashes are public cryptographic identifiers and are not private
keys.

---

## Why the Treasury Was Replaced

The retired treasury was established under the previous SUGR project
organization and used a 2-of-3 multisig structure.

During the SUGR community revival, that structure was no longer suitable
for long-term operation for two main reasons.

### 1. The signer structure no longer reflected the active team

A member of the previous team was no longer participating in the
project.

The active revival team had become:

- Nicholas
- IQ
- Akinga

Continuing to depend on a legacy signer structure involving an inactive
participant would have created an unnecessary operational and governance
dependency.

The revival team therefore established a new 2-of-3 treasury with the
three active team members as authorized signers.

No individual signer can independently move treasury assets. At least
two of the three authorized signers are required.

### 2. The legacy treasury depended on a wallet-specific multisig interface

The retired treasury had been created and operated through Eternl's
multisig wallet functionality.

That functionality subsequently became part of Eternl's paid Pro
offering.

Rather than make core treasury operations dependent on continued access
to a specific paid wallet-interface feature, the revival team chose to
establish a new treasury based directly on a Cardano native script.

The current treasury is controlled by the native script itself. Wallet
applications are operational interfaces and are not the source of
treasury authority.

This reduces dependency on any single wallet provider or commercial
wallet feature and makes the treasury control policy independently
verifiable.

The transition did not create a new SUGR token, change the SUGR Policy
ID, alter the token supply, or modify holder balances.

---

## Pre-Migration Revival-Team Allocation

At the beginning of the treasury transition, the retired treasury held
**25,000,000 SUGR**.

As part of establishing the three-member revival team, a one-time
allocation of **1,000,000 SUGR per member** was agreed before the current
Community Treasury was established.

A total of **3,000,000 SUGR** was therefore distributed equally:

| Team Member | Allocation |
|---|---:|
| Nicholas | 1,000,000 SUGR |
| IQ | 1,000,000 SUGR |
| Akinga | 1,000,000 SUGR |
| **Total** | **3,000,000 SUGR** |

These allocations became the respective team members' personal holdings
and are separate from the current SUGR Community Treasury.

The three successful on-chain allocation transactions were:

| Date | Amount | TXID |
|---|---:|---|
| 2026-08-23 | 1,000,000 SUGR | `ce55b3d4d7fd4eef757e7668c70077fbdd79209225105d6990f1a5af2e98c6b2` |
| 2026-08-24 | 1,000,000 SUGR | `67602f19b3eac92c84b66f9c9ca078e249e14125b3fbef34209da86b2e6504d9` |
| 2026-08-24 | 1,000,000 SUGR | `aa6ff15ae29c64d1e522483a63c2e0076bdaac384c2422a9fa5fb9fbfe79352c` |

Following these allocations, **22,000,000 SUGR** remained in the retired
treasury.

The first public SUGR Community Revival announcement subsequently
described the project treasury as holding approximately **22,000,000
SUGR**.

The remaining balance was later migrated in full to the new Community
Treasury.

---

## Treasury Balance Reconciliation

The complete SUGR transition can be reconciled as follows:

| Movement | SUGR |
|---|---:|
| Retired treasury balance at start of transition | 25,000,000 |
| Revival-team allocation — Nicholas | -1,000,000 |
| Revival-team allocation — IQ | -1,000,000 |
| Revival-team allocation — Akinga | -1,000,000 |
| **Remaining treasury balance** | **22,000,000** |
| Migrated to current Community Treasury | **22,000,000** |
| **Unreconciled SUGR** | **0** |

In simple terms:

`25,000,000 - 3,000,000 = 22,000,000 SUGR`

This provides a complete accounting reconciliation between the
historical **25,000,000 SUGR** balance and the **22,000,000 SUGR**
opening balance of the current Community Treasury.

---

## Retirement / Migration

After the pre-migration allocations were completed, the remaining
**22,000,000 SUGR** was migrated from the retired treasury to the
current 2-of-3 SUGR Community Revival Treasury.

**Current Treasury**

`addr1wx8m0ykl983j099ulp93z6q2tm5v4uwu63h209vfujjr4mc4cu408`

**Migration TXID**

`eed7c76d78e5d59240ff6bb715daeadc6a4a85c5c58f09f60d3ccedf716d9bd7`

**Confirmed:** 2026-09-06 22:21:52  
**Block:** `13906298`

Verified movement:

- retired treasury spent **3.072004 ADA**
- retired treasury spent **22,000,000 SUGR**
- current treasury received **2.890883 ADA**
- current treasury received **22,000,000 SUGR**
- network fee was **0.181121 ADA**

This transaction completed the migration of the remaining SUGR balance
from the former treasury and established the opening SUGR balance of the
current Community Treasury.

---

## Verification

All asset movements described in this record can be independently
verified on Cardano Mainnet.

The blockchain is the authoritative source for the actual movement of
assets.

This document provides the historical context and accounting explanation
for those movements.

The historical **3,000,000 SUGR revival-team allocation** is not part of
the current Community Treasury and should not be included when
calculating current treasury holdings.

---

## Status

**RETIRED / HISTORICAL ONLY**

This address is retained in the public record solely for historical
verification.

Current holdings, current control policy, and current transaction records
must be verified from the root [`README.md`](../README.md), not from this
file.
