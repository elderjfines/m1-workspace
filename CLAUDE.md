# Working rules for m1-workspace

This is Jhopet's catch-all repo, used mostly from Claude Code on his phone.
Requests arrive as plain-language questions and small tasks that do not fit
any existing project.

## Defaults

- **Answer first, file second.** Give the answer in chat, then save anything
  worth keeping as a Markdown file in the right folder. Never make Jhopet
  open a file to get the answer.
- **One file per inquiry or task**, named `YYYY-MM-DD-short-slug.md`, with a
  one-line title at the top and the date. Start every new item in `inbox/`;
  move it to `notes/`, `tasks/`, or `decisions/` once it is clear what it is.
- **Commit as you go.** Small commits with plain-language messages
  (`Add note: Shopee fee comparison`). Push after every commit so the Mac
  and the phone stay in sync.
- **Nothing sensitive.** No passwords, API keys, tokens, card numbers,
  customer data, or private business figures — this repo may be public.
  If a task needs a secret, describe where it lives, do not paste it.
- **Plain language.** Jhopet is an operator, not a developer. Explain in
  everyday terms, one comparison, no jargon unless he asks for it.
- **Finished things go to `archive/`**, never deleted.

## When something outgrows this repo

If an inquiry turns into a build (an app, a site, a recurring automation,
anything with more than a handful of files), say so and propose a dedicated
repository. Do not let a real project accumulate in here.

## Related projects (do not duplicate their work here)

- **B.E.X** — ad economics and order tracking for the PH COD brands
- **Cassy** — assistant / ops app
- **Home** — household app
- **NRO / FamCo projects** — client work
- **Telegram replies** — auto-reply bot

If a request clearly belongs to one of those, note it in `inbox/` with a
pointer to the right repo instead of solving it here.
