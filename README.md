# If Keith had AI at high school

Small interactive builds revisiting the bits of 1980s Scottish school I never understood.
Each experiment is one self-contained HTML file: no build step, no sign-in, works on a phone.

| # | Experiment | Concept | Status |
|---|---|---|---|
| 1 | [The Unreasonably Free Trolley](trolley/) | Forces — resultant force changes velocity, it doesn't sustain it | In progress |

Built with AI as the building partner. The apps themselves contain no AI.

## Layout

- `index.html` — the portfolio page
- `<experiment>/index.html` — one folder per experiment

## Publishing

Push to `main` and Vercel deploys it. Preview branches get their own URL.
