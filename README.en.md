# Team memory

This repository stores knowledge that is usually lost in chats: decisions,
incident reviews, repeatable procedures, and notes. Everything is ordinary
Markdown, while TeamBrains adds search and cited answers.

## How to use it

- Write your own records under `workspaces/<your-folder>/`. Do not edit another
  person's workspace. There is no separate «shared» folder: a team-wide decision
  is an ordinary record of type `decision` or `runbook`. It has an author, and
  that is the point — you can see whom to ask about it.
- Do not silently delete outdated knowledge. Mark the old record as superseded
  and link the replacement so search stops presenting it as current while
  history remains available.
- `_archive/` folders are not indexed and contain records removed from memory.

## Layout

| Path | Purpose |
|---|---|
| `workspaces/<person>/summaries/` | work summaries saved by an agent or person |
| `workspaces/<person>/notes/` | notes |
| `workspaces/<person>/assets/` | images and attachments |
| `.teambrains/people/` | person cards: name, role, responsibilities, what to ask them about |
| `.teambrains/` | indexing settings and record schemas |
