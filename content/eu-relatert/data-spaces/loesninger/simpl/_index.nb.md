---
id: 081831ee-073c-4ef4-b443-ea3f811877b8
title: SIMPL
weight: 20
lastmod: 2026-11-17T00:20:21+01:00
last_editor: Erik Hagen

---
*Simpl er EU-kommisjonens satsing for å få fart på utviklingen av europeiske data spaces. Kjernen er Simpl-Open, åpen kildekode som tar i bruk de felles standardene og mønstrene for datadeling. Simpl er ikke ment å være den eneste løsningen. Arkitekturen er føderert, og andre løsninger som følger de samme standardene, skal kunne samvirke med den.*

Programmet har tre deler: programvaren Simpl-Open, test- og sandkassemiljøet Simpl-Labs, og Simpl-Live, som hjelper utvalgte data spaces med å ta programvaren i bruk.

Opplysninger om status på disse sidene gjelder per 16. november 2026 og er hentet fra kildene som er lenket til. Simpl endrer seg raskt, så sjekk kildene før du bruker opplysningene videre.

---

### De tre delene

| Del | Hva det er | Status (november 2026) |
|---|---|---|
| [Simpl-Open](simpl-open/) | Åpen kildekode (EUPL 1.2) med modulære komponenter for datadeling i data spaces | Versjon 4.0 kom i juli 2026 og 4.1 i november 2026. Versjon 5.0 er planlagt |
| [Simpl-Labs](simpl-labs/) | Sandkasse for å prøve ut et data space, og testmiljø for interoperabilitet mot Simpl-Open | Under oppbygging. Gjennomføringsfasen startet i februar 2026 |
| [Simpl-Live](simpl-live/) | Støtte til utvalgte europeiske data spaces: først en forstudie, deretter hjelp med å implementere Simpl-Open | Seks data spaces i wave 1 (bølge 1) og fem initiativer i wave 2. Gjennomføringen av wave 1 startet i februar 2026 |

Hvordan dette kan være relevant for norske aktører, er omtalt under [Relevans for Norge](relevans-for-norge/). Under [Finn fram i Simpl-dokumentasjonen](finn-fram/) finner du en veiledning til arkitekturdokumentasjonen, som nå i hovedsak ligger som Markdown-filer i GitLab.

---

### Hvordan Simpl henger sammen med resten av data space-landskapet

Simpl er ikke et data space i seg selv. Det er verktøykassen data spaces kan bygge på. Data Spaces Support Centre (DSSC) lager veiledningen, blant annet Blueprint, Toolbox og Glossary, mens Simpl-Open er programvare der deler av denne veiledningen kan tas i bruk og testes i praksis. Ifølge DSSC er Simpl-Open ett alternativ blant flere, og man kan bruke hele løsningen eller bare enkeltkomponenter ([DSSC, oktober 2026](https://dssc.eu/articles/from-guidance-to-deployment-how-simpl-helps-put-dsscs-guidance-into-practice)).

Teknisk bygger Simpl-Open på de samme byggeklossene som resten av feltet samles om: Dataspace Protocol, Eclipse Dataspace Connector (EDC), ODRL-policyer, RDF og verifiserbare attester. Se [Simpl-Open](simpl-open/) for detaljer.

---

### Én løsning blant flere

Simpl-Open er laget for å samvirke med andre løsninger, ikke for å erstatte dem. Det står i Simpls egne [arkitekturprinsipper](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/architecture-principles.md):

- **Føderasjon:** Deltakerne er selvstendige enheter som er bundet sammen av felles standarder, rammeverk og juridiske regler, og tjenesteeierne skal ha størst mulig selvstendighet.
- **Interoperabilitet:** Arkitekturen skal beskrive hvordan deltakerne deler ressurser, uten å forutsette hvordan hver deltaker har bygd sin egen del.
- **Modularitet:** Komponenter kan byttes ut eller legges til uten at resten påvirkes, og en deltaker kan ta i bruk bare de komponentene den trenger.

Simpl-programmet sier selv at initiativer kan bruke enkeltkomponenter til å bygge egne løsninger, eller bruke Simpl-Open som grunnlag ([Simpl-programmet](https://simpl-programme.ec.europa.eu/dashboard/about-simpl)). DSSC omtaler Simpl-Open som ett alternativ blant flere. [Simpl-Labs](simpl-labs/) skal også teste samvirke med data spaces som allerede finnes.

*Vår vurdering:* I praksis fungerer Simpl-Open som en referanseimplementasjon. Den viser hvordan standardene henger sammen, og gir et felles sted å teste mot. For nasjonale løsninger er spørsmålet derfor ikke Simpl eller egne løsninger, men om egne løsninger samvirker med Simpl. Se [Relevans for Norge](relevans-for-norge/).

---

### Kommende hendelser

- **9. desember 2026, Brussel:** Simpl Hackathon 2026, der deltakerne installerer og tester Simpl-Open. Samme dag har brukergruppen for Simpl-Labs (User Interest Group) oppstartsmøte. Digdir og IFE er representert i brukergruppen.
- **10. desember 2026, Brussel og digitalt:** Simpl Annual Community Event, det tredje i rekken ([Simpl-programmet, arrangementer](https://simpl-programme.ec.europa.eu/events)).

---

### Kilder

- [Simpl-programmet (simpl-programme.ec.europa.eu)](https://simpl-programme.ec.europa.eu/dashboard/about-simpl)
- [Simpl-Open på code.europa.eu](https://code.europa.eu/simpl/simpl-open)
- [Simpl på LinkTree (EU-kommisjonen)](https://linktr.ee/ec_simpl)
