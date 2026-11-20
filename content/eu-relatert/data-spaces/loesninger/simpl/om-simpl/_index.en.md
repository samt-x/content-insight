---
id: 31003db8-7c1e-43b4-993f-66a005f55841
title: About Simpl
weight: 5
lastmod: 2026-11-20T02:16:30+01:00
last_editor: Erik Hagen

---
*Simpl is the European Commission's initiative to speed up the development of European data spaces. At its core is Simpl-Open, open-source software that puts the common standards and patterns for data sharing into practice. Simpl is not meant to be the only solution. The architecture is federated, and other solutions that follow the same standards should be able to work together with it.*

The programme has three parts: the Simpl-Open software, the Simpl-Labs test and sandbox environment, and Simpl-Live, which helps selected data spaces adopt the software.

Status information on these pages is as of 16 November 2026 and comes from the sources linked. Simpl changes quickly, so check the sources before reusing the information.

---

### The three parts

{{< kortrad >}}
{{< kort tittel="Simpl-Open" ikon="code" lenke="../simpl-open/" etikett="Status November 2026" status="Version 4.0 was released in July 2026 and 4.1 in November 2026. Version 5.0 is planned." >}}
Open-source software (EUPL 1.2) with modular components for data sharing in data spaces.
{{< /kort >}}
{{< kort tittel="Simpl-Labs" ikon="flask" lenke="../simpl-labs/" etikett="Status November 2026" status="Being built. The implementation phase started in February 2026, and interoperability testing is expected in 2027." >}}
A sandbox for trying out a data space, and a test environment for interoperability with Simpl-Open.
{{< /kort >}}
{{< kort tittel="Simpl-Live" ikon="rocket" lenke="../simpl-live/" etikett="Status November 2026" status="Six data spaces in wave 1 and five initiatives in wave 2. Implementation of wave 1 started in February 2026." >}}
Support for selected European data spaces: first a feasibility study, then help implementing Simpl-Open.
{{< /kort >}}
{{< /kortrad >}}

How this may be relevant is discussed under [Relevance for Norwegian actors](../relevans-for-norge/). Under [Finding your way in the Simpl documentation](../finn-fram/) you will find a guide to the architecture documentation, which now lives mainly as Markdown files in GitLab.

---

### How Simpl relates to the rest of the data space landscape

Simpl is not a data space in itself. It is the toolbox that data spaces can build on. The Data Spaces Support Centre (DSSC) produces the guidance, including the Blueprint, Toolbox and Glossary, while Simpl-Open is software in which parts of that guidance can be put into use and tested in practice. According to DSSC, Simpl-Open is one option among several, and it can be used as a whole or as individual components ([DSSC, October 2026](https://dssc.eu/articles/from-guidance-to-deployment-how-simpl-helps-put-dsscs-guidance-into-practice)).

Technically, Simpl-Open builds on the same building blocks that the rest of the field is converging on: the Dataspace Protocol, the Eclipse Dataspace Connector (EDC), ODRL policies, RDF and verifiable credentials. See [Simpl-Open](../simpl-open/) for details.

---

### One solution among several

Simpl-Open is designed to work together with other solutions, not to replace them. This is stated in Simpl's own [architecture principles](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/architecture-principles.md):

- **Federation:** Participants are autonomous entities tied together by common standards, frameworks and legal rules, and service owners should have maximum autonomy.
- **Interoperability:** The architecture should describe how participants share resources, without assuming how each participant has built its own part.
- **Modularity:** Components can be replaced or added without affecting the rest, and a participant can deploy only the components it needs.

The Simpl programme itself says that initiatives can use individual components to build their own solutions, or use Simpl-Open as a base ([the Simpl programme](https://simpl-programme.ec.europa.eu/dashboard/about-simpl)). DSSC describes Simpl-Open as one option among several. [Simpl-Labs](../simpl-labs/) is also to test interoperability with data spaces that already exist.

*Our assessment:* In practice, Simpl-Open works as a reference implementation. It shows how the standards fit together, and provides a common place to test against. For national solutions, the question is therefore not whether to choose Simpl or build one's own, but whether one's own solutions work together with Simpl. See [Relevance for Norwegian actors](../relevans-for-norge/).

---

### Upcoming events

- **9 December 2026, Brussels:** Simpl Hackathon 2026, where participants install and test Simpl-Open. The same day, the Simpl-Labs user group (User Interest Group) holds its kick-off meeting. Digdir and IFE are represented in the user group.
- **10 December 2026, Brussels and online:** Simpl Annual Community Event, the third of its kind ([Simpl programme, events](https://simpl-programme.ec.europa.eu/events)).

---

### Sources

- [The Simpl programme (simpl-programme.ec.europa.eu)](https://simpl-programme.ec.europa.eu/dashboard/about-simpl)
- [Simpl-Open on code.europa.eu](https://code.europa.eu/simpl/simpl-open)
- [Simpl on LinkTree (European Commission)](https://linktr.ee/ec_simpl)
