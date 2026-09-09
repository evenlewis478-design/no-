# 🥔 Roblox Potato Graphics

A free, client-side settings planner for Roblox.

Pick a **Potato Mode**, keep separate profiles per game, fine-tune 20 graphics options, and get clear performance estimates.  
**You still apply the changes yourself inside Roblox** (Settings → Graphics).

This tool cannot open the Roblox client, inject FastFlags, or change any settings for you. No website can do that safely.

---

## Features

- **Potato Modes** — Normal → Low → Potato → Extreme Potato → Absolute Potato
- **20 individual graphics sliders** (texture, shadows, particles, lighting, etc.)
- **Game profiles** — different setups for Brookhaven, Blox Fruits, BedWars, etc.
- **Optimizer** — guided flow + checklist of what to set in Roblox
- **Performance estimates** (FPS, GPU, CPU, memory — clearly labeled as estimates)
- **History** of optimizations
- **Themes**, accent colors, accessibility options, reduced motion

---

## How to use

1. Open `index.html` in any modern browser (or host the folder on GitHub Pages / Netlify / etc.)
2. Choose a mode or tweak individual settings
3. Run the Optimizer if you want the guided checklist
4. Open Roblox → Settings → Graphics → set Mode to **Manual** and move the quality slider as recommended

---

## Project structure

```
roblox-potato-graphics/
├── index.html          # Main page
├── css/
│   └── style.css       # All styles
├── js/
│   └── app.js          # All application logic
└── README.md
```

Everything runs fully offline after the first load (Google Fonts are optional).

---

## License

MIT — do whatever you want with it.
