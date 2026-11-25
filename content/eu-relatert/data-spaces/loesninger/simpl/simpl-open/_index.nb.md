---
id: 66e10fc5-050e-49ac-a195-fe6459699649
title: Simpl-Open
weight: 10
lastmod: 2026-11-25T01:05:10+01:00
last_editor: Erik Hagen

---
*Simpl-Open er programvaren i Simpl: åpen kildekode med modulære komponenter som et data space kan bruke for å la deltakerne finne hverandre, avtale vilkår og dele data på en kontrollert måte.*

---

### Hva Simpl-Open gjør

Simpl-Open dekker hele løpet i et data space. Først settes det opp en katalog med skjema og vokabular, og deltakerne tas inn. Deretter kan deltakerne publisere og finne ressurser (data, infrastruktur eller programvarepakker), inngå avtaler og få tilgang til ressursene de har avtalt ([Ana Juan Ferrer (Europakommisjonen), mars 2026](https://coe-dsc.nl/wp-content/uploads/2026/04/Ana-Ferer-180326_Simpl_DataSharingFestival.pdf)).

Arkitekturen er bygd rundt tre typer *agenter*, én for hver rolle i et data space: myndigheten som styrer data spacet (governance authority), dataleverandøren og datakonsumenten. Hver deltaker kjører sin egen agent. Funksjonaliteten er ordnet i et kapabilitetskart med seks dimensjoner: Administrasjon, Data, Integrasjon, Infrastruktur, Styring og Sikkerhet ([arkitekturrepoet](https://code.europa.eu/simpl/simpl-open/foundations/architecture)).

Simpl-Open bygger på etablerte standarder og prosjekter: Gaia-X/XFSC, Eclipse Dataspace Connector (EDC), Dataspace Protocol (DSP), ODRL for bruksvilkår og RDF for metadata. Støtte for DCAT-AP er planlagt. Identitet og tillit bygger på verifiserbare attester. Arkitekturbeslutningene (ADR-ene) omfatter blant annet en OID4VP-verifikator og avtaleinngåelse ved at verifiserbare attester overføres mellom partene.

Programvaren er lisensiert under EUPL 1.2. Den kan brukes som én samlet løsning, eller man kan plukke enkeltkomponenter og bygge videre på dem.

---

### Releaser og status

Simpl-Open kommer i releaser oppkalt etter europeiske byer, omtrent én per kvartal:

| Release | Innhold (hovedtrekk) | Status |
|---|---|---|
| Gdynia (4.0) | Ressurs- og vokabularhåndtering, tilgangskontroll, provisjonering, observabilitet, databehandling | Utgitt 6. juli 2026 (installasjonsguiden er tagget v4.0.0 7. juli 2026) |
| Hamburg (4.1) | Føderasjon, håndtering av attester, ressurssøk, datastyring, applikasjons- og datadeling, varsling | Planlagt til andre halvdel av oktober 2026. Installasjonsguiden er tagget v4.1.0 5. november 2026, så Hamburg er trolig utgitt litt forsinket. Programmet har ikke kunngjort det |
| Innsbruck (5.0) | Avansert styring (revisjon, deltakere, policyer, kontrakter, samtykke), håndheving av kontrakter, HPC | Planlagt, opprinnelig for 4. kvartal 2026 |

Kilder: [utviklingsstatus](https://simpl-programme.ec.europa.eu/documentation/development-status), [Coffee with Simpl 3, juli 2026](https://simpl-programme.ec.europa.eu/news/coffee-simpl-3rd-session-recap), [installasjonsguiden](https://code.europa.eu/simpl/simpl-open/cross-cutting/documentation/installation-guide). Veikartet sier selv at det er veiledende og kan endres.

#### Byggeklosser per release

Veikartet ordner byggeklossene etter de seks dimensjonene i kapabilitetskartet. På siden for [utviklingsstatus](https://simpl-programme.ec.europa.eu/documentation/development-status) vises det også som en tidslinje over 2.–4. kvartal 2026, med én farge per dimensjon. Fargene viser dimensjonen, ikke status. Gdynia har 10 elementer, Hamburg 12 og Innsbruck 27. Tabellen viser hva hver release inneholder.

| Dimensjon | Gdynia (4.0), utgitt juli 2026 | Hamburg (4.1), utgitt november 2026 | Innsbruck (5.0), planlagt 4. kvartal 2026 |
|---|---|---|---|
| Administrasjon | Overvåking av forretningshendelser; personlig startside | Overvåking av agentene; støttetjenester og brukerstøtte; tjenestekvalitet og varsler | Overvåking av data- og applikasjonsbruk; dashbord og rapportering; overvåking av infrastrukturen |
| Data | Orkestrering av databehandling; analyse og visualisering; skjemahåndtering; vokabularhåndtering | Datastyring: sporing av opphav (lineage) og datakvalitet | Datastrømming; vurdering av metadatakvalitet |
| Styring | Ressursbeskrivelser i katalogen (XFSC) | – | Revisjon; fakturering; samtykke ved opptak; inngåelse og forvaltning av kontrakter; policyer i skjema; dashbord for styringsmyndigheten; kontraktsvilkår i ressursbeskrivelser; revisjon av deltakere |
| Integrasjon | Overføring av store datamengder | Bruk av applikasjoner og AI-modeller; publisering og søk etter applikasjoner i katalogen | Bruk på tvers av data spaces; håndheving av kontrakter; distribuert prosessering; føderert katalogsøk på tvers av data spaces |
| Infrastruktur | Katalogtjenester for infrastruktur (skript og maler) | Utrulling av applikasjoner; føderasjon mellom data spaces (Tier 2) | Sky og edge; energiforbruk; HPC; integrasjon med plattformtjenester (PaaS) |
| Sikkerhet | Kobling til ekstern identitetsleverandør | Samtykke for datasett med personopplysninger; VPN; selvstyrt identitet med digital lommebok (SSI Tier 1) | Hendelseshåndtering (CSIRT); DCAT-AP; VPN; selvstyrt identitet (SSI Tier 2) |

Kilder: veikartet for [Gdynia](https://simpl-programme.ec.europa.eu/development/development-status/simpl-open-roadmap-items-gdynia-4.0), [Hamburg](https://simpl-programme.ec.europa.eu/development/development-status/simpl-open-roadmap-items-hamburg-4.1) og [Innsbruck](https://simpl-programme.ec.europa.eu/development/development-status/simpl-open-roadmap-items-innsbruck-5.0), publisert januar 2026 og lest 18. november 2026. Veikartet viser ikke status for hvert element. At en release er utgitt, betyr derfor ikke nødvendigvis at alle elementene i den er levert fullt ut. Funksjonalitet fra tidligere releaser (MVP til 3.x), som opptak av deltakere og inngåelse av bruksavtaler, er ikke med i tabellen.

Det nærmeste vi har funnet en status underveis, er det programmet viste fram på Coffee with Simpl 1. oktober 2026: arbeid med publisering og søk etter applikasjoner, overvåking, sikkerhet, utrulling av applikasjoner, støttetjenester, oppsett av føderasjon og samtykke. Alt dette er elementer i Hamburg, som altså var under arbeid da ([Coffee with Simpl 4](https://simpl-programme.ec.europa.eu/news/coffee-simpl-4th-edition-recap)).

Ved siden av releasene utvikles tre utvidelser (Simpl-Open Extensions): AI/ML med kobling til EuroHPCs føderasjonsplattform, kobling av katalogen til markedsplassen DOME, og inntekter for styringsmyndigheten (monetisation). Fellesskapet kunne gi innspill til dem fram til 16. mars 2026, og i oktober var de under arbeid ([Juan Ferrer, mars 2026](https://coe-dsc.nl/wp-content/uploads/2026/04/Ana-Ferer-180326_Simpl_DataSharingFestival.pdf), [Coffee with Simpl 4](https://simpl-programme.ec.europa.eu/news/coffee-simpl-4th-edition-recap)).

#### Endringer i planen over tid

Programmet har publisert veikartet i flere versjoner. Når vi sammenligner dem, ser vi at flere av styringsfunksjonene er skjøvet omtrent ett år:

| Element | Veikart februar 2025 | Veikart mai 2025 | Veikart januar 2026 (gjeldende) |
|---|---|---|---|
| Samtykke ved opptak (Consent extensions to onboarding) | 3.–4. kvartal 2025 | 3.–4. kvartal 2025 | Innsbruck, 4. kvartal 2026 |
| Samtykkehåndtering (Consent management) | 3. kvartal 2025 – 1. kvartal 2026 | 4. kvartal 2025 – 1. kvartal 2026 | Innsbruck, 4. kvartal 2026 |
| Policyer i skjema (Define policies in schema) | 1.–3. kvartal 2025 | 1.–3. kvartal 2025 | Innsbruck, 4. kvartal 2026 |
| Revisjon (Audit) | 4. kvartal 2025 – 1. kvartal 2026 | 4. kvartal 2025 – 1. kvartal 2026 | Innsbruck, 4. kvartal 2026 |
| Håndheving av kontrakter (Contract enforcement) | 4. kvartal 2025 – 2. kvartal 2026 | 4. kvartal 2025 – 2. kvartal 2026 | Innsbruck, 4. kvartal 2026 |

Kilder: veikartene i Simpl-forumet fra [februar 2025](https://simpl-programme.ec.europa.eu/group/simpl-forum-0/discussion/simpl-open-development-roadmap-2025-2026) og [mai 2025](https://simpl-programme.ec.europa.eu/group/simpl-forum-0/discussion/simpl-open-roadmap-update-may-2025), og [utviklingsstatus](https://simpl-programme.ec.europa.eu/documentation/development-status). Kvartalene er lest av tidslinjene og er omtrentlige. Veikartet sier selv at det er veiledende og kan endres etter innspill fra fellesskapet og funn i Simpl-Live, så endringene kan også skyldes nye prioriteringer.

---

### Hvor koden og dokumentasjonen ligger

Alt ligger åpent på [code.europa.eu/simpl/simpl-open](https://code.europa.eu/simpl/simpl-open). Kodebasen flyttes nå fra en gammel struktur under «development» til en struktur der prosjektene er ordnet etter kapabilitetskartet. I overgangsperioden kan en komponent ligge begge steder. Se [Finn fram i Simpl-dokumentasjonen](../finn-fram/).

---

### Vurdering av modenhet

*Dette er en vurdering, ikke programmets.* Simpl-Open leveres jevnlig og har en tydelig arkitektur. Grunnleggende styring har vært med siden MVP: myndighetsrollen, opptak av deltakere og inngåelse av bruksavtaler. Forvaltning av kontrakter, policyer, samtykke og revisjon, og håndheving av kontrakter, kommer først i 5.0 ([utviklingsstatus](https://simpl-programme.ec.europa.eu/documentation/development-status)). Vi kjenner i hovedsak til bruk i Simpl-Live og i testmiljøer. Programvaren er derfor best egnet til å lære, teste og gjenbruke komponenter, og mindre egnet som ferdig plattform for et nytt norsk data space i dag.
