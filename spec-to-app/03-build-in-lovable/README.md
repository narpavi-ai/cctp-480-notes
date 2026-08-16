# Stage 3 — Build in Lovable

**Tool:** Lovable
**Goal:** Turn your Stage 2 prompt into a working app, one screen at a
time, using Lovable's own recommended workflow.

## Lovable's recommended workflow

*(Source: [Lovable docs — Best practices](https://docs.lovable.dev/tips-tricks/best-practice).)*

1. **Paste your Stage 2 prompt first** — it gives Lovable the app's context
   from message one.
2. **Use Plan mode early and often.** Lovable has two main modes:
   - **Plan mode** — conversational and reasoning-only. It explores ideas
     and reasons about a change *before any code is written*, and **never
     modifies your code** — safe to use freely.
   - **Build mode** *(formerly Agent mode)* — actually implements changes:
     explores your project, edits files, resolves issues.

   Lovable's own guidance: spend roughly **60-70% of your time in Plan
   mode** — deciding what to do next — and switch to Build mode only once
   you know exactly what you want built.
3. **Build incrementally, one screen at a time**: layout → real data →
   logic → test. Don't ask for the whole app in one message.
4. **Connect a database last** — only once the front-end and flow feel
   stable.
5. **When something goes wrong, don't just keep re-prompting the same
   fix.** Switch to Plan mode and describe the problem before trying an
   edit again — more in [Stage 4](../04-test-iterate).

## Applied to InvoiceTrack

Screen order: Dashboard skeleton → Invoice List (with placeholder data) →
Invoice Detail → New Invoice form → wire the "New Invoice" form to actually
add to the list → connect real storage last.

## What "done" looks like

- All the screens from your Stage 1 spec, wired with real (not
  placeholder) data and logic
- The app actually saves what the user creates (a new invoice, a status
  change) and reflects it back
- Click-through-able start to finish, as a real, shareable app

Then move to [Stage 4 — Test & iterate](../04-test-iterate).
