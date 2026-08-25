# Stage 2 — The Lovable Prompt

**Tool:** ChatGPT or Claude, to *draft* the prompt · then Lovable, to receive it
**Goal:** Turn your Stage 1 spec into one detailed, technical prompt — the
single message that kicks off the build in Stage 3.

## Why this stage exists

Your first message to Lovable matters more than any other — it sets the
foundation everything else gets built on. Rather than guessing at what
makes a good first prompt, ask ChatGPT/Claude (which already has your
Stage 1 spec in context) to draft it for you, following Lovable's own
documented prompting principles.

### Lovable's five prompting principles

*(Source: [Lovable Academy — Learn to Prompt](https://academy.lovable.app/academy/prompting).)*

1. **Know what you're building before you build it** — Stage 1 was for this.
2. **Build one piece at a time** — a working foundation first, then one
   screen at a time, not the whole app in one message.
3. **Say exactly what you want, and what you don't** — give Lovable
   guardrails the same way you'd brief a teammate.
4. **Use the right tool for the job** — Plan mode for thinking things
   through, Build mode for implementing. More in
   [Stage 3](../03-build-in-lovable).
5. **Think in iterations, not one shot** — expect to go back and forth.

## How to run it

1. Open [`prompt.md`](prompt.md) here.
2. Paste in your Stage 1 spec (screens, flow, out-of-scope list).
3. Run it in ChatGPT or Claude — it will draft one detailed, technical
   prompt for Lovable.
4. Save that prompt. You'll paste it into Lovable's chat to open Stage 3.

## What "done" looks like

A single prompt that:

- Opens with a short paragraph describing the app and who it's for
- Names a **concrete visual identity** — a real reference, not a vague
  adjective like "clean" or "modern"
- Explicitly asks for **at least one real visual element** — an icon,
  badge, or thumbnail
- Is precise about every screen, field, and the navigation between them
- Asks for the **foundation only** — placeholder content and working
  navigation, not full data logic
- States what's explicitly out of scope for this first message

Real logic and later screens come as follow-up prompts during the live
build in [Stage 3](../03-build-in-lovable).
