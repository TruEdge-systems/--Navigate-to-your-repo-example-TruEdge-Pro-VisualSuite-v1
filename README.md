# 🌀 TruEdge Apex Engine™

> A modular trading system that fuses volatility tier overlays, recursive wave mapping, and IBD-style breakout geometry into a fully synchronized signal engine.

![LegacyDrop](https://img.shields.io/badge/LegacyDrop-v1.0-purple?style=for-the-badge)
![Platform](https://img.shields.io/badge/Built%20for-Thinkorswim-blue?style=for-the-badge)
![WaveSync](https://img.shields.io/badge/Wave_Sync-Enabled-green?style=for-the-badge)

---

## 📦 Module Overview

| Module                  | Purpose                                                   |
|--------------------------|------------------------------------------------------------|
| `TI_VBH_MultiTickerUnifiedSTUDY.ts` | Hour-aware volatility tiers for 10 tickers × 2 modes      |
| `ZigZagRecursive.ts`     | Detects pivot swings + tracks phase-aware wave sequences   |
| `IBD_PatternEngine.ts`   | Detects base patterns (e.g. cup with handle)                |
| `TruEdgeApexLauncher.ts` | Combines overlays + gates entry when all modules align     |
| `TI_ApexWatchlistColumn.ts` | Displays signal readiness across watchlist tickers        |

---

## 🚀 Getting Started

1. 📁 Clone or download the full `TruEdgeApexSuite/` folder
2. Open Thinkorswim → Charts → Studies → “Create”
3. Paste contents of each `.ts` file into its own named study
4. Add `TruEdgeApexLauncher.ts` to your chart
5. (Optional) Add `TI_ApexWatchlistColumn.ts` to your watchlist columns

---

## 🎯 Signal Fires Only When:

✔️ Time-based **bias tier** is active (VBH zones)  
✔️ Valid **wave phase** is in play (≥ Phase 3 and upward swing)  
✔️ Confirmed **IBD-style pattern** geometry is detected

This ensures intentional entries—no cloud until all systems align.

---

## 🎼 Inspired By...

- 📊 VolatilityBox-style matrix logic  
- 🎷 Elliott Wave symmetry and rhythm  
- 🧱 Modular coding ethics for remixability and clarity  
- 🧭 A desire to make market structure feel musical and navigable

---

## 🛠 Developer Notes

- Full matrix supports 10 tickers × 2 bias modes × 7 hours = 140 tier conditions
- All modules can be extended separately: try divergence overlays or volume filters
- Watchlist column enables scalable signal tracking across sectors

---

## 🧪 File Map

# 🎛 TruEdge Pro™ Visual Suite — v1.0_LegacyDrop
![TruEdge Architecture Map](docs/truedge_suite_map.svg)
This suite interprets tiered market behavior through rhythm-aware overlays.  
Built in ThinkScript. Designed to pulse. Tuned for remix.

---

## 🎯 Modules Included

- `TierPulse.ts` — Pulse-state logic (0–3)
- `VisualLayer.ts` — L3 Glow Zones, Fade overlays
- `OverlayToggle.ts` — Pro, Classic, and Silent display modes
- `ColorTheme.ts` — Branded tone engine
- `StageEngine.ts` — Session-aware tempo behavior
- `PulseConfig/sample_config.txt` — Sample configuration
- `TruEdgePro_Icons/README_Icons.txt` — Icon usage notes

---

## ♊ Philosophy

Modular. Expressive. Remixable.  
This suite is designed to be extended, recolored, and reimagined. Whether you're building your own overlay logic or remixing the pulse engine, the system is yours to shape.

---

## 📦 Getting Started

1. Download the latest `.zip` from [Releases](https://github.com/your-repo/releases)
2. Import `.ts` modules into ThinkOrSwim
3. Customize `ColorTheme.ts` and `PulseConfig/` to match your chart style
4. Toggle display modes via `OverlayToggle.ts`

---

## 🛠️ Remix Ideas

- Rewire `TierPulse.ts` to support 5+ pulse states
- Add new session logic to `StageEngine.ts`
- Fork and theme your own visual suite

---

## 📜 License

MIT — remix, reuse, and build your legacy.

---

Want me to drop this into a file and help you upload it to your repo? Or generate a matching `ABOUT_THIS_DROP.md` to go deeper into your vision? Let’s keep the suite singing. ♊🔥
