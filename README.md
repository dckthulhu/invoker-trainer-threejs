# 🪄 Orbweaver: An Invoker Training & Spellcasting Game

**Orbweaver** is a mobile first, browser-based wave defense game built with **Three.js**.  
Inspired by *Dota 2’s Invoker*, the game challenges players to **combine elemental orbs** through **gesture-based swipes** to **invoke and cast spells** against incoming enemy waves.

Whether you're an aspiring Invoker player learning to master Quas–Wex–Exort combos, or you just love the thrill of elemental spellcraft — this game brings the art of invocation to life.

---

## 🎮 Core Concept

Each match pits you (the Invoker) against endless waves of enemies charging in from the Radiant side of the battlefield.  
Use your **three elemental orbs** — *Quas (Q)*, *Wex (W)*, and *Exort (E)* — to create and unleash powerful spells before you’re overwhelmed.

| Orb | Type | Effect |
|------|------|--------|
| ❄️ **Q - Quas** | Ice | Control & sustain (slows, heals) |
| 🌪️ **W - Wex** | Lightning | Speed, disruption, mobility |
| 🔥 **E - Exort** | Fire | Damage, explosions, chaos |

Combine **any three orbs** to *Invoke* one of many spells — just like in Dota 2, but now in a fast, wave-based survival format.

---

## 🧩 Gameplay Features (Planned)

- **Swipe-to-Cast System** – draw gestures or swipe to select and combine orbs.
- **Real-Time Wave Spawner** – endless waves of Radiant creatures attacking your Dire side.
- **Spell Combo System** – invoke classic spells like *Tornado*, *EMP*, *Chaos Meteor*, and *Sun Strike*.
- **Invoker Training Mode** – learn real Invoker combos, timings, and mechanics.
- **Progression System** – unlock new visuals, spell effects, and challenge tiers.
- **Three.js 3D World** – fully rendered in WebGL with dynamic lighting and particle effects.

---

## 🌐 Tech Stack

- **Three.js** — 3D rendering engine for the battlefield, orbs, and spell effects.
- **JavaScript / ES6 Modules**
- **Node.js + Vite** — for lightweight bundling and local development.
- **HTML / CSS / GLSL shaders** — UI, layout, and particle magic.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/dckthulhu/orbweaver.git
cd orbweaver
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run the Local Dev Server
```bash
npm run dev
```
Then open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🧠 Learn Invoker Mode

Use **Practice Mode** to train your muscle memory for Invoker’s spells.  
Swipe, drag, or tap the orbs to simulate **Quas–Wex–Exort** combos and invoke real Dota-style spells with visual and sound feedback.

Example Combos:
| Combo | Spells | Description |
|--------|---------|-------------|
| Q Q Q | Cold Snap | Stuns and interrupts enemies. |
| W W W | EMP | Drains mana and deals AoE damage. |
| E E E | Sunstrike | Massive single-target burst. |
| Q W E | Deafening Blast | Pushback wave of magic. |

---

## 🧰 Project Structure

```
orbweaver/
│
├── /src/
│   ├── core/            # Game loop, render engine
│   ├── scenes/          # Environment setup, lighting
│   ├── spells/          # Spell definitions and effects
│   ├── ui/              # HUD, orb display, invoke button
│   ├── assets/          # Textures, models, sounds
│   └── main.js          # Entry point
│
├── /public/             # Static assets
├── package.json
├── vite.config.js
└── README.md
```

---

## 🧩 Contributing

Contributions are welcome!  
If you’d like to add new spells, improve visuals, or expand Invoker’s teaching mode:

1. Fork the repo  
2. Create a new branch (`feature/spell-tornado`)  
3. Commit and push  
4. Submit a pull request

---

## 🎨 Roadmap

- [ ] Core wave-spawn and orb-swipe system  
- [ ] Basic spell invocation and particle system  
- [ ] Invoker training mode (combo recognition)  
- [ ] Score and leaderboard  
- [ ] Sound design and UI polish  
- [ ] Mobile optimization (touch input + landscape view)

---

## ⚖️ License

Not for commerical use.

---

## 🧙‍♂️ About

**Orbweaver** is created by [DCthulhu](https://github.com/dckthulhu),  
a fan of Dota’s Invoker, built to blend gameplay mastery with educational design.

> *“True mastery is not in remembering spells — it’s in feeling their rhythm.”*
