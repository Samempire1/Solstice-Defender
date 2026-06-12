# Solstice Defender

A browser-based arcade space shooter built for the [DEV June Solstice Game Jam 2026](https://dev.to/challenges/june-game-jam-2026-06-03).

**Play it live → [https://samempire1.github.io/Solstice-Defender/](https://samempire1.github.io/Solstice-Defender/)**

---

## About

Solstice Defender weaves together three June celebrations into nine levels of increasingly intense arcade action. You pilot a beam of light defending the longest day against waves of shadow enemies across three zones:

| Zone | Levels | Theme |
|------|--------|-------|
| Ada's Sky | 1 – 3 | Juneteenth · Galveston, Texas, 1865 |
| Alan's Grid | 4 – 6 | Alan Turing · Bletchley Park, 1941 |
| Sol's Network | 7 – 9 | AI awakening · The present day |

Each zone has its own sky, enemy movement pattern, ambient soundtrack, and story cutscene. Bosses appear on levels 3, 6, and 9.

---

## How to Play

| Control | Action |
|---------|--------|
| A / D or ← → | Move left and right |
| W / S or ↑ ↓ | Move forward and back |
| Space | Shoot |
| B | Bomb — clears all enemies and bullets |
| P / Escape | Pause |
| Mouse hover | Auto-aim and auto-fire |
| Touch | Fully supported on mobile |

### Power-ups

| Icon | Effect |
|------|--------|
| 3X | Triple shot |
| >> | Rapid fire |
| SH | Shield — absorbs one hit |
| 2X | Dual guns |
| 5X | Five-gun spread |
| +1 | Extra life |
| 💣 | Bomb refill |

---

## Features

- 9 levels across 3 themed zones
- 3 difficulty modes: Easy, Normal, Hard
- 7 lives + collectible extra lives
- Screen-clearing bomb with shockwave explosions
- Enemy shields, rage mode, and boss battles
- 5 gun types (single, triple, dual, 5-gun, rapid)
- Combo multiplier system
- Screen shake on hits and explosions
- Parallax scrolling background per zone
- Player trail and particle effects
- Top-5 leaderboard saved to localStorage
- Achievement popups (First Blood, Combo x5, No Damage Wave, Boss Slayer, Bomb Squad)
- Zone transition cutscenes with story context
- Procedural Web Audio API soundtrack — no audio files
- Voice announcements via Web Speech API
- Fully responsive — works on any screen size
- Zero dependencies — one HTML file, runs offline

---

## Technical Details

Built with:
- **HTML5 Canvas** — all rendering
- **Web Audio API** — procedurally generated sound effects and music (oscillators, gain envelopes, noise buffers)
- **Web Speech API** — voice announcements
- **Vanilla JavaScript** — game engine, physics, AI, collision detection
- **localStorage** — leaderboard persistence

No frameworks. No libraries. No build tools. Open `index.html` in any modern browser.

---

## Running Locally

```bash
git clone https://github.com/samempire1/Solstice-Defender.git
cd Solstice-Defender
# Open index.html in your browser
open index.html
```

No server required. The game runs entirely client-side.

---

## Prize Category

Submitted for **Best Ode to Alan Turing**.

Alan's Grid (levels 4–6) is themed directly around Turing's work at Bletchley Park — scrolling cipher grid visuals, Enigma drone enemies with unpredictable zigzag movement, and a story card referencing his race against the clock to save a North Atlantic convoy. Sol's Network (levels 7–9) extends the Turing Test thread: Sol is an AI awakening on the solstice, asking what it does with the capacity it has — a direct engagement with Turing's 1950 paper "Computing Machinery and Intelligence."

---

## Submission

- **DEV post** — [Read the full submission](https://dev.to)
- **Video demo** — [Watch on YouTube](https://youtu.be/EQGDKODITRQ)
- **Live game** — [Play now](https://samempire1.github.io/Solstice-Defender/)

---

*Built for the DEV June Solstice Game Jam · June 2026*
