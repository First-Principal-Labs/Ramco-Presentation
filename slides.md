---
theme: default
title: Vizuara × Ramco — Our Approach
info: Vizuara's proposed approach for Ramco's Agent Orchestration and Data Migration projects.
author: Vizuara
highlighter: shiki
colorSchema: light
fonts:
  sans: Inter
  serif: Inter
  mono: JetBrains Mono
  provider: google
transition: fade
mdc: true
---

<style>
:root {
  --v-primary: #111111;
  --v-secondary: #525252;
  --v-muted: #737373;
  --v-accent: #1e3a5f;
  --v-accent-soft: #4a6b8a;
  --v-border: #e5e5e5;
  --v-bg: #ffffff;
  --v-surface: #fafafa;
}

.slidev-layout {
  font-family: 'Inter', system-ui, -apple-system, sans-serif;
  color: var(--v-primary);
  background: var(--v-bg);
  padding: 3rem 4rem 4rem 4rem;
  font-feature-settings: 'ss01', 'cv11';
  overflow-y: auto;
  max-height: 100vh;
  scrollbar-width: thin;
  scrollbar-color: #c7c7c7 transparent;
}

.slidev-layout::-webkit-scrollbar {
  width: 8px;
}

.slidev-layout::-webkit-scrollbar-track {
  background: transparent;
}

.slidev-layout::-webkit-scrollbar-thumb {
  background: #c7c7c7;
  border-radius: 4px;
}

.slidev-layout::-webkit-scrollbar-thumb:hover {
  background: #9a9a9a;
}

.slidev-layout::before {
  content: '';
  position: absolute;
  top: 1.5rem;
  right: 2.5rem;
  width: 110px;
  height: 32px;
  background-image: url('/vizuara-logo.png');
  background-repeat: no-repeat;
  background-position: right center;
  background-size: contain;
  opacity: 0.9;
  z-index: 50;
  pointer-events: none;
}

.slidev-layout h1 {
  font-family: 'Inter', system-ui, sans-serif;
  font-weight: 600;
  color: var(--v-primary);
  letter-spacing: -0.025em;
  font-size: 2.1rem;
  margin-bottom: 0.75rem;
  line-height: 1.2;
  border-bottom: 1px solid var(--v-border);
  padding-bottom: 0.75rem;
}

.slidev-layout h2 {
  font-family: 'Inter', system-ui, sans-serif;
  font-weight: 600;
  color: var(--v-primary);
  letter-spacing: -0.02em;
  font-size: 1.4rem;
  margin-top: 1.25rem;
  margin-bottom: 0.5rem;
}

.slidev-layout h3 {
  font-family: 'Inter', system-ui, sans-serif;
  font-weight: 600;
  color: var(--v-primary);
  letter-spacing: -0.01em;
  font-size: 1.05rem;
  margin-bottom: 0.4rem;
}

.slidev-layout p, .slidev-layout li {
  color: var(--v-primary);
  font-size: 0.95rem;
  line-height: 1.65;
  font-style: normal;
}

.slidev-layout strong {
  font-weight: 600;
  color: var(--v-primary);
}

.slidev-layout em, .slidev-layout i {
  font-style: normal;
  font-weight: 500;
}

.slidev-layout ul {
  list-style: none;
  padding-left: 0;
  margin-top: 0.5rem;
}

.slidev-layout ul li {
  position: relative;
  padding-left: 1.25rem;
  margin-bottom: 0.4rem;
}

.slidev-layout ul li::before {
  content: '';
  position: absolute;
  left: 0;
  top: 0.65rem;
  width: 5px;
  height: 5px;
  background: var(--v-accent);
  border-radius: 50%;
}

.slidev-layout .eyebrow {
  font-size: 0.7rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: var(--v-accent);
  margin-bottom: 0.4rem;
}

.slidev-layout .muted {
  color: var(--v-muted);
  font-size: 0.9rem;
}

.slidev-layout .divider {
  height: 1px;
  background: var(--v-border);
  margin: 1.25rem 0;
  border: 0;
}

.slidev-layout .card {
  border: 1px solid var(--v-border);
  border-radius: 8px;
  padding: 1.1rem 1.25rem;
  background: var(--v-bg);
}

.slidev-layout .card.soft {
  background: var(--v-surface);
}

.slidev-layout .card h3 {
  margin-top: 0;
}

.slidev-layout .accent {
  color: var(--v-accent);
}

.slidev-layout .num {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 1.6rem;
  height: 1.6rem;
  border: 1px solid var(--v-accent);
  color: var(--v-accent);
  border-radius: 50%;
  font-size: 0.8rem;
  font-weight: 600;
  margin-right: 0.5rem;
  vertical-align: middle;
}

.slidev-layout .cover {
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 100%;
  padding: 2rem 0;
}

.slidev-layout .cover h1 {
  font-size: 3.25rem;
  font-weight: 700;
  letter-spacing: -0.035em;
  margin-bottom: 1rem;
  line-height: 1.05;
  border: 0;
  padding: 0;
}

.slidev-layout .cover .sub {
  font-size: 1.15rem;
  color: var(--v-secondary);
  font-weight: 400;
  margin-bottom: 2rem;
  max-width: 48rem;
  line-height: 1.5;
}

.slidev-layout .cover .meta {
  font-size: 0.75rem;
  color: var(--v-muted);
  text-transform: uppercase;
  letter-spacing: 0.12em;
}

.slidev-layout .keyline {
  border-left: 3px solid var(--v-accent);
  padding-left: 1rem;
  color: var(--v-primary);
}
</style>

<div class="cover">
  <div class="eyebrow">Vizuara × Ramco</div>
  <h1>Our Approach</h1>
  <div class="sub">A proposed engagement to deliver Agent Orchestration and Data Migration for the Ramco ERP division, built on a shared foundation and executed on-site at Chennai.</div>
  <div class="meta">Vizuara · Eight-Month Plan · ERP Division First · Prepared for Ramco Leadership</div>
</div>

---

# What Ramco Asked For

<div class="eyebrow">Meeting Summary</div>

Two initiatives emerged from the conversation at Chennai. They are distinct in scope but share the same underlying foundation.

<div class="grid grid-cols-2 gap-6 mt-6">
  <div class="card">
    <div class="eyebrow">Project One</div>
    <h3>Agent Orchestration</h3>
    <p class="muted">Turn the form-heavy ERP into a conversational, agent-driven experience built on the rAegis platform and the Journey Engine.</p>
  </div>
  <div class="card">
    <div class="eyebrow">Project Two</div>
    <h3>Data Migration</h3>
    <p class="muted">Compress the twelve to eighteen month SAP and Oracle to Ramco customer migration down to weeks, using an ontology-first approach inspired by Palantir.</p>
  </div>
</div>

<div class="mt-6 keyline">
  Both projects depend on a single prerequisite — a deep, structural understanding of Ramco's database, models, and business processes.
</div>

---

# Scope — Starting with ERP

<div class="eyebrow">Which Division First</div>

Ramco operates across three major business divisions, each with its own processes, data models, and customers.

<div class="grid grid-cols-3 gap-4 mt-6">
  <div class="card">
    <div class="eyebrow">Division One</div>
    <h3>ERP</h3>
    <p class="muted">Finance, procurement, manufacturing, supply chain, and enterprise services.</p>
  </div>
  <div class="card" style="opacity: 0.55;">
    <div class="eyebrow">Division Two</div>
    <h3>Payroll and HCM</h3>
    <p class="muted">Global payroll and HR across more than 150 countries.</p>
  </div>
  <div class="card" style="opacity: 0.55;">
    <div class="eyebrow">Division Three</div>
    <h3>Aviation</h3>
    <p class="muted">Maintenance, Repair, and Overhaul for airlines, defence, and fleet operators.</p>
  </div>
</div>

<div class="mt-6 keyline">
  For both projects, we will focus on the ERP division as the first division we tackle. The patterns, the Ramco Brain, and the delivered platforms will be designed so that Payroll and Aviation can be onboarded as subsequent phases without a rebuild.
</div>

---

# Project One — Agent Orchestration

<div class="eyebrow">Current State</div>

Creating a single Purchase Order in the current ERP requires navigating eight or more screens and filling fifty or more fields. Users learn the system over weeks of training. Twelve to fifteen minutes per PO is typical.

<h2>What Ramco Already Has</h2>

<ul>
  <li>rAegis platform with the Journey Engine, XIA chat, and four domain agents</li>
  <li>Eight hundred and thirty three XML and JS artifacts parsed into a Neo4j knowledge graph</li>
  <li>MCP integration layer for governed tool invocation</li>
  <li>Rflow workflow engine for long-running temporal processes</li>
</ul>

<h2>What Remains to Be Built</h2>

A production-grade agent orchestration layer that makes the Journey Engine composable, reliable, and agent-reasonable across both chat and form surfaces.

---

# Project Two — Data Migration

<div class="eyebrow">Current State</div>

The current customer migration runs as a seven-stage sequential pipeline across twelve to eighteen months. Three hundred thirty thousand dollar average cost. Seventy six man-months of effort. Zero percent AI assistance today.

<h2>Ramco's Unique Advantage</h2>

The Neo4j knowledge graph from rAegis already encodes the target ontology for the Ramco platform. No other ERP vendor has this. Palantir's customers build their target ontology from scratch. Ramco has it on day one.

<h2>What Remains to Be Built</h2>

An AI-powered migration pipeline with ontology-based concept mapping, continuous validation, and auto-generated deliverables — inspired by Palantir, but built on Ramco's unique graph foundation.

---

# The Shared Foundation

<div class="eyebrow">The Key Insight</div>

Both projects depend on the same thing.

<ul class="mt-4">
  <li>Both need a clear map of entities, relationships, rules, and state machines</li>
  <li>Both need runtime access to the knowledge graph, not just a developer-time reference</li>
  <li>Both need to understand how Rflow captures and executes long-running processes</li>
  <li>Both need clarity on the MCP layer and how the existing artifacts translate into Skills</li>
</ul>

<div class="mt-6 keyline">
  If this foundation is built once, properly, both projects move at full speed. If it is skipped, both projects will spend months rediscovering the same ground independently.
</div>

---

# Our Approach

<div class="eyebrow">Three Phases · Eight Months</div>

<div class="mt-4 space-y-3">

  <div class="card">
    <div class="eyebrow">Phase 1 · Months 1 to 2</div>
    <h3><span class="num">1</span>The Ramco Brain</h3>
    <p class="muted">On-site immersion at Chennai. Two Vizuara engineers working alongside the Ramco team to build a unified, structural understanding of the platform.</p>
  </div>

  <div class="card">
    <div class="eyebrow">Phase 2A · Months 3 to 8 · Parallel</div>
    <h3><span class="num">2</span>Agent Orchestration Build</h3>
    <p class="muted">Independent build of the agent orchestration layer for the Journey Engine, operating on the Ramco Brain from Phase 1.</p>
  </div>

  <div class="card">
    <div class="eyebrow">Phase 2B · Months 3 to 8 · Parallel</div>
    <h3><span class="num">3</span>Data Migration Build</h3>
    <p class="muted">Independent build of the AI-powered migration pipeline, also operating on the Ramco Brain from Phase 1.</p>
  </div>

</div>

---

# Phase 1 — The Ramco Brain

<div class="eyebrow">Foundation · Months 1 to 2</div>

<div class="grid grid-cols-2 gap-8 mt-4">
  <div>
    <h3>What It Is</h3>
    <p>A complete, machine-readable understanding of the Ramco platform — its database, its models, its state machines, and its execution layer.</p>
    <p>This is the single most important deliverable of the engagement. Everything downstream depends on it.</p>
  </div>
  <div>
    <h3>Engagement Details</h3>
    <ul>
      <li>Duration: two months</li>
      <li>Location: on-site at Ramco Chennai</li>
      <li>Team: two Vizuara engineers, fully immersed</li>
      <li>Mode: daily working sessions with the rAegis team</li>
    </ul>
  </div>
</div>

<div class="mt-6 card soft">
  Our engineers will work next to yours. They will stay in Chennai for the full duration of Phase 1. This is the fastest and most reliable way to resolve ambiguity and build shared context.
</div>

---

# Phase 1 — What We Will Do

<div class="eyebrow">Week by Week</div>

<div class="grid grid-cols-3 gap-4 mt-4">

  <div class="card">
    <div class="eyebrow">Weeks 1 to 2</div>
    <h3>Discovery</h3>
    <ul>
      <li>Work alongside the rAegis team</li>
      <li>Study the existing artifacts, Neo4j graph, and MCP layer</li>
      <li>Map the Journey Engine end to end</li>
      <li>Understand Rflow and how processes persist</li>
    </ul>
  </div>

  <div class="card">
    <div class="eyebrow">Weeks 3 to 5</div>
    <h3>Structural Mapping</h3>
    <ul>
      <li>Document the full entity and relationship model</li>
      <li>Catalogue state machines and business rules</li>
      <li>Separate static metadata from runtime state</li>
      <li>Identify gaps and ambiguities</li>
    </ul>
  </div>

  <div class="card">
    <div class="eyebrow">Weeks 6 to 8</div>
    <h3>Foundation Build</h3>
    <ul>
      <li>Expose the knowledge graph as a queryable runtime layer</li>
      <li>Build shared infrastructure for both Phase 2 tracks</li>
      <li>Produce the written Ramco Brain reference</li>
      <li>Hand off to the Phase 2 teams</li>
    </ul>
  </div>

</div>

---

# Phase 1 — Deliverables

<ul>
  <li>A queryable runtime knowledge graph exposing entities, relationships, rules, and state machines</li>
  <li>A complete structural map of the Ramco platform — database, models, Rflow processes, and the MCP surface</li>
  <li>A shared foundation library used by both Phase 2A and Phase 2B</li>
  <li>A written Ramco Brain reference document, versioned and owned by Ramco at the end of Phase 1</li>
  <li>Clear identification of any architectural gaps that need to be resolved before Phase 2 begins</li>
</ul>

<div class="mt-6 card soft">
  At the end of Phase 1, Ramco has a foundation that is immediately usable — not just by our teams, but by Ramco's own engineers for any future work on the platform.
</div>

---

# Phase 2A — Agent Orchestration

<div class="eyebrow">Months 3 to 8 · Parallel with Phase 2B · ERP Division</div>

<div class="grid grid-cols-2 gap-8 mt-4">
  <div>
    <h3>Approach</h3>
    <p>Independent build. Vizuara owns delivery end to end. Ramco does not need to allocate dedicated engineers to manage us.</p>
    <p>Weekly sync with the Ramco team. Monthly working demos. Quarterly executive reviews.</p>
  </div>
  <div>
    <h3>What We Will Build</h3>
    <ul>
      <li>Agent orchestration framework for composable journeys</li>
      <li>Runtime integration with the knowledge graph for grounding and planning</li>
      <li>Production-quality handling of long-running, stateful journeys via Rflow</li>
      <li>Coverage of all core ERP processes — not a single showcase</li>
    </ul>
  </div>
</div>

<h2>Process Coverage</h2>

<p>The goal of Phase 2A is complete coverage of Ramco's ERP process catalogue — every major business flow converted into an agent-driven, composable journey. Representative examples include:</p>

<div class="grid grid-cols-3 gap-3 mt-3">
  <div class="card soft">
    <div class="eyebrow">Procurement</div>
    <ul>
      <li>Purchase Requisition to Purchase Order</li>
      <li>Supplier onboarding and qualification</li>
      <li>Quotation and negotiation</li>
      <li>Goods receipt and inspection</li>
      <li>Invoice matching and payment</li>
    </ul>
  </div>
  <div class="card soft">
    <div class="eyebrow">Finance</div>
    <ul>
      <li>Accounts payable and receivable</li>
      <li>General ledger and journal entries</li>
      <li>Budget creation and variance analysis</li>
      <li>Financial period close</li>
      <li>Bank reconciliation</li>
    </ul>
  </div>
  <div class="card soft">
    <div class="eyebrow">Sales and Order</div>
    <ul>
      <li>Sales order creation and fulfilment</li>
      <li>Customer onboarding and credit check</li>
      <li>Pricing and discount approval</li>
      <li>Shipment and delivery tracking</li>
      <li>Returns and credit notes</li>
    </ul>
  </div>
  <div class="card soft">
    <div class="eyebrow">Inventory and Warehouse</div>
    <ul>
      <li>Stock transfer and replenishment</li>
      <li>Cycle counting and adjustments</li>
      <li>Bin and lot management</li>
      <li>Pick, pack, and dispatch</li>
      <li>Reservation and allocation</li>
    </ul>
  </div>
  <div class="card soft">
    <div class="eyebrow">Manufacturing</div>
    <ul>
      <li>Work order creation and release</li>
      <li>Bill of materials and routing</li>
      <li>Shop floor execution</li>
      <li>Quality inspection and yield</li>
      <li>Production variance reporting</li>
    </ul>
  </div>
  <div class="card soft">
    <div class="eyebrow">Master Data and Approvals</div>
    <ul>
      <li>Item, supplier, and customer master creation</li>
      <li>Multi-level approval workflows</li>
      <li>Policy and authorization management</li>
      <li>Audit and exception handling</li>
      <li>Cross-module reporting and search</li>
    </ul>
  </div>
</div>

<div class="mt-6 keyline">
  Every process above currently lives as forms, screens, and artifacts in the ERP. Phase 2A converts them into agent-orchestrated journeys that work from both chat and form surfaces, using the same Rflow and knowledge graph underneath.
</div>

---

# Phase 2B — Data Migration

<div class="eyebrow">Months 3 to 8 · Parallel with Phase 2A · ERP Division</div>

<div class="grid grid-cols-2 gap-8 mt-4">
  <div>
    <h3>Approach</h3>
    <p>Independent build. Vizuara owns delivery end to end. Ramco does not need to allocate dedicated engineers to manage us.</p>
    <p>Weekly sync with the Ramco team. Monthly working demos. Quarterly executive reviews.</p>
  </div>
  <div>
    <h3>What We Will Build</h3>
    <ul>
      <li>Source ontology builder for SAP and Oracle ERP systems</li>
      <li>AI mapping agent connecting source ontologies to Ramco's ERP target ontology</li>
      <li>Transformation and validation pipeline with continuous feedback</li>
      <li>Auto-generation of fit-gap reports, test scenarios, and cutover plans</li>
      <li>Demonstration on a reference ERP customer migration scenario</li>
    </ul>
  </div>
</div>

---

# Timeline — Eight Months

<div class="timeline">
  <div class="timeline-header">
    <div class="timeline-month">M1</div>
    <div class="timeline-month">M2</div>
    <div class="timeline-month">M3</div>
    <div class="timeline-month">M4</div>
    <div class="timeline-month">M5</div>
    <div class="timeline-month">M6</div>
    <div class="timeline-month">M7</div>
    <div class="timeline-month">M8</div>
  </div>
  <div class="timeline-row">
    <div class="timeline-label">Phase 1 · Ramco Brain</div>
    <div class="timeline-track">
      <div class="timeline-bar phase-1" style="width: 25%;">
        On-site at Chennai · 2 engineers immersed
      </div>
    </div>
  </div>
  <div class="timeline-row">
    <div class="timeline-label">Phase 2A · Agent Orchestration</div>
    <div class="timeline-track">
      <div class="timeline-bar phase-2a" style="margin-left: 25%; width: 75%;">
        Independent build · Dedicated Vizuara team
      </div>
    </div>
  </div>
  <div class="timeline-row">
    <div class="timeline-label">Phase 2B · Data Migration</div>
    <div class="timeline-track">
      <div class="timeline-bar phase-2b" style="margin-left: 25%; width: 75%;">
        Independent build · Dedicated Vizuara team
      </div>
    </div>
  </div>
</div>

<style scoped>
.timeline {
  margin-top: 1.5rem;
  font-size: 0.85rem;
}
.timeline-header {
  display: grid;
  grid-template-columns: repeat(8, 1fr);
  margin-left: 14rem;
  margin-bottom: 0.75rem;
  border-bottom: 1px solid var(--v-border);
  padding-bottom: 0.4rem;
}
.timeline-month {
  color: var(--v-muted);
  font-size: 0.7rem;
  text-align: center;
  font-weight: 500;
  letter-spacing: 0.05em;
}
.timeline-row {
  display: flex;
  align-items: center;
  margin-bottom: 0.75rem;
}
.timeline-label {
  width: 14rem;
  font-weight: 500;
  color: var(--v-primary);
  font-size: 0.85rem;
  padding-right: 1rem;
}
.timeline-track {
  flex: 1;
  position: relative;
}
.timeline-bar {
  height: 2.4rem;
  display: flex;
  align-items: center;
  padding: 0 0.9rem;
  color: white;
  font-size: 0.72rem;
  font-weight: 500;
  border-radius: 4px;
  letter-spacing: 0.01em;
}
.phase-1 { background: #1e3a5f; }
.phase-2a { background: #4a6b8a; }
.phase-2b { background: #6b8caa; }
</style>

<div class="mt-8 muted">
  Phase 1 lays the foundation. Phases 2A and 2B run in parallel for six months, each with a dedicated Vizuara team operating on the shared Ramco Brain.
</div>

---

# Engagement Model

<div class="grid grid-cols-2 gap-8">
  <div>
    <h3>Phase 1 · On-site at Chennai</h3>
    <ul>
      <li>Two Vizuara engineers resident in Chennai</li>
      <li>Daily working sessions with the rAegis team</li>
      <li>Full access to the codebase and knowledge graph</li>
      <li>Shared workspace at Ramco</li>
    </ul>
  </div>
  <div>
    <h3>Phase 2 · Independent Build</h3>
    <ul>
      <li>Vizuara teams operate independently from Vizuara offices</li>
      <li>Weekly sync calls with Ramco technical liaison</li>
      <li>Monthly working demos</li>
      <li>Quarterly executive reviews</li>
    </ul>
  </div>
</div>

<hr class="divider">

<h3>Handover</h3>
<p>All code, documentation, and infrastructure are handed over at the end of each phase. Ramco owns everything Vizuara builds. Both projects are demonstrated end to end on reference scenarios before handover.</p>

---

# Why This Approach Works

<ul>
  <li><strong>One foundation, two projects.</strong> We do not pay the understanding cost twice.</li>
  <li><strong>On-site immersion.</strong> Ambiguity gets resolved in person, in hours — not over email, in weeks.</li>
  <li><strong>Parallel execution.</strong> Once the foundation is built, both projects run at full velocity without blocking each other.</li>
  <li><strong>Independent delivery.</strong> Ramco does not need to allocate dedicated engineers to manage our teams.</li>
  <li><strong>Clear handover.</strong> Everything is documented, reproducible, and owned by Ramco at completion.</li>
  <li><strong>Lasting value.</strong> The Ramco Brain from Phase 1 is an asset Ramco keeps forever — usable for any future work on the platform, not just these two projects.</li>
</ul>

---

# What We Need From Ramco

<ul>
  <li>Access to the rAegis codebase, Neo4j graph, MCP layer, and Rflow during Phase 1</li>
  <li>Dedicated time with the core architects during the first two weeks</li>
  <li>Workspace at Chennai for the two on-site engineers during Phase 1</li>
  <li>A designated technical liaison throughout the full engagement</li>
  <li>A reference customer migration scenario for the Phase 2B demonstration</li>
  <li>Agreement on scope, timeline, and commercial terms to kick off</li>
</ul>

---

# Next Steps

<div class="grid grid-cols-2 gap-6 mt-4">
  <div class="card">
    <div class="eyebrow">Week 0</div>
    <h3>Agreement</h3>
    <p class="muted">Scope, timeline, and commercial terms agreed between Vizuara and Ramco leadership.</p>
  </div>
  <div class="card">
    <div class="eyebrow">Week 1</div>
    <h3>Kickoff</h3>
    <p class="muted">Two Vizuara engineers arrive at Chennai. On-site working sessions begin with the rAegis team.</p>
  </div>
  <div class="card">
    <div class="eyebrow">Month 2</div>
    <h3>Phase 1 Handover</h3>
    <p class="muted">Ramco Brain delivered. Phase 2 teams onboarded onto the foundation.</p>
  </div>
  <div class="card">
    <div class="eyebrow">Month 3</div>
    <h3>Phase 2 Launch</h3>
    <p class="muted">Agent Orchestration and Data Migration builds begin in parallel.</p>
  </div>
</div>

---

<div class="cover">
  <div class="eyebrow">Eight Months · Two Projects · One Foundation</div>
  <h1>Let us build this together.</h1>
  <div class="sub">The two projects Ramco described are not separate problems. They share a single foundation. Our proposal is to build that foundation once, in Chennai, with two engineers immersed in your team — and then execute both projects in parallel on top of it.</div>
  <div class="meta">Vizuara · Ready to begin</div>
</div>
