---
id: e99c3bf9-6c4d-4ebf-bd9a-db18df23dd38
title: Relevans for norsk digital infrastruktur
weight: 60
lastmod: 2026-11-24T23:58:02+01:00
last_editor: Erik Hagen

---
*Hva kan Simpl bety for norsk digital infrastruktur? Denne siden ser på hva Simpl betyr for infrastrukturen samlet, for utvalgte leverandører av fellesløsninger og for totalforsvaret, og på forhold det er lurt å være klar over.*

Siden er i hovedsak en faglig vurdering. Faktaopplysninger har kildehenvisning. Resten er våre vurderinger, og de er merket slik.

---

## Kort fortalt

1. **Standardene kommer uansett.** De europeiske data spacene samles om de samme byggeklossene: Dataspace Protocol, ODRL-policyer, DCAT-baserte kataloger og verifiserbare attester. Simpl-Open er den mest konkrete europeiske implementasjonen av dem. Norske fellesløsninger må forholde seg til disse standardene, med eller uten Simpl.
2. **Simpl blir et krav i EU-finansierte prosjekter.** Flere utlysninger i Digital Europe ber om Simpl-kompatible løsninger, og driften av EOSC EU Node skal integreres med Simpl. Det gjør Simpl relevant for norske deltakere i slike prosjekter allerede nå.
3. **Vinduet for å påvirke er nå.** Simpl er i en tidlig fase. Ingen av initiativene i Simpl-Live var kommet til operativ drift i august 2026, og Simpl-Labs formes nå. Brukergruppen for Simpl-Labs har oppstartsmøte i Brussel 9. desember 2026, og Digdir er representert der.
4. **Norske løsninger kan nå lenger.** Simpl er føderert: hver deltaker beholder sine egne løsninger så lenge de følger de felles standardene. Norske fellesløsninger kan dermed bli Norges tilkoblingspunkt til europeiske data spaces.
5. **Åpen kildekode i et større bilde.** Simpl-Open er en del av EUs satsing på åpen kildekode og digitale fellesgoder. Vi kan gjenbruke komponenter, bidra til videreutviklingen, og prøve egne løsninger mot alternativene: er de gode, kan andre bygge videre på dem; finnes det bedre alternativer, kan vi heller slutte oss til dem.
6. **Innsatsen er liten og fleksibel.** Deltakelse i brukergruppen handler om tilbakemeldinger, testing og møter av og til, tilpasset den enkeltes kapasitet. Til gjengjeld får vi tidlig tilgang til et felles europeisk testmiljø.

Kildene står i kapitlene under.

---

## Norsk digital infrastruktur

Simpl bygger på en føderert arkitektur der hver deltaker beholder sine egne løsninger, så lenge de følger de felles standardene (se [Én løsning blant flere](../om-simpl/#én-løsning-blant-flere)). Det får følger for hele den norske digitale fellesinfrastrukturen, ikke bare for enkeltløsninger.

### Felles standarder kommer uansett

Simpl-Open er den mest konkrete europeiske implementasjonen av byggeklossene som de europeiske data spacene samles om: Dataspace Protocol, connector, ODRL-policyer, verifiserbare attester og DCAT-baserte kataloger. For norske fellesløsninger er spørsmålet derfor ikke om de skal forholde seg til disse standardene, men hvordan og når.

Løsningene må følge standardene for datadeling (Dataspace Protocol, ODRL, DCAT-AP) og kravene til identitet og tillitstjenester (eIDAS 2.0, EUDI-lommeboken, verifiserbare attester). Det arbeidet må gjøres uansett, med eller uten Simpl.

### Fellesløsningenes plass

Arkitekturprinsippene i Simpl er føderasjon, og samvirke uten krav om hvordan hver deltaker har bygd sin del (se [Én løsning blant flere](../om-simpl/#én-løsning-blant-flere)). Norske fellesløsninger trenger derfor ikke erstattes av Simpl, men må kunne samvirke med det.

*Vår vurdering:* Den som er med og former standardene og kravene, kan sørge for at de passer med egne løsninger. Den som ikke er med, må tilpasse seg dem senere.

Hvilke fellesløsninger som bør analyseres, og hvilke spørsmål som må avklares, står i et eget utkast under Arkitektur: [Fellesløsninger og europeiske krav](/arkitektur/loesningslandskap/fellesloesninger-og-europeiske-krav/). Det dekker også eIDAS 2.0 og Once-Only, ikke bare data spaces.

### Muligheter

- **Utbredelse:** Fellesløsninger som følger de samme standardene, kan bli Norges tilkoblingspunkt til europeiske data spaces, og nå lenger ut enn i dag, også utenfor Norge. Eksempler er tjenester bygd med Altinn Studio, Altinn Autorisasjon, ID-porten og lommeboken, og data.norge.no.
- **Påvirkning:** I [brukergruppen for Simpl-Labs](../simpl-labs/#brukergruppen-user-interest-group) kan vi melde inn norske testbehov og påvirke hva Labs skal tilby, mens tjenesten fortsatt formes.
- **Uttesting før det blir krav:** I [Simpl-Labs](../simpl-labs/) kan vi teste om norske løsninger samvirker med det europeiske oppsettet, før en sektor eller en utlysning krever det.

### Åpen kildekode i et større bilde

Komponentene i Simpl-Open er lisensiert under EUPL 1.2 og kan gjenbrukes i norske løsninger uten at man tar i bruk hele Simpl. Simpl tar også imot bidrag utenfra, både kode, vurderinger av krav og arkitektur, feilmeldinger og strategisk samarbeid. Programmet lover å svare på bidrag innen tre virkedager ([Simpl-programmet: How to contribute](https://simpl-programme.ec.europa.eu/dashboard/how-contribute)).

EUs strategi for åpen kildekode fra juni 2026 nevner Simpl som et av EUs eksisterende tiltak, med mellomvare for europeiske data spaces. Strategien skal blant annet gjennomføres gjennom Digital Commons EDIC ([EU Open Source Strategy](https://digital-strategy.ec.europa.eu/en/policies/open-source-strategy)). Konsortiet ble lansert i desember 2025, med Frankrike, Tyskland, Nederland og Italia som medlemmer, og skal samordne nasjonal utvikling av åpne, samvirkende og gjenbrukbare løsninger som kan deles på tvers av landegrenser ([Kommisjonen, desember 2025](https://digital-strategy.ec.europa.eu/en/news/digital-commons-edic-launches-advance-europes-technological-sovereignty)). Internasjonalt finnes beslektede initiativer, blant annet Digital Public Goods Alliance og GovStack.

*Vår vurdering:* Vi har ikke funnet at Simpl er formelt knyttet til Digital Public Goods Alliance eller GovStack, men Simpl bygger på den samme tankegangen: felles digital infrastruktur som åpen kildekode, som flere land kan bruke og videreutvikle sammen. For Norge går det begge veier:

- **Gjenbruk:** Norske fellesløsninger kan ta i bruk komponenter som andre har utviklet.
- **Videreutvikling sammen med andre:** Er norske løsninger gode, kan de få bidrag og brukere utenfor Norge. Et eksempel er Digdirs løsninger for beskrivelser av datasett og offentlige tjenester på data.norge.no, som bygger på de europeiske standardene DCAT-AP og CPSV-AP.
- **Sammenligning:** Viser testene at andre løsninger har et bedre konsept eller har kommet lenger, kan det være riktigere å slutte seg til samarbeidet om dem enn å videreutvikle alt selv.

Simpl-Labs, med samsvarstester mot Simpl-Open, er et sted der en slik sammenligning kan gjøres. Selve samarbeidet om koden skjer i prosjektenes egne fellesskap, for eksempel i Simpl-Open eller i SEMIC, som forvalter DCAT-AP og CPSV-AP.

---

## Leverandører av fellesløsninger

Muligheter og konsekvenser henger sammen for hver leverandør, og står derfor samlet per aktør.

### Digdir

- **Tilgangsstyring og autorisasjon (Altinn):** Altinn Autorisasjon bygger på XACML, mens Simpl og andre data spaces uttrykker bruksvilkår i ODRL. Det trengs en kobling mellom de to modellene hvis norske tilganger skal kunne gjelde i europeiske data spaces.
- **Identitet og lommebok (ID-porten, EUDI-lommebok):** Simpl-Open bruker verifiserbare attester både til identifisering og til avtaleinngåelse, og har valgt en OID4VP-verifikator. Det knytter Simpl direkte til arbeidet med digitale lommebøker under eIDAS 2.0.
- **Datakataloger (data.norge.no):** Simpl-Open bruker RDF-baserte beskrivelser og planlegger støtte for DCAT-AP. Norske kataloger følger DCAT-AP-NO, og samsvaret mellom dem bør testes.
- **Åpen kildekode:** *Vår vurdering:* Digdir kan gjenbruke komponenter fra Simpl-Open, la egne løsninger møte alternativene i Simpl-Labs, og samarbeide med andre om videreutviklingen der det lønner seg (se [Åpen kildekode i et større bilde](#åpen-kildekode-i-et-større-bilde)).

### KS Digital

- **Kommunale fellesløsninger:** Kommunene blir deltakere i flere data spaces, blant annet for smarte samfunn (SCDS), mobilitet og energi. Fellesløsninger som KS Fiks kan bli det naturlige tilkoblingspunktet for kommunene, i stedet for at hver kommune kobler seg på hvert data space.

---

## Totalforsvaret og Forsvaret

Forsvaret lanserte *Forsvarets datasentriske arkitektur* (FDSA), også kalt «datagrunnloven», under Arendalsuka i august 2026. Arkitekturen er utviklet sammen med NATO, NSM og FFI. Prinsippene er at data skal holdes atskilt fra systemene, at regler for sikkerhet, tilgang og deling skal følge dataene, at teknologien skal kunne byttes ut, og at grensesnittene skal være standardiserte. FDSA styrer først og fremst Forsvarets egne anskaffelser, men prinsippene er åpne slik at sivile aktører som telekom, transport og kommuner kan dele data med Forsvaret i en krise ([Digital Norway, august 2026](https://digitalnorway.com/aktuelt/forsvaret-lanserer-ny-datagrunnlov-grunnmuren-for-et-digitalt-totalforsvar)). NATO har publisert en egen [datasentrisk referansearkitektur](https://nhqc3s.hq.nato.int/apps/DCRA_Report/index.html).

På EU-siden bygger Det europeiske forsvarsbyrået (EDA) et eget forsvarsdatarom, European Defence Artificial Intelligence Data Space (DAIDS). Det skal være i ordinær bruk rundt 2029–2030 ([Computing](https://www.computing.co.uk/news/2026/security/eu-hopes-to-sever-defence-data); [Sopra Steria, april 2025](https://www.soprasteria.be/newsroom/press-releases/details/european-defence-agency-select-sopra-steria-CDE-and-CEA-for-framework-contract)). Vi har ikke funnet noen kobling mellom DAIDS og Simpl.

*Vår vurdering:* Prinsippene i FDSA passer godt med tankegangen i data spaces. At regler skal følge dataene, tilsvarer for eksempel ODRL-policyer som følger med dataene gjennom en connector. Totalforsvaret er avhengig av datadeling med sivile aktører, og disse vil i økende grad være koblet til europeiske data spaces. Simpl-Labs kan derfor være en nøytral, sivil og ugradert arena for å teste datadeling mellom sivile og militære aktører, uten at noen binder seg til en plattform.

Simpl er ikke laget for graderte data. For gradert informasjon gjelder fortsatt NATO-standarder og graderingskrav, og DAIDS er et eget spor.

---

## Forhold å være klar over

### Status og utbredelse

Simpl-Live omfatter 11 data spaces og initiativer, seks i wave 1 og fem i wave 2 ([arbeidsprogrammet for Digital Europe 2025–2027, uoffisiell konsolidert utgave](https://www.ffg.at/sites/default/files/2026-05/DIGITAL%20WP%2025-27_Unofficial%20version%20with%20amendments.pdf), s. 30). Programmet deler gjennomføringen i fem trinn: revisjon av krav, teknisk validering, akseptanse, operativ drift og vedlikehold ([Simpl-programmet, august 2026](https://simpl-programme.ec.europa.eu/system/files/2026-08/Simpl_Live_Implementation_Phase_Visual.pdf)).

- **Wave 1:** Integrasjonen av Simpl-Open startet i februar 2026. I mai 2026 var de første workshopene holdt for å revidere krav og scenarier ([Simpl, mai 2026](https://ec.europa.eu/newsroom/simpl/redirection/item/940026)), og i oktober 2026 var integrasjonen i gang i alle seks ([Simpl, oktober 2026](https://ec.europa.eu/newsroom/simpl/items/959708/en)). Den er planlagt ferdig i oktober 2027 ([faktaark for Simpl-Live](https://simpl-programme.ec.europa.eu/system/files/2026-05/Factsheet_Simpl-Live_A4%2016.pdf)). Ifølge programmets milepælsrapport, sist oppdatert 24. august 2026, var bare språkdataspacet (LDS) ferdig med revisjonen og i gang med teknisk validering. De fem andre var fortsatt i første trinn, og ingen var kommet til akseptanse eller drift (se [Simpl-Live](../simpl-live/#status-for-wave-1-per-initiativ)).
- **Wave 2:** Forstudiene er ferdige, og konklusjonene ble publisert i juni 2026 ([dokumentbiblioteket](https://simpl-programme.ec.europa.eu/topic/simpl-live-document-library)). Vi har ikke funnet at implementeringen har startet.
- **Utenfor Simpl-Live:** Flere utlysninger i Digital Europe ber om at løsningene skal være kompatible med Simpl, blant annet for genomdata, kulturarv og helse ([arbeidsprogrammet](https://www.ffg.at/sites/default/files/2026-05/DIGITAL%20WP%2025-27_Unofficial%20version%20with%20amendments.pdf)). Anbudet for driften av EOSC EU Node krever integrasjon med Simpl, «subject to availability» ([anbudet, 2026](https://digital-strategy.ec.europa.eu/en/funding/managed-services-eosc-eu-node-2026)).

Utenfor Simpl-Live har pilotene for smarte samfunn testet Simpl-Open på egen hånd. Én av dem oppgir selv at Valencia har en Simpl-node i drift, men det har vi ikke kunnet etterprøve (se [Uttesting utenfor Simpl-Live](../simpl-live/#uttesting-utenfor-simpl-live)). Ellers har vi ikke funnet noen kilde som sier at Simpl-Open er i operativ drift i et data space ennå.

*Vår vurdering:* Simpl er fortsatt i en tidlig fase. Det betyr at norske aktører kan være med og forme hvordan løsningen tas i bruk, og at kravene om Simpl-kompatibilitet i Digital Europe allerede gjør Simpl relevant for norske deltakere i slike prosjekter.

### Modenhet og framdrift

Simpl-Open kommer i jevnlige versjoner: proof of concept i juli 2024, MVP i januar 2025, versjon 4.0 i juli 2026 og 4.1 i november 2026. Versjon 5.0 er planlagt til 4. kvartal 2026 (se [Simpl-Open](../simpl-open/)). Grunnleggende styring har vært med siden MVP, mens forvaltning og håndheving av kontrakter, policyer og samtykke kommer i 5.0. Flere av disse styringsfunksjonene er skjøvet omtrent ett år siden veikartene fra 2025. Samtykke var for eksempel først planlagt fra 3. kvartal 2025 (se [Endringer i planen over tid](../simpl-open/#endringer-i-planen-over-tid)).

Framdriften har vært langsommere enn først planlagt. I 2023 skulle MVP komme senest ved utgangen av 2024 ([Kommisjonen, oktober 2023](https://digital-strategy.ec.europa.eu/en/node/10891/printable/pdf)). Den kom 30. januar 2025 ([Simpl-Open-veikartet, mai 2025](https://simpl-programme.ec.europa.eu/system/files/2025-05/Simpl-Open%20Roadmap%20May%20Update%20and%20June%20Release%20Details%202025.pdf)). Simpl-Labs var i mars 2026 varslet til høsten 2026, mens DSSC i oktober 2026 omtalte interoperabilitetstesting i Labs som noe som kommer i 2027 (se [Simpl-Labs](../simpl-labs/)).

Programmet er videreført med 52,9 millioner euro for 2025–2027 ([arbeidsprogrammet](https://www.ffg.at/sites/default/files/2026-05/DIGITAL%20WP%2025-27_Unofficial%20version%20with%20amendments.pdf), s. 31–32).

### Simpl og andre løsninger for data spaces

Simpl-Open er ikke den eneste tekniske løsningen for data spaces. DSSC sier det selv ([DSSC, oktober 2026](https://dssc.eu/articles/from-guidance-to-deployment-how-simpl-helps-put-dsscs-guidance-into-practice)), og Kommisjonen skrev i 2023 at Simpl bevisst holder seg unna sektorspesifikke datatjenester, og at Gaia-X, IDSA og Eclipse følges med stor interesse ([Kommisjonen, oktober 2023](https://digital-strategy.ec.europa.eu/en/node/10891/printable/pdf)). IDSA omtaler Simpl som en bruker av sine standarder ([IDSA](https://internationaldataspaces.org/from-idsa-standards-to-simpl-solutions/)).

En fagfellevurdert artikkel fra april 2026 vurderer modenheten til Simpl som klart lavere enn i Eclipse Tractus-X, som brukes i bilindustriens data space Catena-X ([Paz m.fl., JISBD 2026](https://hdl.handle.net/11705/JISBD/2026/168)). To av forfatterne arbeider selv med Tractus-X.

*Vår vurdering:* Det taler for å bruke Simpl-Labs til å teste samvirke mellom flere løsninger, ikke for å binde seg til én. Styringen av programmet og veikartet ligger hos Kommisjonen, og nettopp derfor er det en fordel å være med der prioriteringene settes.

---

## Mulige neste steg

- Delta i brukergruppen for Simpl-Labs fra første wave, med oppstart i Brussel 9. desember 2026, og ta med konkrete norske testbehov. Det er tidlig at prioriteringene settes (se [Simpl-Labs](../simpl-labs/#brukergruppen-user-interest-group)).
- Teste koblingen mellom Altinn-autorisasjon og ODRL, mellom lommebok og verifiserbare attester, og mellom DCAT-AP-NO og DCAT-AP, i Simpl-Labs.
- Samordne norsk deltakelse med Institutt for energiteknikk (IFE), som også er i brukergruppen og driver en egen sandkasse for data space-infrastruktur.
- Utforske en felles sivil–militær test av datadeling i totalforsvaret sammen med Forsvaret.
