# Building a Duplex — Lessons From Mine

A personal duplex lessons-learned checklist, shared as a website instead of a spreadsheet:
real experiences (including the regrets) from building and living in a duplex, organised
into 7 categories / 135 lessons for a friend building a duplex-plus-laneway.

**Live site:** https://zerononeex.github.io/duplex-checklist/

- Single self-contained `index.html` — no build step, no framework, no external requests.
- Check-offs are stored only in the visitor's own browser
  (localStorage key `duplex-checklist-v1`); nothing is sent to a server.
- To update: edit the data block in `index.html`, commit to `main`, and GitHub Pages republishes.
