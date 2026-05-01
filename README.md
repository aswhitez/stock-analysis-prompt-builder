# Stock Analysis Prompt Builder [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**AI-assisted stock prompt builder for valuation analysis.** Templates, preview, export. *No financial advice.*

## 🚀 Overview

This single-page web app generates clean, valuation-focused prompts for stock analysis using **three predefined templates**. 

- Select a template
- Input company details (ticker, position size, cost basis, etc.)
- Preview live and copy/export for AI tools like Perplexity

**Key features**: Live preview, light/dark mode, current price vs. cost basis comparison. Built with vanilla HTML/CSS/JS—no backend needed.

## ✨ Features

| Feature | Description |
|---------|-------------|
| **3 Templates** | Broad overview, buy-now decision, target entry price—all fundamentals-first |
| **Live Preview** | Updates as you type + summary cards |
| **Export** | Copy clipboard or download .txt |
| **Responsive** | Desktop/mobile + theme toggle |
| **Private** | Session-only, no storage/tracking |

## ⚡ Quick Start

1. **Open** `index.html` in any browser
2. **Select** template (defaults to #1)
3. **Fill** details:  
   - Company: LVMH  
   - Ticker: MC  
   - Position: 25 shares  
   - Cost basis: €702.50
4. **Preview** → **Copy** or **Download**

**Sample output**:  
```
Analyse LVMH (MC) listed on Stock Analysis Paris. 
I want a valuation-based entry price in euros...
- Position size: 25 shares
- Average cost basis: €702.50 per share
```

## 📝 Usage Notes

- **EUR-focused** cost basis + optional current price comparison
- **Notes field** for peers, margin of safety, etc.
- **Reset** clears form, keeps template
- Exchanges: Paris, Frankfurt (expandable)

> **Disclaimer**: Prompt builder only—not financial advice. Verify independently.

## 🛠️ Tech Stack

- **HTML5** + **CSS3** (custom properties, grid, backdrop blur)
- **Vanilla JS** (no frameworks)
- **Fonts**: Satoshi (body), Cabinet Grotesk (headings)
- **Size**: ~29KB, zero dependencies

## 📱 Demo

Live preview on [GitHub Pages](https://yourusername.github.io/stock-prompt-builder/) (deploy after upload)

## 🔧 Development

```bash
# Just open index.html
# Edit CSS vars for theming
# Add templates in JS const templates = {...}
```

## 📄 License

This project is [MIT licensed](LICENSE).  
Created with ❤️ for valuation workflows.

---

⭐ **Star if useful!** Questions? [Open an issue](https://github.com/yourusername/stock-prompt-builder/issues)
