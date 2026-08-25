# Stage 4 — Test & Iterate

**Tool:** Lovable (Preview) + Plan mode
**Goal:** Click through what you built like a stranger would, find what's
broken or confusing, and fix it without getting stuck re-prompting the
same thing over and over.

## Testing checklist

- **Click through the whole core flow, start to finish**, as if you'd
  never seen the app before.
- **Test it as a brand-new user** — refresh, or use an incognito window.
- **Try the "nothing yet" state** — what does a list screen look like
  *before* you've added anything? Is that empty state handled?
- **Try doing things out of order** — skip a step, tap a button twice, go
  back.
- **Read every screen's text out loud** — does it make sense to someone
  who's never seen this app?

## Iteration prompt pattern

When you find something broken, resist "fix it." Describe it like a bug
report — see [`prompt.md`](prompt.md):

```
On [SCREEN], when I [exact steps to reproduce], [what actually happens].
I expected [what should happen instead].

Do not change [anything else that's already working].
```

## Avoiding the re-prompting loop

If you've tried to fix the same thing two or three times and it's still
broken, **stop re-prompting the same way** — this is exactly what
Lovable's own best practices warn against. Instead:

1. Switch to **Plan mode** and describe the problem — let it reason about
   what's likely happening before touching code.
2. If you have an earlier working version, consider reverting and
   re-applying the change more narrowly.
3. If you're truly stuck, it's fine to leave that one thing as a known
   rough edge and move on.

## What "done" looks like

You've clicked through the full flow at least twice (once as if new, once
trying to break it), fixed what clearly didn't work, and you know what (if
anything) is still a known rough edge.

Then move to [Stage 5 — Scale up](../05-scale-up).
