# PERSBERICHT

## Bewindvoerderskantoor vernietigde bewijs binnen uren na sommatie — netwerk van 28 vennootschappen, gecoördineerde opschoningsactie door vijf kantoren, en geld van 250.000 kwetsbare Nederlanders loopt via Malta

**Embargo:** Geen — vrij voor publicatie
**Datum:** 6 maart 2026
**Contact:** B. van Rooij (geb. 28-02-1989)
**E-mail:** [op aanvraag beschikbaar]
**Dossier:** 608

---

## Kernboodschap

Een cliënt van bewindvoerderskantoor Almass Bewindvoering B.V. in het Land van Cuijk heeft na forensische analyse van 2.906 banktransacties vijftien structurele gebreken geconstateerd (geschatte schade EUR 33.471). Nadat hij op 4 maart 2026 een sommatie verstuurde, begon het kantoor diezelfde nacht met het herschrijven en verwijderen van websitepagina's. De volgende ochtend volgden vier gelieerde kantoren met een gecoördineerde verwijderingsactie van in totaal 28 pagina's. Branchevereniging Aegis — voorgezeten door voormalig minister Dennis Wiersma (VVD) — verwijderde gelijktijdig haar eigen ledenlijst.

OSINT-onderzoek bracht vervolgens aan het licht dat het geld van naar schatting 250.000 onder bewind gestelde Nederlanders via een Britse eenpersoonsvennootschap wordt doorgesluisd naar Malta — buiten bereik van de Nederlandse toezichthouders AFM en DNB — en dat achter het kantoor een netwerk van minimaal 28 vennootschappen in drie landen schuilgaat.

---

## 1. De aanleiding: één cliënt, vijftien gebreken, EUR 33.471 schade

B. van Rooij (37, Mill) staat sinds februari 2022 onder beschermingsbewind bij Almass Bewindvoering B.V. (KvK 55819125, Cuijk). Na eigen analyse van alle 2.906 transacties op zijn beheer-, leefgeld- en spaarrekening constateerde hij:

| # | Gebrek | Schade |
|---|--------|--------|
| 1 | Geen bijstandsuitkering aangevraagd na baanverlies | EUR 4.784 |
| 2 | Leefgeld 13 weken niet uitgekeerd | EUR 910 |
| 3 | Vakantiegeld nimmer uitgekeerd (4 jaar, 3 werkgevers) | EUR 3.300 |
| 4 | Huurtoeslag niet herberekend na inkomensverlies | EUR 3.360 |
| 5 | Zorgtoeslag niet herberekend | EUR 1.300 |
| 6 | 41 maanden dubbele telecomabonnementen (34% van leefgeld) | EUR 4.825 |
| 7 | Onnodig inschakelen schuldbemiddelaar PLANgroep/Verder | EUR 1.173 |
| 8 | Huurschuld Mooiland gegroeid onder bewind (EUR 681 → EUR 1.793) | EUR 1.112 |
| 9 | Zorgverzekeringspremie 14+ maanden niet betaald (CAK-wanbetaler) | EUR 351 |
| 10 | 28 gestorneerde incasso's door saldotekort | EUR 710 |
| 11 | Driedubbele bewindvoerderskosten boven wettelijk maximum | EUR 646 |
| 12 | Aflossing EUR 600 vanuit leefgeldrekening | EUR 600 |
| 13 | Salaris structureel op verkeerde rekening | — |
| 14 | Feitelijke bewindvoering door assistent (4 jaar geen contact bewindvoerder) | — |
| 15 | Psychische schade (huisartsverklaring) | EUR 7.500 |
| | **Totaal (incl. immaterieel, rente, BGK)** | **EUR 33.471** |

Van Rooij kwam bij Almass met een schuld van EUR 681. Na vier jaar bewind heeft hij EUR 6.418 schuld, geen spaargeld, en een CAK-wanbetaling op zijn naam. Van zijn netto-inkomen van EUR 107.921 is naar schatting 20 tot 22 procent (EUR 21.515-24.019) verdwenen.

---

## 2. Bewijsvernietiging binnen 8,5 uur na screenshots

Op **4 maart 2026** stuurde Van Rooij een sommatie en aansprakelijkstelling aan Almass (kenmerk BvR-2026-002). Diezelfde avond om **23:27 uur** maakte hij screenshots van de volledige Almass-website. Alle pagina's functioneerden normaal.

De volgende ochtend, **5 maart om 07:57 uur** — 8,5 uur later — begon directeur D.A.M. van Iersel MBA met het wijzigen van pagina's:

**Sessie 1 (ochtend):**

| Pagina | Tijdstip wijziging |
|--------|-------------------|
| `/klachten/` | 07:57 |
| `/nieuwsbericht/` | 07:57 |
| `/tarieven/` | 08:02 |
| `/over-ons/` | 11:06 |
| `/contact/` | 11:06 |
| `/beschermingsbewind/` | 12:02 |
| `/bedrijfsadministratie/` | 12:02 |
| `/budgetbeheer/` | 12:37 |
| `/curatele/` | 12:37 |
| `/downloads/` | 12:37 |
| `/levenstestament/` | 12:37 |
| `/mentorschap/` | 12:37 |
| `/` (homepage) | 12:52 |
| `/aangifte-inkomensbelasting/` | 12:55 |

**Vier pagina's permanent verwijderd (HTTP 404):**

| Verwijderde pagina | Inhoud | Relevantie |
|--------------------|--------|-----------|
| `/bewindvoering-b-v/` | Dienstbeschrijving | Verwijderd tijdens aansprakelijkstelling over kwaliteit diensten |
| `/voorstellen-medewerkers/` | Teamoverzicht met namen | Verwijderd terwijl KvK "1 werknemer" vermeldt maar site 7+ toonde |
| `/almass-en-de-avg/` | Privacybeleid | Verwijderd terwijl lopend AVG-inzageverzoek was ingediend |
| `/klachtenreglement/` | Klachtenreglement | Verwijderd terwijl klacht was ingediend |

**Bewijs:** De wijzigingstijden zijn vastgelegd via HTTP Last-Modified headers — door de server gegenereerde timestamps die niet door de website-eigenaar zijn te manipuleren. Screenshots van de vóórsituatie, volledige website-mirrors en monitoring-snapshots met SHA256-checksums zijn beschikbaar.

---

## 3. Gecoördineerde paginaverwijdering door vijf kantoren

Op **6 maart 2026** documenteerde Van Rooij dat bij vijf bewindvoerderskantoren in totaal **28 webpagina's** HTTP 404 (niet gevonden) retourneerden:

| Kantoor | Regio | Verwijderde pagina's | Aantal |
|---------|-------|---------------------|--------|
| CNAD | Noord-Brabant | tarieven, team, medewerkers, over-ons, beschermingsbewind, budgetbeheer, curatele, mentorschap, klachten | 9 |
| InBalans Beschermingsbewind | Gennep | over-balans, tarieven, klachten, team, bewindvoering, curatele, mentorschap + 1 | 8 |
| Atisha Bewind | — | tarieven, klachten, privacyverklaring, over-atisha + 2 | 6 |
| Almass Bewindvoering | Cuijk / Afferden | bewindvoering, medewerkers, avg, klachtenreglement | 4 |
| Kroezen Bewind | Boxmeer | medewerkersprofiel Carla Visser | 1 |
| **Totaal** | | | **28** |

Alle vijf kantoren verwijderden dezelfde categorieën: tarieven, klachtenregelingen, teamoverzichten en dienstbeschrijvingen. De sommatie was uitsluitend aan Almass gericht — het feit dat vier andere kantoren reageerden, bewijst onderlinge communicatie.

Gelijktijdig verwijderde branchevereniging **Aegis** (voorheen NBBI) vijf eigen pagina's, waaronder de volledige **ledenlijst van 1.269 kantoren** en de pagina met **kwaliteitseisen**.

---

## 4. Convenant Gennep — formeel bewijs van samenwerking

Drie van de vijf bij de paginaverwijderingen betrokken kantoren ondertekenden in **februari 2021** samen het **Convenant Beschermingsbewind Gemeente Gennep**:

- **D.A.M. van Iersel** — Almass Bewindvoering B.V.
- **K. Bitter-Reijnen** — InBalans Beschermingsbewind
- **A.J.P. Weijers** — K&K Bewindvoeringen (gelieerd aan Kroezen B.V.)

De overige twee convenantondertekenaars vertonen eveneens verdachte signalen: de website van Bewindvoering van A tot Z is volledig leeggehaald, en Bilancio Budget verwijderde specifiek het rayon Oss-Boxmeer — het werkgebied van de betrokken kantoren.

---

## 5. Het netwerk: 28+ vennootschappen in drie landen

Achter Almass Bewindvoering B.V. schuilt een netwerk van minimaal **28 rechtspersonen en ondernemingen** in Nederland, Duitsland en het Verenigd Koninkrijk:

### Kernentiteiten

| Entiteit | KvK | Bijzonderheid |
|----------|-----|---------------|
| Van Iersel Beheer B.V. | 73960152 | Holdingvennootschap directeur |
| Almass Bewindvoering B.V. | 55819125 | Operationeel kantoor |
| Almass Administratie B.V. | 55819257 | Administratie + registerexecuteur |
| Van Iersel Bewindvoering | 72395931 | Eenmanszaak directeur |

### Kruisbestuurdersschap

Almass Bewindvoering B.V. is sinds december 2014 **bestuurder** van **A. Roelofs Holding B.V.** (KvK 17202940, Boxmeer). Roelofs Bewindvoering (KvK 14126224, Vierlingsbeek) is een zelfstandig bewindvoeringskantoor. Een bewindvoerder die tevens bestuurder is van de holding van een collega-bewindvoerder vormt een belangenconflict.

### Familie Tonnissen — holdings en Duitsland

De oprichter van Almass, wijlen **Albert M. Tonnissen** (overleden 10 april 2024), liet een netwerk na van holdings en vastgoedvennootschappen:

| Entiteit | Bijzonderheid |
|----------|---------------|
| B&C Tonnissen Holding B.V. (KvK 73599883) | Holding |
| B&C Tonnissen Onroerend Goed B.V. (KvK 73599913) | Vastgoed |
| BT Holding B.V. (KvK 83763864) | Holding |
| Zeche Amalia GmbH (HRB 11423, AG Kleve) | **Balanstotaal EUR 2 miljoen**, Duitsland |

### Familie Winkelmolen — recreatie-imperium

Via huwelijksverbintenis (Tonnissen-Winkelmolen Beheer B.V.) is het netwerk verbonden met **Eldorado Parken B.V.** (KvK 92617433), een recreatie-imperium met minimaal vijf vakantieparken in Noord-Limburg en Noord-Brabant, waaronder Camping Klein Canada in Afferden — hetzelfde dorp als het Almass-kantooradres.

### Registratie na overlijden

Het domein **tonnissen.com** is in **oktober 2025** opnieuw geregistreerd — zes maanden na het overlijden van Tonnissen. In dezelfde maand is de KvK-inschrijving van Registerexecuteur A.M. Tonnissen (KvK 60609583) gewijzigd. Iemand beheert actief de digitale en juridische nalatenschap van de oprichter.

---

## 6. De smoking gun: stoffelsma.com

De gevolmachtigde van Almass, **Peter Stoffelsma** (Stoffelsma Oeffelt, KvK 17160081, gebouw 1.865 m²), exploiteert het domein stoffelsma.com. Bij het opvragen van dit domein retourneert de server:

```
HTTP/1.1 301 Moved Permanently
Location: https://almassbv.nl
```

**Stoffelsma.com verwijst permanent door naar de Almass-website.** Een HTTP 301 is een permanente redirect — een technische verklaring dat beide domeinen dezelfde organisatie vertegenwoordigen.

Stoffelsma is gevolmachtigde sinds 25 februari 2019 — exact de dag van de overname door Van Iersel. Zijn betrokkenheid gaat echter terug tot minimaal 2013 onder oprichter Tonnissen. Hij woont op 50 meter van het voormalige kantooradres.

---

## 7. Het fictieve cliëntportaal

Almass verstrekte cliënten inloggegevens voor het portaal **mijnbewinddossier.nl**, inclusief wachtwoorden in platte tekst per e-mail. Onderzoek wijst uit:

| Gegeven | Detail |
|---------|--------|
| Registratiedatum | **25 februari 2019** — exact de dag van de overname |
| SSL-certificaten | 38 certificaten aangevraagd in 7 jaar (2019-2026) |
| Wayback Machine | **0 snapshots** — site heeft nooit gefunctioneerd |
| Huidige status | "Domein gereserveerd" |

Er zijn 38 SSL-certificaten aangevraagd, maar de site is nooit live geweest. Cliënten kregen inloggegevens voor een portaal dat niet bestond.

Op **5 maart 2026** — één dag na de sommatie — werd het dossiernummer van Van Rooij gewijzigd van **608 naar 761**. Forensisch onderzoek van het OnView-portaal toonde dat dossier 761 niet bestaat in de database (NullReferenceException) en het oorspronkelijke account (RooiB608) was uitgeschakeld zonder kennisgeving.

---

## 8. Omzet versus personeel

Almass staat bij de Kamer van Koophandel geregistreerd met **1 werknemer**. De website vermeldde 7+ medewerkers en er werden actief stagiaires geworven. Bij een geschat cliëntenbestand van 250-500 dossiers en een gemiddelde vergoeding van EUR 1.800-2.500 per cliënt per jaar bedraagt de geschatte jaaromzet **EUR 600.000 tot EUR 1.250.000** — doorlopend via een vennootschap met 1 geregistreerde werknemer en **geen gedeponeerde jaarrekeningen** (art. 2:394 BW).

De vier jaar dat Van Rooij cliënt was, werd zijn dossier feitelijk behandeld door een "mevrouw Brons" — een persoon die in geen enkel openbaar register, LinkedIn, sociale media of Aegis-database te vinden is.

---

## 9. Het doorverwijzingspatroon

In de uitspraak **ECLI:NL:RBOBR:2025:4956** (Rechtbank Oost-Brabant, juli 2025) trad advocaat **mr. J.W.J. Hopmans** op namens een partij die ontslag van de zittende bewindvoerder vorderde. Ter zitting bood Almass zich aan als **opvolgend bewindvoerder**.

Hopmans werkt op toevoegingsbasis voor kwetsbare cliënten. Zijn B.V. (KvK 09159717) heeft als SBI-code niet alleen "advocatenkantoren" maar ook **"bewindvoerders en curatoren"**. Zijn kantoor ligt op 5 km van het Almass-adres in Afferden.

In 2014 werd **Stichting Bronn** (Gennep) door drie rechtbanken tegelijk ontslagen uit **685 dossiers** — wegens identieke gebreken als die Van Rooij bij Almass constateerde. Het vacuüm dat Bronn achterliet werd gevuld door kantoren met een officiële doorverwijspositie. Almass had die positie via het Convenant Gennep.

---

## 10. Stichting Het Palet

Van Iersel is **secretaris van het bestuur** van Stichting Het Palet — een zorginstelling voor **veertien verstandelijk gehandicapte bewoners**. Deze bewoners kunnen niet voor zichzelf opkomen en hun financiële situatie is niet onafhankelijk gecontroleerd.

---

## 11. De geldstroom: van Nederland via Londen naar Malta

### 11.1 Modura — het betaalplatform

Aegis biedt haar 1.300 aangesloten kantoren (4.400 professionals) het betaalplatform **Modura** aan, gepresenteerd als "non-profit initiatief". De werkelijke structuur:

```
Bewindvoerderskantoren (1.300 kantoren, 4.400 professionals)
    ↓ contributie + transactiekosten
Aegis (branchevereniging, Zwolle)
    ↓
Orenda Financial Services Ltd (Londen, UK)
    ↓
Transact Payments Malta Ltd (Il-Gżira, Malta)
    ↓
Cliëntgelden (~250.000 kwetsbare Nederlanders)
```

### 11.2 Eén persoon achter het platform

Het Britse bedrijf **Orenda Financial Services Ltd** (Companies House nr. 12404984) wordt volledig bestuurd door één persoon: **P.J. Vittori** (geb. 1987, Brits staatsburger). Vittori is enig bestuurder én secretaris van vier Orenda-entiteiten, waarvan er één in 2024 is ontbonden. Hij had eerder drie andere UK-bedrijven, waarvan twee eveneens ontbonden.

De Modura-backoffice draait aantoonbaar op het domein `modura-backoffice.orenda.finance` — een Orenda-domein, niet van Aegis.

### 11.3 Geen depositogarantie

**Transact Payments Malta Ltd** (MFSA-registratie C 91879) is een Electronic Money Institution, geen bank. Dit betekent:
- Het geld valt **niet** onder het Nederlandse Depositogarantiestelsel
- Het valt **niet** onder toezicht van AFM of DNB
- Bij faillissement van het platform zijn bewindvoerders **persoonlijk aansprakelijk** voor het verlies

### 11.4 Belangenverstrengeling Aegis-bestuur

De directeuren van Aegis — **A. van den Ham** en **B. Benjamins** — zijn tevens eigenaar van bewindvoerderskantoor **Aktiva B.V.** (KvK 62507931) en betrokken bij Modura. Zij opereren daarmee in een drievoudige rol: branchevereniging, eigen kantoor en betaalplatform.

Over deze belangenverstrengeling is reeds een zaak voorgelegd aan de **Autoriteit Consument & Markt** (ACM). Het platform BewindConnect publiceerde hierover artikelen met de titel "belangenverstrengeling en onethisch handelen". Het vakblad Handboek Bewind documenteerde dat lidmaatschapsbijdragen niet naar de vereniging vloeien, maar naar een besloten vennootschap van de directie.

**Sjoerd de Jong**, directeur van Atisha Bewind — één van de vijf kantoren die pagina's verwijderden — is tevens **bestuurslid van Aegis**. Hij reguleert daarmee zijn eigen kantoor.

---

## 12. Aegis-voorzitter Dennis Wiersma

Op 1 oktober 2025 werd **Dennis Wiersma** (VVD, geb. 1986) aangesteld als voorzitter van Aegis. Wiersma was van januari 2022 tot juli 2023 minister voor Primair en Voortgezet Onderwijs in het kabinet-Rutte IV. Hij trad af na berichtgeving van NRC en BNNVARA over intimiderend en grensoverschrijdend gedrag jegens ambtenaren.

Bij Aegis verving Wiersma voorganger G. Boeve, die vertrok vanwege een integriteitscrisis binnen het bestuur.

**Opmerking:** Er is op dit moment geen bewijs dat Wiersma kennis had van de hierboven beschreven constructies of paginaverwijderingen. Zijn betrokkenheid beperkt zich tot het voorzitterschap van de organisatie.

---

## 13. Kroezen Bewind — gedeelde IT-infrastructuur

**Bewindvoerderskantoor Kroezen B.V.** (KvK 62262912, Boxmeer) en het gelieerde **K&K Bewindvoeringen** delen identieke IT-infrastructuur:

- Beide gehost op **cybox.nl**
- Beide draaien op **Backstage CMS**
- Identieke SSL-certificaatstructuur

Kroezen B.V. opereert onder twee KvK-nummers: 17141460 (holding, "Financiële holdings") en 62262912 (operationele vennootschap). Het kantoor heeft 33 medewerkers (25 bewindvoerders, 8 overig personeel).

---

## 14. Tijdlijn

| Datum | Gebeurtenis |
|-------|-------------|
| 2002 | Domein stoffelsma.com geregistreerd |
| 2013 | Stoffelsma betrokken bij Almass onder oprichter Tonnissen |
| 2014 | Stichting Bronn ontslagen uit 685 dossiers (drie rechtbanken) |
| 16 feb 2021 | Vijf kantoren tekenen Convenant Beschermingsbewind Gennep |
| feb 2022 | Van Rooij komt onder bewind bij Almass |
| 10 apr 2024 | Oprichter Albert M. Tonnissen overlijdt |
| okt 2025 | Tonnissen.com opnieuw geregistreerd; KvK Registerexecuteur gewijzigd |
| 1 okt 2025 | Dennis Wiersma wordt voorzitter Aegis |
| 27 okt 2025 | Driedubbele bewindvoerderskosten: 3× EUR 182,91 |
| 4 mrt 2026 | Van Rooij stuurt sommatie aan Almass (BvR-2026-002) |
| 4 mrt 2026, 23:27 | Screenshots bevestigen: alle Almass-pagina's werkend |
| 5 mrt 2026, 07:57 | Almass begint met herschrijven pagina's (HTTP Last-Modified) |
| 5 mrt 2026, 12:55 | 14 pagina's herschreven |
| 5 mrt 2026 | Dossiernummer gewijzigd van 608 naar 761 |
| 5 mrt 2026, 22:55 | Tweede sessie wijzigingen voltooid; 4 pagina's verwijderd |
| 6 mrt 2026 | 28 pagina's HTTP 404 bij 5 kantoren |
| 6 mrt 2026 | Aegis verwijdert 5 eigen pagina's waaronder ledenlijst |

---

## 15. Beschikbaar bewijsmateriaal

Het volledige dossier (608) bevat meer dan **15.000 bestanden** en omvat:

- Forensische analyse van alle 2.906 banktransacties (feb 2022 — mrt 2026)
- HTTP-headers met server-timestamps van alle websitewijzigingen
- Screenshots van de vóórsituatie (4 maart 2026, 23:27 uur)
- Volledige website-mirrors (5 maart 2026, twee rondes)
- HTTP 404-headers van alle 28 verwijderde pagina's bij vijf kantoren
- Wayback Machine-snapshots van alle verwijderde pagina's
- KvK-registraties en holdingstructuren van alle 28+ entiteiten
- Companies House UK-filings van alle Orenda-entiteiten
- Duitse Handelsregister-data Zeche Amalia GmbH
- WHOIS-registraties van stoffelsma.com, mijnbewinddossier.nl, tonnissen.com
- HTTP 301 redirect bewijs stoffelsma.com → almassbv.nl
- SSL-certificaathistorie mijnbewinddossier.nl (38 certificaten)
- Convenant Beschermingsbewind Gemeente Gennep (16 februari 2021)
- ECLI-uitspraken met doorverwijzingspatroon
- Drie artikelen van BewindConnect over belangenverstrengeling Aegis
- OnView-portaaldata met dossiermanipulatie (608 → 761)
- SHA256-checksums van alle bewijsbestanden
- OpenTimestamps blockchain-timestamps (bewijs van bestaan op datum)

Het dossier is beschikbaar voor inzage door journalisten na afspraak.

---

## 16. Reactie gevraagd aan

- **Almass Bewindvoering B.V.** — Waarom werden 14 pagina's herschreven en 4 verwijderd binnen 8,5 uur na screenshots? Waarom werden vier gelieerde kantoren gewaarschuwd?
- **Aegis** — Waarom werden de ledenlijst en kwaliteitseisen verwijderd op dezelfde dag als de kantoorpagina's?
- **A. van den Ham / B. Benjamins** — Hoe verhouden uw rollen bij Aegis, Aktiva en Modura zich tot de Mededingingswet?
- **Dennis Wiersma** — Was u bij uw aanstelling op de hoogte van de belangenverstrengeling binnen het Aegis-bestuur?
- **Sjoerd de Jong (Atisha Bewind / Aegis-bestuur)** — Hoe reguleert u uw eigen kantoor via de branchevereniging waarvan u bestuurslid bent?
- **P.J. Vittori (Orenda Finance)** — Welke waarborgen bestaan er voor de gelden van 250.000 Nederlandse bewindvoerdercliënten?
- **Transact Payments Malta** — Onder welk toezichtregime vallen de gelden van Nederlandse bewindvoerdercliënten?
- **Mr. J.W.J. Hopmans** — Wat is de aard van de samenwerking met Almass bij het overnemen van bewindsdossiers?
- **Gemeente Land van Cuijk** — Hoe beoordeelt u het functioneren van de convenantpartners?

---

## Noot voor de redactie

B. van Rooij is een 37-jarige inwoner van Mill (gemeente Land van Cuijk). Hij werkt sinds zijn zesde met computers en beoefent al ruim twintig jaar hobbymatig OSINT (Open Source Intelligence) en cybersecurity. Zijn bewindvoerder was niet op de hoogte van deze achtergrond toen hij na ontvangst van de sommatie besloot webpagina's te gaan verwijderen.

Van Rooij voerde het volledige onderzoek zelfstandig uit met veertien professionele OSINT-tools op negentien domeinen, gebruikmakend van uitsluitend openbare bronnen: KvK-registers, DNS-records, HTTP-headers, Wayback Machine, Companies House UK, het Duitse Handelsregister en openbare websites. Er is geen gebruik gemaakt van niet-openbare informatie of ongeautoriseerde toegang tot systemen.

Dit persbericht is opgesteld op basis van verifieerbare feiten. Beweringen die niet hard bewezen zijn, worden als zodanig gemarkeerd.

---

*Dit persbericht is onderdeel van Dossier 608 — B. van Rooij vs. Almass Bewindvoering B.V.*
*Datum: 6 maart 2026*
