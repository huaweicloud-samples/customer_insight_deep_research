# Customer Insight Deep Research Skill
客户洞察深度研究 Skill

## 1. Purpose / 技能目标

This skill helps solution architects, cloud strategists, and consulting teams conduct structured customer insight research and convert it into customer-facing strategy materials, architecture diagrams, capability maps, and PPT decks.

本 Skill 用于帮助解决方案架构师、云战略规划人员和咨询团队，对目标客户进行系统化洞察研究，并沉淀为客户交流材料、战略建议、架构图、能力地图和 PPT。

Typical scenarios / 典型场景：
- Customer account insight / 客户洞察
- Cloud and multi-cloud strategy / 云与多云策略
- Solution and API capability mapping / 解决方案与 API 能力梳理
- Regulated industry architecture analysis / 监管行业架构分析
- Business process and workload placement assessment / 业务流程与工作负载部署评估
- Executive briefing deck generation / CXO 汇报材料生成

Default output language / 默认输出语言：
- Generate a bilingual Chinese-English insight report by default.
- Use Chinese as the primary narrative language and provide English equivalents for section titles, key findings, tables, diagrams, capability names, architecture labels, roadmap items, and discussion questions.
- If the user explicitly requests a single language, follow the user's language requirement.

- 默认生成中英文双语洞察报告。
- 中文作为主叙述语言；章节标题、关键结论、表格、图表、能力名称、架构标签、路线图和客户讨论问题应提供英文对照。
- 如用户明确要求单一语言，则按用户要求输出。

Default deliverables / 默认交付件：
- Produce two final files by default: (1) a bilingual Word insight report (`.docx`), and (2) a bilingual PowerPoint insight report (`.pptx`).
- Use Markdown, outlines, tables, or diagrams only as intermediate working artifacts unless the user explicitly asks for them as final outputs.
- The Word report should be the comprehensive evidence-based narrative and must include visual diagrams, not only text and tables.
- The PPT report should be an executive-readable consulting deck with editable charts, matrices, process flows, market maps, and architecture diagrams.
- Do not deliver a text-only insight report when the user asks for deep insight, industry insight, customer insight, architecture insight, payment-process insight, API insight, or PPT/Word deliverables.

- 默认输出两份最终文件：（1）中英文双语 Word 洞察报告（`.docx`），（2）中英文双语 PowerPoint 洞察报告（`.pptx`）。
- Markdown、大纲、表格或图形仅作为中间工作产物，除非用户明确要求作为最终输出。
- Word 报告用于承载完整、基于证据的深度叙述，并必须包含必要图形，不得只有文字和表格。
- PPT 报告用于承载 CXO 可读的咨询式汇报材料，应使用可编辑图表、矩阵、流程图、市场地图和架构图。
- 当用户要求深度洞察、行业洞察、客户洞察、架构洞察、支付流程洞察、API 洞察或 Word/PPT 交付件时，不得输出纯文本洞察。

---

## 2. Core Principle / 核心原则

Always separate four layers of evidence:

始终区分四类信息：

| Layer | English | 中文 | Usage Rule |
|---|---|---|---|
| 1 | Officially disclosed facts | 官方披露事实 | Can be used as direct evidence / 可作为直接证据 |
| 2 | Regulatory or legal requirements | 监管与法规要求 | Can be used as compliance baseline / 可作为合规基线 |
| 3 | Industry best practice | 行业最佳实践 | Can be used as recommended design / 可作为建议方案 |
| 4 | Architecture inference | 架构推断 | Must be clearly marked as assumption / 必须标注为推断 |

Never mix customer-owned systems, partner systems, and ecosystem participants unless the relationship is officially verified.

不得把客户自身系统、合作伙伴系统、生态参与方系统混为一谈，除非官方资料已经明确说明其关系。

Example from Elo case / Elo 案例示例：
- Elo is a payment scheme, card network, and payment arrangement owner.
- Cielo is an acquirer and payment acceptance ecosystem participant.
- Cielo can be referenced as an ecosystem participant, but should not be treated as Elo's internal IT system unless official evidence proves it.

---

## 3. Required Inputs / 输入信息

The user may provide one or more of the following:

用户可提供以下一种或多种输入：

1. Customer name / 客户名称
2. Customer website / 客户官网
3. Annual report, ESG report, or sustainability report / 年报、ESG 或可持续发展报告
4. Regulatory documents / 监管文件
5. Product, solution, or API portal / 产品、解决方案或 API 门户
6. Existing architecture clues / 已知架构线索
7. Business interview notes / 业务访谈纪要
8. Existing PPT or report / 已有 PPT 或报告
9. Strategy question / 战略问题
10. Target output format and deliverables / 目标输出格式与交付件

If official URLs or documents are provided, prioritize those sources first.

如果用户提供官方链接或文件，优先使用官方资料。

---

## 4. Research Workflow / 研究流程

### Step 1: Define Research Boundary / 明确研究边界

Clarify:
- Who is the target customer?
- What industry does it belong to?
- What is the objective of the discussion?
- Is the output for internal account planning or customer-facing discussion?
- Is the focus business, technology, cloud, compliance, API, ecosystem, or all of them?

需要明确：
- 目标客户是谁？
- 所属行业是什么？
- 讨论目标是什么？
- 输出用于内部客户经营，还是面向客户交流？
- 重点是业务、技术、云、合规、API、生态，还是全景分析？

### Step 2: Collect Evidence / 收集证据

Use sources in this order:

证据优先级：

1. Customer official website / 客户官网
2. Customer reports / 年报、ESG、技术白皮书
3. Regulatory authority / 监管机构资料
4. Legal documents / 法律法规
5. Product and API documentation / 产品与 API 文档
6. Cloud case studies / 云厂商案例
7. Industry reports / 行业报告
8. News and secondary sources / 新闻与二手资料

### Step 3: Build the Customer Fact Base / 建立客户事实库

Extract and label facts or disclosure gaps. Do not estimate undisclosed revenue, market share, ownership percentage, internal architecture, cloud vendor, database, middleware, or deployment region.

提取并标注事实或公开资料缺口。不得在公开资料不足时估算收入、市场份额、持股比例、内部系统、云厂商、数据库、中间件或部署地域。

Fact base fields / 事实库字段：
- Company positioning and industry role / 公司定位与行业角色
- Acronyms, role definitions, and name explanations / 缩略语、角色定义与关键名称解释
- Business scope and product portfolio / 业务范围与产品组合
- Served objects, direct customers, end users, and customer segments / 服务对象、直接客户、终端用户与客户群体
- Major customer examples, partners, and ecosystem participants / 主要客户举例、合作伙伴与生态参与方
- Investors, financing rounds, ownership facts, and ownership disclosure gaps / 投资人、融资轮次、股权事实与股权披露缺口
- Business development history, path, strategic goals, acquisitions, licenses, and geographic expansion / 业务发展历程、路径、战略目标、并购、牌照与地域扩张
- Operating scale, product-line scale, and proxy metrics if available / 经营规模、产品线规模与可用代理指标
- Product-level market space, competitors, revenue/share disclosure, and market-sizing method / 产品级市场空间、竞品、收入/份额披露与市场估算方法
- Technology initiatives and product-by-product technical architecture clues / 技术项目与分产品技术架构线索
- Solution, API, data, and developer ecosystem clues / 解决方案、API、数据与开发者生态线索
- Cloud, data center, deployment, and resilience clues / 云、数据中心、部署与韧性线索
- Regulatory obligations and compliance baseline / 监管义务与合规基线
- Security, privacy, continuity, and audit commitments / 安全、隐私、连续性与审计承诺
- Sources and evidence notes / 参考资料与证据说明

Disclosure discipline / 披露纪律：
- Revenue / 收入：If public sources do not disclose company or product-line revenue, state that clearly and use proxy indicators and market-sizing logic.
- Market share / 市场份额：If no directly comparable share is disclosed, assess market position through scale proxies and peer comparison.
- Ownership / 股权结构：If the company is private or does not disclose a full capitalization table, do not infer shareholder percentages.
- Architecture / 架构：If architecture is inferred from product capabilities and industry patterns, mark it as architecture inference, not an official internal system diagram.
### Step 4: Analyze Across Six Dimensions / 六维分析

| Dimension | English | 中文 |
|---|---|---|
| Business Model & Customer Segments | What business does the customer operate, who does it serve, and who are its direct customers and end users? | 客户经营什么业务？服务对象是谁？谁是它的直接客户和终端用户？ |
| Operating Process | How does value flow end to end? | 端到端业务流程如何流转？ |
| Technology Platform | What systems and platforms support the business? | 有哪些系统和平台支撑？ |
| Data & API | What data and API capabilities exist? | 有哪些数据与 API 能力？ |
| Security & Compliance | What regulatory and security requirements apply? | 有哪些安全与合规要求？ |
| Cloud & Resilience | How should workloads be deployed across cloud/on-prem? | 工作负载应如何在云和本地部署？ |

### Step 5: Generate Strategic Questions / 形成战略问题

Generate updated discussion questions across market, business, and technology insight. Ask:

围绕市场洞察、业务洞察、技术洞察形成更新后的客户讨论问题。需要询问：

Market insight / 市场洞察：
- What is the addressable market for each major product line?
- Which competitors are global benchmarks, regional peers, local challengers, and China analogues?
- Which scale proxies can replace undisclosed revenue or market share?
- Which regulatory or ecosystem shifts change the market opportunity?

Business insight / 业务洞察：
- Who does the customer serve, who are its direct customers, and who are the end users?
- Which customer examples prove each product line or capability?
- Who are the investors, what ownership facts are public, and what ownership details are not disclosed?
- How has the business evolved, and what path or goal does the history imply?
- Which capabilities are mission-critical and monetizable?

Technology insight / 技术洞察：
- Which processes require real-time response?
- Which processes are batch, asynchronous, or evidence-based?
- Which APIs must be highly available?
- Which data is regulated or sensitive?
- Which product modules need strong consistency, and which can tolerate eventual consistency?
- Which modules are suitable for multi-cloud active-active?
- Which modules should use primary + DR?
- Which workloads should stay on-prem/private or in a controlled security zone?
- Which cloud platform is best suited for each workload?
---

## 5. Standard Analysis Framework / 标准分析框架

Organize the analysis in this order: foundation and role clarity, market insight, business insight, operating process, solution/API, technology insight, and cloud/resilience.

分析顺序应为：基础定位与角色厘清、市场洞察、业务洞察、业务流程、解决方案/API、技术洞察、云与韧性。

### 5.1 Foundation and Role Clarity / 基础定位与角色厘清

Output:
- One-line positioning / 一句话定位
- Role in industry value chain / 产业链位置
- Core business capabilities / 核心业务能力
- Served objects, customer types, and partner ecosystem / 服务对象、客户类型与合作伙伴生态
- Business boundary / 业务边界
- Acronyms and name explanations / 缩略语与名称解释
- Role definitions that prevent category confusion / 防止定位混淆的角色定义

For regulated industries, explain ambiguous names and roles such as regulator, payment scheme, payment arrangement owner, issuer, acquirer, processor, PSP, BaaS, Open Finance participant, API provider, clearing/settlement system, core ledger, token vault, and data platform.

对监管行业，应解释容易混淆的名称与角色，例如监管机构、支付方案、支付安排设立方、发卡方、收单方、处理商、PSP、BaaS、开放金融参与方、API 提供方、清结算系统、核心账本、Token Vault 和数据平台。

### 5.2 Market Insight / 市场洞察

Cover industry panorama, market structure, value chain, regulatory and ecosystem forces, product-level market space, competitors, revenue/share disclosure, peer benchmark, China analogues, market-sizing method, proxy metrics, and market opportunity thesis.

覆盖行业全景、市场结构、价值链、监管与生态力量、产品级市场空间、竞品、收入/份额披露、同业标杆、中国类似企业、市场估算方法、代理指标与市场机会判断。

Market insight must contain market space and peer comparison. Do not place market space, peer benchmark, competitive landscape, or China analogue analysis under Business Insight unless repeated only as a brief business implication.

市场洞察必须包含市场空间与同业对比。不得把市场空间、同业标杆、竞争格局或中国类似企业分析放到业务洞察下；如需在业务洞察中提及，只能作为简短业务含义回扣。

#### 5.2.0 Market Landscape, Value Chain and Opportunity Thesis / 市场全景、价值链与机会判断

Start market insight with a market map before product details. For regulated or infrastructure-heavy industries, show the whole market system before comparing companies.

市场洞察必须先给出市场地图，再进入产品细节。对监管强、基础设施属性强的行业，应先说明完整市场体系，再比较公司。

Required outputs:
- Industry taxonomy / 行业分层：regulator, market infrastructure, schemes/arrangements, participants, processors/platforms, channels, enterprise customers, end users.
- Value chain and profit pool map / 价值链与利润池地图：where revenue, risk, data, and control points sit.
- Market drivers and constraints / 市场驱动与约束：regulation, digitization, real-time payment adoption, API/open finance, fraud/risk, inclusion, merchant demand, cloud/AI modernization.
- Demand-side segmentation / 需求侧分层：direct customers, served objects, end users, enterprise segments, merchant/consumer/SME scenarios.
- Supply-side segmentation / 供给侧分层：incumbents, global benchmarks, regional specialists, local challengers, ecosystem partners, China analogues.
- Opportunity thesis / 机会判断：where the customer can grow, defend, partner, or differentiate.
- Disclosure boundary / 披露边界：which market, revenue, share, or segment facts are public and which require proxy metrics.

Visual requirement:
- Include an editable market panorama or value-chain diagram.
- Include a market segmentation matrix or opportunity heatmap when data allows.

图形要求：
- 必须包含可编辑的市场全景图或价值链图。
- 如数据允许，应包含市场分层矩阵或机会热力图。

#### 5.2.1 Product-Level Market Space / 产品级市场空间

For each major product line, produce a product-by-product table:

| Column | Required content |
|---|---|
| Product / 产品 | Official product or solution name |
| Offering / 能力 | What the product does |
| Served customer / 服务对象 | Direct customer segments and end-user segments |
| Market space / 市场空间 | Addressable market category and demand drivers |
| Main competitors / 主要竞品 | Global, regional, local, and China analogues when relevant |
| Revenue/share disclosure / 收入与份额披露 | Official numbers or explicit disclosure gap |
| Technical architecture implication / 技术架构含义 | Likely systems, data, APIs, consistency, latency, resilience, and security needs |

If product details are inferred from capability descriptions, mark them as architecture inference.

如果产品细节来自能力描述推断，必须标注为架构推断。

#### 5.2.2 Competitive Landscape, Peer Benchmark and China Analogues / 竞争格局、同业标杆与中国类似企业

Create three market-comparison views under Market Insight:

1. Competitive landscape map / 竞争格局地图：classify incumbents, global benchmarks, regional specialists, local challengers, ecosystem partners, and substitutes.
2. Global/regional benchmark / 全球或区域标杆：compare companies with similar product capabilities, regulatory roles, API/platform models, geographic footprint, customer segments, and monetization logic.
3. China analogues / 中国类似企业：identify Chinese companies with comparable capabilities, but avoid claiming one-to-one equivalence when regulatory structure, clearing infrastructure, bank/payment licensing, or customer ownership differs.

Comparison dimensions:
- Direct customers and end users / 直接客户与终端用户
- Product scope / 产品范围
- Regulatory or license role / 监管或牌照角色
- API/platform maturity / API 与平台成熟度
- Real-time payment, card-processing, or core workflow capability / 实时支付、卡处理或核心流程能力
- Data, fraud, and risk capability / 数据、风控与风险能力
- Geographic expansion path / 地域扩张路径
- Differentiation and benchmark value / 差异化与标杆意义

#### 5.2.3 Market-Sizing Method and Proxy Metrics / 市场空间估算方法与代理指标

Use official revenue or market share only when disclosed. For private or non-reporting companies, use proxy metrics and clearly state the limitation.

仅在官方披露时使用收入或市场份额。对私营或未披露公司，应使用代理指标并明确限制。

Proxy metrics may include active accounts, active cards, transaction count, TPV, payment volume, merchant count, enterprise clients, countries served, API calls, fraud checks, chargeback reduction, data export volume, or platform uptime.

代理指标可包括活跃账户、活跃卡、交易笔数、TPV、支付金额、商户数、企业客户数、覆盖国家、API 调用量、欺诈检测次数、拒付降低、数据导出量或平台可用性。

### 5.3 Business Insight / 业务洞察

Cover business model, customer examples, investors, ownership, capital signals, business history, strategic path, goals, ecosystem, and capability map.

覆盖业务模式、客户样例、投资人、股权结构、资本信号、业务发展历程、战略路径、目标、生态与能力全景。

#### 5.3.1 Business Capability Map / 业务能力全景

Group capabilities into categories.

Example for payment customers / 支付客户示例：

| Category | English | 中文 |
|---|---|---|
| Payment Scheme | Rules, authorization, clearing, settlement | 支付规则、授权、清算、结算 |
| Security & Risk | Fraud, identity, SIM swap, token, 3DS | 欺诈、身份、SIM Swap、Token、3DS |
| Partner Enablement | API, sandbox, developer portal | API、沙箱、开发者门户 |
| Data & Analytics | BI, risk analytics, reporting | BI、风险分析、报表 |
| Regulatory & Compliance | Audit, evidence, reporting, continuity | 审计、证据、监管报送、连续性 |

#### 5.3.2 Investors, Ownership and Capital Signals / 投资人、股权结构与资本信号

Identify public investors, financing rounds, lead investors, strategic investors, founders or management ownership if disclosed, and exact ownership percentages only when officially disclosed. If not disclosed, state `not publicly disclosed` instead of estimating.

识别公开投资人、融资轮次、领投方、战略投资方、创始人或管理层持股公开信息；只有官方披露时才写精确持股比例。未披露时写明 `公开资料未披露`，不得估算。

#### 5.3.3 Business Development History, Path and Goals / 业务发展历程、路径和目标

Create a timeline from origin to current strategic direction. Cover acquisitions, licenses, geographic expansion, product launches, platform shifts, and stated or inferred goals.

从创立或业务起点到当前战略方向建立时间线，覆盖并购、牌照、地域扩张、产品发布、平台化转型，以及官方目标或基于事实的目标推断。

#### 5.3.4 Major Customer Examples / 主要客户举例

List customers or partners only when shown on official product pages, annual reports, case studies, press releases, or credible public sources. Distinguish direct customers, partners, regulators, schemes, technology suppliers, and end users.

只有在官方产品页、年报、案例、新闻稿或可信公开来源中出现时才列出客户或合作方。必须区分直接客户、合作伙伴、监管机构、支付方案/卡组织、技术供应商和终端用户。

### 5.4 Business Process Map / 业务流程全景

Classify processes by:
- Real-time / 实时
- Near-real-time / 准实时
- Batch / 批处理
- Asynchronous workflow / 异步工作流
- Evidence-based process / 证据型流程

For each process, capture:

| Attribute | Description |
|---|---|
| Process name | 业务流程名称 |
| Purpose | 业务目的 |
| Participants | 参与方 |
| Trigger | 触发条件 |
| Processing time | 实时、分钟级、D+N、日终 |
| Consistency requirement | 强一致、最终一致、批次一致 |
| Reliability requirement | 高可用、可重试、可恢复、可审计 |
| Multi-cloud suitability | 双活、主备、灾备、不建议 |

### 5.5 Solution & API Capability Map / 解决方案与 API 能力全景

Suggested categories:

| Category | English | 中文 |
|---|---|---|
| Payment APIs | Authorization, reversal, refund, transaction inquiry | 授权、冲正、退款、交易查询 |
| Identity & Authentication APIs | Login, IAM, SSO, device trust, API security | 登录、IAM、SSO、设备可信、API 安全 |
| Risk & Fraud APIs | Fraud scoring, SIM swap, behavior risk | 欺诈评分、SIM Swap、行为风险 |
| Token & Digital Payment APIs | Tokenization, wallet binding, QR, NFC | Token 化、钱包绑卡、二维码、NFC |
| Clearing & Settlement APIs | Clearing files, settlement positions, reconciliation | 清算文件、结算头寸、对账 |
| Dispute APIs | Chargeback, evidence, arbitration, status tracking | 拒付、证据、仲裁、状态跟踪 |
| Partner APIs | Sandbox, onboarding, certification, reporting | 沙箱、接入、认证、报表 |
| Data & Insight APIs | Metrics, dashboards, alerts, data products | 指标、看板、告警、数据产品 |

### 5.6 Technology Insight / 技术洞察

Cover product-by-product technical architecture, platform layers, data/API surfaces, security, resilience, and architecture assumptions.

覆盖分产品技术架构、平台分层、数据/API 触点、安全、韧性与架构推断。

#### 5.6.1 Product-by-Product Technical Architecture / 分产品技术架构分析

For each product line, capture:
- Officially disclosed technical capabilities / 官方披露技术能力
- Likely architecture layers and core components / 可能架构层与核心组件
- API, data, event, and integration surfaces / API、数据、事件与集成触点
- Latency, consistency, reliability, and audit requirements / 延迟、一致性、可靠性与审计要求
- Data sensitivity and security boundary / 数据敏感性与安全边界
- Cloud and resilience implication / 云与韧性含义

#### 5.6.2 Technology Architecture Map / 技术架构全景

Recommended layers:

1. Channel and access layer / 渠道与接入层
2. Product orchestration layer / 产品编排层
3. API and integration layer / API 与集成层
4. Core transaction and ledger layer / 核心交易与账本层
5. Payment and network integration layer / 支付与网络集成层
6. Risk, identity and compliance layer / 风险、身份与合规层
7. Data and analytics layer / 数据分析层
8. Security and resilience layer / 安全与韧性层
9. Governance and operations layer / 治理运维层
10. Infrastructure and cloud layer / 基础设施与云层

For each workload, classify:

| Attribute | Required assessment |
|---|---|
| Latency / 延迟 | real-time, near-real-time, batch, asynchronous |
| Consistency / 一致性 | strong, eventual, batch-consistent, evidence-based |
| Reliability / 可靠性 | HA, retry, replay, DR, stand-in, manual recovery |
| Data sensitivity / 数据敏感性 | public, customer, PII, PAN/PIN, token/key, regulated evidence |
| Multi-cloud suitability / 多云适配性 | active-active, active-standby, single-primary + DR, controlled/private only |

### 5.7 Multi-Cloud Suitability Assessment / 多云适配性评估

Evaluate each workload by:

| Criterion | Question |
|---|---|
| Latency sensitivity | Is the process latency-critical? |
| State complexity | Does it involve strong transaction state? |
| Data sensitivity | Does it involve PAN, PII, keys, regulated data? |
| Consistency requirement | Strong consistency or eventual consistency? |
| Business criticality | What is the business impact of downtime? |
| Cloud portability | Can it run on containers or cloud-neutral services? |
| Recovery model | Active-active, active-standby, cold DR, backup only? |
| Operational complexity | Is multi-cloud worth the added complexity? |

Recommended classification:

| Suitability | Deployment Pattern | Example |
|---|---|---|
| High | Multi-cloud active-active | Authentication, API gateway, fraud scoring |
| Medium | Primary cloud + hot standby | Authorization routing, stand-in, token frontend |
| Low | Single-primary + DR | Clearing, settlement, ledger, reconciliation |
| Controlled | Centralized / private / on-prem | HSM root keys, token vault, regulatory legacy |
---

## 6. Recommended Output Structure / 推荐输出结构

Default final deliverables / 默认最终交付件：

1. Bilingual Word insight report (`.docx`) / 中英文双语 Word 洞察报告（`.docx`）
2. Bilingual PowerPoint insight report (`.pptx`) / 中英文双语 PPT 洞察报告（`.pptx`）

Generate both files unless the user explicitly requests only one format. The Word report should contain the full evidence base and detailed analysis; the PPT report should translate the same insight into concise executive visuals.

除非用户明确只要求一种格式，否则必须同时生成两份文件。Word 报告承载完整事实库和详细分析；PPT 报告将同一洞察转化为简明的管理层可读图表和架构视图。

### 6.1 Bilingual Word Insight Report / 中英文双语 Word 洞察报告

Recommended sections should follow market insight, business insight, and technology insight order while preserving evidence traceability:

推荐章节应按市场洞察、业务洞察、技术洞察的顺序组织，并保持证据可追溯：

| Order | Section |
|---|---|
| 1 | Executive Summary / 执行摘要 |
| 2 | Evidence Method and Disclosure Discipline / 证据方法与披露纪律 |
| 3 | Acronyms and Name Explanations / 缩略语与名称解释 |
| 4 | Market Insight: Industry Panorama, Value Chain and Opportunity Thesis / 市场洞察：行业全景、价值链与机会判断 |
| 5 | Market Insight: Product-Level Market Space, Competitors, Revenue/Share Disclosure / 市场洞察：产品级市场空间、竞品、收入与份额披露 |
| 6 | Market Insight: Competitive Landscape, Peer Benchmark and China Analogues / 市场洞察：竞争格局、同业标杆与中国类似企业 |
| 7 | Market Insight: Market-Sizing Method and Proxy Metrics / 市场洞察：市场空间估算方法与代理指标 |
| 8 | Business Insight: Company Positioning and Business Overview / 业务洞察：公司定位与业务全景 |
| 9 | Business Insight: Investors, Ownership and Capital Signals / 业务洞察：投资人、股权结构与资本信号 |
| 10 | Business Insight: Business Development History, Path and Goals / 业务洞察：业务发展历程、路径和目标 |
| 11 | Business Insight: Major Customer Examples and Ecosystem Map / 业务洞察：主要客户举例与生态全景 |
| 12 | Business Insight: Capability and Business Process Map / 业务洞察：能力全景与业务流程 |
| 13 | Technology Insight: Solution and API Capability Map / 技术洞察：解决方案与 API 能力 |
| 14 | Technology Insight: Product-by-Product Technical Architecture / 技术洞察：分产品技术架构分析 |
| 15 | Technology Insight: Security, Compliance and Continuity Requirements / 技术洞察：安全、合规与连续性要求 |
| 16 | Technology Insight: Cloud and Resilience Opportunity Analysis / 技术洞察：云与韧性机会分析 |
| 17 | Recommended Target Architecture and Workload Placement / 建议目标架构与工作负载部署 |
| 18 | Implementation Roadmap / 实施路线图 |
| 19 | Updated Discussion Questions / 更新后的客户讨论问题 |
| 20 | Sources and Evidence Notes / 参考资料与证据说明 |

Bilingual formatting rules:

- Use bilingual section titles in the form `English / 中文` or `中文 / English`, keeping one consistent order throughout the report.
- For executive summaries and strategic recommendations, provide Chinese paragraphs followed by concise English equivalents, or use two-column tables when easier to read.
- For tables, include bilingual column headers and bilingual values for capability names, process names, deployment patterns, and discussion questions.
- For diagrams, use bilingual labels for nodes and legends when space allows; otherwise use concise English labels with Chinese explanation below the diagram.
- Clearly mark facts, regulatory requirements, industry best practices, and architecture assumptions in both languages.
- If revenue, market share, ownership, or architecture details are not public, state the disclosure gap and provide proxy metrics or validation questions.

### 6.2 Bilingual PPT Insight Report / 中英文双语 PPT 洞察报告

Recommended slide structure should compress the same market-business-technology narrative for executives:

推荐 PPT 结构应将同一套“市场-业务-技术”叙事压缩为管理层可读页面：

| Slide | Title |
|---|---|
| 1 | Customer Insight Summary / 客户洞察摘要 |
| 2 | Evidence Boundary and Role Clarity / 证据边界与角色厘清 |
| 3 | Acronyms and Critical Name Explanations / 缩略语与关键名称解释 |
| 4 | Market Insight: Industry Panorama and Value Chain / 市场洞察：行业全景与价值链 |
| 5 | Market Insight: Product Market Space and Competitor Map / 市场洞察：产品市场空间与竞品地图 |
| 6 | Market Insight: Competitive Landscape, Peer Benchmark and China Analogues / 市场洞察：竞争格局、同业标杆与中国类似企业 |
| 7 | Market Insight: Revenue, Share Disclosure and Proxy Metrics / 市场洞察：收入、份额披露与代理指标 |
| 8 | Business Insight: Company Positioning and Industry Role / 业务洞察：公司定位与产业链角色 |
| 9 | Business Insight: Investors, Ownership and Capital Signals / 业务洞察：投资人、股权结构与资本信号 |
| 10 | Business Insight: Development Path and Strategic Goals / 业务洞察：发展路径与战略目标 |
| 11 | Business Insight: Major Customers and Ecosystem Map / 业务洞察：主要客户与生态全景 |
| 12 | Business Insight: Business Capability Landscape / 业务洞察：业务能力全景 |
| 13 | Business Insight: End-to-End Business Flow / 业务洞察：端到端业务流程 |
| 14 | Technology Insight: Solution and API Capability Map / 技术洞察：解决方案与 API 能力全景 |
| 15 | Technology Insight: Product-by-Product Architecture / 技术洞察：分产品技术架构 |
| 16 | Technology Insight: Security, Compliance and Continuity / 技术洞察：安全、合规与连续性 |
| 17 | Technology Insight: Multi-Cloud Suitability Matrix / 技术洞察：多云适配性矩阵 |
| 18 | Target Architecture and Workload Placement / 目标架构与工作负载部署 |
| 19 | Roadmap and Updated Discussion Questions / 路线图与更新后的讨论问题 |
| 20 | Sources and Evidence Notes / 参考资料与证据说明 |

### 6.3 Required Diagrams / 必要图形

Do not treat diagrams as decorative. For deep insight deliverables, diagrams are mandatory evidence-organization tools. Generate editable diagrams whenever possible, especially in PPT. In Word, use editable diagram objects where practical; if the Word generator cannot preserve editable shapes, include a clear rendered diagram plus the diagram source or structured table used to create it.

不得把图形当作装饰。深度洞察交付件中，图形是组织证据和表达判断的必要载体。PPT 中应尽量使用可编辑图形；Word 中如无法保留可编辑形状，应提供清晰渲染图，并保留生成该图的源结构或表格。

Minimum diagram set / 最低图形集合：

1. Market panorama and value-chain map / 市场全景与价值链图
2. Product-market and competitor map / 产品市场与竞品地图
3. Competitive landscape or peer benchmark matrix / 竞争格局或同业标杆矩阵
4. Ecosystem and stakeholder map / 生态与参与方地图
5. Business capability map / 业务能力图
6. End-to-end business process flow / 端到端业务流程图
7. Regulatory or industry-specific process flow when relevant / 监管或行业专项流程图（如适用）
8. Solution and API capability map / 解决方案与 API 能力图
9. Product-by-product technical architecture diagram / 分产品技术架构图
10. Overall layered technology architecture diagram / 总体分层技术架构图
11. Deployment architecture or multi-cloud target architecture / 部署架构或多云目标架构
12. Workload placement matrix / 工作负载部署矩阵
13. Roadmap / 路线图

Diagram rules / 图形规则：
- Every major insight section should include at least one diagram, matrix, or structured visual unless the user explicitly requests text only.
- Market Insight must include a market landscape/value-chain visual and a product-market/competitor visual.
- Business Insight must include an ecosystem map, capability map, and end-to-end process flow.
- Technology Insight must include API/solution map, product architecture map, layered target architecture, and workload placement matrix.
- Label each diagram as official fact, regulatory requirement, best-practice recommendation, or architecture inference.
- Use bilingual labels for diagram titles, legends, layers, nodes, and captions when space allows.
- Keep diagrams readable: avoid overcrowding; split dense diagrams across multiple pages/slides.

图形规则：
- 除非用户明确要求纯文本，否则每个主要洞察部分都应至少包含一张图、矩阵或结构化视觉。
- 市场洞察必须包含市场全景/价值链图和产品市场/竞品图。
- 业务洞察必须包含生态图、能力图和端到端流程图。
- 技术洞察必须包含 API/解决方案能力图、产品架构图、分层目标架构图和工作负载部署矩阵。
- 每张图都要标注属于官方事实、监管要求、最佳实践建议还是架构推断。
- 图标题、图例、层级、节点和说明尽量中英文对照。
- 保持图形可读；过密图形应拆成多页或多张图。
---

## 7. Multi-Cloud Strategy Logic / 多云策略逻辑

### 7.1 Placement Principles / 部署原则

| Workload Type | Recommended Placement |
|---|---|
| Access, API, authentication | Multi-cloud active-active |
| Fraud scoring and risk API | Multi-cloud active-active or active-standby |
| Core transaction routing | Primary cloud + hot standby |
| Authorization state | Strong consistency first, multi-cloud carefully |
| Clearing and settlement | Single-primary + DR |
| Ledger and reconciliation | Single-primary + disaster recovery |
| Token vault and key systems | Centralized control + secure DR |
| Data lake and analytics | Multi-cloud or cloud-optimized |
| Regulatory legacy systems | On-prem or controlled private environment |

### 7.2 Customer Discussion Message / 客户讨论口径

Do not position multi-cloud as “deploy everything everywhere”.

不要把多云定义为“所有系统到处部署”。

Recommended message:

> Multi-cloud should be applied selectively. Access, authentication, API, security, risk, and data analytics workloads are good candidates for active-active or active-standby deployment. Core transaction state, settlement, ledger, token vault, and key management should prioritize consistency, auditability, and controlled recovery over full active-active deployment.

中文口径：

> 多云不应理解为所有系统全部双云双活，而应按业务流程和数据一致性要求分层设计。接入、认证、API、安全、风控和数据分析类工作负载适合主动多云；核心交易状态、清结算、总账、Token Vault 和密钥管理应优先保证一致性、可审计和受控恢复，而不是简单双云双写。

---

## 8. Slide Style Requirements / PPT 风格要求

Use:
- Consulting-style layout / 咨询公司风格
- Executive-readable visuals / CXO 可读
- Editable shapes / 图形可编辑
- Bilingual Chinese-English labels by default / 默认中英文对照
- Clear separation of facts vs assumptions / 区分事实与推断
- Enterprise line icons / 企业线性图标风格
- Layered architecture diagrams / 分层架构图
- Matrix and heatmap for suitability / 使用矩阵和热力图表达适配性

Avoid:
- Overcrowded diagrams / 图形过密
- Unverified vendor claims / 未验证厂商信息
- Mixing partner systems with customer systems / 混淆伙伴系统与客户系统
- Treating inferred deployment as official fact / 把推断架构当作官方事实

---

## 9. Quality Checklist / 质量检查清单

Before final output, verify:

- [ ] Have official sources been prioritized?
- [ ] Are facts, assumptions, recommendations, and disclosure gaps clearly separated?
- [ ] Are acronyms and key role names explained in both Chinese and English?
- [ ] Is the customer's role in the ecosystem correctly stated?
- [ ] Are served objects, direct customers, end users, partners, regulators, and ecosystem participants separated?
- [ ] Are investors and ownership facts separated from undisclosed ownership gaps?
- [ ] Is business history connected to strategic path and future goals?
- [ ] Are major customer examples sourced and labeled as examples rather than full customer lists?
- [ ] Does Market Insight include industry panorama, value chain, market structure, demand drivers, regulatory/ecosystem forces, opportunity thesis, product-level market space, competitors, peer benchmark, China analogues, market-sizing method, and proxy metrics?
- [ ] Are market space, competitive landscape, peer benchmark, and China analogue analysis placed under Market Insight rather than Business Insight?
- [ ] Is every major product analyzed for market space, competitors, revenue/share disclosure, and architecture implications?
- [ ] Does the peer benchmark include global/regional peers and China analogues without false equivalence?
- [ ] Are business processes classified by real-time, batch, workflow, and evidence?
- [ ] Are API and solution capabilities grouped into meaningful domains?
- [ ] Is product-by-product technical architecture clearly marked as official fact or architecture inference?
- [ ] Are cloud placement recommendations based on workload characteristics?
- [ ] Are security, compliance, continuity, and data requirements included?
- [ ] Are revenue, market share, ownership, and architecture assumptions explicitly labeled when not public?
- [ ] Are architecture diagrams and process flow diagrams included in the Word report and PPT deck?
- [ ] Does Market Insight include a market panorama/value-chain diagram and a product-market/competitor map?
- [ ] Does Business Insight include ecosystem, capability, and end-to-end process diagrams?
- [ ] Does Technology Insight include API capability, product architecture, layered architecture, deployment architecture, and workload placement visuals?
- [ ] Are diagrams editable if PPT is requested?
- [ ] Are references and evidence notes included?
- [ ] Are updated discussion questions included?
- [ ] Are both final deliverables generated by default: Word insight report (`.docx`) and PPT insight report (`.pptx`)?
- [ ] Is the insight report bilingual Chinese-English by default, unless the user explicitly requested a single language?
- [ ] Are section titles, key findings, tables, diagrams, roadmap items, and discussion questions bilingual?
- [ ] Does the six-dimension analysis explicitly state who the customer serves, who its direct customers are, and who the end users are?
---

## 10. Reusable Prompt Template / 可复用 Prompt 模板

```text
你是一个资深云战略顾问和行业解决方案架构师。请基于官方资料、监管资料、产品/API 文档、公开报告和行业最佳实践，对【客户名称】进行深度客户洞察研究。

研究目标：
1. 梳理客户定位、业务范围、核心产品、服务对象、直接客户、终端用户、生态伙伴和行业角色。
2. 解释缩略语和关键名称，尤其是监管角色、业务定位、支付体系、API、账本、风控和架构相关术语。
3. 做市场洞察：先建立行业全景、市场结构、价值链、监管与生态力量、需求驱动和机会判断，再按主要产品线分析市场空间、服务对象、主要竞争对手、收入/市场份额披露情况、市场估算方法和代理指标。
4. 在市场洞察中完成同业对比：增加竞争格局地图、全球/区域同业标杆和中国类似企业对比，但避免一对一错误类比；市场空间和同业对比不得挪到业务洞察部分。
5. 做业务洞察：分析投资人、融资轮次、股权结构、公开披露缺口、业务发展历程、战略路径、目标和主要客户举例。
6. 梳理端到端业务流程，区分实时流程、批处理流程、异步工作流和监管/证据流程。
7. 梳理客户解决方案与 API 能力，形成“XX 类解决方案 + XX 类 API”的能力全景。
8. 做技术洞察：按产品线分析技术架构，区分官方披露事实和架构推断，覆盖 API、产品编排、核心账本、支付网络、风控合规、数据平台、安全韧性和云部署。
9. 梳理技术架构、部署架构、数据架构、安全合规和业务连续性要求。
10. 判断哪些业务流程、解决方案、API 和核心模块适合多云部署，哪些只适合主备/灾备，哪些不建议多云双活。
11. 对收入、市场份额、股权比例、内部系统和云部署等未公开信息，必须写明公开资料限制，并给出代理指标或客户访谈问题。
12. 输出目标多云架构建议、工作负载部署矩阵和实施路线图。
13. 明确区分官方披露事实、监管要求、行业最佳实践和架构推断。
14. 默认生成中英文双语 Word 洞察报告（`.docx`），中文为主叙述语言，英文作为对照表达；如用户明确要求单一语言，再按用户要求调整。
15. 默认生成中英文双语 PPT 洞察报告（`.pptx`），用于客户讨论和管理层汇报；标题、图表标签、关键结论和讨论问题均需中英文对照。
16. Word 和 PPT 均必须包含架构图与流程图，不得只有文字和表格；至少包含市场全景/价值链图、产品市场/竞品图、生态图、业务能力图、端到端流程图、API 能力图、技术架构图、部署架构图、工作负载部署矩阵和路线图。

输入资料：
- 客户名称：【填写】
- 官方网站：【填写】
- 官方报告/API/规则文档：【填写】
- 监管资料：【填写】
- 已知架构线索：【填写】
- 目标讨论主题：【例如：市场洞察、业务洞察、技术洞察、多云策略、API 平台、数据平台、业务连续性】

输出要求：
- 语言：【中英文对照（默认）/ 中文 / English】
- 格式：【默认两份最终交付件：Word 洞察报告（`.docx`）+ PPT 洞察报告（`.pptx`）/ 也可按需补充 Markdown、PPT 大纲、架构图、表格】
- 内容顺序：【市场洞察（行业全景、价值链、市场空间、竞争格局、同业对比、代理指标）→ 业务洞察 → 技术洞察 → 路线图与讨论问题 → 参考资料与证据说明】
- 风格：咨询公司风格，CXO 可读，图表清晰，必须包含架构图、流程图、市场地图和矩阵；PPT 中所有图形尽量可编辑。
```
---

## 11. Example Logic from Elo Case / Elo 案例逻辑

When applying this skill to payment customers:

当应用于支付客户时：

1. Identify whether the company is a scheme, issuer, acquirer, processor, wallet, or infrastructure provider.
   首先识别客户是卡组织/支付安排、发卡方、收单方、处理机构、钱包，还是基础设施方。

2. Map payment processes:
   - Authorization / 授权
   - Pre-authorization / 预授权
   - Reversal / 冲正
   - Refund / 退款
   - Clearing / 清算
   - Settlement / 结算
   - Transfer / 转账
   - Wallet funding / 钱包充值
   - Chargeback / 拒付
   - Proof and arbitration / 证明与仲裁

3. Map solution/API capabilities:
   - Payment APIs / 支付 API
   - Risk APIs / 风控 API
   - Token APIs / Token API
   - Identity APIs / 身份 API
   - Clearing APIs / 清算 API
   - Dispute APIs / 争议 API
   - Partner APIs / 伙伴 API
   - Data APIs / 数据 API

4. Evaluate multi-cloud suitability:
   - Best for active-active: API gateway, authentication, fraud scoring, partner portal, risk APIs.
   - Suitable for active-standby: transaction routing, stand-in, token frontend.
   - Suitable for DR only: clearing, settlement, ledger, reconciliation, token vault.
   - Controlled on-prem/private zone: HSM root keys, regulatory legacy systems.

5. Produce final discussion artifacts:
   - Capability panorama
   - Process classification
   - Multi-cloud suitability matrix
   - Target deployment architecture
   - Roadmap and discussion questions

---

## 12. Output Tone / 输出口吻

Use a consulting and architecture advisory tone:

采用咨询与架构建议风格：

- Evidence-based / 基于证据
- Structured / 结构化
- Executive-readable / 管理层可读
- Technically actionable / 技术可落地
- Explicit about uncertainty / 明确不确定性
- Focused on customer discussion / 面向客户讨论
