# Rainfall Animation

Pure HTML canvas rain effect. No libraries. Just me figuring out how this works.

---

## Live

👉 [View Latest (v3)](https://yota321.github.io/Rainfall_Animation_Learning/Rain_v3.html)

Or jump to a specific version:

- [index / v2](https://yota321.github.io/Rainfall_Animation_Learning/) — stable version
- [Rain v1](https://yota321.github.io/Rainfall_Animation_Learning/Rain_v1.html)
- [Rain v2](https://yota321.github.io/Rainfall_Animation_Learning/Rain_v2.html)
- [Rain v3](https://yota321.github.io/Rainfall_Animation_Learning/Rain_v3.html)

---

## What This Is

Saw [this video](https://youtu.be/veHKIu6-V1I) by Snippets Code. Wanted to understand how it worked. So I built it myself.

This repo is my learning process, not a finished product.

---

## Version History

### v1 — First Attempt
- Basic canvas rain
- Drops fell toward a vanishing point, creating an upside-down V shape
- Black background
- Resolution looked blurry on high-DPI screens
- No interactions

### v2 — Fixed the Basics
- Drops now fall straight down from random positions across the full screen width
- Fixed resolution with `devicePixelRatio` for crisp rendering on retina screens
- Water-blue background gradient
- Slow, calm rain instead of heavy/fast
- Ripples, splash particles and mist added

### v3 — Perspective + Interactions
- Full tilted perspective surface, horizon line at ~38% of screen height
- Ripples are flat ellipses near the horizon, rounder near the bottom, like rain on actual water
- Drops fall toward random points on the surface instead of just straight down
- Wind toggle with smooth easing, direction label, affects drops, particles and mist
- Day / Night toggle, two full colour palettes
- Click anywhere on the surface to spawn a ripple and crown
- Mobile touch support, tap and drag both work
- Fully responsive, surface recalculates on every resize

---

## What's Coming in v4

- [ ] Sound, ambient rain audio that reacts to density
- [ ] Rain intensity slider, from drizzle to downpour
- [ ] Splash size based on drop depth
- [ ] Underwater / looking-up-through-water mode

---

## Files

| File | What it is |
|------|------------|
| `index.html` | Stable version (same as v2) |
| `Rain_v1.html` | First attempt |
| `Rain_v2.html` | Kept here, index updates to newer versions over time |
| `Rain_v3.html` | Latest version |

---

## What I Learned

- HTML5 canvas basics
- `requestAnimationFrame` render loop
- `devicePixelRatio` for sharp rendering on high-DPI screens
- Depth-based scaling for near vs far drops
- Particle systems: spawning, updating, culling
- `createLinearGradient` for the streak fade on each drop
- Affine perspective projection for a tilted surface
- Lerping wind strength for smooth transitions
- Handling pointer and touch events on canvas

---

## Inspired By

[This Website Effect is Weirdly Addictive! by Snippets Code](https://youtu.be/veHKIu6-V1I)

Not a copy. Used it as a reference to understand the concept, then built my own version from scratch.

---

## This Is Just One Thing I Made

If you want to see actual design work: [sayanahamed.online](https://www.sayanahamed.online/)

---

*Golam Sayon Ahamed — learning in public.*
