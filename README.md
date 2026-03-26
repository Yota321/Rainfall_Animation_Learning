# Rainfall Animation

Pure HTML canvas rain effect. No libraries. Just me figuring out how this works.

---

## Live

👉 [View Animation](https://yota321.github.io/Rainfall_Animation_Learning/)

Or go straight to a version:

- [Rain v1](https://yota321.github.io/Rainfall_Animation_Learning/Rain_v1.html) — first attempt
- [Rain v2 / index](https://yota321.github.io/Rainfall_Animation_Learning/Rain_v2.html) — fixed version

---

## What This Is

Saw [this video](https://youtu.be/veHKIu6-V1I) by Snippets Code. Wanted to understand how it worked. So I built it myself.

This repo is my learning process, not a finished product.

---

## What It Does

- Raindrops fall straight down from random positions across the screen
- Each drop hits the surface and creates a ripple and splash
- Water-blue background
- Slow, calm rain
- Crisp on retina displays
- Fully responsive

---

## What I Learned

- HTML5 canvas basics
- `requestAnimationFrame` render loop
- `devicePixelRatio` for sharp rendering on high-DPI screens
- Depth-based scaling for near vs far drops
- Particle systems: spawning, updating, culling
- `createLinearGradient` for the streak fade on each drop

---

## Files

| File | What it is |
|------|------------|
| `index.html` | Same as v2, GitHub Pages entry point |
| `Rain_v1.html` | First version, perspective rain converging to a vanishing point |
| `Rain_v2.html` | Fixed version, drops fall straight, water-blue background |

---

## Inspired By

[This Website Effect is Weirdly Addictive! by Snippets Code](https://youtu.be/veHKIu6-V1I)

Not a copy. Used it as a reference to understand the concept, then built my own version from scratch.

---

## What's Next

- [ ] Wind and angle effect
- [ ] Mouse click ripple
- [ ] Day / night toggle
- [ ] Mobile touch support

---

*Yota321 — learning in public.*
