# Stage 1 — Problem + Lightweight Spec

**Tool:** ChatGPT or Claude (not Lovable yet)
**Goal:** Get specific about who this is for and what it does — before
writing a single Lovable prompt.

## Why this stage exists

It's tempting to open Lovable and start describing a screen. That produces
something that *looks* like a product without necessarily solving anything
for anyone specific. This stage forces two quick decisions first: the
problem, and the shape of the app that solves it.

## How to run it

1. Open [`prompt.md`](prompt.md) and fill in the blanks with your own idea
   — a rough one-liner is enough to start.
2. Paste it into ChatGPT or Claude and actually engage with the follow-up
   questions — this only works if you answer honestly instead of taking
   the first draft.
3. Once the problem is clear, ask directly: *"Now turn this into a short
   spec: a list of screens, the core flow between them, and anything
   explicitly out of scope for a first version."*

## Worked example — InvoiceTrack

- **Who:** an independent contractor or small-business owner who currently
  tracks invoices in a spreadsheet
- **Today:** manually checks the spreadsheet to see who owes what; easy to
  lose track of who's overdue
- **Pain:** no reminder system — payments slip through the cracks
- **Better:** open one screen, immediately see who's overdue, send a
  reminder in one click

**Resulting screen list:** Dashboard, Invoice List, Invoice Detail, New
Invoice. **Core flow:** Dashboard → Invoice List → Invoice Detail → send
reminder. **Out of scope for v1:** real payment processing, multi-user
accounts, recurring invoices.

## What "done" looks like

- Who, in one sentence — a specific person, not "everyone"
- What "better" looks like for them, in plain language
- A short screen list (3-5 screens) and the core flow between them
- One or two things explicitly out of scope for the first build

Carry these into [Stage 2](../02-lovable-prompt).
