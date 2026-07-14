# Payment and Regulated Industry Playbook / 支付与强监管行业分析手册

Use this playbook for customers in payments, banking, fintech, cards, acquiring, wallets, open finance, account infrastructure, transaction processing, fraud/risk, clearing, settlement, or other regulated transaction networks.

## Role Taxonomy / 角色分类

Do not merge ecosystem roles. Identify each participant separately:

- Regulator or supervisor / 监管机构.
- Scheme or arrangement owner / 支付方案或规则组织.
- Payment system operator / 支付系统运营方.
- Financial institution or payment institution / 金融机构或支付机构.
- Issuer or account provider / 发卡方或账户提供方.
- Acquirer or merchant service provider / 收单机构或商户服务方.
- Processor or infrastructure provider / 处理商或基础设施提供方.
- PSP or payment service provider / 支付服务提供商.
- Payment initiation service provider / 支付发起服务提供商.
- Data provider, data receiver, or consent manager / 数据提供方、接收方或授权管理方.
- Merchant, platform, marketplace, wallet, enterprise, and end user / 商户、平台、钱包、企业与最终用户.

For each role, answer who owns the customer relationship, initiates the transaction, authorizes, routes, executes, settles, bears risk, reports to the regulator, and keeps evidence.

## Regulatory Analysis / 监管分析

Collect licensing scope, regulatory authority, official rules, operating manuals, technical standards, API standards, certification rules, participant obligations, incident reporting obligations, and requirements for availability, latency, reliability, transaction integrity, data consistency, audit logs, customer consent, privacy, security, fraud controls, disputes, clearing, settlement, and business continuity.

Keep legal requirements separate from industry best practices and architecture inference.

## Process Analysis / 流程分析

Map process flows with swimlanes. Typical payment processes include onboarding/KYC, payment initiation, authorization, real-time execution, confirmation, card authorization, reversal, refund, clearing, settlement, chargeback, merchant onboarding, acquiring, reconciliation, fraud screening, risk scoring, reporting, audit evidence, incident management, and regulatory communication.

For each step identify actor, trigger, input/output, API/message, system of record, real-time requirement, consistency requirement, failure mode, retry/idempotency requirement, and evidence/audit record.

## API Deep Dive / API 深入洞察

Classify APIs into identity/KYC/authentication, account/ledger, payment initiation/execution, card issuing/tokenization/lifecycle, acquiring/merchant/POS/e-commerce, open finance consent/data/payment initiation, fraud/risk/AML, reporting/analytics/audit, developer portal/sandbox/certification/status.

Where public documentation allows, record API groups and endpoint count. If unavailable, use proxy metrics such as API categories, public repositories, standards coverage, sandbox presence, documentation depth, and version history.

## Reliability and Consistency / 可靠性与一致性

Real-time initiation and confirmation require low latency, high availability, idempotency, backpressure handling, and precise monitoring. Ledger, settlement, reconciliation, and dispute processes require auditability, transactional integrity, immutable evidence, and explainable correction flows. Consent and open finance APIs require secure authentication, authorization, revocation, data minimization, traceability, and version control.

## Cloud and Workload Placement / 云与工作负载放置

Do not position multi-cloud as deploying everything everywhere. Use workload characteristics:

- Active-active: access gateway, API gateway, authentication front end, risk scoring, fraud screening, notification, read-heavy channels.
- Active-standby: transaction routing, token front end, payment initiation orchestration, partner gateway, stand-in authorization.
- Primary plus DR: clearing, settlement, reconciliation, ledger, consent record, dispute case management, regulatory evidence stores.
- Controlled/private: HSM root keys, regulated legacy cores, sensitive key custody, jurisdiction-constrained systems.

For each workload define business criticality, RTO/RPO, latency, consistency model, data residency, regulatory evidence, and recommended deployment pattern.

## Brazil Payment and Open Finance Lens / 巴西支付与开放金融视角

For Brazil payment customers, examine central bank/regulator role, payment arrangements, payment institutions, payment system rules, Pix participant roles and flows, Open Finance consent/API/security/certification model, card schemes, issuing, acquiring, processing, authorization, clearing, settlement, tokenization, chargeback, PSP, payment initiation, scheme, infrastructure, merchant, platform, and end user roles.

Use official regulator and scheme documents as primary evidence. State a named company's role only when evidence confirms it; otherwise label it as inferred or to be validated.