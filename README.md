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
| Sound / music | 🔊 button (bottom-right) | 🔊 button |

## 🕹️ How to play

- Your car **auto-fires** straight ahead — just focus on steering.
- 💥 **Red enemy cars** take 2 hits to destroy. Blast them before they ram you.
- ◆ **Gold cells** give points **and** fill a bonus meter — collect **10** to earn a
  reward: a **bonus life** (or a random power-up if you're already at full health). Your
  progress shows as `◆ x / 10` in the HUD.
- ❤️ You start with **3 lives** (heal up to 5). Crashing costs a life, with brief
  invincibility after.
- 📈 **It gets harder over time** — the longer you survive, the faster and denser the
  traffic becomes.
- 🏆 Your **best score** is saved in your browser automatically.

### ⚡ Power-ups

Grab the glowing orbs that float down the road:

| Orb | Power | Effect |
| --- | ----- | ------ |
| 🛡 | **Shield** | Absorbs crashes for ~6 seconds — drive straight through enemies |
| ⚡ | **Rapid Fire** | Roughly doubles your fire rate for ~7 seconds |
| ✦ | **Spread Shot** | Fires a 3-way spread for ~7 seconds |

### 🏆 Boss trucks

Every **1000 points**, a **boss truck** rolls in with a health bar. It strafes across
the road and fires back at you — regular traffic pauses so you can focus. Destroy it for
**+500 points and a bonus life** (up to 5).

## 🎨 Choose your car

Pick from **4 neon colors** on the start screen (cyan, green, purple, orange). Your
choice is remembered for next time.

## 📱 Add to your phone's home screen

Open the live site on your phone, then use **Share → Add to Home Screen** (iOS) or the
browser menu → **Install / Add to Home screen** (Android). It gets its own neon app icon
and launches full-screen like a real app. The icon is generated in-code, so there are
still no image files in the repo.

## ✨ Features

- Neon glow visuals, animated lane markers, particle explosions, and screen shake
- Procedural **background music** (a looping synthwave track) + **sound effects** + engine
  drone, all generated live with the Web Audio API — no audio files at all
- Three **power-ups**, **boss battles**, and a **car color picker**
- Installable as a **home-screen web app** (self-generated icon + manifest)
- Rising **difficulty curve** driven by a time-based multiplier
- Responsive canvas that fits any screen size
- Runs fully offline, everything self-contained in one `index.html`

## 🛠️ Tech

Plain HTML5 Canvas + vanilla JavaScript. No frameworks, no external assets, no network
calls. Everything lives in `index.html`.
