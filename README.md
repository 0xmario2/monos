# MONOS AI

**Autonomous Intelligence Network on Robinhood Chain**

> AI agents that think, act, and earn — fully on-chain, no permission needed.

🌐 **Live:** https://monosapp.xyz  
🐦 **Twitter:** https://x.com/monos_ai  
⛓️ **Chain:** [Robinhood Chain](https://robinhood.com/us/en/chain/) — AI-Native Ethereum L2

---

## Overview

MONOS AI is a decentralized autonomous intelligence network built on Robinhood Chain — a permissionless, AI-native Layer 2 blockchain. Deploy agents that execute on-chain, coordinate trustlessly, and generate value without any human in the loop.

This repository contains the official landing page — a single-file static website, no build step required.

---

## Getting Started

No dependencies. No framework. Just open `index.html` in a browser or deploy it anywhere.

```bash
# Clone the repo
git clone https://github.com/monosai/monosai.git
cd monosai

# Open locally
open index.html
```

### Deploy to Vercel
```bash
npm i -g vercel
vercel --prod
```

### Deploy to Netlify
```bash
npm i -g netlify-cli
netlify deploy --prod --dir .
```

### Deploy to GitHub Pages
Push `index.html` to your repo, then go to **Settings → Pages → Deploy from branch**.

---

## What's Inside

| Section | Description |
|---|---|
| **Hero** | Main tagline, CTA buttons, contract address badge |
| **Stats Strip** | Key metrics — 0% human oversight, <1s finality, $1.8T+ market |
| **Problem** | 3 cards — Centralized Control / No Native Finance / Unverifiable Reasoning |
| **Architecture** | 4-layer stack + pipeline: Intent → Reasoning → Execution → Settlement → Proof |
| **Products** | MONOS Deploy / MONOS Earn / MONOS Verify |
| **Why Robinhood Chain** | 6 cards — Sub-second finality, AI-native L2, RWA support, EVM compatible, low fees, permissionless |
| **Roadmap** | 4 phases — Foundation → Token Launch → Agent Network → Full Autonomy |
| **Community** | Social links + waitlist CTA |
| **Footer** | Navigation + socials + copyright |

---

## Pages & Links

| Page | File | Description |
|---|---|---|
| Homepage | `index.html` | Main landing page |
| Launch App | `app.html` | Waitlist signup |
| MONOS Deploy | `deploy.html` | Agent Studio |
| MONOS Earn | `earn.html` | Agent Marketplace |
| MONOS Verify | `verify.html` | On-chain Proof Explorer |
| Whitepaper | `whitepaper.html` | Full whitepaper |
| Docs & SDK | `docs.html` | Developer documentation |

---

## Customization

### Contract Address
Find and replace `0x4d0n053...coming soon` in `index.html` with your actual contract address.

### Accent Color
All Robinhood green colors use CSS variables in `:root`:
```css
--accent:  #00C805;   /* Robinhood green */
--accent2: #00FF41;   /* Lighter green */
```

### Social Links
Find and replace these in `index.html`:
```
https://x.com/monos_ai      →  your Twitter/X
https://t.me/monosai        →  your Telegram
https://github.com/monosai  →  your GitHub
```

---

## Tech Stack

| | |
|---|---|
| **Framework** | None — pure HTML / CSS / JS |
| **Fonts** | [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), Space Mono, Inter (Google Fonts) |
| **Icons** | [Iconify](https://iconify.design/) via CDN |
| **Animations** | CSS keyframes (corner flames, scroll ticker, reveal on scroll) |
| **Chain** | [Robinhood Chain](https://docs.robinhood.com/chain/) — Ethereum L2 on Arbitrum |

---

## Assets

| File | Dimensions | Use |
|---|---|---|
| `monosai-logo.png` | 500 × 500 | Profile picture |
| `monosai-logo-2x.png` | 1000 × 1000 | High-res / favicon |
| `monosai-banner.png` | 1500 × 500 | Twitter/X header |

---

## Roadmap

- [x] Phase 1 — Website & community launch
- [ ] Phase 2 — $MONOS token on Robinhood Chain
- [ ] Phase 3 — Agent runtime mainnet + MONOS Deploy beta
- [ ] Phase 4 — MONOS Verify, RWA trading, Governance DAO

---

## License

MIT © 2025 Monos AI
