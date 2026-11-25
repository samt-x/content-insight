---
id: e99c3bf9-6c4d-4ebf-bd9a-db18df23dd38
title: Relevance of Simpl for Norwegian digital infrastructure
linkTitle: Relevance for Norwegian digital infrastructure
weight: 60
lastmod: 2026-11-25T01:20:24+01:00
last_editor: Erik Hagen

---
*Simpl is the EU's programme for common, open software that is to make it easier to set up and connect [data spaces](../../../om-data-spaces/), that is, agreed frameworks for sharing data across organisations and countries (see [About Simpl](../om-simpl/)). What can Simpl mean for Norwegian digital infrastructure, as a whole, for selected providers of shared national solutions and for total defence? And which matters are worth being aware of?*

---

## In brief

The Norwegian government's goal is for Norway to be the most digitalised country in the world by 2030. The digitalisation strategy also states that Norway will take part in the EU's work on common European data spaces where relevant, and create strong synergies between Norwegian and European digitalisation policy ([The Digital Norway of the Future, 2024](https://www.regjeringen.no/en/documents/the-digital-norway-of-the-future/id3054645/?ch=2)).

*Assessment:* The goal cannot be reached alone. The road there must include being among the best at European and international cooperation, and Simpl is one of the arenas for that:

1. **Help in navigating a complex landscape.** The European data spaces build on many standards and requirements at the same time, including for exchanging data, expressing terms for the use of data, describing datasets and verifying digital credentials. Norwegian shared national solutions must relate to them, with or without Simpl. Simpl-Open, the software Simpl develops, shows how they fit together in practice, and can be a locomotive to hitch on to in order to get in line with the standards and requirements.
2. **Simpl is becoming a requirement in EU-funded projects.** Several calls in the EU's Digital Europe programme ask for solutions that work with Simpl, including in health, genomic data and cultural heritage. This already makes Simpl relevant for Norwegian participants in such projects.
3. **The window for influence is now.** Simpl is at an early stage. None of the first data spaces adopting Simpl (Simpl-Live) had reached operational deployment in August 2026, and the Simpl-Labs test environment is being shaped now. The Simpl-Labs user group holds its kick-off meeting in Brussels on 9 December 2026.
4. **Norwegian solutions can reach further.** Simpl is federated: each participant keeps its own solutions as long as they follow the common standards. Norwegian shared solutions can thus become Norway's connection point to European data spaces.
5. **Simpl is part of the EU strategy for open source and digital commons.** Norwegian actors can reuse components, contribute to further development, and test their own solutions against the alternatives: if theirs are good, others can build on them; if there are better alternatives, Norwegian actors can join those instead.
6. **The Simpl-Labs user group is a low-cost first step.** Digdir has recently joined the user group, along with the Institute for Energy Technology (IFE) from Norway. According to the Simpl-Labs team, participation is about feedback, testing selected features and occasional meetings, adapted to each organisation's capacity (see [What participation involves](../simpl-labs/#what-participation-involves)). In return, participants get early access to a common European test environment. Participation does not commit anyone to adopting Simpl-Open.

The sources are given in the chapters below.

---

## Norwegian digital infrastructure

Simpl builds on a federated architecture where each participant keeps its own solutions, as long as they follow the common standards (see [One solution among several](../om-simpl/#one-solution-among-several)). This has consequences for Norway's digital public infrastructure as a whole, not just for individual solutions.

### Common standards are coming anyway

The European data spaces are converging on the same building blocks, including the Dataspace Protocol, connectors, ODRL policies, verifiable credentials and DCAT-based catalogues. For Norwegian shared national solutions, the question is therefore not whether they should relate to these standards, but how and when.

The solutions must follow the standards for data sharing (Dataspace Protocol, ODRL, DCAT-AP) and the requirements for identity and trust services (eIDAS 2.0, the EUDI wallet, verifiable credentials). That work has to be done anyway, with or without Simpl.

*Assessment:* Simpl-Open is the most concrete European implementation of these building blocks, and can be a locomotive to hitch on to in order to get in line with the standards and requirements.

### The place of the shared national solutions

Simpl's architecture principles are federation, and interoperability without requirements on how each participant has built its part (see [One solution among several](../om-simpl/#one-solution-among-several)). Norwegian shared solutions therefore do not need to be replaced by Simpl, but must be able to work together with the solutions in the European data spaces. This is not only about technical interfaces. Just as important is the trust framework: the common rules for how participants are identified, how credentials are verified, and how terms for the use of data are followed up.

*Assessment:* Those who take part in shaping the standards and requirements can make sure they fit their own solutions. Those who do not will have to adapt to them later.

Which shared solutions should be analysed, and which questions must be clarified, is set out in a separate draft under Architecture: [Shared solutions and European requirements](/en/arkitektur/loesningslandskap/fellesloesninger-og-europeiske-krav/). It also covers eIDAS 2.0 and Once-Only, not just data spaces.

### Opportunities

- **Reach:** Shared solutions that follow the same standards can become Norway's connection point to European data spaces, and reach further than today, also outside Norway. Examples are services built with Altinn Studio, Altinn Authorisation, ID-porten and the wallet, and data.norge.no.
- **Influence:** In the [Simpl-Labs user group](../simpl-labs/#the-user-group-user-interest-group) Norwegian actors can bring in testing needs and influence what Labs will offer, while the service is still being shaped.
- **Testing before it becomes a requirement:** In [Simpl-Labs](../simpl-labs/) Norwegian actors can test whether their solutions work together with the European setup, before a sector or a call requires it.

### Simpl as part of the EU open source strategy

The components of Simpl-Open are licensed under EUPL 1.2 and can be reused in Norwegian solutions without adopting all of Simpl. Simpl also accepts contributions from outside: code, assessments of requirements and architecture, issue reports and strategic cooperation. The programme commits to addressing contributions within three working days ([the Simpl programme: How to contribute](https://simpl-programme.ec.europa.eu/dashboard/how-contribute)).

The EU's open source strategy from June 2026 lists Simpl among the EU's existing actions, as middleware for European data spaces. The strategy is to be implemented in particular through the Digital Commons EDIC ([EU Open Source Strategy](https://digital-strategy.ec.europa.eu/en/policies/open-source-strategy)). The consortium was launched in December 2025, with France, Germany, the Netherlands and Italy as members, and is to coordinate national development of open, interoperable and reusable solutions that can be shared across borders ([the Commission, December 2025](https://digital-strategy.ec.europa.eu/en/news/digital-commons-edic-launches-advance-europes-technological-sovereignty)). Internationally there are related initiatives, including the Digital Public Goods Alliance and GovStack.

*Assessment:* No sources have been found that formally link Simpl to the Digital Public Goods Alliance or GovStack, but Simpl builds on the same thinking: shared digital infrastructure as open source, which several countries can use and develop together. For Norway this works both ways:

- **Reuse:** Norwegian shared solutions can adopt components that others have developed.
- **Development together with others:** If Norwegian solutions are good, they can gain contributors and users outside Norway. One example is Digdir's solutions for describing datasets and public services on data.norge.no, which build on the European standards DCAT-AP and CPSV-AP.
- **Comparison:** If tests show that other solutions have a better concept or have come further, it may be better to join the collaboration on them than to develop everything alone.

Simpl-Labs, with conformance tests against Simpl-Open, is a place where such a comparison can be made. The actual collaboration on the code takes place in the projects' own communities, for example in Simpl-Open or in SEMIC, which maintains DCAT-AP and CPSV-AP.

---

## Providers of shared national solutions

Opportunities and consequences are linked for each provider, and are therefore set out together per actor.

### Digdir

- **Access control and authorisation (Altinn):** Altinn Authorisation is based on XACML, while Simpl and other data spaces express usage terms in ODRL. A link between the two models is needed if Norwegian access rights are to apply in European data spaces.
- **Identity and wallet (ID-porten, EUDI wallet):** Simpl-Open uses verifiable credentials both for identification and for contracting, and has chosen an OID4VP verifier. This ties Simpl directly to the work on digital wallets under eIDAS 2.0.
- **Data catalogues (data.norge.no):** Simpl-Open uses RDF-based descriptions and plans support for DCAT-AP. Norwegian catalogues follow DCAT-AP-NO, and the alignment between them should be tested.
- **Open source:** *Assessment:* Digdir can reuse components from Simpl-Open, let its own solutions meet the alternatives in Simpl-Labs, and work with others on further development where it pays off (see [Simpl as part of the EU open source strategy](#simpl-as-part-of-the-eu-open-source-strategy)).

### KS Digital

- **Municipal shared solutions:** Municipalities will become participants in several data spaces, including smart communities (SCDS), mobility and energy. Shared solutions such as KS Fiks may become the natural connection point for municipalities, instead of each municipality connecting to each data space.

---

## Total defence and the Norwegian Armed Forces

The Norwegian Armed Forces launched *the Armed Forces' data-centric architecture* (FDSA), also called the "data constitution", during Arendalsuka in August 2026. The architecture was developed together with NATO, the Norwegian National Security Authority (NSM) and the Norwegian Defence Research Establishment (FFI). The principles are that data should be kept separate from the systems, that rules for security, access and sharing should follow the data, that the technology should be replaceable, and that interfaces should be standardised. FDSA primarily governs the Armed Forces' own procurements, but the principles are open, so that civilian actors such as telecoms, transport and municipalities can share data with the Armed Forces in a crisis ([Digital Norway, August 2026](https://digitalnorway.com/aktuelt/forsvaret-lanserer-ny-datagrunnlov-grunnmuren-for-et-digitalt-totalforsvar)). NATO has published its own [data-centric reference architecture](https://nhqc3s.hq.nato.int/apps/DCRA_Report/index.html).

On the EU side, the European Defence Agency (EDA) is building a separate defence data space, the European Defence Artificial Intelligence Data Space (DAIDS). It is to be in routine use around 2029–2030 ([Computing](https://www.computing.co.uk/news/2026/security/eu-hopes-to-sever-defence-data); [Sopra Steria, April 2025](https://www.soprasteria.be/newsroom/press-releases/details/european-defence-agency-select-sopra-steria-CDE-and-CEA-for-framework-contract)). No link has been found between DAIDS and Simpl.

*Assessment:* The principles in FDSA fit well with the thinking behind data spaces. That rules should follow the data corresponds, for example, to ODRL policies that travel with the data through a connector. Total defence depends on data sharing with civilian actors, and these will increasingly be connected to European data spaces. Simpl-Labs could therefore be a neutral, civilian and unclassified arena for testing data sharing between civilian and military actors, without anyone committing to a platform.

Simpl is not designed for classified data. For classified information, NATO standards and classification requirements still apply, and DAIDS is a separate track.

---

## Matters to be aware of

### Status and adoption

Simpl-Live covers 11 data spaces and initiatives, six in wave 1 and five in wave 2 ([Digital Europe work programme 2025–2027, unofficial consolidated version](https://www.ffg.at/sites/default/files/2026-05/DIGITAL%20WP%2025-27_Unofficial%20version%20with%20amendments.pdf), p. 30). The programme divides implementation into five steps: review of requirements, technical validation, acceptance, operational deployment and maintenance ([the Simpl programme, August 2026](https://simpl-programme.ec.europa.eu/system/files/2026-08/Simpl_Live_Implementation_Phase_Visual.pdf)).

- **Wave 1:** Integration of Simpl-Open started in February 2026. By May 2026 the first workshops had been held to review requirements and scenarios ([Simpl, May 2026](https://ec.europa.eu/newsroom/simpl/redirection/item/940026)), and in October 2026 integration was under way in all six ([Simpl, October 2026](https://ec.europa.eu/newsroom/simpl/items/959708/en)). It is planned to be completed in October 2027 ([Simpl-Live factsheet](https://simpl-programme.ec.europa.eu/system/files/2026-05/Factsheet_Simpl-Live_A4%2016.pdf)). According to the programme's milestone report, last updated 24 August 2026, only the Language Data Space (LDS) had completed the review and started technical validation. The other five were still in the first step, and none had reached acceptance or operational deployment (see [Simpl-Live](../simpl-live/#status-of-wave-1-by-initiative)).
- **Wave 2:** The feasibility studies are complete, and the conclusions were published in June 2026 ([document library](https://simpl-programme.ec.europa.eu/topic/simpl-live-document-library)). No sources have been found showing that implementation has started.
- **Outside Simpl-Live:** Several Digital Europe calls ask for solutions to be compatible with Simpl, including for genomic data, cultural heritage and health ([the work programme](https://www.ffg.at/sites/default/files/2026-05/DIGITAL%20WP%2025-27_Unofficial%20version%20with%20amendments.pdf)). The tender for operating the EOSC EU Node, the EU's common platform for open research (European Open Science Cloud), requires integration with Simpl, "subject to availability" ([the tender, 2026](https://digital-strategy.ec.europa.eu/en/funding/managed-services-eosc-eu-node-2026)).

Outside Simpl-Live, the smart communities pilots have tested Simpl-Open on their own. One of them states that Valencia has a Simpl node in operation, but this has not been possible to verify (see [Testing outside Simpl-Live](../simpl-live/#testing-outside-simpl-live)). Otherwise, no source has been found saying that Simpl-Open is in operational use in a data space yet.

*Assessment:* Simpl is still at an early stage. This means that Norwegian actors can help shape how the solution is adopted, and that the requirements for Simpl compatibility in Digital Europe already make Simpl relevant for Norwegian participants in such projects.

### Maturity and progress

Simpl-Open is released regularly: a proof of concept in July 2024, the MVP in January 2025, version 4.0 in July 2026 and 4.1 in November 2026. Version 5.0 is planned for Q4 2026 (see [Simpl-Open](../simpl-open/)). Basic governance has been included since the MVP, while management and enforcement of contracts, policies and consent arrive in 5.0. Several of these governance functions have been moved back by about a year since the 2025 roadmaps. Consent, for example, was first planned from Q3 2025 (see [Changes to the plan over time](../simpl-open/#changes-to-the-plan-over-time)).

Progress has been slower than first planned. In 2023 the MVP was to arrive no later than the end of 2024 ([the Commission, October 2023](https://digital-strategy.ec.europa.eu/en/node/10891/printable/pdf)). It arrived on 30 January 2025 ([Simpl-Open roadmap, May 2025](https://simpl-programme.ec.europa.eu/system/files/2025-05/Simpl-Open%20Roadmap%20May%20Update%20and%20June%20Release%20Details%202025.pdf)). In March 2026 Simpl-Labs was announced for autumn 2026, while in October 2026 DSSC described interoperability testing in Labs as coming in 2027 (see [Simpl-Labs](../simpl-labs/)).

The programme has been continued with EUR 52.9 million for 2025–2027 ([the work programme](https://www.ffg.at/sites/default/files/2026-05/DIGITAL%20WP%2025-27_Unofficial%20version%20with%20amendments.pdf), pp. 31–32).

### Simpl and other solutions for data spaces

Simpl-Open is not the only technical option for data spaces. DSSC says so itself ([DSSC, October 2026](https://dssc.eu/articles/from-guidance-to-deployment-how-simpl-helps-put-dsscs-guidance-into-practice)), and the Commission wrote in 2023 that Simpl deliberately stays away from sector-specific data services, and that Gaia-X, IDSA and Eclipse are followed with great interest ([the Commission, October 2023](https://digital-strategy.ec.europa.eu/en/node/10891/printable/pdf)). IDSA describes Simpl as a user of its standards ([IDSA](https://internationaldataspaces.org/from-idsa-standards-to-simpl-solutions/)).

A peer-reviewed article from April 2026 assesses Simpl's maturity as significantly lower than that of Eclipse Tractus-X, which is used in the automotive data space Catena-X ([Paz et al., JISBD 2026](https://hdl.handle.net/11705/JISBD/2026/168)). Two of the authors work on Tractus-X themselves.

*Assessment:* This speaks for using Simpl-Labs to test interoperability between several solutions, not for committing to one. Governance of the programme and the roadmap lies with the Commission, and that is precisely why it is an advantage to take part where the priorities are set.

---

## Possible next steps

- Take part in the Simpl-Labs user group from the first wave, with the kick-off in Brussels on 9 December 2026, and bring concrete Norwegian testing needs. Priorities are set early (see [Simpl-Labs](../simpl-labs/#the-user-group-user-interest-group)).
- Test the link between Altinn authorisation and ODRL, between the wallet and verifiable credentials, and between DCAT-AP-NO and DCAT-AP, in Simpl-Labs.
- Connect Simpl-Labs with Norwegian sandboxes and test environments for data sharing and artificial intelligence (AI). Examples are the Norwegian Data Protection Authority's regulatory sandbox for privacy-friendly innovation, which has also had projects on data sharing, and the regulatory AI sandbox that the Data Protection Authority, the Norwegian Communications Authority (Nkom) and Digdir are in the process of establishing as part of KI-Norge ([the Data Protection Authority's annual report for 2025](https://www.regjeringen.no/contentassets/d0c7f859c7034c2d943158143e724783/nn-no/sved/datatilsynet.pdf), in Norwegian). The Institute for Energy Technology (IFE) is also in the user group, and runs its own sandbox for data space infrastructure. *Assessment:* The Norwegian sandboxes can clarify legal and ethical questions, while Simpl-Labs can test whether the solutions work together with the European setup. Together they can offer a path from Norwegian testing to European interoperability.
- Explore a joint civil–military test of data sharing in total defence together with the Armed Forces.
