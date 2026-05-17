# LycosAI.com

Satirical Silicon Valley startup landing page for **LycosAI** — a fictional company selling "Autonomous Quadruped Apex Predator Mesh Networks" as a high-tech response to Japan's rural bear crisis.

Inspired by the [Popular Science article on Japan's Monster Wolf robot scarecrows](https://www.popsci.com/environment/japan-robot-wolf-army/).

## Concept

Instead of Japan's current stationary, solar-powered "Monster Wolf" scarecrows, LycosAI offers an overly engineered alternative: robotic wolf packs sold under an **Agentic Deterrence Platform** subscription model. The page is written in deadpan Silicon Valley corporate jargon and is designed to look completely authentic at a glance.

> *"Restoring the Ghost of the Predator via Edge-Computing."*

## Stack

- Plain HTML5 — single `index.html`, no build step
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) + Inter via Google Fonts
- Vanilla JavaScript (modal, scroll effects, counter animation)
- GitHub Pages via GitHub Actions

## Structure

```
LycosAI.com/
├── index.html                  # Full landing page
├── CNAME                       # Custom domain → lycosai.com
├── .github/
│   └── workflows/
│       └── deploy.yml          # Deploy to GitHub Pages on push to main
└── README.md
```

## Page Sections

| Section | Description |
|---|---|
| Hero | Geometric low-poly wolf SVG with pulsing red LED eyes, tactical grid background |
| The Problem | Deadpan market framing + Monster Wolf competitive teardown |
| The Solution | Pack-Mind Mesh, Computer Vision Species ID, Dynamic Acoustic Deterrence |
| Platform Specs | 8-tile hardware spec grid with fake-but-plausible figures |
| Pricing | Scout / Pack / Alpha tiers — the Alpha price is classified |
| Footer | Full legal fine print including "Not responsible for territory disputes between autonomous units." |

The **Request Deployment** button opens a 3-step intake modal asking about hectares of perimeter, primary threat vectors (*Ursus arctos*, *Sus scrofa*, *Cervus nippon*), and preferred deployment timeline.

## Deployment

Pushes to `main` automatically deploy to GitHub Pages via the workflow in `.github/workflows/deploy.yml`. The custom domain `lycosai.com` is configured via the `CNAME` file.

To enable GitHub Pages on a new repo:

1. Go to **Settings → Pages**
2. Set source to **GitHub Actions**
3. Push to `main`
