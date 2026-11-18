---
id: 66e10fc5-050e-49ac-a195-fe6459699649
title: Simpl-Open
weight: 10
lastmod: 2026-11-18T23:56:54+01:00
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
| Gdynia (4.0) | Ressurs- og vokabularhåndtering, tilgangskontroll, provisjonering, observabilitet, databehandling | Utgitt juli 2026 (installasjonsguiden er tagget v4.0.0 7. juli 2026) |
| Hamburg (4.1) | Føderasjon, håndtering av attester, ressurssøk, datastyring, applikasjons- og datadeling, varsling | Installasjonsguiden er tagget v4.1.0 5. november 2026. At dette er Hamburg-releasen, er vår tolkning |
| Innsbruck (5.0) | Avansert styring (revisjon, deltakere, policyer, kontrakter, samtykke), håndheving av kontrakter, HPC | Planlagt, opprinnelig for 4. kvartal 2026 |

Kilder: [utviklingsstatus](https://simpl-programme.ec.europa.eu/dashboard/development-status), [installasjonsguiden](https://code.europa.eu/simpl/simpl-open/cross-cutting/documentation/installation-guide). Veikartet sier selv at det er veiledende og kan endres.

#### Byggeklosser per release

Veikartet ordner byggeklossene etter de seks dimensjonene i kapabilitetskartet. Tabellen viser hva hver release inneholder.

| Dimensjon | Gdynia (4.0), utgitt juli 2026 | Hamburg (4.1), utgitt november 2026 | Innsbruck (5.0), planlagt 4. kvartal 2026 |
|---|---|---|---|
| Administrasjon | Overvåking av forretningshendelser; personlig startside | Overvåking av agentene; støttetjenester og brukerstøtte; tjenestekvalitet og varsler | Overvåking av data- og applikasjonsbruk; dashbord og rapportering; overvåking av infrastrukturen |
| Data | Orkestrering av databehandling; analyse og visualisering; skjemahåndtering; vokabularhåndtering | Datastyring: sporing av opphav (lineage) og datakvalitet | Datastrømming; vurdering av metadatakvalitet |
| Styring | Ressursbeskrivelser i katalogen (XFSC) | – | Revisjon; fakturering; samtykke ved opptak; inngåelse og forvaltning av kontrakter; policyer i skjema; dashbord for styringsmyndigheten; kontraktsvilkår i ressursbeskrivelser; revisjon av deltakere |
| Integrasjon | Overføring av store datamengder | Bruk av applikasjoner og AI-modeller; publisering og søk etter applikasjoner i katalogen | Bruk på tvers av data spaces; håndheving av kontrakter; distribuert prosessering; føderert katalogsøk på tvers av data spaces |
| Infrastruktur | Katalogtjenester for infrastruktur (skript og maler) | Utrulling av applikasjoner; føderasjon mellom data spaces (Tier 2) | Sky og edge; energiforbruk; HPC; integrasjon med plattformtjenester (PaaS) |
| Sikkerhet | Kobling til ekstern identitetsleverandør | Samtykke for datasett med personopplysninger; VPN; selvstyrt identitet med digital lommebok (SSI Tier 1) | Hendelseshåndtering (CSIRT); DCAT-AP; VPN; selvstyrt identitet (SSI Tier 2) |

Kilder: veikartet for [Gdynia](https://simpl-programme.ec.europa.eu/development/development-status/simpl-open-roadmap-items-gdynia-4.0), [Hamburg](https://simpl-programme.ec.europa.eu/development/development-status/simpl-open-roadmap-items-hamburg-4.1) og [Innsbruck](https://simpl-programme.ec.europa.eu/development/development-status/simpl-open-roadmap-items-innsbruck-5.0), publisert januar 2026 og lest 18. november 2026. Veikartet viser ikke status for hvert element. At en release er utgitt, betyr derfor ikke nødvendigvis at alle elementene i den er levert fullt ut. Funksjonalitet fra tidligere releaser (MVP til 3.x), som opptak av deltakere og inngåelse av bruksavtaler, er ikke med i tabellen.

Fra 2. kvartal 2026 utvides veikartet blant annet med AI/ML-tjenester, kobling til markedsplassen DOME og integrasjon med EuroHPCs føderasjonsplattform ([Juan Ferrer, mars 2026](https://coe-dsc.nl/wp-content/uploads/2026/04/Ana-Ferer-180326_Simpl_DataSharingFestival.pdf)).

---

### Hvor koden og dokumentasjonen ligger

Alt ligger åpent på [code.europa.eu/simpl/simpl-open](https://code.europa.eu/simpl/simpl-open). Kodebasen flyttes nå fra en gammel struktur under «development» til en struktur der prosjektene er ordnet etter kapabilitetskartet. I overgangsperioden kan en komponent ligge begge steder. Se [Finn fram i Simpl-dokumentasjonen](../finn-fram/).

---

### Vurdering av modenhet

*Dette er vår vurdering, ikke programmets.* Simpl-Open leveres jevnlig og har en tydelig arkitektur. Grunnleggende styring har vært med siden MVP: myndighetsrollen, opptak av deltakere og inngåelse av bruksavtaler. Forvaltning av kontrakter, policyer, samtykke og revisjon, og håndheving av kontrakter, kommer først i 5.0 ([utviklingsstatus](https://simpl-programme.ec.europa.eu/dashboard/development-status)). Vi kjenner i hovedsak til bruk i Simpl-Live og i testmiljøer. Programvaren er derfor best egnet til å lære, teste og gjenbruke komponenter, og mindre egnet som ferdig plattform for et nytt norsk data space i dag.
