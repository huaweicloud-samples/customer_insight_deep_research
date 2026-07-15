# Reusable Prompt Template / 可复用提示词模板

Use this template when asking the skill to generate a customer insight package.

```text
Use $customer-insight-deep-research to generate a bilingual Chinese-English customer insight package for:

Customer / 客户:
<customer name>

Country or region / 国家或区域:
<country/region>

Business question / 核心问题:
<account strategy, cloud opportunity, architecture modernization, regulated process analysis, API analysis, executive briefing, etc.>

Input materials / 输入材料:
- <official website>
- <annual report / investor material>
- <regulatory documents>
- <API or developer documentation>
- <industry reports>
- <customer interview notes>
- <existing PPT/report>

Required output / 输出要求:
1. Bilingual Word insight report.
2. Bilingual PowerPoint insight deck.
3. Market insight, business insight, and technology insight in that order.
4. Acronyms and name explanations.
5. Served objects, direct customers, end users, and payer/user separation.
6. Investors, ownership, business development history, path, and goals.
7. Major customer examples.
8. Product-level market space, competitors, revenue/share disclosure or proxy metrics.
9. Peer benchmark and China analogues.
10. Product-by-product technical architecture and deployment architecture.
11. API categories and business process analysis.
12. Cloud requirements: availability, latency, reliability, data consistency, DR, observability, compliance, and workload placement.
13. Editable diagrams: market panorama, ecosystem map, process flow, API/capability map, technical architecture, deployment architecture, workload placement matrix, and roadmap.
14. Updated customer discussion questions.
15. Sources and evidence notes.

Important constraints / 约束:
- Separate confirmed facts, regulatory requirements, industry benchmarks, and inferences.
- Do not invent undisclosed revenue, market share, internal architecture, cloud vendor, database, middleware, or deployment region.
- Use official and regulatory sources first.
- Verify arrow direction in all flowcharts and architecture diagrams.
```