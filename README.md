# ReLoop

ReLoop is a polished circular-economy MVP that helps people find a useful next life for everyday items through giving, exchanging, renting, selling, repair, reuse, and recycling.

## Features

- Responsive landing, discovery, AI analyzer, Rescue Radar, My Items, Impact, and profile views
- Demo inventory spanning categories such as electronics, books, furniture, sports, clothing, tools, and household items
- Search, action/category filters, item details, and listing creation
- Local image upload preview and drag-and-drop in the analyzer
- Simulated analysis, requests, messaging/payment confirmation states, and impact feedback

## Important prototype note

This version is a frontend-only prototype. Its AI analysis, matching, payment confirmations, messaging, and data changes are simulated in the browser. It does not charge money or send messages, and it does not save data to a remote database. Uploaded images are previewed locally in the browser. Add suitable AI, payment, database, and storage integrations before using these features with real users or claiming real transactions.

## Requirements

- Node.js 20 or later
- pnpm (the project uses pnpm)

## Run locally

```bash
pnpm install
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000).

## Build for production

```bash
pnpm build
pnpm start
```

## Tech stack

- Next.js App Router
- React and TypeScript
- Tailwind CSS
- Lucide icons

## GitHub upload

Upload the project source and configuration files, including `app/`, `components/`, `lib/`, `public/`, `package.json`, `pnpm-lock.yaml`, `pnpm-workspace.yaml`, `tsconfig.json`, `next.config.mjs`, `postcss.config.mjs`, `components.json`, `.gitignore`, and this README. Do not upload generated or private files such as `node_modules/`, `.next/`, or `.env*` secrets.
