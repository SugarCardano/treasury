# SUGR Treasury Transaction Records

This directory is the public record of **completed material treasury movements** made by the SUGR Community Revival Team.

The Cardano blockchain is the authoritative record of the transfer. These files provide the public context for **why** the transaction occurred.

## Management Rule

Create or update a transaction record when community-controlled assets materially move.

Do not create a completed transaction record for a planned transaction that has not yet confirmed on-chain.

Related transactions that form one treasury action may be grouped into one record when that makes the disclosure easier to understand.

## Standard Record

Use this structure for future records:

```markdown
# Short Description — YYYY-MM-DD

**Status:** Completed and confirmed on Cardano Mainnet

## Purpose

Short explanation of why the transaction occurred.

## Transaction

**Date:** YYYY-MM-DD  
**Asset:** SUGR / ADA / USDM  
**Amount:** X  
**From:** Treasury / Counterparty  
**To:** Treasury / Counterparty  
**TXID:** `...`

## Context

Any short explanation needed to understand the transaction.

For related-party transactions, include the relevant disclosed terms or pricing where applicable.

## Supporting Evidence

- Public announcement: [link if applicable]
- Invoice/receipt: [link if publicly available/applicable]
- Related transaction: [link if applicable]

## Status

Confirmed on Cardano Mainnet.
```

## Existing Records

- [`2026-09-06-treasury-migration.md`](./2026-09-06-treasury-migration.md) — migration of 22,000,000 SUGR from the retired treasury to the current 2-of-3 treasury.
- [`2026-09-10-11-internal-sugr-purchase.md`](./2026-09-10-11-internal-sugr-purchase.md) — related-party purchase of 9,900,000 treasury-held SUGR by Nicholas and IQ for a combined 300 USDM.

## Future Legacy Recovery

Individual legacy-holder claims should **not** create dozens of separate treasury Markdown files.

When the legacy recovery process becomes operational, claim activity should be maintained as a single public recovery ledger with only the information necessary for on-chain verification and without unnecessary personal information.
