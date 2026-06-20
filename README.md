# AI-Assisted Legal Research — Jacob Gerszten

A small, dependency-free static site showcasing working papers in banking and
financial-regulation law, researched and drafted in collaboration with Claude
(Anthropic) and directed, verified, and edited by the author.

## Contents
- `index.html` — the showcase page (self-contained HTML/CSS, no build step).
- `papers/` — the PDF working papers.

## Papers
- **The Rise of the National Trust Charter** — the OCC's December 2025 crypto
  trust-charter approvals and the GENIUS Act.
- **Sovereign Stablecoins** — state-issued stablecoins (Wyoming FRNT, North
  Dakota Roughrider Coin).

## Framing
Each work is presented as **AI-assisted, human-directed**: Claude served as a
research and drafting partner; the author set the questions and theses, checked
the legal sources, edited the drafts, and is responsible for the content. The
papers are working drafts.

## Update / deploy
Static site — edit and push; GitHub Pages redeploys automatically.
To preview locally: `python -m http.server 8124 --directory .` then open
http://localhost:8124
