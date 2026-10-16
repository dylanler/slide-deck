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

Swipe works on touch screens. The tiny controls appear top-right on hover.

## Slides

1. Title — compute flowing up an exponential
2. How a chatbot is made — 4 animated, plain-language scenes (guess the next word → learn from examples → humans rank answers → practice against the judge); click a step to jump
3. 2023 hints → 2026 reality (click cards to flip)
4. The Bitter Lesson — human knowledge vs. search + learning, cycling domains
5. Scaling laws — log-log loss curves, compute slider
6. Three ways to spend compute — read more (pretraining + SFT), practice more (RL), think longer (test-time), with real examples and the training-vs-using split
7. Chronology — two tracks: 2019–2024, then a zoomed 2025 → Oct 2026 line (π0.5, GR00T, AlphaEvolve, Erdős problems, Navier–Stokes, 722 AI math papers…); hover dots
8. Test-time compute — animated tree search + accuracy curve
9. RLVR — sample → verify → reinforce loop
10. Agentic coding — live terminal + METR task-horizon chart
11. VLAs — pixels + words → action tokens → robot arm
12. Embodied agents — System 2 planner / System 1 policy
13. Mind map — draggable
14. Humanoid actuator, exploded (rotary strain-wave & linear roller-screw; hover parts)
15. Humanoid cost breakdown (hover donut)
16. Lab robot (Opentrons-style), exploded; collapses to run a pipetting protocol
17. Self-driving lab loop
18. Labs you can prompt — startup showcase: C5R Facility-0 (GIFs from its launch video), Periodic Labs, Lila Sciences, Medra, Automata, Trilobio, Radical AI, Emerald Cloud Lab, Tetsuwan Scientific
19. What to invest in — clickable bubbles
20. Close

Slide 18 uses images and GIFs in `assets/labs/`, taken from each company's website and C5R's launch videos on X. Keep that folder next to `index.html`.
