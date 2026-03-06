# Technische Documentatie: Bewijsvernietiging na Sommatie

**Dossier 608 — B. van Rooij vs. Almass Bewindvoering B.V.**
**Datum:** 6 maart 2026
**Classificatie:** Openbare publicatie — forensisch bewijsmateriaal

---

## 1. Samenvatting

Op 4 maart 2026 ontving Almass Bewindvoering B.V. een sommatie (kenmerk BvR-2026-002) en een AVG-inzageverzoek (BvR-2026-003). In de sommatie werd uitdrukkelijk verzocht alle bewijsmateriaal te bewaren. Binnen 24 uur begon het kantoor met het systematisch herschrijven en verwijderen van websitepagina's. De volgende dag volgden vier gelieerde kantoren met een gecoordineerde verwijderingsactie van in totaal 28 pagina's. Branchevereniging Aegis verwijderde gelijktijdig vijf eigen pagina's, waaronder de volledige ledenlijst.

---

## 2. Almass: 14 pagina's herschreven op 5 maart 2026

### 2.1 Causaal verband

| Datum | Gebeurtenis |
|-------|-------------|
| 4 maart 2026, ochtend | Sommatie BvR-2026-002 verzonden per e-mail en aangetekende post |
| 4 maart 2026, ochtend | AVG-inzageverzoek BvR-2026-003 verzonden |
| 4 maart 2026, middag | Almass bevestigt ontvangst per e-mail |
| 4 maart 2026, 23:27 | Screenshots bevestigen: alle pagina's functioneren normaal |
| **5 maart 2026, 07:57** | **Eerste wijzigingen gedetecteerd — 8,5 uur na screenshots** |

### 2.2 Complete Last-Modified tabel — Ochtendsessie (07:57 - 12:55 CET)

De wijzigingen zijn gedetecteerd via de HTTP `Last-Modified` header die door de Apache-webserver van Almass wordt meegezonden. Dit is een serverzijdige timestamp die niet door de website-eigenaar is te manipuleren.

| Pagina | Tijdstip wijziging (CET) |
|--------|--------------------------|
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

**Totaal ochtendsessie:** 14 pagina's herschreven in 4 uur en 58 minuten.

### 2.3 Avondsessie (18:53 - 22:55 CET)

Elf van de veertien herschreven pagina's werden diezelfde avond opnieuw gewijzigd:

| Pagina | Ochtend | Avond |
|--------|---------|-------|
| `/klachten/` | 07:57 | 18:53 |
| `/nieuwsbericht/` | 07:57 | 18:53 |
| `/tarieven/` | 08:02 | 18:58 |
| `/contact/` | 11:06 | 21:50 |
| `/over-ons/` | 11:06 | 21:50 |
| `/beschermingsbewind/` | 12:02 | 22:53 |
| `/budgetbeheer/` | 12:37 | 22:55 |
| `/curatele/` | 12:37 | 22:55 |
| `/downloads/` | 12:37 | 22:55 |
| `/levenstestament/` | 12:37 | 22:55 |
| `/mentorschap/` | 12:37 | 22:55 |

Het feit dat 11 pagina's op dezelfde dag tweemaal zijn herschreven toont opzettelijk handelen — geen routine-onderhoud.

---

## 3. Vier pagina's permanent verwijderd (HTTP 404)

| Verwijderde pagina | Inhoud | Forensische relevantie |
|--------------------|--------|------------------------|
| `/bewindvoering-b-v/` | Dienstbeschrijving bewindvoering | Verwijderd tijdens aansprakelijkstelling over kwaliteit diensten |
| `/voorstellen-medewerkers/` | Teamoverzicht met 8 namen | Verwijderd terwijl KvK "1 werknemer" vermeldt maar website 7+ toonde |
| `/almass-en-de-avg/` | AVG-privacybeleid | Verwijderd terwijl lopend AVG-inzageverzoek was ingediend |
| `/klachtenreglement/` | Klachtenreglement | Verwijderd terwijl formele klacht was ingediend |

### Wayback Machine — Laatste werkende snapshots

| Pagina | Laatste HTTP 200 (Wayback) |
|--------|---------------------------|
| `/voorstellen-medewerkers/` | 18 juni 2025 |
| `/almass-en-de-avg/` | 8 september 2025 |
| `/klachtenreglement/` | 13 augustus 2025 |
| `/bewindvoering-b-v/` | 8 september 2025 |

---

## 4. Geocoordineerde verwijdering door vijf kantoren (6 maart 2026)

Op 6 maart 2026 retourneerden bij vijf bewindvoerderskantoren in totaal 28 webpagina's HTTP 404 (niet gevonden):

| Kantoor | Regio | Verwijderde pagina's | Aantal |
|---------|-------|---------------------|--------|
| CNAD | Noord-Brabant (Sint Anthonis) | tarieven, team, medewerkers, over-ons, beschermingsbewind, budgetbeheer, curatele, mentorschap, klachten | 9 |
| InBalans Beschermingsbewind | Gennep | over-balans, tarieven, klachten, team, bewindvoering, curatele, mentorschap, over-ons | 8 |
| Atisha Bewind | Mook en Middelaar | tarieven, klachten, privacyverklaring, over-atisha, beschermingsbewind, diensten | 6 |
| Almass Bewindvoering | Cuijk / Afferden | bewindvoering-b-v, voorstellen-medewerkers, almass-en-de-avg, klachtenreglement | 4 |
| Kroezen Bewind | Boxmeer | carla-visser (medewerkersprofiel) | 1 |
| **Totaal** | | | **28** |

Alle vijf kantoren verwijderden dezelfde categorieen: tarieven, klachtenregelingen, teamoverzichten en dienstbeschrijvingen. De sommatie was uitsluitend aan Almass gericht — het feit dat vier andere kantoren reageerden bewijst onderlinge communicatie.

### Overige verdachte kantoren

| Kantoor | Status |
|---------|--------|
| Bewindvoering van A tot Z (Gassel) | Gehele website leeggehaald — alleen "webserver is functioning normally" |
| Bilancio Budget | Rayon Oss-Boxmeer specifiek verwijderd (404), overige rayons werkend |

---

## 5. Aegis: 5 pagina's verwijderd

Gelijktijdig met de kantoorverwijderingen verwijderde branchevereniging Aegis (voorheen NBBI) vijf eigen pagina's:

| Verwijderde Aegis-pagina | Inhoud |
|--------------------------|--------|
| `/onze-leden/` | Volledige ledenlijst van 1.269 kantoren |
| `/kwaliteitseisen/` | Kwaliteitseisen voor leden |
| `/klachtenregeling/` | Klachtenregeling van de branchevereniging |
| `/over-aegis/` | Informatie over de organisatie |
| `/lidmaatschap/` | Lidmaatschapsinformatie |

De ledenlijst werd verwijderd nadat 1.269 leden waren gescand als onderdeel van het OSINT-onderzoek.

---

## 6. Uitleg HTTP Last-Modified headers als forensisch bewijs

### 6.1 Wat is een Last-Modified header?

Elke keer dat een webbrowser een pagina opvraagt, stuurt de webserver een reeks HTTP-headers mee. Een van deze headers is `Last-Modified` — een door de server gegenereerde timestamp die aangeeft wanneer de pagina-inhoud voor het laatst is gewijzigd.

### 6.2 Waarom is dit betrouwbaar bewijs?

| Eigenschap | Toelichting |
|------------|-------------|
| Serverzijdig | De timestamp wordt gegenereerd door de webserver (Apache), niet door de browser of bezoeker |
| Niet manipuleerbaar door eigenaar | De website-eigenaar kan de Last-Modified header niet handmatig instellen via het WordPress CMS |
| Consistente tijdzone | De server rapporteert in GMT; de omrekening naar CET (GMT+1) is eenduidig |
| Reproduceerbaar | Elke bezoeker die dezelfde pagina opvraagt, ontvangt dezelfde Last-Modified waarde |

### 6.3 Serverinformatie Almass

| Kenmerk | Waarde |
|---------|--------|
| Domein | www.almassbv.com |
| IP-adres | 77.111.243.41 |
| Hosting | Hostnet (Nederland) |
| Webserver | Apache + Varnish cache |
| CMS | WordPress 6.9.1 |
| PHP | PHP/8.4.18 |
| SSL | Let's Encrypt R12 |

### 6.4 Voorbeeld ruwe HTTP-response

```
HTTP/1.1 200 OK
Date: Wed, 05 Mar 2026 17:27:00 GMT
Server: Apache
Last-Modified: Wed, 05 Mar 2026 06:57:00 GMT
Content-Type: text/html; charset=UTF-8
```

In dit voorbeeld is de pagina om 06:57 GMT (= 07:57 CET) voor het laatst gewijzigd. De `Date`-header bevestigt het exacte moment van opvraging.

---

## 7. Bewijsborging: SHA256 + OpenTimestamps

### 7.1 SHA256 hashes

Alle vastgelegde pagina's zijn voorzien van SHA256-checksums — cryptografische vingerafdrukken die de integriteit van elk bestand garanderen. Elke wijziging, hoe klein ook, resulteert in een volledig andere hash.

Voorbeelden (verkort weergegeven):

| Bestand | SHA256 (eerste 8 tekens) |
|---------|--------------------------|
| aangifte-inkomensbelasting_.html | 8e9d442d... |
| beschermingsbewind_.html | bfbb26bb... |
| budgetbeheer_.html | 9d4bb6b5... |
| contact_.html | f83342b9... |
| curatele_.html | b46b5d83... |
| downloads_.html | 3c31d229... |
| executeur-testamentair_.html | 1b30981a... |
| homepage.html | 838c277b... |
| klachten_.html | 835d3282... |
| levenstestament_.html | 540752ce... |
| mentorschap_.html | f7684f85... |
| nieuwsbericht_.html | 5f9780f2... |
| over-ons_.html | eec0bcd7... |
| tarieven_.html | 55370762... |

Volledige 64-teken SHA256-hashes zijn beschikbaar in de bewijsbestanden.

### 7.2 OpenTimestamps

Alle bewijsbestanden zijn voorzien van OpenTimestamps blockchain-timestamps — een onafhankelijk bewijs dat de bestanden op een bepaald moment bestonden. OpenTimestamps maakt gebruik van de Bitcoin-blockchain, waardoor de timestamps niet met terugwerkende kracht zijn te creeren of te manipuleren.

### 7.3 Wayback Machine snapshots

De verwijderde pagina's zijn veiliggesteld via de Wayback Machine en lokaal opgeslagen:

| Bestand | Grootte | SHA256 (eerste 12 tekens) |
|---------|---------|--------------------------|
| almass_medewerkers_20250618.html | 61.022 bytes | f438163223... |
| almass_klachten_20250813.html | 63.107 bytes | ace90f0d14... |
| inbalans_over_ons_20240715.html | 15.068 bytes | 255244ccac... |
| aegis_onze_leden_20250605.html | 156.274 bytes | e41ea5b7f1... |
| bilancio_rayon_boxmeer_20251108.html | 250.073 bytes | f4d23e86c6... |
| vanatotz_20210926.html | 4.839 bytes | c55b4b52d9... |

---

## 8. Veiliggesteld bewijsmateriaal — Overzicht

### 8.1 Voor de verwijdering (4 maart 2026)

| Type | Omschrijving |
|------|-------------|
| Websitemirror | Volledige Almass-site, 4 maart 2026, 3.1 MB |
| Screenshots | Alle pagina's, 4 maart 2026, 23:27 uur |
| Wayback Machine | Alle 4 verwijderde pagina's (historische snapshots 2023-2025) |

### 8.2 Na de verwijdering — Ochtendronde (5 maart, 18:27 CET)

| Type | Omschrijving |
|------|-------------|
| HTTP headers | Last-Modified timestamps alle pagina's |
| HTML-pagina's | 27 individuele pagina's met SHA256 |
| 404-status | Headers verwijderde pagina's met timestamp |

### 8.3 Na de verwijdering — Avondronde (5 maart, 23:30 CET)

| Type | Omschrijving |
|------|-------------|
| HTTP headers | Nieuwe Last-Modified timestamps (tweede ronde) |
| HTML-pagina's | 14 individuele pagina's met SHA256 |
| Websitemirror | Volledig archief, 139 bestanden, 4.9 MB |
| SHA256-hashes | Integriteitscontrole alle bestanden |

### 8.4 Geocoordineerde verwijdering (6 maart 2026)

| Type | Omschrijving |
|------|-------------|
| HTTP 404 headers | 28 pagina's over 5 kantoren, met timestamps |
| Aegis 404 headers | 5 pagina's, inclusief ledenlijst |
| Website-mirrors | Alle 7 betrokken domeinen volledig gearchiveerd |
| Google Cache | 65+ HTML-snapshots kantoorwebsites |
| Screenshots | 28 PNG-screenshots kantoorpagina's |

---

## 9. Eerdere coordinatie: Zomer 2025

Wayback Machine CDX-analyse toont dat Aegis en Almass al in de zomer van 2025 tegelijkertijd soortgelijke pagina's verwijderden:

| Kantoor | Pagina | Laatste HTTP 200 |
|---------|--------|-----------------|
| Aegis | /onze-leden/ | 5 juni 2025 |
| Almass | /voorstellen-medewerkers/ | 18 juni 2025 |

Beide pagina's zijn binnen 13 dagen van elkaar voor het laatst als werkend gearchiveerd. Twee verschillende organisaties (branchevereniging versus individueel kantoor) die in dezelfde korte periode dezelfde soort pagina verwijderen — dit patroon is onverklaarbaar als onafhankelijke beslissingen.

---

## 10. Juridische kwalificatie

| Kwalificatie | Toelichting |
|-------------|-------------|
| Bewijsvernietiging (art. 189 lid 1 sub 2 Sr) | Verwijdering van webpagina's na sommatie met bewaringsverzoek |
| AVG-schending (art. 12 AVG) | Verwijdering AVG-beleidspagina binnen 24 uur na AVG-inzageverzoek |
| Bewaarplicht geschonden | Sommatie verzocht expliciet om bewaring van alle documenten |
| Onrechtmatige daad (art. 6:162 BW) | Opzettelijk bemoeilijken van waarheidsvinding |

---

*Dit document is onderdeel van Dossier 608 — B. van Rooij vs. Almass Bewindvoering B.V.*
*Alle bewijs is veiliggesteld met SHA256-checksums en OpenTimestamps blockchain-timestamps.*
*Datum: 6 maart 2026*
