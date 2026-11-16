---
id: e99c3bf9-6c4d-4ebf-bd9a-db18df23dd38
title: Relevance for Norway
weight: 40
lastmod: 2026-11-17T00:40:21+01:00
last_editor: Erik Hagen

---
*Why should Norwegian providers of shared national solutions and sector solutions, and the Norwegian Armed Forces, keep an eye on Simpl? This page brings together the arguments, and also the most important objections.*

The page is mainly a professional assessment. Factual statements are sourced. The rest is our assessment.

---

### An opportunity, not a threat

Many will see Simpl as a competitor to Norwegian shared national solutions. We believe the opposite is true. Simpl builds on a federated architecture where each participant keeps its own solutions, as long as they follow the common standards (see [One solution among several](../#one-solution-among-several)).

- **Reach:** Shared solutions that follow the same standards can become Norway's connection point to European data spaces, and reach further than today, also outside Norway. Examples are services built with Altinn Studio, Altinn Authorisation, ID-porten and the wallet, and data.norge.no.
- **Precondition:** The solutions must comply with the common requirements: the standards for data sharing (Dataspace Protocol, ODRL, DCAT-AP) and the requirements for identity and trust services (eIDAS 2.0, the EUDI wallet, verifiable credentials). That work has to be done anyway, with or without Simpl.
- **Arena:** In [Simpl-Labs](../simpl-labs/) we can show that Norwegian solutions work together, and influence the requirements while they are being shaped.

---

### A common ecosystem: shared national solutions and sector solutions

Simpl-Open is the most concrete European implementation of the building blocks that the European data spaces are converging on: the Dataspace Protocol, connectors, ODRL policies, verifiable credentials and DCAT-based catalogues. For Norwegian shared national solutions, the question is therefore not whether they should relate to these standards, but how and when.

- **Access control and authorisation (Digdir, Altinn):** Altinn Authorisation is based on XACML, while Simpl and other data spaces express usage terms in ODRL. A link between the two models is needed if Norwegian access rights are to apply in European data spaces.
- **Identity and wallet (ID-porten, EUDI wallet):** Simpl-Open uses verifiable credentials both for identification and for contracting, and has chosen an OID4VP verifier. This ties Simpl directly to the work on digital wallets under eIDAS 2.0.
- **Data catalogues (data.norge.no):** Simpl-Open uses RDF-based descriptions and plans support for DCAT-AP. Norwegian catalogues follow DCAT-AP-NO, and the alignment between them should be tested.
- **Municipal shared solutions (KS Digital):** Municipalities will become participants in several data spaces, including smart communities (SCDS), mobility and energy. Shared solutions such as KS Fiks may become the natural connection point for municipalities, instead of each municipality connecting to each data space.
- **Reuse of open source:** The components are licensed under EUPL 1.2 and can be reused in Norwegian solutions without adopting all of Simpl.

[Simpl-Labs](../simpl-labs/) makes it possible to test this against the European setup before it becomes a requirement from a sector.

Which shared solutions should be analysed, and which questions must be clarified, is set out in a separate draft under Architecture: [Shared solutions and European requirements](/en/arkitektur/loesningslandskap/fellesloesninger-og-europeiske-krav/). It also covers eIDAS 2.0 and Once-Only, not just data spaces.

---

### Total defence and the Norwegian Armed Forces

The Norwegian Armed Forces launched *the Armed Forces' data-centric architecture* (FDSA), also called the "data constitution", during Arendalsuka in August 2026. The architecture was developed together with NATO, the Norwegian National Security Authority (NSM) and the Norwegian Defence Research Establishment (FFI). The principles are that data should be kept separate from the systems, that rules for security, access and sharing should follow the data, that the technology should be replaceable, and that interfaces should be standardised. FDSA primarily governs the Armed Forces' own procurements, but the principles are open, so that civilian actors such as telecoms, transport and municipalities can share data with the Armed Forces in a crisis ([Digital Norway, August 2026](https://digitalnorway.com/aktuelt/forsvaret-lanserer-ny-datagrunnlov-grunnmuren-for-et-digitalt-totalforsvar)). NATO has published its own [data-centric reference architecture](https://nhqc3s.hq.nato.int/apps/DCRA_Report/index.html).

On the EU side, the European Defence Agency (EDA) is building a separate defence data space, the European Defence Artificial Intelligence Data Space (DAIDS). It is to be in routine use around 2029–2030 ([Computing](https://www.computing.co.uk/news/2026/security/eu-hopes-to-sever-defence-data); [Sopra Steria, April 2025](https://www.soprasteria.be/newsroom/press-releases/details/european-defence-agency-select-sopra-steria-CDE-and-CEA-for-framework-contract)). We have found no link between DAIDS and Simpl.

*Our assessment:* The principles in FDSA fit well with the thinking behind data spaces. That rules should follow the data corresponds, for example, to ODRL policies that travel with the data through a connector. Total defence depends on data sharing with civilian actors, and these will increasingly be connected to European data spaces. Simpl-Labs could therefore be a neutral, civilian and unclassified arena for testing data sharing between civilian and military actors, without anyone committing to a platform.

---

### Objections

- **Simpl could crowd out Norwegian shared solutions.** The architecture principles point the other way: federation, and interoperability without requirements on how each participant has built its part. The risk is a different one: those who do not take part in shaping the standards and requirements will have to adapt to them later. That argues for taking part early, not for keeping a distance.
- **Heavy and driven by the Commission.** Simpl is a large EU programme, and the roadmap is governed by the Commission's priorities. Norwegian actors may get more out of adopting the standards (DSP, ODRL, DCAT-AP) directly than out of relating to all of Simpl.
- **Limited maturity.** The core governance functions arrive only in Simpl-Open 5.0, and when Simpl-Labs will be generally available is unclear.
- **Unclear adoption.** There is no public overview of which data spaces actually run Simpl-Open in production.
- **Not designed for classified data.** For the Armed Forces, Simpl is at best a place to learn about civilian data sharing. NATO standards and classification requirements still apply, and DAIDS is a separate track.

Our overall assessment is that Simpl is most valuable as a signal of the direction things are heading, and as an arena for testing, learning and influence. It is less valuable as a platform Norwegian actors should adopt today.

---

### Possible next steps

- Take part in the Simpl-Labs user group from the first wave, and bring concrete Norwegian testing needs. Priorities are set early (see [Simpl-Labs](../simpl-labs/)).
- Test the link between Altinn authorisation and ODRL, and between the wallet and verifiable credentials, in Simpl-Labs.
- Explore a joint civil–military test of data sharing in total defence together with the Armed Forces.
