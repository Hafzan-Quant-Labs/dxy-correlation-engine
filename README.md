# Hafzan DXY Correlation Engine

<div align="center">

![Hafzan](https://img.shields.io/badge/Hafzan-DXY%20Engine-c8a96e?style=for-the-badge&labelColor=0d0d0d)
![Version](https://img.shields.io/badge/version-1.0-c8a96e?style=flat-square&labelColor=141414)
![License](https://img.shields.io/badge/license-Proprietary-red?style=flat-square&labelColor=141414)
![HTML](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20JS-c8a96e?style=flat-square&labelColor=141414)

**A professional-grade, single-file analytical engine for modeling DXY (US Dollar Index) correlation impacts across FX pairs, commodities, indices, and crypto assets.**

[**→ Try the Engine Live**](https://hafzan-quant-labs.github.io/dxy-correlation-engine/)

</div>

---

## Overview

The **Hafzan DXY Correlation Engine** is a client-side financial analytical tool that allows traders, analysts, and portfolio managers to simulate how a hypothetical move in the US Dollar Index (DXY) propagates across a multi-asset portfolio. It combines correlation data, real-time-style visual feedback, and P&L simulation — all in a single, dependency-free HTML file.

No server. No backend. No installation. Just open it and trade.

---

## Features

### 🔍 Correlation Analysis
- DXY correlation coefficients across **multiple timeframes** — 1W, 1M, 3M, 6M, 1Y
- Coverage across **40+ instruments**: major & exotic FX pairs, metals, energy, equity indices, and crypto
- Visual **correlation heatmap** with hover tooltips showing estimated % move per instrument
- **Correlation bar chart** with per-timeframe breakdowns

### 📊 Portfolio P&L Simulator
- Add multiple positions with custom notional sizes
- Input a hypothetical DXY % shock — bullish or bearish
- Instant **P&L table** sorted by impact, with per-position % return and bar visualization
- Summary metrics: total P&L, biggest winner, biggest loser, position count
- **P&L bar chart** rendered via Chart.js

### 🧮 Live Metrics Bar
- DXY index value display with intraday change indicator
- Portfolio-level summary tiles: estimated P&L, best/worst performers, position count

### 🎨 UI/UX
- Full **dark / light theme** toggle
- Elegant serif + monospace typographic system (Playfair Display + Courier Prime)
- Fully **responsive layout** — works on desktop, tablet, and mobile
- Animated noise grain overlay for premium aesthetic
- Smooth transitions, hover states, and toast notifications

---

## Asset Coverage

| Category        | Examples                                               |
|-----------------|--------------------------------------------------------|
| **FX — Majors** | EUR/USD, GBP/USD, USD/JPY, AUD/USD, USD/CAD, USD/CHF  |
| **FX — Exotics**| USD/TRY, USD/ZAR, USD/MXN, USD/NOK, USD/SEK           |
| **Metals**      | Gold, Silver, Platinum, Palladium, Copper              |
| **Energy**      | WTI Crude, Brent Crude, Natural Gas                    |
| **Indices**     | S&P 500, NASDAQ, DAX, FTSE 100, Nikkei 225, ASX 200   |
| **Crypto**      | BTC/USD, ETH/USD                                       |

---

## Getting Started

### Option 1 — Use Online
> [**→ Try the Engine Live**](https://hafzan-quant-labs.github.io/dxy-correlation-engine/)

No setup required. Works directly in your browser.

### Option 2 — Run Locally

```bash
# Clone the repository
git clone https://github.com/Hafzan-Quant-Labs/dxy-correlation-engine.git

# Open the file
open hafzan-dxy-engine.html
```

Or simply download `hafzan-dxy-engine.html` and double-click it. That's it.

> **Requirements:** Any modern browser (Chrome, Firefox, Safari, Edge). No Node.js, no build tools, no dependencies to install.

---

## How to Use

1. **Set a DXY Shock** — Enter a percentage move in the DXY input field (e.g., `+1.5` for a 1.5% DXY rally) and click **Apply**.
2. **Select a Timeframe** — Choose the correlation timeframe: 1W · 1M · 3M · 6M · 1Y.
3. **Browse the Correlation Table** — Review each asset's correlation coefficient and estimated % move under your scenario.
4. **Explore the Heatmap** — Get a color-coded visual snapshot of cross-asset DXY sensitivity.
5. **Build Your Portfolio** — Add positions in the left panel with symbol and notional size.
6. **Run Analysis** — Click *Run Analysis* to generate full P&L breakdown across your book.

---

## Tech Stack

| Layer       | Technology                        |
|-------------|-----------------------------------|
| Structure   | HTML5                             |
| Styling     | Vanilla CSS (custom properties, grid, flexbox) |
| Logic       | Vanilla JavaScript (ES6+)         |
| Charts      | [Chart.js 4.4.1](https://www.chartjs.org/) via CDN |
| Fonts       | Google Fonts — Playfair Display, Courier Prime |

Zero npm packages. Zero build step. Zero frameworks.

---

## File Structure

```
hafzan-dxy-engine.html   ← The entire engine in one file
README.md                  ← This document
```

---

## Screenshots

<img width="1440" height="819" alt="Screenshot 2026-03-11 at 9 53 03 PM" src="https://github.com/user-attachments/assets/362b0d3b-5813-4759-84b7-5a0aac627c92" /></br>
<img width="1440" height="820" alt="Screenshot 2026-03-11 at 9 53 17 PM" src="https://github.com/user-attachments/assets/141bc93a-99f0-466d-8923-f7b1f6b70413" /></br>
<img width="1440" height="820" alt="Screenshot 2026-03-11 at 9 53 30 PM" src="https://github.com/user-attachments/assets/67315dd9-e30f-4c08-903c-74cd8f235f2a" /></br>
<img width="1439" height="820" alt="Screenshot 2026-03-11 at 9 53 43 PM" src="https://github.com/user-attachments/assets/288b4f02-11eb-4122-9e45-3ccd2ef47157" /></br>
<img width="1440" height="819" alt="Screenshot 2026-03-11 at 9 53 56 PM" src="https://github.com/user-attachments/assets/b811dfb5-673f-4f42-936b-4f5326691c3a" /></br>

 Multi-currency notional support

---

## License

**Copyright © 2025 Hafzan. All rights reserved.**

This software and its source code are **proprietary and confidential**. No part of this codebase may be reproduced, distributed, modified, sublicensed, or used in any form — commercial or otherwise — without the express prior written permission of the author.

Unauthorized use, copying, or distribution of this software, in whole or in part, is strictly prohibited and may be subject to legal action.

---

## Disclaimer

This tool is provided for **informational and analytical purposes only**. Correlation data is based on historical estimates and does not guarantee future asset behaviour. Nothing in this engine constitutes financial advice. Always conduct your own due diligence before making trading or investment decisions.

---

<div align="center">
  <sub>Built with precision by <strong>Hafzan</strong></sub>
</div>
