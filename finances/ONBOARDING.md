# Onboarding a new client or prospect

The route for one person or company who has talked to you about paid work.

## 1. First contact (stage `lead`)
1. Make `finances/<payer-slug>/<engagement-slug>/`. The payer is whoever signs and pays: a platform buyer is the payer, and the platform is the channel.
2. Copy `templates/engagement.md` to `engagement.md` and fill it in. Stage `lead`.
3. Copy `templates/brief.md` to `brief.md`. Paste what they asked for word for word, with its source and date. No phone numbers or signatures.
4. Not a named person or company? A funder, grant, competition, listing or cold target goes in `../the-next-yes/opportunities/` instead.
5. If there is client knowledge worth keeping, keep it in a notes folder of your own, with the same name, linked both ways.

## 2. Before agreeing (`briefed`, then `quoted`)
1. The brief should state the job type, the length or hours, and the scope. List what is missing and ask for it.
2. Quote on `templates/quote.md`. Set your own numbers in `rates.md` first.
3. Record the rate or price in `engagement.md` (`value`) and say who said it and where.

## 3. At agreement (`signed`)
1. Say what the agreement is: a signed `contract.md` plus PDF, or a platform order (note its id). Contract wording comes from your own template; assistants do not draft it.
2. Add a row to `quote-history.csv` with the job type, rate or price, and billing basis.
3. Keep logins, keys and access for the client's systems out of this folder.

## 4. While working (`active`)
1. Log hours in `time.md` (`templates/time.md`) as you go.
2. Add a dated line under "Where it stands" in `engagement.md`. Keep `next_action` and `next_date` current.

## 5. After the work (`delivered`, `invoiced`, `paid`)
1. Invoice on `templates/invoice.md`, or note the platform payout.
2. Add `ledger.csv` rows: `invoiced`, `paid`, and `expense` for fees. Decide whether fees get their own row or amounts are logged net, and keep to it.
3. Fill in `hours_actual` on the `quote-history.csv` row.
4. Draft a `../the-next-yes/work/` record. Its Use stays ASK FIRST until the client says yes to being named.
5. In your weekly review, look at every engagement's `next_date` and at stale leads.

## Always
- Engagements start as `Use: PRIVATE`. A client may be named publicly only after they say yes.
- Check the platform's own rules before moving messages, files or payment off it.
