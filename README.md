```
 ██████╗  ██████╗ ███████╗███████╗██╗███████╗██████╗      ██████╗  ██████╗  █████╗
 ██╔══██╗██╔═══██╗██╔════╝██╔════╝██║██╔════╝██╔══██╗    ██╔════╝ ██╔═████╗██╔══██╗
 ██║  ██║██║   ██║███████╗███████╗██║█████╗  ██████╔╝    ███████╗ ██║██╔██║╚█████╔╝
 ██║  ██║██║   ██║╚════██║╚════██║██║██╔══╝  ██╔══██╗    ██╔═══██╗████╔╝██║██╔══██╗
 ██████╔╝╚██████╔╝███████║███████║██║███████╗██║  ██║    ╚██████╔╝╚██████╔╝╚█████╔╝
 ╚═════╝  ╚═════╝ ╚══════╝╚══════╝╚═╝╚══════╝╚═╝  ╚═╝     ╚═════╝  ╚═════╝  ╚════╝
```

> **Ze hadden met mij de verkeerde te pakken.**

---

## Dossier 608 — Almass Bewindvoering Ontmaskerd

**Datum:** 7 maart 2026
**Dossier:** 608
**Auteur:** B. van Rooij (37), Mill — computert sinds zijn zesde, 20+ jaar OSINT & cybersecurity
**Website:** [almass-down-24-to-go](https://wimlee115.github.io/almass-down-24-to-go/)

---

### Wat is dit?

Dit is het openbare bewijsdossier tegen **Almass Bewindvoering B.V.** (KvK 55819125, Cuijk) — geleid door directeur **D.A.M. van Iersel MBA**.

Na vier jaar onder beschermingsbewind te staan — en EUR 33.471 schade te lijden — besloot ik het hele kantoor door te lichten. Wat ik vond was groter dan mijn eigen zaak: een netwerk van 28+ vennootschappen in 3 landen, gecoördineerde bewijsvernietiging, en geld dat via Malta buiten Nederlands toezicht loopt.

---

### De feiten

| Feit | Detail |
|------|--------|
| **Schade** | EUR 33.471 — 15 structurele gebreken in bewindvoering door Almass |
| **Bewijsvernietiging** | 14 pagina's herschreven + 4 verwijderd door Van Iersel — 8,5 uur na mijn screenshots |
| **Het netwerk** | 28+ vennootschappen in 3 landen (NL, UK, Malta) achter Almass |
| **Smoking gun** | stoffelsma.com → HTTP 301 redirect → almassbv.com |
| **Het geld** | 250.000 cliënten wier geld via Londen naar Malta loopt — buiten toezicht AFM/DNB |
| **Het bewijs** | 15.000+ bestanden, SHA256-gehashed, blockchain-getimestampt, extern veiliggesteld |

---

### Bewijsvernietiging door Almass — de tijdlijn

```
4 mrt 2026  15:30   Sommatie verzonden aan Almass (BvR-2026-002)
4 mrt 2026  23:27   Screenshots alle Almass-pagina's — alles online
5 mrt 2026  07:57   Eerste pagina gewijzigd door Van Iersel (Last-Modified header)
5 mrt 2026  08:02   /tarieven/ herschreven
5 mrt 2026  11:06   /over-ons/ en /contact/ herschreven
5 mrt 2026  12:02   /beschermingsbewind/ en /bedrijfsadministratie/ herschreven
5 mrt 2026  12:37   5 pagina's herschreven
5 mrt 2026  12:52   Homepage herschreven
5 mrt 2026  12:55   /aangifte-inkomensbelasting/ herschreven
```

**4 pagina's permanent verwijderd (HTTP 404):**
- `/bewindvoering-b-v/` — dienstbeschrijving (verwijderd tijdens aansprakelijkstelling)
- `/voorstellen-medewerkers/` — teamoverzicht (KvK vermeldt "1 werknemer" maar site toonde 7+)
- `/almass-en-de-avg/` — privacybeleid (verwijderd tijdens lopend AVG-inzageverzoek)
- `/klachtenreglement/` — klachtenprocedure (verwijderd tijdens klacht)

---

### Smoking gun — stoffelsma.com

```
$ curl -I https://stoffelsma.com
HTTP/1.1 301 Moved Permanently
Location: https://www.almassbv.com/
```

**Stoffelsma.com** — gepresenteerd als een onafhankelijk bewindvoerderskantoor — stuurt permanent door naar Almass. Dit is het rokend pistool: kantoren die zogenaamd concurreren, zijn technisch één en dezelfde organisatie.

---

### Het netwerk — 28+ vennootschappen

```
                        Van Iersel-van Roessel (Helvoirt)
                                    │
                        Van Iersel Beheer B.V. (KvK 73960152)
                                    │
                ┌───────────────────┼───────────────────┐
                │                   │                   │
        Almass Bewind.       Almass Admin.        + 4 BV's
        (KvK 55819125)       (KvK 55819257)
                │
    ┌───────────┼───────────────────────────────────┐
    │           │           │           │           │
Tonnissen    Hopmans    Stoffelsma   Van Roessel   CNAD
                        (301→Almass)

+ Stichting Het Palet + Zeche Amalia (DE) + Rogmann GmbH (DE) + ...
```

---

### Geldstroom — via Malta, buiten toezicht

```
Bewindvoerderskantoren (1.300 kantoren, ~250.000 cliënten)
    ↓ betaalplatform "Modura"
Aegis (branchevereniging — voorzitter: ex-minister Dennis Wiersma, VVD)
    ↓
Orenda Financial Services Ltd (Londen, Companies House 12404984)
    ↓ enig bestuurder: P.J. Vittori, 4 entiteiten, 1 ontbonden
Transact Payments Malta Ltd (Il-Gżira, MFSA C 91879)
    ↓
GEEN Nederlandse Depositogarantie. GEEN AFM/DNB-toezicht.
```

---

### ⏰ MORGEN: MEER KANTOREN WORDEN ONTMASKERD

Almass opereert niet alleen. Op **6 maart 2026** verwijderden **vier andere kantoren** gecoördineerd **24 webpagina's** — op dezelfde ochtend, na één sommatie aan één kantoor.

**Het onderzoek naar deze kantoren loopt.** Na grondige analyse van alle bewijzen volgt morgen de volgende onthulling:

- Welke kantoren betrokken zijn bij de gecoördineerde bewijsvernietiging
- Het Convenant Gennep — de formele samenwerkingsovereenkomst die het kartel bewijst
- Gedeelde IT-infrastructuur — kantoren die "concurreren" maar op dezelfde servers draaien
- Familieverbanden en kruisbestuurderschap
- Nog meer vennootschappen

**Dit dossier groeit elke dag. Blijf kijken.**

---

### Documenten

| Map | Inhoud |
|-----|--------|
| [`persbericht/`](persbericht/) | Volledig persbericht — alle feiten, alle bronnen |
| [`netwerk/`](netwerk/) | Netwerkanalyse — 28+ vennootschappen, eigendomsschema's |
| [`bewijs/`](bewijs/) | Bewijsvernietiging — HTTP-headers, timestamps, 404-documentatie |
| [`modura/`](modura/) | Geldstroom Modura/Orenda/Malta — Companies House filings |
| [`tijdlijn/`](tijdlijn/) | Volledige tijdlijn |

---

### Klachten worden ingediend op 9 maart 2026

| Instantie | Onderwerp |
|-----------|-----------|
| Kantonrechter Rechtbank Oost-Brabant | Ambtshalve ontslag, schadevergoeding EUR 33.471 |
| Autoriteit Consument & Markt (ACM) | Kartelvorming, mededingingsbeperking |
| Autoriteit Persoonsgegevens (AP) | AVG-schendingen, wachtwoorden platte tekst |
| Bureau Financieel Toezicht (BFT) | Kruisbestuurdersschap, ontbrekende jaarrekeningen |
| AFM / DNB | Modura/Malta-constructie buiten toezicht |
| Politie | Verduistering, valsheid in geschrifte, art. 140 Sr |

---

### Voor journalisten

Dit dossier bevat uitsluitend informatie verkregen via openbare bronnen (OSINT). **Geen hacking. Geen gelekte documenten.** Alles verifieerbaar.

Het volledige dossier (15.000+ bestanden, 500+ MB) is beschikbaar voor inzage na afspraak.

**Contact:** B. van Rooij — e-mailadres op aanvraag

---

### International readers

This dossier exposes **Almass Bewindvoering B.V.**, a Dutch guardianship firm managing finances of vulnerable citizens. Key findings:

- **Evidence destruction**: 18 pages modified/deleted within 8.5 hours of a formal complaint
- **Shell network**: 28+ corporate entities across 3 countries (NL, UK, Malta) behind one firm
- **Money via Malta**: Client funds routed Netherlands → London → Malta, outside Dutch regulatory supervision
- **More firms involved** — investigation ongoing, tomorrow more will be revealed

All evidence obtained through OSINT. Full press release: [`persbericht/`](persbericht/)

---

<sub>Dossier 608 — B. van Rooij vs. Almass Bewindvoering B.V. — 7 maart 2026</sub>
<sub>SHA256-gehashed en blockchain-getimestampt via OpenTimestamps.</sub>
