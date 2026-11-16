---
id: 65e24b6e-d64e-4922-8147-1593f887bc02
title: Finn fram i Simpl-dokumentasjonen
weight: 50
lastmod: 2026-11-16T22:30:00+01:00
last_editor: Erik Hagen

---
*Arkitektur- og brukerdokumentasjonen for Simpl ligger nå som Markdown-filer i GitLab, uten noen egen publiseringsside. Denne siden er en veiledning til hvor du finner hva.*

---

### Slik er dokumentasjonen organisert

Simpl-programmet har flyttet dokumentasjonen fra Confluence til Git høsten 2026. GitLab brukes nå som en slags wiki: README-filene fungerer som inngangsportaler med en «Du er her»-sti øverst og lenker videre ned.

Strukturen følger kapabilitetskartet. Under [simpl-open](https://code.europa.eu/simpl/simpl-open) er det én gruppe for hver dimensjon: administration, data, integration, infrastructure, governance og security. I tillegg kommer cross-cutting, med blant annet installasjonsguide og brukerhåndbok, og foundations, med forretningsprosesser, ikke-funksjonelle krav og arkitektur. Den gamle strukturen under «development» fases ut, men i overgangsperioden kan innhold ligge begge steder.

---

### Inngangsportaler

| Portal | Innhold |
|---|---|
| [Simpl-Open](https://code.europa.eu/simpl/simpl-open) | Startsiden: hvordan repoene henger sammen, kom i gang |
| [Foundations](https://code.europa.eu/simpl/simpl-open/foundations) | Forretningsprosesser (BP01 og videre), ikke-funksjonelle krav, arkitektur |
| [Architecture](https://code.europa.eu/simpl/simpl-open/foundations/architecture) | Innholdsfortegnelse til all arkitekturdokumentasjon |
| [Installasjonsguide](https://code.europa.eu/simpl/simpl-open/cross-cutting/documentation/installation-guide) | Installasjon, versjonert per release |
| [Brukerhåndbok](https://code.europa.eu/simpl/simpl-open/cross-cutting/documentation/user-manual) | Konfigurasjon og drift |

---

### De viktigste arkitekturfilene

| Fil | Hva du finner |
|---|---|
| [description.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/description.md) | Generell introduksjon til Simpl og aktørene |
| [capability-map.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/capability-map.md) | Kapabilitetskartet: dimensjoner, kapabiliteter og tjenester |
| [architecture-principles.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/architecture-principles.md) | De ti arkitekturprinsippene |
| [architectural-patterns.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/architectural-patterns.md) | Arkitekturmønstre som går igjen |
| [agent-anatomy.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/agent-anatomy.md) | Deltakere på nivå 1 og 2 (Tier I/II), og hvordan en Simpl-tjeneste er bygd opp |
| [connector.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/connector.md) | Dataspace Protocol og connectoren |
| [identification-authentication-and-authorisation.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/identification-authentication-and-authorisation.md) | Identitet, autentisering og autorisasjon |
| [functional-architecture.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/functional-architecture.md) | Tjenestene i hver agent og hvordan de samvirker |
| [interface-catalogue.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/interface-catalogue.md) | Oversikt over API-er |
| [technology-choices.md](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/technology-choices.md) | Valgte åpen kildekode-teknologier |
| [adr/](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/adr/README.md) | Arkitekturbeslutninger (ADR-er) |
| [controlled_vocabulary/](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/controlled_vocabulary/README.md) | Kontrollert vokabular og ordliste |

---

### Hoveddokumentet D1.3.4

Den samlede arkitekturspesifikasjonen, *D1.3.4 Functional and Technical Architecture Specifications*, finnes fortsatt som [én stor Markdown-fil](https://code.europa.eu/simpl/simpl-open/foundations/architecture/-/blob/main/functional_and_technical_architecture_specifications/Functional-and-Technical-Architecture-Specifications.md) på rundt 18 800 linjer. Den ble sist endret i juli 2026 og kaller seg versjon 0.1. De mindre filene og ADR-ene oppdateres jevnlig og er derfor ofte nyere enn hoveddokumentet. Det gjelder særlig teknologivalg, grensesnitt og beslutninger.

---

### Tips

- Arkitekturmodellen ligger i ArchiMate-format (Archi med coArchi) i mappen «model» i arkitekturrepoet. Den kan åpnes i Archi.
- For å lese alt samlet er det enklest å klone arkitekturrepoet og åpne det i en Markdown-leser eller editor.
- Det gamle arkitekturrepoet ([simpl/simpl-open/architecture](https://code.europa.eu/simpl/simpl-open/architecture)) er arkivert. Siste versjon der er fra september 2025.
