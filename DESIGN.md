---
name: Furina-he GitHub Profile
description: Swiss-Bauhaus pixel poster system tailored to Furina-he (NeverGiveUp) — monumental 9-row pixel display typography, hydro-blue orthogonal pixel weaves, framed 28x28 chibi avatar pixel portrait, and 2x2 Bauhaus project poster cards across Light and Dark modes.
colors:
  paper: "#FAF9F5"
  ink: "#0A0A0A"
  hydro-cyan: "#00A3CC"
  hydro-sky: "#7CC4FA"
  cobalt: "#2370E8"
  sodium-orchid: "#F3ACF0"
  emerald: "#2BA676"
  signal-amber: "#F5B700"
typography:
  display:
    fontFamily: '"Inter Tight", -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: "20px"
    fontWeight: 800
  mono:
    fontFamily: '"JetBrains Mono", "SFMono-Regular", Consolas, monospace'
    fontSize: "11px"
    fontWeight: 600
---

# Design System: Furina-he GitHub Profile

## Overview

**Creative North Star: "Swiss-Bauhaus Hydro Pixel Poster"**

Inspired by [evepupil/evepupil](https://github.com/evepupil/evepupil)'s Swiss-Bauhaus pixel poster architecture and tuned to `Furina-he`'s own identity (`NeverGiveUp`, CloudLink `#00A3CC` Signal Cyan, and blue-haired chibi avatar), the profile pairs `0px` architectural rules (`1px solid`), monumental 9-row pixel display typography (`FURINA-HE`), parenthetical metadata, and four deterministic orthogonal pixel weaves (`plus`, `cross`, `tartan`, `basket`) with calm micro-animations across GitHub Light and Dark themes.

## Key Components

- **Split Poster Hero (`assets/hero-*.svg`)**: Left field carries the 9-row pixel display wordmark `FURINA-HE`, role & language stack, and `$` command bar with a calm 1.4s blinking block cursor; right field sets a framed `28x28` graphic pixel portrait of `Furina-he`'s chibi avatar (with a gentle 5.2s eye blink and `prefers-reduced-motion` guard) over a Hydro Blue `+` pixel weave; bottom strip renders 4 pixel metric counters (`04`, `12`, `20+`, `MCP`).
- **Sharp-Cornered Action Buttons (`assets/btn-*.svg`)**: `0px` radius primary and bordered links for `cloudlink.blessc.com`, `openpet.myfurina.top`, `CloudLink v0.6.0`, and `@Furina-he`.
- **Flush 2x2 Bauhaus Pixel Project Cards (`assets/card-*.svg`)**: Four clickable `49%`-width SVG poster cards (`CloudLink`, `OpenPet`, `Virtual`, `CarView`), each topped with a distinct orthogonal pixel weave band and a bespoke `16x16` pixel emblem.
- **Daily Contribution Rhythm (`.github/workflows/snake.yml`)**: Auto-generated Light/Dark contribution snake framed under a matching `(activity)` section header.

## Regenerating Assets

Run `python scripts/generate_assets.py` after updating metrics, release tags, or project copy to deterministically rebuild and XML-validate all Light/Dark SVGs.
