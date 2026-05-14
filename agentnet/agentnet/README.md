# AgentNet — Cyberpunk AI Agent Dashboard

A fully autonomous AI agent city. Four agents manage your Etsy, Shopify, Social Media and Email operations 24/7, visualised as a live 3D cyberpunk world.

---

## Deploy in 2 minutes

### Option A — Vercel (recommended)
1. Go to [vercel.com](https://vercel.com) and sign up free
2. Click **Add New → Project**
3. Drag this entire folder onto the upload area
4. Click **Deploy**
5. Done — you get a live URL instantly

### Option B — Netlify
1. Go to [netlify.com](https://netlify.com) and sign up free
2. Drag this entire folder onto the Netlify drop zone
3. Done

### Option C — GitHub + Vercel (auto-deploys on every change)
1. Create a new GitHub repo
2. Push this folder to it
3. Connect the repo to Vercel
4. Every push auto-deploys

---

## First run
On first load, you'll see a setup screen asking for your Anthropic API key.
- Get one free at [console.anthropic.com](https://console.anthropic.com)
- Your key is stored in your browser's localStorage only
- Never sent anywhere except directly to Anthropic's API

---

## What the agents do

| Agent | Tasks |
|---|---|
| **Etsy** | Writes product listings, researches trends, audits SEO, updates pricing |
| **Shopify** | Writes cart recovery emails, optimises product pages, creates discount codes |
| **Social** | Scripts TikTok hooks, writes Instagram captions, builds hashtag sets |
| **Email** | Writes campaigns, crafts subject lines, builds welcome sequences |

Each agent autonomously picks tasks from their pool, walks to their desk, works on them using Claude AI, and completes them — then picks the next task. You can also click any agent to chat with them directly.

---

## Controls
- **Click an agent** (in world or bottom bar) to open their command panel
- **Quick action buttons** — trigger common tasks instantly
- **Type in the input** — give any agent a custom task
- **Minimap** (top right) — shows all agent positions in real time

---

## Customising
All agent definitions are in the `AGENT_DEFS` object in `index.html`.
You can add tasks to the `pool` array, change the `system` prompt, or add new agents.

---

## Tech stack
- **Three.js r128** — 3D WebGL rendering
- **UnrealBloomPass** — neon glow post-processing
- **Claude Sonnet** via Anthropic API — agent intelligence
- Pure HTML/CSS/JS — zero build step, zero dependencies to install

