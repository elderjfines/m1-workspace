# m1-workspace

Jhopet's general-purpose workspace for Claude Code on the phone (M1).

Anything that does not belong to an existing project lives here: quick
questions, one-off tasks, research, drafts, small scripts, decisions worth
keeping. Nothing here is a product — it is a notebook that happens to be a
git repo so M1 can open it anywhere.

## Layout

| Folder        | What goes in it                                              |
|---------------|--------------------------------------------------------------|
| `inbox/`      | New inquiries and tasks, one Markdown file each, dated       |
| `notes/`      | Answers, research, and reference material worth keeping      |
| `tasks/`      | Multi-step tasks with their own working files                 |
| `scripts/`    | Small throwaway scripts (Python, shell, Node)                 |
| `decisions/`  | Short records of decisions made, so they are not re-argued    |
| `archive/`    | Anything finished — moved here instead of deleted             |

## Which repo?

Two catch-all repos, split by where the work happens:

- **`m1-workspace`** (this one) — captured on the phone. Quick questions, one-off
  tasks, throwaway scripts, decisions. Fast in, short entries, graduates out when
  something grows.
- **[`general`](https://github.com/elderjfines/general)** — desktop and web sessions.
  Longer research, write-ups and multi-step work that wants a real keyboard.

If an inbox item outgrows the phone, move it to `general/research/` and leave a line
here pointing at it. Project work still lives in its own repo (e.g. `batchline`).

## How to use it from the phone

1. Open this repo in Claude Code on M1.
2. Ask the question or describe the task in plain words.
3. Claude writes the result into the right folder and commits it.
4. When a thread grows into a real project, it graduates out of here into
   its own repository.

See `CLAUDE.md` for the working rules Claude follows in this repo.
