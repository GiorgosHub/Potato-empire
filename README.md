# 🥔 Potato Empire (Next.js Edition)

A polished, modern idle / incremental game built with Next.js, React, Tailwind CSS and beautiful stage illustrations.

## Quick Start

```bash
# Requires Node.js 18+
npm install
# or
pnpm install

npm run dev
```

Open http://localhost:3000

## Features

- Beautiful animated empire stages with custom art
- Click-to-produce with particles
- Buildings, upgrades, research tree
- Random events with toasts
- Achievements
- Prestige / Potato Essence system
- Offline progress modal
- Responsive, dark-themed UI
- Reduced-motion option for school computers

## Project Structure

- `app/` – Next.js App Router
- `components/game/` – All game UI components
- `lib/game-data.ts` – Buildings, upgrades, research, events, stages
- `lib/game-engine.ts` – State, reducer, production logic
- `public/empire/` – Stage illustrations

## Controls

- Click the big potato or press **Space** to produce
- Tabs: Empire · Buildings · Upgrades · Research · Achievements · Prestige
- Settings gear for motion / particles

Enjoy your intergalactic potato destiny!
