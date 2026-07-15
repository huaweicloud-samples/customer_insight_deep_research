# Customer Insight Deep Research Skill

This repository contains a Codex skill for bilingual Chinese-English customer insight research. It helps produce customer-facing Word and PowerPoint deliverables for account planning, regulated-industry analysis, cloud strategy, business process/API deep dives, technology architecture inference, workload placement, and executive briefing.

## What This Skill Produces

- Bilingual customer insight Word report (`.docx`).
- Bilingual customer insight PowerPoint deck (`.pptx`).
- Market insight, business insight, technology insight, cloud/resilience recommendations, roadmap, and customer discussion questions.
- Editable diagrams such as value-chain maps, ecosystem maps, process flows, API maps, product architecture, deployment architecture, workload placement matrices, and roadmaps.

## Directory Structure

```text
customer-insight-deep-research/
  SKILL.md
  README.md
  agents/
    openai.yaml
  references/
    customer-insight-framework.md
    deliverable-and-diagram-requirements.md
    payment-and-regulated-industry-playbook.md
    reusable-prompt-template.md
```

## Installation

Copy the `customer-insight-deep-research` folder into your Codex skills directory, for example:

```powershell
Copy-Item -Recurse .\customer-insight-deep-research $env:USERPROFILE\.codex\skills\
```

After installation, invoke it by name:

```text
Use $customer-insight-deep-research to research <customer name> and produce a bilingual Word and PPT insight package.
```

## Methodology

The skill follows a structured workflow:

1. Define research boundary and business questions.
2. Collect evidence from official, regulatory, API, market, and user-provided sources.
3. Build a customer fact base, including acronyms, customer roles, served objects, direct customers, end users, investors, ownership, history, products, operating scale, APIs, regulatory obligations, technology clues, and cloud clues.
4. Analyze six dimensions: business model, operating process, technology platform, data/API ecosystem, security/compliance, and cloud resilience.
5. Present findings in the sequence of market insight, business insight, technology insight, cloud strategy, roadmap, and discussion questions.
6. Produce bilingual Word and PPT deliverables with traceable evidence and editable diagrams.

## Notes for GitHub Use

- `SKILL.md` is the Codex entry point and should stay concise.
- Long methodology and industry-specific playbooks belong in `references/`.
- `README.md` is for human readers on GitHub.
- `agents/openai.yaml` provides optional UI metadata for Codex-compatible environments.

## Validation

Run the skill validator after edits:

```powershell
python C:\Users\<user>\.codex\skills\.system\skill-creator\scripts\quick_validate.py .\customer-insight-deep-research
```