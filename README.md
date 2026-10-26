# Awesome-Software-Asset-Management-Sam

# Top Software Asset Management (SAM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Software License Optimization, SaaS Spend Management & IT Asset Intelligence*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Software Asset Management (SAM)**. These tools enable organizations to discover software installations, reconcile licenses against entitlements, optimize SaaS subscriptions, and maintain compliance with publisher contracts—turning software spend from a cost center into a governed, optimized asset.

**Examples** include ServiceNow Software Asset Management, Flexera One, Snow Software, Ivanti Neurons for SAM, Lansweeper, Zylo, Productiv, LeanIX, USU Software Asset Management, and Torii (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted IT asset management, license tracking, and CMDB-linked inventory—ideal for organizations building sovereign SAM infrastructure without per-asset or per-seat licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Software Asset Management](https://www.servicenow.com/)**  
  Enterprise SAM platform on the Now Platform with publisher compliance summarization via Now Assist, guided setup for new products, SAP S/4HANA Cloud support, Microsoft 365 optimization (auto-removal of low-usage licenses), CrowdStrike compliance enhancements, and SAP Ariba integration for subscription visibility .

- **[Flexera One](https://www.flexera.com/)**  
  Hybrid ITAM and FinOps platform with IBM-certified and Oracle-verified license data, SKU Browser, Kubernetes/OpenShift inventory, SAM Publisher Hub, and deep ServiceNow integration; manages software, SaaS, and cloud spend in one solution .

- **[Snow Software](https://www.snowsoftware.com/)**  
  Integrated SAM platform with Snow License Manager for on-premise and cloud license optimization, Snow for Cloud for IaaS/SaaS management, automated discovery across all locations, and vendor audit defense .

- **[Ivanti Neurons for SAM](https://www.ivanti.com/)**  
  Unified asset intelligence platform with automated discovery (active, passive, and third-party connectors), software inventory with usage insights, lifecycle tracking from procurement to retirement, and workflow automation for onboarding/offboarding .

- **[Lansweeper](https://www.lansweeper.com/)**  
  IT asset discovery platform covering IT, IoT, OT, and cloud assets; provides unified inventory, risk insights via NIST catalog, lifecycle tracking, and API integrations for ITSM and SAM workflows .

- **[Zylo](https://zylo.com/)**  
  Enterprise SaaS Management platform with AI Smart Filters (natural language reporting), Contract Assist Agent for extracting contract metadata from order forms, AI Controls for governance, and a roadmap toward agentic SaaS management .

- **[Productiv](https://productiv.com/)**  
  SaaS Management Platform with AI-powered insights for portfolio optimization, App Procurement Hub for renewal management, shadow IT discovery, and automated workflows from purchase to renewal .

- **[LeanIX (SAP LeanIX)](https://www.leanix.com/)**  
  Enterprise Architecture management platform with software asset inventory capabilities via ServiceNow/CMDB integration, manual entry, Excel import, and surveys; focused on technology risk and obsolescence management .

- **[USU Software Asset Management](https://www.usu.com/)**  
  Use-case driven ITAM platform with SAM for SaaS (spend visibility, right-sizing), SAM for SAP (S/4HANA migration strategy), SAM for Clients & Datacenter (90%+ automated product recognition), and Hardware Asset Management .

- **[Torii](https://www.toriihq.com/)**  
  SaaS Management Platform named a Leader in the 2026 Gartner Magic Quadrant; features continuous app discovery including browser extension for shadow apps, license right-sizing on real usage, automated onboarding/offboarding workflows, and AI tool cost tracking .

## Open-Source GitHub Projects

- **[Snipe-IT](https://github.com/snipe/snipe-it)**  
  Leading open-source IT asset/license management system (PHP/Laravel, ~9,700 GitHub stars); tracks hardware and software licenses, manages checkouts and depreciation, supports LDAP/SAML authentication, and includes a REST API; Docker-deployable and widely adopted by schools, nonprofits, and enterprises for license tracking .

- **[GLPI](https://github.com/glpi-project/glpi)**  
  Free asset and IT management software package (GPL-3.0) with licenses tracking, software auditing, data center management, and ITIL service desk; includes inventory agent for automated discovery, CMDB capabilities, and plugin ecosystem for SAM workflows .

- **[Shelf](https://github.com/Shelf-nu/shelf.nu)**  
  Open-source asset management infrastructure (TypeScript, ~1,500 GitHub stars) designed as a modern, self-hosted alternative to spreadsheets; features QR/barcode tagging, asset custody tracking, and a clean web UI; suitable for organizations wanting lightweight asset tracking without enterprise complexity .

### Additional Strong Open-Source Options

- **openstamanager** — Italian open-source management software for technical assistance and invoicing; includes asset tracking suitable for IT service providers managing client software assets .
- **Felicity** — Open-source integrated platform converging service management, operations management, and asset management with an internal workflow engine covering ITIL processes .
- **Community SAM scripts** — Custom reconciliation pipelines combining GLPI or Snipe-IT with publisher entitlement data for basic license compliance reporting.

**Frameworks for building custom systems**: Combine **Snipe-IT** for license and asset tracking with a clean UI, **GLPI** for ITIL-aligned service management with inventory agent, and **Shelf** for lightweight custody tracking in a self-hosted SAM foundation; integrate with spreadsheet-based entitlement reconciliation scripts for publisher-specific compliance workflows.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- SAM platforms handling software inventory and contract data must comply with applicable regulations and publisher licensing terms; inaccurate reconciliation can create audit risk.
- Self-hosted open-source solutions provide foundational asset/license tracking but typically lack publisher-specific licensing rules (Oracle, SAP, Microsoft) and automated entitlement reconciliation found in commercial SAM suites.
- Verify license terms for commercial use; Snipe-IT uses AGPL-3.0, GLPI uses GPL-3.0, and Shelf uses AGPL-3.0.

---

**Made for IT asset managers, SAM analysts, procurement teams, and FinOps practitioners.**  
Let's make software asset management more open, transparent, and audit-ready.
