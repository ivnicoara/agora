# Agora — Direct Democracy Platform

> *ἀγορά* — the central public square in ancient Greek city-states, where citizens gathered to debate proposals and vote in person. The birthplace of direct democracy.

A working prototype of a platform that lets every citizen propose, debate, vote, and delegate — backed by blockchain, free of parties.

## What's in here

- **`index.html`** — Landing page (hero, manifesto, sections, language selector EN/DE/FR/ES/IT/RO).
- **`demo.html`** — Working interactive demo:
  - **Feed** — Reddit-style proposals with support / oppose / delegate-aware voting
  - **Shorts** — TikTok-style vertical video pitches (linked to their proposals)
  - **Delegates** — liquid democracy: per-topic scope, settings panel, discover & follow new delegates, override and restore
  - **Budget** — D3 bubble flow map (revenue ↔ spending) + AI-flagged wasteful expenses (StopRisipa-style)
  - **Civics** — interactive course that gates direct voting
  - **Propose** — submit text + YouTube link / video upload
  - **User profiles** — Twitter-style pages (`#/u/handle`) with Proposals / Votes / Comments tabs
  - **Proposal pages** — full-page debate views (`#/p/id`)
- **`favicon.svg`** — gradient ἀ mark.

## Run locally

It's static HTML + CDN-loaded Tailwind + D3. No build step.

```bash
python3 -m http.server 8765
# open http://localhost:8765
```

## Stack

Static HTML · Tailwind (CDN) · D3 v7 (CDN) · Inter + Georgia fonts.

---

An open proposal. Not affiliated with any party or government.
