# Roadside Rush

**Two childhood road-trip games, across ten worlds.**

[Play Roadside Rush](https://roadside-rush.4ctech.io)

Roadside Rush is a self-contained HTML5 browser game by **4CTech**, featuring two game modes inspired by classic imaginary car-window games.

## Game modes

- **Window Ninja** — Run beside a scrolling road, jump obstacles, double-jump, slide under hazards, and collect stars.
- **Hand Surfing** — Ride simulated airflow, rise and dive to avoid obstacles, catch gusts, and collect stars.

## Ways to play

- **Journey:** 100 levels across 10 themed worlds, with separate locally saved progress for each mode.
- **Endless:** Keep going as speed increases and environments cycle.

## Worlds

1. Neighborhood Escape
2. Country Roads
3. Coastal Highway
4. Mountain Pass
5. Neon Nights
6. Desert Highway
7. Rainforest Run
8. Thunder Road
9. Canyon Country
10. Cross-Country

## Run locally

Open `index.html` in a modern browser. No build tools, dependencies, or server are required.

## Controls

| Action | Window Ninja | Hand Surfing |
| --- | --- | --- |
| Up / Space / on-screen primary button | Jump (press twice to double-jump) | Hold to rise |
| Down / on-screen secondary button | Slide | Dive |
| P / Escape | Pause / resume | Pause / resume |

The game supports touch controls, sound effects, ambience, and local high scores. Journey progress is stored in browser local storage, so it is tied to the browser/device and may be lost if site data is cleared.

## Deployment

This is a static site: deploy the repository root to Vercel with **Framework Preset: Other**, **Build Command: none**, **Output Directory: `.`**. The existing live deployment should only be connected to this repository when ready; connecting GitHub can trigger a production deployment.

## Safety

Roadside Rush is an imaginary game. **Never put your hand outside a moving vehicle.**

© 2026 4CTech. All rights reserved. No open-source license is granted by this repository.
