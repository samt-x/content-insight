---
id: 66e10fc5-050e-49ac-a195-fe6459699649
title: Simpl-Open
weight: 10
lastmod: 2026-11-19T21:41:03+01:00
last_editor: Erik Hagen

---
*Simpl-Open is the software in Simpl: open source with modular components that a data space can use to let participants find each other, agree on terms and share data in a controlled way.*

---

### What Simpl-Open does

Simpl-Open covers the whole flow in a data space. First, a catalogue with schemas and vocabularies is set up, and participants are onboarded. Participants can then publish and discover resources (data, infrastructure or software packages), enter into agreements and get access to the resources they have agreed on ([Ana Juan Ferrer (European Commission), March 2026](https://coe-dsc.nl/wp-content/uploads/2026/04/Ana-Ferer-180326_Simpl_DataSharingFestival.pdf)).

The architecture is built around three types of *agents*, one for each role in a data space: the authority that governs the data space (governance authority), the data provider and the data consumer. Each participant runs its own agent. The functionality is organised in a capability map with six dimensions: Administration, Data, Integration, Infrastructure, Governance and Security ([the architecture repository](https://code.europa.eu/simpl/simpl-open/foundations/architecture)).

Simpl-Open builds on established standards and projects: Gaia-X/XFSC, the Eclipse Dataspace Connector (EDC), the Dataspace Protocol (DSP), ODRL for usage terms and RDF for metadata. Support for DCAT-AP is planned. Identity and trust are based on verifiable credentials. The architecture decisions (ADRs) include, among other things, an OID4VP verifier and contracting by exchanging verifiable credentials between the parties.

The software is licensed under EUPL 1.2. It can be used as one complete solution, or you can pick individual components and build on them.

---

### Releases and status

Simpl-Open is released in versions named after European cities, roughly one per quarter:

| Release | Content (main features) | Status |
|---|---|---|
| Gdynia (4.0) | Resource and vocabulary management, access control, provisioning, observability, data processing | Released 6 July 2026 (the installation guide was tagged v4.0.0 on 7 July 2026) |
| Hamburg (4.1) | Federation, credential management, resource discovery, data governance, application and data sharing, notifications | Planned for the second half of October 2026. The installation guide was tagged v4.1.0 on 5 November 2026, so Hamburg was probably released slightly late. The programme has not announced it |
| Innsbruck (5.0) | Advanced governance (audit, participants, policies, contracts, consent), contract enforcement, HPC | Planned, originally for Q4 2026 |

Sources: [development status](https://simpl-programme.ec.europa.eu/documentation/development-status), [Coffee with Simpl 3, July 2026](https://simpl-programme.ec.europa.eu/news/coffee-simpl-3rd-session-recap), [installation guide](https://code.europa.eu/simpl/simpl-open/cross-cutting/documentation/installation-guide). The roadmap itself states that it is indicative and subject to change.

#### Building blocks by release

The roadmap organises the building blocks by the six dimensions of the capability map. On the [development status](https://simpl-programme.ec.europa.eu/documentation/development-status) page it is also shown as a timeline over Q2–Q4 2026, with one colour per dimension. The colours show the dimension, not the status. Gdynia has 10 items, Hamburg 12 and Innsbruck 27. The table shows what each release contains.

| Dimension | Gdynia (4.0), released July 2026 | Hamburg (4.1), released November 2026 | Innsbruck (5.0), planned Q4 2026 |
|---|---|---|---|
| Administration | Monitoring of business events; personal landing page | Monitoring of the agents; support services and helpdesk; quality of service and alerts | Monitoring of data and application consumption; dashboards and reporting; monitoring of the infrastructure |
| Data | Data orchestration; analytics and visualisation; schema management; vocabulary management | Data governance: lineage and data quality | Data streaming; assessment of metadata quality |
| Governance | Resource descriptions in the catalogue (XFSC) | – | Audit; billing; consent at onboarding; contract establishment and management; policies in schemas; dashboard for the governance authority; contract clauses in resource descriptions; participants audit |
| Integration | Bulk data transfer | Consumption of applications and AI models; publishing and searching for applications in the catalogue | Consumption across data spaces; contract enforcement; distributed processing; federated catalogue search across data spaces |
| Infrastructure | Infrastructure catalogue services (scripts and templates) | Application deployment; federation between data spaces (Tier 2) | Cloud and edge; energy consumption; HPC; integration with platform services (PaaS) |
| Security | Integration with an external identity provider | Consent for datasets with personal data; VPN; self-sovereign identity with a digital wallet (SSI Tier 1) | Incident response (CSIRT); DCAT-AP; VPN; self-sovereign identity (SSI Tier 2) |

Sources: the roadmap for [Gdynia](https://simpl-programme.ec.europa.eu/development/development-status/simpl-open-roadmap-items-gdynia-4.0), [Hamburg](https://simpl-programme.ec.europa.eu/development/development-status/simpl-open-roadmap-items-hamburg-4.1) and [Innsbruck](https://simpl-programme.ec.europa.eu/development/development-status/simpl-open-roadmap-items-innsbruck-5.0), published January 2026 and read on 18 November 2026. The roadmap does not show the status of each item. A release being out therefore does not necessarily mean that every item in it has been fully delivered. Functionality from earlier releases (MVP to 3.x), such as onboarding of participants and conclusion of usage agreements, is not included in the table.

The closest we have found to a status along the way is what the programme presented at Coffee with Simpl on 1 October 2026: work on application publishing and discovery, monitoring, security, application deployment, support services, federation configuration and consent. All of these are Hamburg items, which were therefore in progress at the time ([Coffee with Simpl 4](https://simpl-programme.ec.europa.eu/news/coffee-simpl-4th-edition-recap)).

Alongside the releases, three extensions are being developed (Simpl-Open Extensions): AI/ML with a link to EuroHPC's federation platform, catalogue integration with the DOME marketplace, and monetisation for the governance authority. The community could give input on them until 16 March 2026, and in October they were in progress ([Juan Ferrer, March 2026](https://coe-dsc.nl/wp-content/uploads/2026/04/Ana-Ferer-180326_Simpl_DataSharingFestival.pdf), [Coffee with Simpl 4](https://simpl-programme.ec.europa.eu/news/coffee-simpl-4th-edition-recap)).

#### Changes to the plan over time

The programme has published the roadmap in several versions. Comparing them shows that several of the governance functions have been moved back by about a year:

| Item | Roadmap February 2025 | Roadmap May 2025 | Roadmap January 2026 (current) |
|---|---|---|---|
| Consent extensions to onboarding | Q3–Q4 2025 | Q3–Q4 2025 | Innsbruck, Q4 2026 |
| Consent management | Q3 2025 – Q1 2026 | Q4 2025 – Q1 2026 | Innsbruck, Q4 2026 |
| Define policies in schema | Q1–Q3 2025 | Q1–Q3 2025 | Innsbruck, Q4 2026 |
| Audit | Q4 2025 – Q1 2026 | Q4 2025 – Q1 2026 | Innsbruck, Q4 2026 |
| Contract enforcement | Q4 2025 – Q2 2026 | Q4 2025 – Q2 2026 | Innsbruck, Q4 2026 |

Sources: the roadmaps in the Simpl forum from [February 2025](https://simpl-programme.ec.europa.eu/group/simpl-forum-0/discussion/simpl-open-development-roadmap-2025-2026) and [May 2025](https://simpl-programme.ec.europa.eu/group/simpl-forum-0/discussion/simpl-open-roadmap-update-may-2025), and [development status](https://simpl-programme.ec.europa.eu/documentation/development-status). The quarters are read from the timelines and are approximate. The roadmap itself states that it is indicative and may change based on input from the community and findings in Simpl-Live, so the changes may also reflect new priorities.

---

### Where the code and documentation are

Everything is openly available at [code.europa.eu/simpl/simpl-open](https://code.europa.eu/simpl/simpl-open). The code base is now being moved from an old structure under "development" to a structure where the projects are organised by the capability map. During the transition, a component may be found in both places. See [Finding your way in the Simpl documentation](../finn-fram/).

---

### Assessment of maturity

*This is our assessment, not the programme's.* Simpl-Open is delivered regularly and has a clear architecture. Basic governance has been included since the MVP: the authority role, onboarding of participants and conclusion of usage agreements. Management of contracts, policies, consent and audit, and contract enforcement, arrive only in 5.0 ([development status](https://simpl-programme.ec.europa.eu/documentation/development-status)). We mainly know of use in Simpl-Live and in test environments. The software is therefore best suited for learning, testing and reusing components, and less suited as a finished platform for a new Norwegian data space today.
