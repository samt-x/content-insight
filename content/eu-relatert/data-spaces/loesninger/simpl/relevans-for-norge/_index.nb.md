---
id: e99c3bf9-6c4d-4ebf-bd9a-db18df23dd38
title: Relevans for Norge
weight: 40
lastmod: 2026-11-18T20:33:26+01:00
last_editor: Erik Hagen

---
*Hvorfor bør norske leverandører av fellesløsninger og sektorløsninger, og Forsvaret, følge med på Simpl? Denne siden samler argumentene, og også de viktigste innvendingene.*

Siden er i hovedsak en faglig vurdering. Faktaopplysninger har kildehenvisning. Resten er våre vurderinger.

---

### Mulighet, ikke trussel

Mange vil se Simpl som en konkurrent til norske fellesløsninger. Vi mener det er omvendt. Simpl bygger på en føderert arkitektur der hver deltaker beholder sine egne løsninger, så lenge de følger de felles standardene (se [Én løsning blant flere](../om-simpl/#én-løsning-blant-flere)).

- **Utbredelse:** Fellesløsninger som følger de samme standardene, kan bli Norges tilkoblingspunkt til europeiske data spaces, og nå lenger ut enn i dag, også utenfor Norge. Eksempler er tjenester bygd med Altinn Studio, Altinn Autorisasjon, ID-porten og lommeboken, og data.norge.no.
- **Forutsetning:** Løsningene må samsvare med de felles kravene: standardene for datadeling (Dataspace Protocol, ODRL, DCAT-AP) og kravene til identitet og tillitstjenester (eIDAS 2.0, EUDI-lommeboken, verifiserbare attester). Det arbeidet må gjøres uansett, med eller uten Simpl.
- **Arena:** I [Simpl-Labs](../simpl-labs/) kan vi vise at norske løsninger samvirker, og påvirke kravene mens de formes.

---

### Felles økosystem: fellesløsninger og sektorløsninger

Simpl-Open er den mest konkrete europeiske implementasjonen av byggeklossene som de europeiske data spacene samles om: Dataspace Protocol, connector, ODRL-policyer, verifiserbare attester og DCAT-baserte kataloger. For norske fellesløsninger er spørsmålet derfor ikke om de skal forholde seg til disse standardene, men hvordan og når.

- **Tilgangsstyring og autorisasjon (Digdir, Altinn):** Altinn Autorisasjon bygger på XACML, mens Simpl og andre data spaces uttrykker bruksvilkår i ODRL. Det trengs en kobling mellom de to modellene hvis norske tilganger skal kunne gjelde i europeiske data spaces.
- **Identitet og lommebok (ID-porten, EUDI-lommebok):** Simpl-Open bruker verifiserbare attester både til identifisering og til avtaleinngåelse, og har valgt en OID4VP-verifikator. Det knytter Simpl direkte til arbeidet med digitale lommebøker under eIDAS 2.0.
- **Datakataloger (data.norge.no):** Simpl-Open bruker RDF-baserte beskrivelser og planlegger støtte for DCAT-AP. Norske kataloger følger DCAT-AP-NO, og samsvaret mellom dem bør testes.
- **Kommunale fellesløsninger (KS Digital):** Kommunene blir deltakere i flere data spaces, blant annet for smarte samfunn (SCDS), mobilitet og energi. Fellesløsninger som KS Fiks kan bli det naturlige tilkoblingspunktet for kommunene, i stedet for at hver kommune kobler seg på hvert data space.
- **Gjenbruk av åpen kildekode:** Komponentene er lisensiert under EUPL 1.2 og kan gjenbrukes i norske løsninger uten at man tar i bruk hele Simpl.

[Simpl-Labs](../simpl-labs/) gjør det mulig å teste dette mot det europeiske oppsettet før det blir et krav fra en sektor.

Hvilke fellesløsninger som bør analyseres, og hvilke spørsmål som må avklares, står i et eget utkast under Arkitektur: [Fellesløsninger og europeiske krav](/arkitektur/loesningslandskap/fellesloesninger-og-europeiske-krav/). Det dekker også eIDAS 2.0 og Once-Only, ikke bare data spaces.

---

### Totalforsvaret og Forsvaret

Forsvaret lanserte *Forsvarets datasentriske arkitektur* (FDSA), også kalt «datagrunnloven», under Arendalsuka i august 2026. Arkitekturen er utviklet sammen med NATO, NSM og FFI. Prinsippene er at data skal holdes atskilt fra systemene, at regler for sikkerhet, tilgang og deling skal følge dataene, at teknologien skal kunne byttes ut, og at grensesnittene skal være standardiserte. FDSA styrer først og fremst Forsvarets egne anskaffelser, men prinsippene er åpne slik at sivile aktører som telekom, transport og kommuner kan dele data med Forsvaret i en krise ([Digital Norway, august 2026](https://digitalnorway.com/aktuelt/forsvaret-lanserer-ny-datagrunnlov-grunnmuren-for-et-digitalt-totalforsvar)). NATO har publisert en egen [datasentrisk referansearkitektur](https://nhqc3s.hq.nato.int/apps/DCRA_Report/index.html).

På EU-siden bygger Det europeiske forsvarsbyrået (EDA) et eget forsvarsdatarom, European Defence Artificial Intelligence Data Space (DAIDS). Det skal være i ordinær bruk rundt 2029–2030 ([Computing](https://www.computing.co.uk/news/2026/security/eu-hopes-to-sever-defence-data); [Sopra Steria, april 2025](https://www.soprasteria.be/newsroom/press-releases/details/european-defence-agency-select-sopra-steria-CDE-and-CEA-for-framework-contract)). Vi har ikke funnet noen kobling mellom DAIDS og Simpl.

*Vår vurdering:* Prinsippene i FDSA passer godt med tankegangen i data spaces. At regler skal følge dataene, tilsvarer for eksempel ODRL-policyer som følger med dataene gjennom en connector. Totalforsvaret er avhengig av datadeling med sivile aktører, og disse vil i økende grad være koblet til europeiske data spaces. Simpl-Labs kan derfor være en nøytral, sivil og ugradert arena for å teste datadeling mellom sivile og militære aktører, uten at noen binder seg til en plattform.

---

### Innvendinger

- **Simpl kan fortrenge norske fellesløsninger.** Arkitekturprinsippene peker den andre veien: føderasjon, og samvirke uten krav om hvordan hver deltaker har bygd sin del. Risikoen er en annen: den som ikke er med og former standardene og kravene, må tilpasse seg dem senere. Det taler for å delta tidlig, ikke for å holde avstand.
- **Tungt og styrt fra Kommisjonen.** Simpl er et stort EU-program, og veikartet styres av Kommisjonens prioriteringer. Norske aktører kan få mer ut av å ta i bruk standardene (DSP, ODRL, DCAT-AP) direkte enn av å forholde seg til hele Simpl.
- **Begrenset modenhet.** De sentrale styringsfunksjonene kommer først i Simpl-Open 5.0, og når Simpl-Labs blir allment tilgjengelig, er uklart.
- **Uklar utbredelse.** Det finnes ingen offentlig oversikt over hvilke data spaces som faktisk kjører Simpl-Open i produksjon.
- **Ikke laget for graderte data.** For Forsvaret er Simpl i beste fall et sted å lære om sivil datadeling. NATO-standarder og graderingskrav gjelder fortsatt, og DAIDS er et eget spor.

Vår samlede vurdering er at Simpl er mest verdifullt som et signal om hvilken retning det går, og som en arena for testing, læring og påvirkning. Det er mindre verdifullt som en plattform norske aktører bør ta i bruk i dag.

---

### Mulige neste steg

- Delta i brukergruppen for Simpl-Labs fra første wave, og ta med konkrete norske testbehov. Det er tidlig at prioriteringene settes (se [Simpl-Labs](../simpl-labs/)).
- Teste koblingen mellom Altinn-autorisasjon og ODRL, og mellom lommebok og verifiserbare attester, i Simpl-Labs.
- Utforske en felles sivil–militær test av datadeling i totalforsvaret sammen med Forsvaret.
