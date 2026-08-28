# Awesome-Lead-Routing

## Top Lead Routing Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Lead-to-Account Matching, Round-Robin Distribution, Territory Routing, Speed-to-Lead & Meeting Scheduling*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Lead Routing**. These systems assign inbound and outbound leads to the right sales reps based on territory, capacity, account ownership, and rules — often with instant scheduling.

**Examples** include LeanData, Chili Piper, Distribution Engine, Openprise, Gradient Works, Fullcast, Tray.io Routing, MadKudu, RevenueHero, and Calendly Routing (the category leaders).

**Open-source emphasis**: Dedicated open-source lead-routing products are rare. Useful building blocks exist in **CRM-native automation** (Salesforce Flow, HubSpot workflows), **n8n / open workflow engines**, and custom round-robin services. This section lists the most relevant options while acknowledging commercial dominance of the category.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[LeanData](https://www.leandata.com/)**  
  Leading Salesforce-native GTM orchestration and routing platform — visual flows, lead-to-account matching, territory logic, and complex assignment rules.

- **[Chili Piper](https://www.chilipiper.com/)**  
  Inbound routing and instant meeting scheduling — form-to-calendar concierge and Distro for CRM-level lead distribution.

- **[Distribution Engine](https://www.ncsquared.com/)**  
  Salesforce lead and record distribution with fairness, capacity, and multiple distribution methods for sales teams.

- **[Openprise](https://www.openprise.com/)**  
  Data orchestration and GTM automation platform that includes routing and enrichment workflows across systems.

- **[Gradient Works](https://www.gradient.works/)**  
  Salesforce-native routing and assignment built on Flow — matching, capacity, and territory logic without a separate routing product.

- **[Fullcast](https://www.fullcast.com/)**  
  Revenue planning and GTM platform with territory and capacity-aware routing components.

- **[Tray.io (routing / automation)](https://tray.ai/)**  
  General automation platform frequently used to implement custom lead routing and enrichment across CRMs and tools.

- **[MadKudu](https://www.madkudu.com/)**  
  Predictive lead scoring and routing signals that help prioritize and assign the highest-fit leads.

- **[RevenueHero](https://www.revenuehero.io/)**  
  Routing plus instant scheduling for inbound leads, positioned as a competitive alternative for mid-market teams.

- **[Calendly Routing](https://calendly.com/)**  
  Scheduling platform with routing forms and assignment logic that connects inbound interest to the right calendar.

## Open-Source GitHub Projects
- **[n8n and open workflow engines](https://github.com/n8n-io/n8n)**  
  Self-hosted automation that can implement lead enrichment, deduplication, and round-robin or rule-based assignment across CRM APIs.

- **[Salesforce Flow / HubSpot workflow patterns (documented)](https://github.com/)**  
  Community examples and templates for native CRM assignment rules, queues, and simple territory logic without extra vendors.

- **[Custom round-robin lead routers](https://github.com/)**  
  Small open services that distribute leads across reps or CRM orgs with atomic assignment and duplicate checks.

- **[Mautic](https://github.com/mautic/mautic)**  
  Open-source marketing automation with lead management and basic assignment capabilities (not a full enterprise router).

- **[Odoo CRM and open CRM assignment](https://github.com/odoo/odoo)**  
  Open CRM modules that support rule-based lead assignment for teams already on Odoo.

- **[Lead scoring open models](https://github.com/)**  
  Simple scoring scripts and notebooks that feed priority into routing rules.

- **[Webhook-based form-to-CRM open pipelines](https://github.com/)**  
  Lightweight open handlers that receive form posts, enrich, and assign via CRM APIs.

- **[Territory and capacity open data models](https://github.com/)**  
  Schemas and examples for representing territories and rep capacity that custom routers can consume.

- **[Audit-log and fairness open checkers](https://github.com/)**  
  Scripts that analyze assignment history for load balance and SLA compliance.

- **[Integration platform open alternatives](https://github.com/)**  
  Self-hosted iPaaS-style tools used to glue forms, enrichment, and CRM assignment together.

### Additional Strong Open-Source Options
- Implementing simple round-robin and queue-based assignment entirely in Salesforce Flow or HubSpot workflows when logic is not complex.
- Using **n8n** (or similar) for cross-system routing when you need more than native CRM rules.
- Building a thin custom service for multi-org or multi-CRM distribution when commercial tools don’t fit.
- Combining open enrichment (Clearbit-style alternatives or internal data) with open assignment logic.
- Logging every assignment decision for fairness and compliance review.
- Preferring native CRM automation for small teams before buying a dedicated routing product.

**Frameworks for building custom systems**: Start with **CRM-native flows** for simple rules; add **n8n** or a small custom service for enrichment + round-robin; keep an assignment audit log. For complex lead-to-account matching, multi-object orchestration, and enterprise Salesforce territory models, commercial platforms (LeanData, Chili Piper, Distribution Engine, Gradient Works, RevenueHero, etc.) remain the practical choice. Open tools excel at simple internal assignment and custom glue, not at replacing mature routing products.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Lead routing affects revenue and rep compensation. Incorrect rules cause missed SLAs, double-assignment, and trust issues. Test thoroughly in sandbox, monitor fairness metrics, and document ownership of routing logic. Open or custom routers must handle concurrency and failures safely.
- This list is not sales-operations advice.

---
**Made for RevOps, sales ops, and GTM engineers who get the right lead to the right rep fast.**
Let's keep routing logic transparent, fair, and under operational control.
