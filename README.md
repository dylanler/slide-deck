# slide-deck

**The Bitter Lesson & Scaling Laws** — a 5-minute follow-up to Andrej Karpathy's
[State of GPT (Microsoft Build 2023)](https://www.youtube.com/watch?v=bZQun8Y4L2A).

A single `index.html` (no dependencies, works offline). Almost every visual is
drawn live with JavaScript on `<canvas>`, so the "GIFs" loop on their own and many respond to the mouse.

## Run

Open `index.html` in a browser (Chrome recommended). The deck scales to any 16:9 screen.

| Key | Action |
| --- | --- |
| `→` / `Space` / `PageDown` | next slide |
| `←` / `PageUp` | previous slide |
| `N` | speaker notes (with timing cues) |
| `F` | fullscreen |
| `#7` in URL | jump to slide 7 |

### Deploy to Vercel

It's a static site with no build step. Either import this repo at [vercel.com/new](https://vercel.com/new) (framework preset "Other"), or run `npx vercel --prod` from the repo root.

Swipe works on touch screens. The tiny controls appear top-right on hover.

## Slides

1. The Bitter Lesson — human knowledge vs. search + learning, cycling domains
2. Sutton's own words — excerpt from the 2019 essay, revealed word by word, with its four-beat pattern
3. Title — compute flowing up an exponential
4. How a chatbot is made — 4 animated, plain-language scenes (guess the next word → learn from examples → humans rank answers → practice against the judge); click a step to jump
5. 2023 hints → 2026 reality (click cards to flip)
6. Scaling laws — log-log loss curves, compute slider
7. Three ways to spend compute — read more (pretraining + SFT), practice more (RL), think longer (test-time), with real examples and the training-vs-using split
8. Chronology — two tracks: 2019–2024, then a zoomed 2025 → Oct 2026 line (π0.5, GR00T, AlphaEvolve, Erdős problems, Navier–Stokes, 722 AI math papers…); hover dots
9. Test-time compute — animated tree search + accuracy curve
10. RLVR — sample → verify → reinforce loop
11. Agentic coding — live terminal + METR task-horizon chart
12. VLAs — pixels + words → action tokens → robot arm
13. Embodied agents — System 2 planner / System 1 policy
14. Mind map — draggable
15. Humanoid actuator, exploded (rotary strain-wave & linear roller-screw; hover parts)
16. Humanoid cost breakdown (hover donut)
17. Lab robot (Opentrons-style), exploded; collapses to run a pipetting protocol
18. Self-driving lab loop
19. Labs you can prompt — startup showcase: C5R Facility-0 (GIFs from its launch video), Periodic Labs, Lila Sciences, Medra, Automata, Trilobio, Radical AI, Emerald Cloud Lab, Tetsuwan Scientific
20. What to invest in — clickable bubbles
21. Close

Slide 19 uses images and GIFs in `assets/labs/`, taken from each company's website and C5R's launch videos on X. Keep that folder next to `index.html`.
