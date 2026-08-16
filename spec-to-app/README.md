# Specification to App

A shortened, in-class version of a full rapid-prototyping workshop: go from
a rough idea to a real, working, multi-screen app — built entirely in
[Lovable](https://lovable.dev), no code editor required.

**Format:** one guided session inside Module 2. **You'll need:** a laptop,
a free [Lovable](https://lovable.dev) account, and either
[ChatGPT](https://chatgpt.com) or [Claude](https://claude.ai).

This is adapted from a longer workshop — see
[`rapid-prototyping-with-ai`](https://github.com/narpavi-ai/rapid-prototyping-with-ai)
if you want the full version later, including its own Blueprint stage
(skipped here to fit the time we have — its thinking is folded directly
into Stage 1 below).

## The five stages

| Stage | Folder | What happens |
|---|---|---|
| 1 | [`01-problem`](01-problem) | Pressure-test the idea: who it's for, what they do today, what "better" looks like |
| 2 | [`02-lovable-prompt`](02-lovable-prompt) | Turn that into one detailed, technical build prompt for Lovable |
| 3 | [`03-build-in-lovable`](03-build-in-lovable) | Build the app screen-by-screen inside Lovable |
| 4 | [`04-test-iterate`](04-test-iterate) | Test what you built and fix it without spiraling |
| 5 | [`05-scale-up`](05-scale-up) | What comes after Lovable, briefly |

The source workshop's separate Blueprint stage is skipped here — Stage 1
below folds its essential thinking (screens, flow, what's out of scope)
directly into the problem conversation, so it lands in one sitting.

## The running example: InvoiceTrack

Every stage folder shows its thinking worked through on the same example
app — **InvoiceTrack**, a small-business invoice and payment-reminder
tracker:

1. **Dashboard** — outstanding balance, invoices due this week
2. **Invoice list** — every invoice, filterable by status (paid / due / overdue)
3. **Invoice detail** — line items, client, due date, a "send reminder" action
4. **New Invoice** — a short form to create one

"Small" means fully click-through-able by the end of Stage 2 — not a
single mockup screen.

## Prompt Engineering, applied

This whole flow is Module 2's Role/Task/Context/Output framework and
Chain-of-Thought thinking, applied to one real build — see
[`good-bad-prompts/`](../good-bad-prompts/) if you want the framework
refresher first.

---

*Adapted with AI assistance from
[`rapid-prototyping-with-ai`](https://github.com/narpavi-ai/rapid-prototyping-with-ai);
may contain errors — verify anything about Lovable's current UI against
[docs.lovable.dev](https://docs.lovable.dev).*
