# finances - deals and business money in

One job: record each deal from first brief to paid invoice, hold the rate card and the quote skill, and keep the one ledger of money events. Business money only.

## Layout
- `ONBOARDING.md` - the route for a new client or prospect, from first contact to paid.
- `<payer>/<engagement>/` - one folder per deal. The payer is who signs and pays: a client who pays you directly is the payer; for work through an agency, the agency is the payer, not the end client. Example: `acme/website-refresh/`.
  - `engagement.md` - the index (frontmatter below)
  - `brief.md` - what they asked for, word for word, with its source
  - `quote-v1.md`, `quote-v2.md`... - one per quote
  - `contract.md` and the signed PDF - guarded
  - `time.md` - hours worked
  - `invoices/` - guarded
- `ledger.csv` - guarded. One row per money event. Columns: `date, engagement_id, event, amount_usd, invoice_no, note`. `event` is one of `invoiced`, `paid`, `expense`, `refund`. A quote is not a money event; it lives in `engagement.md` and `quote-history.csv`.
- `quote-history.csv` - one trimmed row per job: no contacts, no contract terms, but the engagement id stays, so it is not anonymous. What the quote skill reads.
- `rates.md` - your rate card. Blank until you set it.
- `templates/` - engagement, brief, quote, invoice, time log, and a contract stub.
- `quote-skill/SKILL.md`

## engagement.md frontmatter
`id` (payer-engagement, e.g. `acme-website-refresh`), `payer`, `channel`, `stage`, `value`, `next_action`, `next_date`, `client_record`, `use`.
- `channel`: `referral`, `Contra`, `Fiverr`, `agency`, `direct` (your own network), `inbound`. Any other marketplace is named the same way.
- `stage`: `lead`, `briefed`, `quoted`, `signed`, `active`, `delivered`, `invoiced`, `paid`, `lost`. Stage lives in frontmatter, not in which folder the deal sits in, because moving folders breaks links.

## Boundaries
- A named person or company who has talked to you about paid work is an engagement here, starting at `lead`. Grants, funders, competitions, platform listings and cold targets stay in `../the-next-yes/opportunities/`.
- Unpaid work is not an engagement until money is on the table.
- Notes about the client's business can live in a notes folder of your own, with the same name, linked both ways.

## Guarded files
Assistants open `ledger.csv`, any `contract.md` or signed PDF, and `invoices/` only when you name them. The quote skill works from `quote-history.csv`, `rates.md` and the new brief. When a deal is delivered, you name it, and the assistant drafts the `quote-history.csv` row and a `work/` record from `time.md` and the contract terms that matter. You approve before either is saved.

## Scope
Plain files can track quotes, contracts, invoices, hours and payments. They do not reconcile bank accounts or assign tax categories.

## Check
You review every quote before it is sent and every ledger row.

## If unsure where context lives
Stop and ask the owner, then add the answer here.
