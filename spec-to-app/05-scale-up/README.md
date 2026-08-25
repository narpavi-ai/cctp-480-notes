# Stage 5 — Scale Up After Lovable (Optional)

**Tool:** GitHub (optional), then whatever comes next
**Goal:** Know your options once the app works — none of which are
required.

> **This stage is entirely optional.** Stages 1-4 already gave you a real,
> working, shareable app with nothing but Lovable, ChatGPT/Claude, and a
> browser. Read this if you're curious what's next.

## Option 1: Connect Lovable to GitHub

*(Source: [Lovable docs — GitHub integration](https://docs.lovable.dev/integrations/github).)*

Lovable can two-way sync your project's actual code to a GitHub
repository — edits in Lovable push to GitHub, and edits pushed to GitHub
pull back into Lovable. Set up from **Project settings → Git → GitHub**;
Lovable creates the repo for you (you can't connect an existing one).

**Why you'd want this:** it gives you an ordinary codebase — useful if you
(or a developer) want to edit code directly or run the app outside
Lovable.

## Option 2: Do nothing

If you don't connect GitHub, the app keeps living in Lovable with a
shareable link, exactly as it does today. You can keep prompting Lovable
to extend it any time.

## Roughly in order of effort, later

1. **Custom domain** — point your own domain at the published app.
2. **Real backend features** — accounts, payments, more complex data via
   Lovable's Supabase integration, still no-code.
3. **Hand code to a developer** — with GitHub sync on, a technical
   collaborator can clone the repo and work in their own editor.
4. **Rebuild pieces outside Lovable** — for parts that outgrow a no-code
   builder, the synced repo is a normal codebase a developer can take over
   incrementally.

None of this needs to happen today. It's worth knowing the door exists.
