# Ramco Presentation — Vizuara's Approach

A Slidev presentation outlining Vizuara's proposed engagement with Ramco Systems for two initiatives: **Agent Orchestration** and **Data Migration**, scoped to the ERP division as the first division of focus.

## Overview

The presentation walks through an eight-month plan built around a single shared foundation:

1. **Phase 1 — The Ramco Brain** (Months 1–2)
   Two Vizuara engineers immersed on-site at Chennai, building a complete, machine-readable understanding of the Ramco ERP platform — its database, models, state machines, Rflow processes, and MCP surface.

2. **Phase 2A — Agent Orchestration** (Months 3–8, parallel)
   Independent build of a production-grade agent orchestration layer for the Journey Engine, covering all core ERP processes (procurement, finance, sales, inventory, manufacturing, master data).

3. **Phase 2B — Data Migration** (Months 3–8, parallel)
   Independent build of an AI-powered migration pipeline, inspired by Palantir's ontology-first approach but built on Ramco's unique Neo4j knowledge graph.

## Running Locally

```bash
npm install
npm run dev
```

The presentation opens at `http://localhost:3030/` by default.

## Building a Static Site

```bash
npm run build
```

The static site is output to `dist/`, which can be deployed to any static host (GitHub Pages, Netlify, Vercel, etc.).

## Exporting to PDF

```bash
npm run export
```

## Structure

- `slides.md` — The full presentation source
- `public/vizuara-logo.png` — Vizuara logo displayed on every slide
- `package.json` — Slidev and dependencies

## Stack

Built with [Slidev](https://sli.dev/) — a Markdown-based presentation framework.
