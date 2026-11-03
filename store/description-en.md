# Rhythm Tap — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Tap four neon lanes in time with fully synthesized tracks. PERFECT to MISS
judging, combo streaks with pitch-up fanfares, three songs from Calm to
Frenzy, and SSS ranks to chase. Free, no install.

(187 characters — within the 200-char limit)

## Details

- Genre: Rhythm / Music / Arcade
- Controls: Touch — tap the 4 screen zones (multi-touch supported).
  Keyboard: D F J K, or ← ↓ ↑ → as an alternative. M = mute, ESC = quit.
- Features: 3 songs (Calm Waters 90 BPM / Neon Groove 115 BPM / Frenzy
  Circuit 140 BPM), chart and music generated from the same beat grid,
  PERFECT(±50ms ×100) / GREAT(±100ms ×50) / GOOD(±150ms ×20) / MISS judging,
  combo display with a pitch-up sound every 50 combo, grade ranks
  C→SSS, per-song best scores in localStorage, mute toggle,
  auto-pause when the tab is hidden, spectrum-bar background driven by
  AnalyserNode, neon lanes with hit beams and ripples.
- Tech: Vanilla JavaScript, Canvas, WebAudio (all music and SFX synthesized
  in real time — kick/snare/hats, bass line, scale-based lead melody).
  Single-file HTML5, no external assets, no frameworks, no tracking.
  Works offline once loaded.
- Portal SDK: loads only on crazygames / gamedistribution / gd.games
  domains (gameplayStart / gameplayStop wired for CrazyGames); runs
  standalone anywhere else.

## Tags

rhythm, music, arcade, timing, ddr, beats, synth, casual, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on matching domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales, portrait-first), touch + keyboard input
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## itch.io
- Upload zip (rhythm-tap-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport 480×720, kind: html
- Pricing: $0 (donations optional)

## GameDistribution
- Upload rhythm-tap-gd.zip (contains only index.html)
