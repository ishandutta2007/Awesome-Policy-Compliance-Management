# Awesome-Policy-Compliance-Management

## Top Policy & Compliance Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on GRC Automation, Control Attestation & Regulatory Compliance*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Policy & Compliance Management**. These tools enable organizations to map regulatory requirements to internal controls, manage policy lifecycles, automate evidence collection, and maintain continuous compliance across frameworks such as SOC 2, ISO 27001, GDPR, HIPAA, and NIS2.



**Examples** include ServiceNow Policy and Compliance Management, Hyperproof, Vanta, Drata, Sprinto, AuditBoard (now Optro), MetricStream, Archer, Workiva, LogicGate, and OneTrust (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted GRC, compliance tracking, and control attestation—ideal for organizations building sovereign compliance infrastructure without per-seat or per-framework licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Policy and Compliance Management](https://www.servicenow.com/)**  

  Enterprise GRC module within Integrated Risk Management (IRM) with a structured data model connecting authority documents (HIPAA, GDPR, PCI DSS) → citations → control objectives → controls → policies; supports policy lifecycle from draft through review, approval, publication, and retirement; control attestation via Smart Assessment Engine and continuous monitoring via Indicators that auto-create Issues on failure; Compliance Workspace provides role-aware dashboards for Corporate Compliance Managers, Analysts, and IT Compliance Managers .



- **[Hyperproof](https://hyperproof.io/)**  

  Compliance operations platform with AI Guided Experiences for Suggested Links (auto-mapping controls, policies, risks, and evidence) and Evidence Collection & Validation (AI identifies needed evidence, drafts credential requests, and validates proof before auditors see it); supports automated evidence collection via Hypersyncs and integrations with Drive, Slack, AWS, and GitHub .



- **[Vanta](https://www.vanta.com/)**  

  Trust management platform with 1,400+ automated tests and 400+ integrations for continuous compliance; supports SOC 2, ISO 27001, and custom frameworks; features IRLs (auditor request list management with control mapping and evidence review), AWS GovCloud environment for FedRAMP/CMMC/NIST, OSCAL export for FedRAMP 20x, and an AI Agent with company-specific memory for GRC queries .



- **[Drata](https://drata.com/)**  

  Continuous compliance automation platform with no-code custom workflows (auto-assign tasks, send reminders, escalate issues based on control status or evidence gaps), Evidence Library upgrades for larger files and additional types, MTTR dashboard for failed monitoring tests, and expanded framework support including TISAX, NYDFS, and ISO/IEC 27018:2025 .



- **[Sprinto](https://sprinto.com/)**  

  Compliance automation platform with Policy Drift Detection (side-by-side comparison of policy language vs. actual controls with one-click updates), Integration Agents for event-driven sync across cloud, HRMS, and SaaS tools, OnGrid integration for background verification evidence, Bulk AI Actions for processing multiple policies/risks/questionnaires at once, and unified entity detail panels across People, Access, and Infra modules .



- **[AuditBoard (now Optro)](https://www.auditboard.com/)**  

  Audit management platform supporting the full audit lifecycle from planning and risk assessment through workpaper management, issue tracking, and reporting; cloud-based SaaS with systemwide deployment options for large enterprises and public sector organizations .



- **[MetricStream](https://www.metricstream.com/)**  

  AI-powered GRC platform recognized as a Category Leader across all seven GRC categories by Chartis Research; features continuous sensing for emerging risks, AI assistants and agents for risk/compliance/audit workflows, autonomous evidence gathering, and outcome assurance for remediation validation .



- **[Archer](https://www.archerirm.com/)**  

  Enterprise GRC platform with integrated risk register, continuous compliance mapping (map once, satisfy duplicate requirements automatically), quantitative risk insights with dollar-value exposure, third-party risk governance, and audit-ready evidence with timestamped trails; serves 1,500+ customers across 48 countries including 50% of Fortune 500 .



- **[Workiva](https://www.workiva.com/)**  

  Financial compliance and SEC reporting platform unifying SEC reporting with ICFR (internal controls over financial reporting) and SOX compliance; provides a single source of truth with data traceability, secure global collaboration with advanced permissions, and streamlined audit interactions with as-needed auditor access .



- **[LogicGate](https://www.logicgate.ai/)**  

  AI GRC platform with GRC Agents now generally available for TPRM, ERM, AI Governance, and Business Continuity Management; features Automated Control Testing (tests linked evidence records automatically with detailed rationale), Bulk Record Linking for hundreds of records at once, GRC Lifecycle Management for safe production-to-development syncing, and upcoming MCP Server Access for natural language Risk Cloud queries .



- **[OneTrust](https://www.onetrust.com/)**  

  GRC platform named a Leader in the IDC MarketScape for Worldwide GRC Software 2025; unifies privacy, AI governance, risk management, and third-party monitoring; features automated privacy/risk/compliance processes, AI-powered data governance, no-code workflow automation, and third-party monitoring with integrated regulatory intelligence; trusted by 14,000+ global brands .



## Open-Source GitHub Projects



- **[Cairn](https://github.com/frousselet/cairn)**  

  Self-hosted GRC platform (single container with Docker Compose) covering governance (ISO 27001 clause 4 context), assets with CIA valuation and dependency mapping, risks (ISO 27005 and EBIOS RM with three-level register and treatment plans), compliance (frameworks, audits, nonconformity register, inter-framework mappings), incidents with sealed evidence and statutory notification clocks, Trust Center public page, and steering dashboards with PDF/DOCX/PPTX/XLSX reports; every feature is API-accessible via REST and built-in MCP server; optional AI (off by default) supports Mistral, OpenAI, Claude, or local Ollama .



### Additional Strong Open-Source Options



- **GitHub `grc` topic** — Community projects covering policy management, risk registers, and compliance tracking; quality and maintenance vary widely.

- **OpenGRC** — Community-driven GRC initiatives that can be adapted for policy and compliance workflows.

- **Compliance-as-code scripts** — Custom pipelines combining infrastructure scanning (e.g., OpenSCAP, Prowler) with policy-as-code engines (OPA/Rego) for automated control evidence generation.



**Frameworks for building custom systems**: Deploy **Cairn** as the core GRC platform for policy management, risk assessment, and compliance tracking with audit-ready evidence trails; extend with API integrations to cloud providers and HR systems for automated evidence collection; layer policy-as-code tools (OPA/Rego) for infrastructure compliance verification in a fully self-hosted policy and compliance management stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Policy and compliance platforms handling audit evidence and regulatory data must comply with applicable regulations and organizational data governance policies; evidence integrity and chain of custody are critical for audit defensibility.

- Self-hosted open-source solutions for GRC are limited in scope compared to commercial platforms—Cairn provides a strong foundation but may require customization for framework-specific control mappings and auditor collaboration workflows.

- Verify license terms for commercial use; Cairn is free software under an open-source license as stated in its repository.



---



**Made for compliance officers, GRC analysts, internal auditors, and risk managers.**  

Let's make policy and compliance management more open, auditable, and continuous.
