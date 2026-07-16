# XSquad — Xsolla Gamer Hub

A web app prototype of **XSquad**, the Xsolla Gamer Hub: a social platform where gamers build
their identity and studios hear their players. Based on the Xsolla Gamer Hub one-pager and the
XSquad brand design (Player Tag logo direction).

## What's inside

- [`prototypes/xsquad-gamer-hub.html`](prototypes/xsquad-gamer-hub.html) — standalone prototype,
  no build step required. Open it in a browser, or serve the repo root:

  ```bash
  python3 -m http.server 8901
  # → http://localhost:8901/prototypes/xsquad-gamer-hub.html
  ```

## Screens

| Tab | What it shows |
|-----|---------------|
| **Home** | Season greeting, level progress, squad activity feed, friends online, Xsolla ecosystem gateway (Publisher Account, Partner Network, Xsolla Wallet) |
| **Discover** | AI-powered "Picked for you" matches with match-percent tags and "why this pick" explanations |
| **Reviews** | Game page (Cyberstrike) with verified, patch-tagged reviews backed by Xsolla purchase data, rating breakdown, and a developer-tools teaser |
| **Squads** | LFG spaces and a live squad chat |
| **Passport** | Gaming passport: account tag label, verified-player badge, achievements, library highlights |

## Design system

Built strictly on the **Xsolla UI Toolkit v2 (XUI)**, Pentagram Dark theme:

- All colors, spacing, radii, and shadows come from `--xui-*` design tokens
- Component HTML/CSS copied from XUI component specs (`xui-btn`, `xui-nav-bar`, `xui-tab-bar`,
  `xui-game-card`, `xui-tag-label`, `xui-cell`, `xui-progress-bar`, …)
- XSquad logo — "Player Tag" direction (1c) from the XSquad brand board
- Vanilla JS only: tab switching, genre filters, helpful votes, chat composer
