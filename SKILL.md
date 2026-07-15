---
name: customer-insight-deep-research
description: Conduct bilingual Chinese-English deep customer insight research and produce customer-facing Word/PPT insight deliverables for account planning, cloud strategy, regulated-industry analysis, business process/API mapping, technology architecture inference, workload placement, peer benchmarking, and executive briefing.
---

# Customer Insight Deep Research

## Overview

Use this skill to turn public evidence, customer materials, regulatory documents, API references, architecture clues, and interview notes into a structured bilingual customer insight package. The default output is a Chinese-English Word report plus a Chinese-English PowerPoint deck for account strategy, cloud architecture discussion, executive briefing, and customer workshops.

## Use This Skill When

- The user asks for customer insight, account insight, company deep research, customer profile, or customer strategy analysis.
- The user needs a bilingual Word report and PPT deck for a named customer.
- The customer operates in a regulated or process-heavy industry such as finance, payment, banking, telecom, government, energy, transportation, healthcare, or manufacturing.
- The task requires mapping market space, business model, customers served, end users, operating processes, APIs, compliance obligations, technology architecture, cloud deployment, resilience, or workload placement.
- The user wants peer benchmarking, China analogues, customer discussion questions, or a sales/solution opportunity roadmap.

## Default Output

Unless the user asks otherwise, produce two final deliverables:

1. A bilingual Chinese-English Word report (`.docx`) with evidence-backed narrative, tables, charts, process flows, and architecture diagrams.
2. A bilingual Chinese-English PowerPoint deck (`.pptx`) with executive-readable, editable diagrams, matrices, flowcharts, roadmaps, and architecture views.

Chinese is the primary narrative language. English equivalents are required for section titles, key findings, charts, table headers, diagram labels, capability names, roadmap items, and discussion questions.

## Evidence Discipline

Keep four evidence layers clearly separated:

1. Officially disclosed customer facts.
2. Regulatory or legal requirements.
3. Industry best practices and market benchmarks.
4. Architecture or business inferences.

Never present an inference as a confirmed fact. Do not estimate undisclosed revenue, market share, ownership, internal architecture, cloud vendor, database, middleware, region, or SLA unless the method, proxy, and confidence level are explicitly stated.

## Workflow

1. Define research boundary: target customer, geography, product scope, business question, time horizon, and output format.
2. Collect and rank evidence: customer website, filings/reports, investor materials, regulatory records, official API/developer documents, industry reports, cloud case studies, reputable news, and user-provided files.
3. Build the fact base: acronyms/name explanations, positioning, served objects, direct customers, end users, products, investors, ownership, history, major customers, operating scale, APIs, regulatory obligations, technology clues, cloud clues, and evidence notes.
4. Analyze six dimensions: business model/customer segments, operating process, technology platform, data/API ecosystem, security/compliance, and cloud/resilience.
5. Organize the narrative in this order: market insight, business insight, technology insight, cloud/resilience recommendations, roadmap, and customer discussion questions.
6. Generate visual diagrams. Every flow arrow must point from upstream/source/trigger to downstream/target/outcome.
7. Produce Word and PPT deliverables, then verify bilingual coverage, evidence separation, chart readability, source traceability, and arrow direction.

## Required Resource Routing

Read the relevant reference files before work:

- `references/customer-insight-framework.md`: full original framework and detailed method. Required for any full customer insight report or deck.
- `references/deliverable-and-diagram-requirements.md`: required before generating Word or PPT deliverables.
- `references/payment-and-regulated-industry-playbook.md`: required for payments, banking, fintech, open finance, cards, acquiring, wallets, PSPs, or regulated transaction platforms.
- `references/reusable-prompt-template.md`: use when the user asks for a reusable prompt, handoff prompt, or research brief template.

## Quality Gate

Before final delivery, verify that:

- The report explains who the customer serves, who pays, who uses the service, and where the customer sits in the value chain.
- Market space and peer comparison are in the market insight section.
- Investors, ownership, history, business path, and customer examples are in the business insight section.
- Product-by-product architecture, deployment architecture, API categories, data flows, resilience, and cloud implications are in the technology insight section.
- Every major insight is tied to a source, a regulation, a benchmark, or an explicitly labeled inference.
- Diagrams include market panorama, ecosystem map, process flow, API/capability map, product architecture, deployment architecture, workload placement, and roadmap when relevant.
- PPT diagrams are editable shapes where practical; avoid text-only slides for complex processes or architectures.
- Arrowheads and flow direction are visually correct.