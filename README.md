# wit-flight ✈ Skydrift

**Play it now → https://yothisislogan.github.io/wit-flight/**

A calm, endless flight over procedural mountains, oceans and clouds — in a single
HTML file with zero dependencies. Open `index.html` in any modern browser
(double-click works; no server or build step needed) and take off.

Deployed with GitHub Pages from the `gh-pages` branch — to ship an update,
push the new `index.html` to that branch.

## Features

- **Endless procedural terrain** — value-noise continents, ridged-noise mountain
  ranges with snow caps, forests, beaches and oceans, streamed in chunks around
  the plane with camera-relative rendering so you can fly forever without
  precision loss.
- **Realistic-but-gentle flight model** — lift/drag/thrust/stall physics with
  angle-of-attack, sideslip weathervaning and coordinated turns. Flight assists
  (bank-angle steering, auto-level, attitude limits) are on by default and can be
  toggled off for full rate-based aerobatics.
- **Touch-first controls** — drag anywhere on the left of the screen for a
  dynamic virtual stick, throttle slider on the right edge. Keyboard
  (arrows / W / S / A / D) and mouse also work.
- **8-bit ambience** — a generative pentatonic chiptune (NES-style pulse and
  triangle voices with echo), engine putt, wind, and soft chimes when you drift
  through a cloud. All synthesized live with the Web Audio API.
- **A slow, eternal golden hour** — the palette drifts between noon, golden hour
  and dusk over several minutes; billboard clouds, shimmering water, valley haze
  and distance fog.
- **Adaptive quality** — resolution and view distance step down automatically on
  slower devices.

## Controls

| Input | Action |
| --- | --- |
| Drag left half of screen | Steer (pull ↓ to climb by default — toggle on the title screen) |
| Right-edge slider / `W` `S` / mouse wheel | Throttle |
| Arrow keys | Pitch & bank |
| `A` / `D` | Rudder |
| `C` | Camera (chase / far / nose) |
| `M` | Mute · `Esc` pause |

Crashes are forgiving: a friendly updraft sets you back in the air.
