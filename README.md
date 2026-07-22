# 🚗 Neon Highway — Drive & Shoot

A fast, neon-styled top-down highway shooter that runs in any browser. Drive up an
endless highway, dodge oncoming traffic, and blast enemy cars with auto-fire. It works
great on both **mobile** (drag to steer) and **desktop** (arrow keys).

No build step, no dependencies — it's a single self-contained `index.html` file.

## ▶️ Play

**Locally:** just open `index.html` in your browser (double-click it).

**Online (GitHub Pages):** enable Pages for this repo (Settings → Pages → Deploy from
branch → `main` / root) and it will be live at:

```
https://<your-username>.github.io/neon-highway/
```

## 🎮 Controls

| Action | Mobile | Desktop |
| ------ | ------ | ------- |
| Steer  | Drag your finger anywhere | `←` `→` or `A` `D` |
| Shoot  | Automatic | Automatic |
| Sound  | 🔊 button (bottom-right) | 🔊 button |

## 🕹️ How to play

- Your car **auto-fires** straight ahead — just focus on steering.
- 💥 **Red enemy cars** take 2 hits to destroy. Blast them before they ram you.
- ◆ **Gold cells** give bonus points — grab them when it's safe.
- ❤️ You start with **3 lives**. Crashing costs a life (with brief invincibility after).
- 📈 **It gets harder over time** — the longer you survive, the faster and denser the
  traffic becomes.
- 🏆 Your **best score** is saved in your browser automatically.

## ✨ Features

- Neon glow visuals, animated lane markers, particle explosions, and screen shake
- Procedural **sound effects** and an engine drone generated with the Web Audio API
  (no audio files needed — fully self-contained)
- Rising **difficulty curve** driven by a time-based multiplier
- Responsive canvas that fits any screen size
- Runs fully offline

## 🛠️ Tech

Plain HTML5 Canvas + vanilla JavaScript. No frameworks, no external assets, no network
calls. Everything lives in `index.html`.
