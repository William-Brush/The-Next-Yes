---
name: quote-skill
description: Draft a quote for new work from a job type, job length or hours, scope, and the owner's cost history. Draft only; the owner sends it. Use when there is a new brief or a client asks what a job would cost.
---

# Quote skill

## Inputs
1. Job type
2. Job length or hours
3. Scope, if the client supplied one
4. Cost history

## May read
- The new brief: the engagement's `brief.md`, or what the owner pastes.
- `../rates.md`
- `../quote-history.csv`
- Records in `../../the-next-yes/work/`, using only claims whose Use label allows the audience.

## Must not read, unless the owner names the file in the request
`../ledger.csv`, any `contract.md` or signed PDF, `invoices/`, another payer's `engagement.md`, anything outside this folder.

## Output
A `quote-vN.md` in the engagement folder, made from `../templates/quote.md`. Status DRAFT. It states the inputs as understood, what is missing, and the basis for the price. It never sends anything, never drafts legal terms (contracts come from the owner's template), and never names another payer from the history in quote text.

## Method
The owner defines the pricing method. Until `../rates.md` holds real numbers, do not invent a formula, a rate or a range. Restate the inputs, list the rows in `../quote-history.csv` as they are (job type, hours, quoted, signed, outcome), say how few there are, and ask the owner for each number that is missing.

## After a job is delivered
When the owner names a delivered engagement, draft its `quote-history.csv` row (from `time.md` and the contract terms that matter: job type, scope summary, billing basis, hours, price) and a `work/` record. The owner approves before either is saved.
