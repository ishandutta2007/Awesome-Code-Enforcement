# Awesome-Code-Enforcement

## Top Code Enforcement Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Municipal Code Compliance, Violation Tracking, Case Management & Field Inspections*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Code Enforcement**. These tools help local governments, municipalities, and regulatory agencies manage complaints, track violations, conduct field inspections, and enforce compliance with building codes, zoning ordinances, and property maintenance standards.



**Examples** include OpenGov Code Enforcement, Accela Code Enforcement, Tyler EnerGov, CityView, CentralSquare, SmartGov, CivicPlus, CityWorks, Clariti, and CityReporter (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom case workflows, and transparent municipal data — ideal for local governments that need full control over their code enforcement operations without per-case SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[OpenGov Code Enforcement](https://opengov.com/products/permitting-and-licensing/building-permit-software/)**

  Cloud-based code enforcement software integrated into OpenGov's Public Service Platform. Centralizes complaints, violations, and inspections in a mobile-friendly platform . Features configurable workflows with drag-and-drop tools and conditional logic, mobile inspections with offline access, and direct applicant-to-staff communication . Used by 2,000+ governments with 65% faster review times and 70%+ applications moved online .



- **[Accela Code Enforcement](https://www.accela.com/)**

  Comprehensive code enforcement management platform for public sector. Provides complaint tracking, violation processing, field inspections, and integrated billing/payment modules engineered for public sector fee administration . Fresno County selected Accela in 2026 for a 5-year, $513,025 agreement after receiving 15 responsive proposals, citing mobile capabilities for field officers, automated billing, real-time KPI dashboards, and AI-driven capabilities .



- **[Tyler EnerGov](https://www.tylertech.com/)**

  Integrated community development suite including code enforcement, planning, building, and public works. Features **iG Enforce** and **iG Inspect** mobile apps for field officers . Lake Forest, California increased online inspection requests by 40%+ through EnerGov's Citizen Access Portal and reported 20%+ year-over-year permit activity increase with minimal staff additions .



- **[CivicPlus](https://www.civicplus.com/)**

  Civic Experience Platform with Municode codification, online code hosting, and integration with ViewPro Zoning and SeeClickFix for code enforcement complaint intake and management .



- **[CityView](https://www.cityviewsoftware.com/)**

  Permitting, licensing, and code enforcement software for local governments. Provides case management, inspections, and citizen portals.



- **[CentralSquare](https://www.centralsquare.com/)**

  Public sector software platform with code enforcement modules integrated into broader community development and public safety solutions.



- **[SmartGov](https://www.smartgov.com/)**

  Government permitting and code enforcement platform. Provides online application submission, case tracking, and inspection scheduling.



- **[CityWorks](https://www.cityworks.com/)**

  GIS-centric asset management and permitting platform. Includes code enforcement case management and field inspection capabilities.



- **[Clariti](https://www.clariti.app/)**

  Community development and permitting platform with code enforcement case management, citizen self-service, and mobile field tools.



- **[CityReporter](https://www.cityreporter.com/)**

  Code enforcement and inspections software for municipalities. Provides complaint intake, case tracking, and field inspection workflows.



## Open-Source GitHub Projects



### Citizen Reporting & Complaint Intake



- **[FixMyStreet Platform](https://github.com/mysociety/fixmystreet)**

  **The most established open-source platform for citizens to report local problems.** Free, open-source software platform designed to empower websites that want people to report problems in their local area . In the UK, FixMyStreet.com has sent **over 200,000 reports to over 400 local governments** . Posts are publicly viewable, where users can leave updates and set up alerts . Developed by mySociety, written in Perl using the Catalyst framework, with MySQL database . Features **Open311 client** capability, allowing any Open311-compliant back-end to be used with little or no modification . The open nature and GitHub availability make it relatively easy for competent developers to add or customise any parts to their own requirements . Direct competitors include PublicStuff and SeeClickFix .



- **[Open311 on Joget](https://github.com/codeforamerica/open311-on-joget)**

  Implementation of an **Open311 backend using the Joget workflow system** . Requires Joget V3 and MySQL. Provides a Joget application for **Open311 Request Form** (citizens create requests that enter the database), **Open311 Data List** (view all requests), and **open311data.jsp** (displays Open311 requests in XML specification for Open311 Dashboard) . Includes sample 311 requests file. **Open source**.



### Additional Strong Open-Source Options



- **Citizen Reporting**: **FixMyStreet Platform** (200,000+ reports to 400+ governments, Open311-compliant) .

- **Open311 Backend**: **Open311 on Joget** (Joget workflow system, MySQL) .

- **Open311 Standards**: **Open311 GeoReport v2** specification (open standard for service requests, used by FixMyStreet and many municipal 311 systems) .



**Frameworks for building custom systems**: **FixMyStreet Platform** serves as the primary open-source foundation for citizen-facing code complaint intake, with Open311 API compatibility enabling integration with municipal back-end systems . Add **Joget** or custom workflows for case management, **PostgreSQL/MySQL** for persistence, and **GIS/mapping** (OpenStreetMap or ESRI ArcGIS) for spatial case visualization.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Code enforcement platforms handle sensitive municipal data; ensure compliance with local government regulations and public records requirements.

- **Open-source reality**: The open-source ecosystem for code enforcement is **limited**. **FixMyStreet** provides a mature, production-proven platform for **citizen complaint intake** with Open311 compatibility, deployed at scale in the UK . However, **full code enforcement case management** — violation processing, field inspections, officer assignment, penalty calculation, and compliance tracking — is not covered by open-source alternatives. Municipalities typically use **FixMyStreet for public reporting** and pair it with internal case management systems (often commercial, like Accela or EnerGov) or build custom workflows on platforms like **Joget** . Commercial platforms (OpenGov, Accela, Tyler EnerGov) remain the primary choice for comprehensive code enforcement operations.
