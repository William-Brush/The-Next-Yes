# The Next Yes starter kit

A plain-files workflow for two jobs: **getting your next paid yes**, and **tracking every deal and the money from it**. Everything is markdown and two CSV files in this folder. There is no account, no install and no server. One file, `index.html`, gives you a dashboard and readable pages for everything you write.

## Open it
1. Double-click `index.html`.
2. In Chrome or Edge, press **OPEN FOLDER TO EDIT**, choose this folder, and allow editing when the browser asks. (**OPEN READ-ONLY** never changes anything.)
3. Browse: dashboard, pipeline, deal pages, documents, tables and search.

A web page cannot reach your disk by itself, so you choose the folder each visit. Chrome and Edge can remember it (RECONNECT). The browser may say it is "uploading" the files; nothing leaves your computer, and the page blocks every network request.

## Edit from the page
In Chrome or Edge you can change things without leaving the page:
- Open a document and press **EDIT** (its properties and sections) or **RAW** (the whole file).
- Press **+ NEW** for the guided deal steps: **New lead** (opens a deal folder from the templates), **Stage update**, **Agreement**, **Log hours**, **Quote draft** and **Delivered**. Every ledger row, hours entry and quote belongs to a deal, so start with **New lead**.
- Add, change or void rows in the ledger, quote history, rates, evidence, people and hours tables.
- Every save is shown as a before-and-after first, and nothing is written until you confirm.
- The old version of any file a save changes is copied into `.backups/` inside this folder (a hidden folder). **UNDO LAST** on a document brings it back. If a file changed after you opened it, for example in another editor, the save stops and says so.
- Rows are voided, never deleted.

Safari and Firefox can only read the folder. You can also write and edit the files in any text editor, or in Obsidian.

## What is in the folder
| Path | What it is |
|---|---|
| `index.html` | the viewer |
| `the-next-yes/` | who you help, the proof behind it, and every pitch you make |
| `finances/` | your deals, quotes, hours, contracts and money |
| `AGENTS.md`, `CONTEXT.md` | rules for you and for any AI assistant working in this folder |
| `GLOSSARY.md` | what each folder, file and term means |

## The two loops
**Getting the next yes** (`the-next-yes/`)
1. Write the one line in `START-HERE.md`: "For [who], I [what] so they can [result], shown by [proof]." Copy it into `me.md`.
2. Add proof: one file per project in `work/`, one row per piece of proof in `evidence/evidence-log.md`, and the people involved in `people/people.md`.
3. Make one pitch for one person and save it in `outputs/`, dated and named for them.
4. Note funders, platform listings and cold targets in `opportunities/`.
5. Send the one ask yourself.

**Tracking deals and money** (`finances/`)
1. Someone talks to you about paid work: follow `finances/ONBOARDING.md` to open `finances/<payer>/<engagement>/`.
2. Move `stage` in its `engagement.md` as the deal changes: lead, briefed, quoted, signed, active, delivered, invoiced, paid or lost.
3. Log hours in `time.md` and add money rows to `finances/ledger.csv`.
4. When a deal is delivered, add a `work/` record and a `finances/quote-history.csv` row. They become proof, and price history for the next deal.

## Two labels on every claim
- **Status** says how you know it: `MEASURED`, `THEY SAID IT` or `PLANNED`.
- **Use** says who may see it: `PUBLIC`, `ANONYMISED`, `ASK FIRST` or `PRIVATE`.

## Rules worth keeping
- Business money only. Keep personal finances somewhere else.
- Keep logins and keys out of this folder.
- Treat `finances/ledger.csv`, contracts and invoices as guarded.
- Do not share this folder once it holds a client's details. Share a clean copy of the kit instead.

## Credits and what is not included
The "next yes" idea, the one-line exercise, the warm ask, and the status and use labels come from Jake Van Clief's Lyceum course (Eduba). The course's own templates are **not** included. The work-record and opportunity layouts are yours to write, or take them from the course.

The page's guided forms cover the deal side. Work records, pitches and asks are plain files you write yourself (the course explains them).
