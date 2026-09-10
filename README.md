# MBA / PGPM Portfolio

Academic project portfolio from my PGPM (Post Graduate Program in Management) at Great Lakes Institute of Management, spanning Terms 1–7. This repository curates coursework and independent case studies into a form useful to both academic reviewers and recruiters — it is **not** a raw dump of every file submitted, and it does not present coursework as professional client engagements.

## How to read this repository

Projects are organized by **domain** (Analytics, Finance, Marketing, Strategy & Consulting, Economics, Operations & Supply Chain, Project Management, and Org Behavior & Design Thinking) under `projects/`, so a visitor can quickly see what I studied and demonstrated in a given area regardless of which term it came from.

Full academic traceability — every subject, its term, its professor, and where (or whether) a project exists for it — is preserved separately in [`docs/academic-index.md`](docs/academic-index.md), including subjects for which no project was located and two known metadata discrepancies between the subject workbook and the actual coursework (flagged there, not silently corrected).

## Domain map

| Domain | What's here |
|---|---|
| **Analytics** | End-to-end analytics capstone, LP optimization, BI/fraud analysis, retail analytics, big-data/cloud strategy, applied statistics |
| **Finance** | Corporate finance valuations (CAPM/WACC), financial modelling, financial risk analytics, managerial accounting (CVP) |
| **Marketing** | Product positioning, GTM strategy, qualitative consumer research, AR/consumer-tech experimental research |
| **Strategy & Consulting** | Individual strategic case analysis; pointers to two Independent Case Studies hosted in `Consulting-Projects` |
| **Economics** | Applied microeconomics (pricing/demand) from a real campus micro-business |
| **Operations & Supply Chain** | JIT analysis, ERP/CRM systems design, an applied AI agent for trade-document compliance |
| **Project Management** | PM execution planning for two real-world-styled launch scenarios |
| **Org Behavior & Design Thinking** | Organizational-communication case analysis, end-to-end Design Thinking process |

## Featured projects

- **[Advanced Business Analytics Capstone](projects/analytics/advanced-business-analytics-capstone/)** — a full 7-notebook pipeline (EDA → clustering → regression → classification → executive insights) on a customer-churn dataset, with a generator script and an executive deck. The most technically complete project in this repository.
- **[Trade Document Automation Agent](projects/operations-supply-chain/trade-document-automation-agent/)** — a hybrid rule-based + LLM agent concept for supply-chain compliance; the clearest bridge between this academic portfolio and my [Agentic AI work](#relationship-to-my-other-repositories).
- **[Healthcare Lakehouse Strategy](projects/analytics/healthcare-lakehouse-strategy/)** — combines a real Databricks Lakehouse architecture and live demo with strategic ROI framing.
- **[Agilus Diagnostics — Profit Sensitivity & Operating Leverage](projects/finance/agilus-diagnostics-profit-sensitivity/)** — an individually authored, quantitatively rigorous CVP analysis.
- **IndiGo Market Leadership CIS** and **Business Economics (BE-2) CIS series** — two individually authored Independent Case Studies, both hosted in my `Consulting-Projects` repository rather than duplicated here; see [Relationship to Consulting-Projects](#relationship-to-consulting-projects) below.

## Individual vs. group work

Project types are labeled explicitly in each project's README and in `docs/academic-index.md`. A few projects are individually authored assignments or Independent Case Studies (clearly marked "Individual"); most are group coursework. Where group authorship could not be fully confirmed from the available material, that is stated rather than assumed. Group work is never presented as individual work.

## Privacy & sourcing note

Classmates' names and roll numbers have been removed from every migrated group-project file in this repository (replaced with a "Group Project — N members" line where a roster previously appeared); redaction was applied only to these public copies, never to the original source files. One deliverable containing personal, first-person workplace reflections from multiple named classmates was excluded from this repository entirely rather than redacted (see `docs/academic-index.md`). Third-party teaching-case narrative text has not been reproduced — see the note in the org-behavior-design-thinking case-analysis project. Three plagiarism/similarity-check screenshots found in the source material were excluded outright.

## Relationship to my other repositories

This repository documents business and management thinking — the complement to, not a duplicate of, my technical portfolio:

- **Gen AI & Agentic AI** — the Trade Document Automation Agent (above) is the direct bridge: an applied AI agent built for a genuine supply-chain business problem.
- **Predictive Analytics / Descriptive Analytics** — the Advanced Business Analytics Capstone and several other Analytics-domain projects here demonstrate the same statistical/ML skill set applied to business questions. One possible additional overlap (an ML-1 coursework notebook that may live in `Predictive-Analytics` rather than here) was investigated but not confirmed — see `docs/academic-index.md` for details.
- **Celonis / Process Intelligence** — this repository's ERP/CRM and operations projects sit conceptually alongside that process-intelligence work, without duplicating it.

### Relationship to Consulting-Projects

Two of my strongest Independent Case Studies — the IndiGo market-leadership analysis and the Business Economics (BE-2) case series — are hosted in a dedicated `Consulting-Projects` repository rather than duplicated here, to avoid publishing the same deliverable twice across my portfolio. This repository includes only short pointer files for both, with full academic metadata preserved in `docs/academic-index.md`.

## Repository structure

```
MBA-PGPM-Portfolio/
├── README.md
├── docs/
│   └── academic-index.md
└── projects/
    ├── analytics/
    ├── finance/
    ├── marketing/
    ├── strategy-consulting/
    ├── economics/
    ├── operations-supply-chain/
    ├── project-management/
    └── org-behavior-design-thinking/
```

## Program context

PGPM (Post Graduate Program in Management), Great Lakes Institute of Management. Coursework spans Terms 1 through 7 across Economics, Marketing, Operations, Finance, Analytics, Strategy, and Organizational Behavior.
