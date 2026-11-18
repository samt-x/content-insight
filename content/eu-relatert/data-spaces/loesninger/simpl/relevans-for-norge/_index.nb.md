---
id: e99c3bf9-6c4d-4ebf-bd9a-db18df23dd38
title: Relevans for Norge
weight: 60
status: Pågår
lastmod: 2026-11-18T22:07:52+01:00
last_editor: Erik Hagen

---
{{< warning >}}◐ <strong>I arbeid.</strong> Denne siden skrives om og er ikke ferdig vurdert. Den bør ikke brukes som grunnlag ennå. Kapitler merket «Kommer» har foreløpig bare stikkord.{{< /warning >}}

*Hva kan Simpl bety for Norge? Denne siden ser på mulighetene, på konsekvensene for Norges digitale fellesinfrastruktur og for utvalgte aktører, og på forhold det er lurt å være klar over.*

Siden er i hovedsak en faglig vurdering. Faktaopplysninger har kildehenvisning. Resten er våre vurderinger.

---

### Muligheter for Norge

Simpl bygger på en føderert arkitektur der hver deltaker beholder sine egne løsninger, så lenge de følger de felles standardene (se [Én løsning blant flere](../om-simpl/#én-løsning-blant-flere)). Det gir norske løsninger flere muligheter:

- **Utbredelse:** Fellesløsninger som følger de samme standardene, kan bli Norges tilkoblingspunkt til europeiske data spaces, og nå lenger ut enn i dag, også utenfor Norge. Eksempler er tjenester bygd med Altinn Studio, Altinn Autorisasjon, ID-porten og lommeboken, og data.norge.no.
- **Arena:** I [Simpl-Labs](../simpl-labs/) kan vi vise at norske løsninger samvirker, og påvirke kravene mens de formes.

---

### Konsekvenser for Norge

#### Overordnet: Norges digitale fellesinfrastruktur

Simpl-Open er den mest konkrete europeiske implementasjonen av byggeklossene som de europeiske data spacene samles om: Dataspace Protocol, connector, ODRL-policyer, verifiserbare attester og DCAT-baserte kataloger. For norske fellesløsninger er spørsmålet derfor ikke om de skal forholde seg til disse standardene, men hvordan og når.

- **Samsvar med de felles kravene:** Løsningene må følge standardene for datadeling (Dataspace Protocol, ODRL, DCAT-AP) og kravene til identitet og tillitstjenester (eIDAS 2.0, EUDI-lommeboken, verifiserbare attester). Det arbeidet må gjøres uansett, med eller uten Simpl.
- **Gjenbruk av åpen kildekode:** Komponentene er lisensiert under EUPL 1.2 og kan gjenbrukes i norske løsninger uten at man tar i bruk hele Simpl.

[Simpl-Labs](../simpl-labs/) gjør det mulig å teste dette mot det europeiske oppsettet før det blir et krav fra en sektor.

Hvilke fellesløsninger som bør analyseres, og hvilke spørsmål som må avklares, står i et eget utkast under Arkitektur: [Fellesløsninger og europeiske krav](/arkitektur/loesningslandskap/fellesloesninger-og-europeiske-krav/). Det dekker også eIDAS 2.0 og Once-Only, ikke bare data spaces.

*Kommer.* Stikkord: et samlet blikk på Norges digitale fellesinfrastruktur (Digital Public Infrastructure, DPI) i lys av Simpl.

#### For utvalgte aktører

**Digdir**

- **Tilgangsstyring og autorisasjon (Altinn):** Altinn Autorisasjon bygger på XACML, mens Simpl og andre data spaces uttrykker bruksvilkår i ODRL. Det trengs en kobling mellom de to modellene hvis norske tilganger skal kunne gjelde i europeiske data spaces.
- **Identitet og lommebok (ID-porten, EUDI-lommebok):** Simpl-Open bruker verifiserbare attester både til identifisering og til avtaleinngåelse, og har valgt en OID4VP-verifikator. Det knytter Simpl direkte til arbeidet med digitale lommebøker under eIDAS 2.0.
- **Datakataloger (data.norge.no):** Simpl-Open bruker RDF-baserte beskrivelser og planlegger støtte for DCAT-AP. Norske kataloger følger DCAT-AP-NO, og samsvaret mellom dem bør testes.
- *Kommer.* Stikkord: i større grad bygge på gjenbruk av og samarbeid om åpen kildekode.

**KS Digital**

- **Kommunale fellesløsninger:** Kommunene blir deltakere i flere data spaces, blant annet for smarte samfunn (SCDS), mobilitet og energi. Fellesløsninger som KS Fiks kan bli det naturlige tilkoblingspunktet for kommunene, i stedet for at hver kommune kobler seg på hvert data space.

**Novari, STAF, Sikt, HK-dir og SSB**

*Kommer.* Aktører som er særlig relevante i SAMT-BU.

#### Totalforsvaret og Forsvaret

Forsvaret lanserte *Forsvarets datasentriske arkitektur* (FDSA), også kalt «datagrunnloven», under Arendalsuka i august 2026. Arkitekturen er utviklet sammen med NATO, NSM og FFI. Prinsippene er at data skal holdes atskilt fra systemene, at regler for sikkerhet, tilgang og deling skal følge dataene, at teknologien skal kunne byttes ut, og at grensesnittene skal være standardiserte. FDSA styrer først og fremst Forsvarets egne anskaffelser, men prinsippene er åpne slik at sivile aktører som telekom, transport og kommuner kan dele data med Forsvaret i en krise ([Digital Norway, august 2026](https://digitalnorway.com/aktuelt/forsvaret-lanserer-ny-datagrunnlov-grunnmuren-for-et-digitalt-totalforsvar)). NATO har publisert en egen [datasentrisk referansearkitektur](https://nhqc3s.hq.nato.int/apps/DCRA_Report/index.html).

På EU-siden bygger Det europeiske forsvarsbyrået (EDA) et eget forsvarsdatarom, European Defence Artificial Intelligence Data Space (DAIDS). Det skal være i ordinær bruk rundt 2029–2030 ([Computing](https://www.computing.co.uk/news/2026/security/eu-hopes-to-sever-defence-data); [Sopra Steria, april 2025](https://www.soprasteria.be/newsroom/press-releases/details/european-defence-agency-select-sopra-steria-CDE-and-CEA-for-framework-contract)). Vi har ikke funnet noen kobling mellom DAIDS og Simpl.

*Vår vurdering:* Prinsippene i FDSA passer godt med tankegangen i data spaces. At regler skal følge dataene, tilsvarer for eksempel ODRL-policyer som følger med dataene gjennom en connector. Totalforsvaret er avhengig av datadeling med sivile aktører, og disse vil i økende grad være koblet til europeiske data spaces. Simpl-Labs kan derfor være en nøytral, sivil og ugradert arena for å teste datadeling mellom sivile og militære aktører, uten at noen binder seg til en plattform.

Simpl er ikke laget for graderte data. For gradert informasjon gjelder fortsatt NATO-standarder og graderingskrav, og DAIDS er et eget spor.

---

### Forhold å være klar over

#### Status og utbredelse

Simpl-Live omfatter 11 data spaces og initiativer, seks i wave 1 og fem i wave 2 ([arbeidsprogrammet for Digital Europe 2025–2027, uoffisiell konsolidert utgave](https://www.ffg.at/sites/default/files/2026-05/DIGITAL%20WP%2025-27_Unofficial%20version%20with%20amendments.pdf), s. 30). Programmet deler gjennomføringen i fem trinn: revisjon av krav, teknisk validering, akseptanse, operativ drift og vedlikehold ([Simpl-programmet, august 2026](https://simpl-programme.ec.europa.eu/system/files/2026-08/Simpl_Live_Implementation_Phase_Visual.pdf)).

- **Wave 1:** Integrasjonen av Simpl-Open startet i februar 2026. I mai 2026 var de første workshopene holdt for å revidere krav og scenarier ([Simpl, mai 2026](https://ec.europa.eu/newsroom/simpl/redirection/item/940026)), og i oktober 2026 var integrasjonen i gang i alle seks ([Simpl, oktober 2026](https://ec.europa.eu/newsroom/simpl/items/959708/en)). Den er planlagt ferdig i oktober 2027 ([faktaark for Simpl-Live](https://simpl-programme.ec.europa.eu/system/files/2026-05/Factsheet_Simpl-Live_A4%2016.pdf)).
- **Wave 2:** Forstudiene er ferdige, og konklusjonene ble publisert i juni 2026 ([dokumentbiblioteket](https://simpl-programme.ec.europa.eu/topic/simpl-live-document-library)). Vi har ikke funnet at implementeringen har startet.
- **Utenfor Simpl-Live:** Flere utlysninger i Digital Europe ber om at løsningene skal være kompatible med Simpl, blant annet for genomdata, kulturarv og helse ([arbeidsprogrammet](https://www.ffg.at/sites/default/files/2026-05/DIGITAL%20WP%2025-27_Unofficial%20version%20with%20amendments.pdf)). Anbudet for driften av EOSC EU Node krever integrasjon med Simpl, «subject to availability» ([anbudet, 2026](https://digital-strategy.ec.europa.eu/en/funding/managed-services-eosc-eu-node-2026)).

Vi har ikke funnet noen kilde som sier at Simpl-Open er i operativ drift i et data space ennå.

*Vår vurdering:* Simpl er fortsatt i en tidlig fase. Det betyr at norske aktører kan være med og forme hvordan løsningen tas i bruk, og at kravene om Simpl-kompatibilitet i Digital Europe allerede gjør Simpl relevant for norske deltakere i slike prosjekter.

#### Modenhet og framdrift

Simpl-Open kommer i jevnlige versjoner: proof of concept i juli 2024, MVP i januar 2025, versjon 4.0 i juli 2026 og 4.1 i november 2026. Versjon 5.0 er planlagt til 4. kvartal 2026 (se [Simpl-Open](../simpl-open/)). Grunnleggende styring har vært med siden MVP, mens forvaltning og håndheving av kontrakter, policyer og samtykke kommer i 5.0.

Framdriften har vært langsommere enn først planlagt. I 2023 skulle MVP komme senest ved utgangen av 2024 ([Kommisjonen, oktober 2023](https://digital-strategy.ec.europa.eu/en/node/10891/printable/pdf)). Den kom 30. januar 2025 ([Simpl-Open-veikartet, mai 2025](https://simpl-programme.ec.europa.eu/system/files/2025-05/Simpl-Open%20Roadmap%20May%20Update%20and%20June%20Release%20Details%202025.pdf)). Simpl-Labs var i mars 2026 varslet til høsten 2026, mens DSSC i oktober 2026 omtalte interoperabilitetstesting i Labs som noe som kommer i 2027 (se [Simpl-Labs](../simpl-labs/)).

Programmet er videreført med 52,9 millioner euro for 2025–2027 ([arbeidsprogrammet](https://www.ffg.at/sites/default/files/2026-05/DIGITAL%20WP%2025-27_Unofficial%20version%20with%20amendments.pdf), s. 31–32).

#### Kritikk

*Kommer.* Stikkord: hva en europeisk referanseimplementasjon betyr for markedsløsninger som bygger på de samme åpne standardene. Styringen av programmet og veikartet ligger hos Kommisjonen.

#### Fellesløsningenes plass

*Kommer.* Stikkord: forholdet mellom Simpl og Norges eksisterende fellesløsninger. Arkitekturprinsippene i Simpl er føderasjon, og samvirke uten krav om hvordan hver deltaker har bygd sin del (se [Én løsning blant flere](../om-simpl/#én-løsning-blant-flere)). Den som ikke er med og former standardene og kravene, må tilpasse seg dem senere.

---

### Mulige neste steg

- Delta i brukergruppen for Simpl-Labs fra første wave, og ta med konkrete norske testbehov. Det er tidlig at prioriteringene settes (se [Simpl-Labs](../simpl-labs/)).
- Teste koblingen mellom Altinn-autorisasjon og ODRL, og mellom lommebok og verifiserbare attester, i Simpl-Labs.
- Utforske en felles sivil–militær test av datadeling i totalforsvaret sammen med Forsvaret.
