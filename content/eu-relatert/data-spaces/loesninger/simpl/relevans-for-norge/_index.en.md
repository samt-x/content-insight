---
id: e99c3bf9-6c4d-4ebf-bd9a-db18df23dd38
title: Relevance for Norway
weight: 60
status: In progress
lastmod: 2026-11-18T22:07:52+01:00
last_editor: Erik Hagen

---
{{< warning >}}◐ <strong>Work in progress.</strong> This page is being rewritten and has not been fully assessed. It should not be used as a basis yet. Chapters marked "Coming" so far contain only keywords.{{< /warning >}}

*What can Simpl mean for Norway? This page looks at the opportunities, at the consequences for Norway's digital public infrastructure and for selected actors, and at matters worth being aware of.*

The page is mainly a professional assessment. Factual statements are sourced. The rest is our assessment.

---

### Opportunities for Norway

Simpl builds on a federated architecture where each participant keeps its own solutions, as long as they follow the common standards (see [One solution among several](../om-simpl/#one-solution-among-several)). This gives Norwegian solutions several opportunities:

- **Reach:** Shared solutions that follow the same standards can become Norway's connection point to European data spaces, and reach further than today, also outside Norway. Examples are services built with Altinn Studio, Altinn Authorisation, ID-porten and the wallet, and data.norge.no.
- **Arena:** In [Simpl-Labs](../simpl-labs/) we can show that Norwegian solutions work together, and influence the requirements while they are being shaped.

---

### Consequences for Norway

#### Overall: Norway's digital public infrastructure

Simpl-Open is the most concrete European implementation of the building blocks that the European data spaces are converging on: the Dataspace Protocol, connectors, ODRL policies, verifiable credentials and DCAT-based catalogues. For Norwegian shared national solutions, the question is therefore not whether they should relate to these standards, but how and when.

- **Compliance with the common requirements:** The solutions must follow the standards for data sharing (Dataspace Protocol, ODRL, DCAT-AP) and the requirements for identity and trust services (eIDAS 2.0, the EUDI wallet, verifiable credentials). That work has to be done anyway, with or without Simpl.
- **Reuse of open source:** The components are licensed under EUPL 1.2 and can be reused in Norwegian solutions without adopting all of Simpl.

[Simpl-Labs](../simpl-labs/) makes it possible to test this against the European setup before it becomes a requirement from a sector.

Which shared solutions should be analysed, and which questions must be clarified, is set out in a separate draft under Architecture: [Shared solutions and European requirements](/en/arkitektur/loesningslandskap/fellesloesninger-og-europeiske-krav/). It also covers eIDAS 2.0 and Once-Only, not just data spaces.

*Coming.* Keywords: an overall view of Norway's digital public infrastructure (DPI) in the light of Simpl.

#### For selected actors

**Digdir**

- **Access control and authorisation (Altinn):** Altinn Authorisation is based on XACML, while Simpl and other data spaces express usage terms in ODRL. A link between the two models is needed if Norwegian access rights are to apply in European data spaces.
- **Identity and wallet (ID-porten, EUDI wallet):** Simpl-Open uses verifiable credentials both for identification and for contracting, and has chosen an OID4VP verifier. This ties Simpl directly to the work on digital wallets under eIDAS 2.0.
- **Data catalogues (data.norge.no):** Simpl-Open uses RDF-based descriptions and plans support for DCAT-AP. Norwegian catalogues follow DCAT-AP-NO, and the alignment between them should be tested.
- *Coming.* Keywords: building to a greater extent on reuse of, and collaboration on, open source.

**KS Digital**

- **Municipal shared solutions:** Municipalities will become participants in several data spaces, including smart communities (SCDS), mobility and energy. Shared solutions such as KS Fiks may become the natural connection point for municipalities, instead of each municipality connecting to each data space.

**Novari, STAF, Sikt, HK-dir and SSB**

*Coming.* Actors that are particularly relevant in SAMT-BU.

#### Total defence and the Norwegian Armed Forces

The Norwegian Armed Forces launched *the Armed Forces' data-centric architecture* (FDSA), also called the "data constitution", during Arendalsuka in August 2026. The architecture was developed together with NATO, the Norwegian National Security Authority (NSM) and the Norwegian Defence Research Establishment (FFI). The principles are that data should be kept separate from the systems, that rules for security, access and sharing should follow the data, that the technology should be replaceable, and that interfaces should be standardised. FDSA primarily governs the Armed Forces' own procurements, but the principles are open, so that civilian actors such as telecoms, transport and municipalities can share data with the Armed Forces in a crisis ([Digital Norway, August 2026](https://digitalnorway.com/aktuelt/forsvaret-lanserer-ny-datagrunnlov-grunnmuren-for-et-digitalt-totalforsvar)). NATO has published its own [data-centric reference architecture](https://nhqc3s.hq.nato.int/apps/DCRA_Report/index.html).

On the EU side, the European Defence Agency (EDA) is building a separate defence data space, the European Defence Artificial Intelligence Data Space (DAIDS). It is to be in routine use around 2029–2030 ([Computing](https://www.computing.co.uk/news/2026/security/eu-hopes-to-sever-defence-data); [Sopra Steria, April 2025](https://www.soprasteria.be/newsroom/press-releases/details/european-defence-agency-select-sopra-steria-CDE-and-CEA-for-framework-contract)). We have found no link between DAIDS and Simpl.

*Our assessment:* The principles in FDSA fit well with the thinking behind data spaces. That rules should follow the data corresponds, for example, to ODRL policies that travel with the data through a connector. Total defence depends on data sharing with civilian actors, and these will increasingly be connected to European data spaces. Simpl-Labs could therefore be a neutral, civilian and unclassified arena for testing data sharing between civilian and military actors, without anyone committing to a platform.

Simpl is not designed for classified data. For classified information, NATO standards and classification requirements still apply, and DAIDS is a separate track.

---

### Matters to be aware of

#### Status and adoption

*Coming.* The status of Simpl-Live (waves 1 and 2) and other known uses of Simpl-Open is being investigated.

#### Maturity and progress

*Coming.* Keywords: what is in place in Simpl-Open 4.x, and what comes in 5.0. Progress in the programme, including the experience from the first round of requirements specification.

#### Criticism

*Coming.* Keywords: what a European reference implementation means for market solutions built on the same open standards. Governance of the programme and the roadmap lies with the Commission.

#### The place of the shared national solutions

*Coming.* Keywords: the relationship between Simpl and Norway's existing shared national solutions. Simpl's architecture principles are federation, and interoperability without requirements on how each participant has built its part (see [One solution among several](../om-simpl/#one-solution-among-several)). Those who do not take part in shaping the standards and requirements will have to adapt to them later.

---

### Possible next steps

- Take part in the Simpl-Labs user group from the first wave, and bring concrete Norwegian testing needs. Priorities are set early (see [Simpl-Labs](../simpl-labs/)).
- Test the link between Altinn authorisation and ODRL, and between the wallet and verifiable credentials, in Simpl-Labs.
- Explore a joint civil–military test of data sharing in total defence together with the Armed Forces.
