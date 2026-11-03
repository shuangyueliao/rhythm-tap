# Rhythm Tap · 4-Lane Beat Tapper

Free single-file HTML5 rhythm game. Four neon lanes, falling beats, three
synth tracks (Calm 90 BPM / Groove 115 BPM / Frenzy 140 BPM). The chart and
the music are generated from the same beat grid, so every note you tap is a
note you hear. PERFECT/GREAT/GOOD/MISS judging, combo with pitch-up fanfare
every 50, grade ranks from C to SSS, per-song best scores saved locally.

**Play:** https://shuangyueliao.github.io/rhythm-tap/

- Mobile touch (tap the 4 lanes, multi-touch) + desktop (D F J K or ← ↓ ↑ →)
- Music and SFX fully synthesized with WebAudio — zero assets, no CDN
- Spectrum-bar background driven by AnalyserNode, portrait-first canvas
- Best scores in localStorage, mute toggle, auto-pause when tab is hidden

## Submitting to portals

The game is a single self-contained HTML file, ready for HTML5 game portals
(CrazyGames, GameDistribution, itch.io). The portal SDK loader activates
only on matching domains (crazygames / gamedistribution / gd.games) and the
game runs standalone anywhere else. Fork/clone and submit.
