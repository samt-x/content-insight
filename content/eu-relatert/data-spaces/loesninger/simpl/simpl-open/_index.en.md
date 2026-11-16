---
title: Simpl-Open
weight: 10
lastmod: 2026-11-16T22:30:00+01:00
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
| Gdynia (4.0) | Resource and vocabulary management, access control, provisioning, observability, data processing | Released July 2026 (the installation guide was tagged v4.0.0 on 7 July 2026) |
| Hamburg (4.1) | Federation, credential management, resource discovery, data governance, application and data sharing, notifications | The installation guide was tagged v4.1.0 on 5 November 2026. That this is the Hamburg release is our interpretation |
| Innsbruck (5.0) | Advanced governance (audit, participants, policies, contracts, consent), contract enforcement, HPC | Planned, originally for Q4 2026 |

Sources: [development status](https://simpl-programme.ec.europa.eu/dashboard/development-status), [installation guide](https://code.europa.eu/simpl/simpl-open/cross-cutting/documentation/installation-guide). The roadmap itself states that it is indicative and subject to change.

From Q2 2026, the roadmap is extended with, among other things, AI/ML services, a link to the DOME marketplace and integration with EuroHPC's federation platform ([Juan Ferrer, March 2026](https://coe-dsc.nl/wp-content/uploads/2026/04/Ana-Ferer-180326_Simpl_DataSharingFestival.pdf)).

---

### Where the code and documentation are

Everything is openly available at [code.europa.eu/simpl/simpl-open](https://code.europa.eu/simpl/simpl-open). The code base is now being moved from an old structure under "development" to a structure where the projects are organised by the capability map. During the transition, a component may be found in both places. See [Finding your way in the Simpl documentation](../finn-fram/).

---

### Assessment of maturity

*This is our assessment, not the programme's.* Simpl-Open is delivered regularly and has a clear architecture, but the core governance functions (contracts, consent, policy enforcement) arrive only in 5.0. We mainly know of use in Simpl-Live and in test environments. The software is therefore best suited for learning, testing and reusing components, and less suited as a finished platform for a new Norwegian data space today.
