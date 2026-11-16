---
title: Finding your way in the Simpl documentation
weight: 50
lastmod: 2026-11-16T22:30:00+01:00
last_editor: Erik Hagen

---
*The architecture and user documentation for Simpl now lives as Markdown files in GitLab, without a separate publishing site. This page is a guide to where to find what.*

---

### How the documentation is organised

The Simpl programme moved its documentation from Confluence to Git in autumn 2026. GitLab is now used as a kind of wiki: the README files act as entry portals with a "You are here" path at the top and links further down.

The structure follows the capability map. Under [simpl-open](https://code.europa.eu/simpl/simpl-open) there is one group for each dimension: administration, data, integration, infrastructure, governance and security. In addition there is cross-cutting, with the installation guide and user manual among other things, and foundations, with business processes, non-functional requirements and architecture. The old structure under "development" is being phased out, but during the transition, content may be found in both places.

---

### Entry portals

| Portal | Content |
|---|---|
| [Simpl-Open](https://code.europa.eu/simpl/simpl-open) | The start page: how the repositories fit together, getting started |
| [Foundations](https://code.europa.eu/simpl/simpl-open/foundations) | Business processes (BP01 onwards), non-functional requirements, architecture |
| [Architecture](https://code.europa.eu/simpl/simpl-open/foundations/architecture) | Table of contents for all architecture documentation |
| [Installation guide](https://code.europa.eu/simpl/simpl-open/cross-cutting/documentation/installation-guide) | Installation, versioned per release |
| [User manual](https://code.europa.eu/simpl/simpl-open/cross-cutting/documentation/user-manual) | Configuration and operation |

---

### The most important architecture files

| File | What you will find |
|---|---|
| [description.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/description.md) | General introduction to Simpl and the actors |
| [capability-map.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/capability-map.md) | The capability map: dimensions, capabilities and services |
| [architecture-principles.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/architecture-principles.md) | The ten architecture principles |
| [architectural-patterns.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/architectural-patterns.md) | Recurring architectural patterns |
| [agent-anatomy.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/agent-anatomy.md) | Tier I and Tier II participants, and how a Simpl service is structured |
| [connector.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/connector.md) | The Dataspace Protocol and the connector |
| [identification-authentication-and-authorisation.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/identification-authentication-and-authorisation.md) | Identity, authentication and authorisation |
| [functional-architecture.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/functional-architecture.md) | The services in each agent and how they interact |
| [interface-catalogue.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/interface-catalogue.md) | Overview of APIs |
| [technology-choices.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/technology-choices.md) | Chosen open-source technologies |
| [adr/](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/adr/README.md) | Architecture decisions (ADRs) |
| [controlled_vocabulary/](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/controlled_vocabulary/README.md) | Controlled vocabulary and glossary |

---

### The main document D1.3.4

The consolidated architecture specification, *D1.3.4 Functional and Technical Architecture Specifications*, still exists as [one large Markdown file](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/functional_and_technical_architecture_specifications/Functional-and-Technical-Architecture-Specifications.md) of around 18,800 lines. It was last changed in July 2026 and calls itself version 0.1. The smaller files and the ADRs are updated regularly and are therefore often more recent than the main document. This applies in particular to technology choices, interfaces and decisions.

---

### Tips

- The architecture model is in ArchiMate format (Archi with coArchi) in the "model" folder of the architecture repository. It can be opened in Archi.
- To read everything together, the easiest is to clone the architecture repository and open it in a Markdown reader or editor.
- The old architecture repository ([simpl/simpl-open/architecture](https://code.europa.eu/simpl/simpl-open/architecture)) is archived. The latest version there is from September 2025.
