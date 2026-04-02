
# Ferncrest Carousel Studio

Instagram carousel generator for the Ferncrest team.
Renders 12 slides at 1080×1350 (4:5) with Karrik font and Ferncrest brand style.

## Deploy to Vercel (10 minutes)

### Step 1 — GitHub
1. Go to [github.com](https://github.com) and create a free account if you don't have one
2. Click **New repository** → name it `ferncrest-carousel` → click **Create repository**
3. Upload `index.html` and `vercel.json` to the repo

### Step 2 — Vercel
1. Go to [vercel.com](https://vercel.com) and sign up with your GitHub account
2. Click **Add New Project** → select your `ferncrest-carousel` repo
3. Click **Deploy** — no settings needed

### Step 3 — Share
Vercel gives you a URL like `ferncrest-carousel.vercel.app`
Share this with your team — works in any browser, no install needed.

### Step 4 — API Key (for Transcript mode)
Each team member needs their own Anthropic API key for the AI transcript feature.
Get one at [console.anthropic.com](https://console.anthropic.com)
Keys are entered in the app each session — never stored.

## Features

### Templates mode
- 5 pre-built Ferncrest templates (Property Walkthrough, Franchise Opportunity, Season Update, Industry Predictions, Origin Story)
- Click any template → edit slide copy inline → upload photos → render → download PNGs
- No API key needed

### Transcript mode
- Paste any reel transcript
- Choose a story pattern (Money Story, Authority, Character Story, etc.)
- Claude generates 12 slides in Ferncrest brand voice
- Requires Anthropic API key (~$0.01 per generation)

## Brand System
- H1: Solid black box, white text, Karrik font, 32×26px padding
- H2: Solid green box (#2d5a2d), white text, same padding
- CTA: Solid white box, black text, smaller (last slide only)
- Boxes hug text width — no full-bleed boxes
- All slides: 1080×1350px (4:5 Instagram format)
