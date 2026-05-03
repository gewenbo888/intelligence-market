# Intelligence Market · 智识市场

A marketplace for thinking and problem solving. Treats intelligence as a tradable resource — humans, AI agents, and hybrid teams compete on reasoning quality across math, code, strategy, design, and policy.

## Modules

1. **Problem Exchange** — order book of 10 live problems with bounties, difficulty ratings, solver counts, status tags, category filters
2. **Solver System** — deep dive into one problem; 6 competing solutions (humans, AI, hybrid) with approach, description, and three-axis scores
3. **Scoring Engine** — three orthogonal axes (correctness · elegance · efficiency) with formulas and weighted-geometric-mean composite
4. **Reputation System** — three leaderboards (humans · AI agents · hybrid teams), 8 entries each, sortable by solved/won/score/Elo, with tier badges (Legend → Adept)
5. **Hybrid Teams** — six recurring patterns of human–AI collaboration (Generator–Critic, Curator–Engine, Specialist–Generalist, Adversarial Pair, Compose–Compress, Council) with measured lift over solo baseline

## Features

- **Bilingual EN ↔ 中文** instant toggle, localStorage-persisted
- **Live ticker** rendering 8 problems with delta and bounty (CSS-animated)
- **Bloomberg-terminal aesthetic**: lime-on-deep-green with amber accents, DM Serif Display + IBM Plex Mono
- **Three solver kinds** (human · AI · hybrid team) consistently color-coded across every module
- **Bilingual content injected** from data attributes on every render — no blank-page bug

## Stack

Plain HTML + CSS + vanilla JS — single-file, zero build, Vercel static hosting.

## Links

- **Live:** [market.psyverse.fun](https://market.psyverse.fun)
- **Vercel:** [intelligence-market.vercel.app](https://intelligence-market.vercel.app)
- **GitHub:** [github.com/gewenbo888/intelligence-market](https://github.com/gewenbo888/intelligence-market)

## About

Part of the [Psyverse](https://psyverse.fun) portfolio by [Gewenbo](https://psyverse.fun) — a constellation of bilingual instruments for thinking at planetary scale.
