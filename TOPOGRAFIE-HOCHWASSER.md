# Topographie-Analyse Melbtal & Win-Win-Hochwasserschutz am Melbbad

> Recherche-Stand: 17. Juli 2026
> Höhendaten: EU-DEM (25 m Raster) via OpenTopoData; im engen, bewaldeten Kerbtal mit Unsicherheit von mehreren Metern (Vegetationseinfluss). Für belastbare Planung: DGM1 NRW (open data, 1-m-Raster) auswerten.

---

## 1. Gewässersteckbrief Melbbach (amtliche Daten)

| Merkmal | Wert |
|---|---|
| Name | Melbbach (auch Engelbach/Engelsbach, unterhalb "Poppelsdorfer Bach") |
| Gewässerkennzahl | DE 2719716 |
| Länge | **6,1 km** |
| **Einzugsgebiet** | **5,024 km²** (LANUV-Gewässerverzeichnis) |
| Quelle | Waldau (Kottenforst), ca. **166 m ü. NHN** |
| Mündung | Rhein (km 653,93), ca. **54 m ü. NHN** |
| Gesamtgefälle | ca. 112 m → Sohlgefälle **~18 ‰** (steil!) |
| Verlauf | **3,1 km offen** durchs Melbtal → **durch das Melbbad-Gelände (renaturiert!)** → ab Poppelsdorf **~1,5 km verrohrt** → Weiher Botanischer Garten (Melbweiher) → unterirdisch zum Rhein |
| Abflussmengen (BEP 2008) | normal **5–40 l/s**, Hochwasser **2.100 l/s** (Bemessungsangabe Stadt Bonn; BEP nennt EZG 3,4 km², LANUV 5,02 km² – Differenz klären!) |
| Historie | Melbbad steht am Standort einer **ehemaligen Wassermühle** ("Obere Mühle") – Wasserrückhalt an dieser Stelle hat also historische Tradition (Mühlenteich) |
| Hochwasserhistorie | Hochwasser in Poppelsdorf 1970 → **1991 neuer, größerer Entlastungskanal** vom Weiher zum Rhein, seit **25.2.1994** mündet der Bach direkt in den Rhein (vorher Mischwasserkanalisation); **2005** Offenlegung durchs Freibad + **Neubau eines kleinen HRB oberhalb des Bades**; Starkregen **2020 zerstörte trotzdem die Melbbad-Technik** |

Quellen: https://de.wikipedia.org/wiki/Melbbach · Bachentwicklungsplan Stadt Bonn 2008 (S. 37): https://web.archive.org/web/20151213063607/https://www2.bonn.de/bo_ris/daten/O/pdf/08/0810154ED2.pdf

## 2. Höhenprofil (EU-DEM 25 m, gemessen entlang des ECHTEN Bachlaufs aus OSM-Geometrie)

Talweg = OSM-Relation 3446379 (Melbbach, 554 Stützpunkte); Melbbad-Gelände = OSM-Way 164071759 (Zentrum 50.7150, 7.0881).

| Station | Koordinate (Bachlauf) | Höhe |
|---|---|---|
| Quelle Waldau | 50.6938, 7.0936 | ~180 m* |
| Oberlauf | 50.6989, 7.0906 | ~162 m |
| Mittellauf | 50.7036, 7.0849 | ~147 m |
| Unterlauf NSG (Melbbrücke-Bereich) | 50.7090, 7.0868 | ~128 m |
| kurz oberhalb Melbbad | 50.7134, 7.0892 | ~115 m |
| **MELBBAD (Geländezentrum)** | **50.7150, 7.0881** | **~99 m** |
| unmittelbar unterhalb Bad | 50.7171, 7.0876 | ~96 m |
| Beginn Verrohrung (Poppelsdorf) | 50.7199, 7.0870 | ~77 m |
| Poppelsdorfer Weiher | 50.7245, 7.0947 | ~67 m |
| Flanke West auf Bad-Höhe (Ippendorf) | 50.7134, 7.0810 | ~160 m |
| Flanke Ost auf Bad-Höhe (Venusberg) | 50.7134, 7.0960 | ~163 m |

\* DEM überschätzt im Wald leicht (amtliche Quellhöhe: 166 m); Relief/Differenzen sind belastbar.

### Was das Profil bedeutet

1. **Tiefes, enges Kerbtal:** Auf Höhe des Bades liegen BEIDE Flanken (Ippendorf 160 m, Venusberg 163 m) rund **60 m über der Talsohle** (~100 m). Bei Starkregen wirkt das Tal wie ein **Trichter mit hoher Fließgeschwindigkeit** – genau das traf das Bad 2020.
2. **Das Melbbad liegt in der ersten Talweitung** unmittelbar am NSG-Rand – die letzte offene Fläche, bevor der Bach ~500 m weiter unter die dichte Poppelsdorfer Bebauung abtaucht (Verrohrung ab ~77 m Geländehöhe).
3. **Poppelsdorf liegt 25–30 m TIEFER als das Bad** (67–77 m vs. ~99 m). Alles Wasser, das am Bad nicht gebremst wird, schießt mit starkem Gefälle in den Stadtteil (Bad → Weiher: ~32 m Gefälle auf ~1,2 km).
4. **Der Engpass ist die Verrohrung:** 1,5 km Rohr unter Poppelsdorf. Übersteigt der Zufluss die Rohrkapazität, tritt das Wasser an der Trierer Straße über und flutet oberirdisch den Stadtteil (Szenario 1970, Teilszenario 2020). Der 1991er Entlastungskanal hilft erst **ab dem Weiher** – der kritische Abschnitt Bad → Weiher bleibt.

### Faktencheck: Was seit 1970 bereits gebaut wurde (und warum es 2020 nicht reichte)

| Jahr | Maßnahme | Wirkung / Grenze |
|---|---|---|
| 1991 | **Entlastungskanal Weiher → Rhein** (Mündung Zweite Fährgasse) | Entlastet nur den Abschnitt **ab dem Poppelsdorfer Weiher**; der kritische Abschnitt Bad → Weiher (Verrohrung unter der Trierer Straße) profitiert nicht |
| 25.2.1994 | Melbbach mündet **direkt in den Rhein** statt in die Mischwasserkanalisation (BEP 2008) | Entlastet das Kanalnetz, ändert aber nichts am Engpass oberhalb |
| 2005 | **Offenlegung des Bachs** ab Hochhäuser Trierer Str. durchs Freibadgelände + **Neubau eines Hochwasserrückhaltebeckens direkt oberhalb des Melbbades** (BEP 2008, Stat. 3,27–3,30: "Erdbecken mit Schlammfang und Ökoprofil durch das Dammbauwerk") | Es gibt also **bereits Retention am Talausgang** – aber als kleines Erdbecken (~30 m Stationslänge). Der Starkregen **2020 überforderte es nachweislich**: Bad-Technik zerstört (GA: Bach konnte Wasser aus Melbtal, Hängen Trierer Str. und Venusberg "nicht mehr aufnehmen") |
| 2024–2026 | **Regenrückhaltebecken Hauweg** (Venusberg, ehem. Sportplatz, ~2,2 Mio. €) | Städtische Praxis der Überflutungsvorsorge – schützt aber **Bergstraße/Rosenburgweg (Richtung Kessenich)**, nicht das Melbbach-System; die vorhandenen Becken Bergstraße liefen zuvor mehrfach über |

**Kein Beleg gefunden** für ein großes unterirdisches Becken "unter dem Poppelsdorfer Platz" (geprüft: Wikipedia, BEP 2008, bonn.de-Pressemitteilungen, Starkregen-Broschüre Tiefbauamt 2025). Vermutlich wird der 1991er Entlastungskanal bzw. das HRB am Bad erinnert. → Für belastbare Aussagen: **Kanalbestandsplan/Bemessung beim Tiefbauamt erfragen** (siehe offene Aufgaben).

**Konsequenz für die Argumentation:** Nicht "Poppelsdorf hat keinen Schutz", sondern: **Die vorhandenen Maßnahmen (Kanal 1991, kleines HRB 2005) haben das Ereignis 2020 nachweislich nicht beherrscht.** Das Konzept ersetzt sie nicht, sondern **vergrößert die vorhandene, zu kleine Retention am richtigen Ort um ein Vielfaches** (15.000–30.000 m³ statt eines kleinen Erdbeckens) – als Ausbau erklärter städtischer Praxis (Holzlarer See, Hauweg).

## 3. Harte Standort-Restriktionen (neu recherchiert)

| Restriktion | Befund | Konsequenz |
|---|---|---|
| **Naturschutzgebiet Melbtal (BN-011, seit 2013, IUCN IV)** | Das gesamte Tal "von der Waldau bis zum Melbbad" ist NSG: https://nsg.naturschutzinformationen.nrw.de/nsg/de/fachinfo/gebiete/gesamt/BN-011 | Ein klassisches **Rückhaltebecken mit Damm IM Tal ist praktisch nicht genehmigungsfähig** (NSG-Befreiung § 67 BNatSchG nur bei überwiegendem öffentlichen Interesse + fehlender Alternative). Die Alternative gibt es aber: das Bad selbst (liegt am/unterhalb des NSG-Rands). |
| **Geologie: Hangrutschgebiet** | Wasserundurchlässiger Ton unter Lösslehm, dazwischen ~5 cm quellfähige **Braunkohleschicht als Gleitfläche**; in den 1960ern rutschten Häuser ins Tal ab (Wikipedia Melbtal) | **Dammbauwerke an den Talflanken sind geotechnisch riskant** – zweites K.-o. für ein Talsperren-HRB. Positiv: toniger Untergrund ("Melb" = keltisch "lehmig"!) ist ideal für **Teichbau** – dieselbe Ausgangslage wie beim Schorndorfer Ziegeleisee (ehem. Lehmgrube). |
| **Kaltluftschneise Melbtalwind** | Nächtlicher Kaltluftabfluss kühlt Hangfuß bis −3 °C, Poppelsdorfer Allee bis −1 °C (Messungen 1976–84) | Jede Bebauung am Talausgang (z. B. der 2020 per Bürgerentscheid verhinderte Wohnkomplex, aber auch eine große Kletterhalle des "Sportpark"-Vorschlags!) würde die **Frischluftversorgung der Bonner Innenstadt** verschlechtern. Ein flacher Wasser-/Parkbereich erhält und **verstärkt** die Kühlfunktion. |

## 4. Win-Win-Konzept: Das Bad ALS Hochwasserschutz

**Antwort auf die Kernfrage: Ja – und die Topographie macht das Melbbad sogar zum idealen Standort dafür.** Das Konzept heißt **multifunktionale Retentionsfläche** ("Wasserplatz"-Prinzip, bekannt vom Benthemplein Rotterdam; in Deutschland Baustein der wassersensiblen Stadtentwicklung / DWA-Regelwerk zur Überflutungsvorsorge).

### Funktionsweise (Kaskade am Talausgang)

```
Melbtal (NSG)          Melbbad-Gelände                    Poppelsdorf
─────────────►  ┌───────────────────────────────┐  ──────────────────►
 Bach offen     │ 1. Einlaufbereich m. Grobrechen│   Verrohrung (Engpass!)
 ~18‰ Gefälle   │ 2. Renaturierter Bachlauf      │   gedrosselter Abfluss
                │    durchs Gelände (existiert!) │
                │ 3. NORMALFALL: Naturbad + Park │
                │ 4. STARKREGEN: Liegewiesen +   │
                │    Mulden als Einstauflächen,  │
                │    Drosselbauwerk am Auslauf   │
                └───────────────────────────────┘
```

- **Normalfall (99 % der Zeit):** Naturbad, Park, Bachlauf – der Bach fließt wie heute schon durchs Gelände.
- **Starkregen:** Ein Drosselbauwerk am Geländeauslauf begrenzt die Abgabe an die Verrohrung auf deren Kapazität. Der Überschuss staut **kontrolliert** auf tiefer gelegten Liegewiesen/Mulden ein (Einstauhöhe z. B. 0,5–1,5 m) und läuft nach dem Ereignis über die Drossel wieder ab.
- **Die Badebecken selbst** werden durch eine niedrige Geländemodellierung (Verwallung ~0,5 m) vor häufigen kleinen Ereignissen geschützt; bei Extremereignissen dürfen sie **kontrolliert überstaut** werden ("sacrificial flooding") – danach Reinigung statt Totalschaden.

### Warum das Naturbad hier doppelt gewinnt

Der Treppenwitz von 2020: Zerstört wurde damals die **Badewassertechnik**. Ein Naturbad **hat fast keine Technik** (nur eine Pumpe, hochwassersicher aufständerbar) – es ist die einzige Badform, die eine Überflutung ohne Millionenschaden übersteht. Konventionelle DIN-19643-Technik am Talausgang eines Starkregen-Kerbtals zu ersetzen (Plan der Stadt) heißt dagegen: **denselben Fehler wiederholen**.

### Grobe Volumenabschätzung (Plausibilitätsrechnung, zu verifizieren!)

- EZG 5,02 km²; Extremregen 50 mm in 1–2 h ≈ 250.000 m³ Gesamtabfluss (mit Wald-Retention effektiv deutlich weniger, grob 80.000–150.000 m³ Direktabfluss)
- Melbbad-Gelände gesamt ca. 2,5–3 ha; davon einstaubar (Wiesen/Mulden) ca. **1,5–2 ha × 1,0–1,5 m ≈ 15.000–30.000 m³**
- → Das Gelände kann eine Extremwelle nicht vollständig schlucken, aber die **Abflussspitze um die kritische Stunde kappen bzw. verzögern** – genau das, was die Verrohrung vor Überlastung und Poppelsdorf vor Überflutung schützt. Ergänzend: naturnahe Mikro-Retention IM NSG (Totholz, Sohlschwellen, Auenmulden – als NSG-konforme Gewässerentwicklungsmaßnahme sogar erwünscht) plus Regenwassermanagement auf den Höhen (Ippendorf/Venusberg: Abkopplung, Mulden, Zisternen).
- **Benötigt:** hydrologisches Gutachten (HQ100/HQextrem, Kapazität der Verrohrung, N-A-Modell) – Standardleistung eines Wasserwirtschaftsbüros, Kosten grob 20.000–50.000 €. Die Starkregengefahrenkarte Bonn liefert die Vorstufe kostenlos.

### Strategischer Effekt

| Ohne Konzept (Stadt-Plan) | Mit Melbtal-Konzept |
|---|---|
| Bad wird aufgegeben, Gelände "Sportpark" (Kletterhalle = Baukörper in Kaltluftschneise, null zusätzliche Retention) | Bad bleibt + die 2020 nachweislich zu kleine Retention am Talausgang wird um ein Vielfaches vergrößert |
| Starkregenrisiko Poppelsdorf bleibt auf dem Stand von 2020 (kleines HRB + Kanal von 1991 reichten nicht) | Große Retention am Talausgang + Drossel vor der Verrohrung |
| Kosten: Bäderetat (erschöpft) | Finanzierung anteilig aus **Wasserwirtschaft/Klimaanpassung** (HWRM-Förderung NRW, ANK) |
| Verliert gegen Bürgerentscheid-Erbe | Erfüllt Bürgerwillen UND schafft Mehrwert für alle Unterlieger |

Damit wird aus "Poppelsdorf will sein Freibad zurück" (Partikularinteresse) → **"Bonn löst sein Starkregenproblem und bekommt sein erstes Naturbad geschenkt dazu"** (Gemeinwohl). Anwohner, die nie schwimmen gehen, profitieren trotzdem – das verbreitert die Unterstützerbasis für ein Bürgerbegehren erheblich.

## 5. Naturbad-Planungsbüros (für Grobkostenschätzung / Machbarkeitscheck)

| Büro | Profil | Kontakt |
|---|---|---|
| **Polyplan-Kreikenbaum Gruppe GmbH** (Bremen) | Marktführer-Profil: interdisziplinär (Ingenieure, Architekten, Naturwissenschaftler), plant Naturbäder UND DIN-19643-Bäder UND "Bäder in Flüssen und Seen" – ideal für den Variantenvergleich; von Projektentwicklung bis Betriebsbetreuung | https://www.polyplan-kreikenbaum.eu/ · Referenzen: https://www.polyplan-kreikenbaum.eu/leistungen/natur-und-chlorbaeder-alle-arten-von-baedern/ |
| **WasserWerkstatt** (Bamberg / Wien) | Spezialisiert auf Sanierung/Umbau/Neubau von Freibädern zu Naturbädern; veröffentlicht eigene Wirtschaftlichkeitsdaten (siehe KOSTENVERGLEICH.md); Landschaftsarchitekten | http://www.wasserwerkstatt.com/ · Referenzen: http://www.wasserwerkstatt.com/referenzen.php |
| **Büro für Freiraumplanung Griebel** | Öffentliche Naturbäder, Wasserspielplätze, Grünanlagen – passt zum Park-Ansatz | https://www.griebel-naturbad.de/ · Projekte: https://www.griebel-naturbad.de/projekte/oeffentliche-baeder/ |
| **Janisch & Schulz** | Naturbäder + Wassermanagement + Klärtechnik – wasserwirtschaftliche Kompetenz für die Retentions-Komponente | https://janisch-schulz.com/naturbaeder/ |
| **DGfNB-Planersuche** (Verband) | Umkreissuche nach Fachplanern, Fachbetrieben und Sachverständigen; auch Ansprechpartner für Betreiber-Erfahrungsaustausch | https://www.dgfnb.de/planer/ |

**Taktischer Hinweis:** Zwei Büros parallel um eine **kostenlose/kostengünstige Ersteinschätzung** bitten (Ortsbegehung + Grobkosten). Polyplan kann zusätzlich den DIN-19643-Vergleich aus einer Hand liefern → besonders zitierfähig gegenüber der Stadt. Für die Hochwasserkomponente separat ein Wasserwirtschaftsbüro (Suche über BWK NRW / DWA) oder Janisch & Schulz ansprechen.

## 6. Offene Aufgaben

- [ ] DGM1 NRW (opengeodata.nrw.de) für exaktes Geländemodell Bad + Talausgang auswerten (ersetzt EU-DEM-Schätzung)
- [ ] Starkregengefahrenkarte Bonn für Poppelsdorf/Melbtal einsehen (Fließwege, Einstautiefen 2020-Szenario)
- [ ] Kapazität der Melbbach-Verrohrung (Bemessungsabfluss) bei Stadt/Tiefbauamt erfragen (IFG-Anfrage möglich)
- [ ] **Bestehendes HRB oberhalb des Melbbades:** Volumen, Bemessungsereignis, Drosselabfluss und Zustand beim Tiefbauamt erfragen – zentrale Zahl für das Argument "vorhandene Retention zu klein"
- [ ] Kanalbestandsplan Poppelsdorf einsehen: Gibt es unterirdische Stauräume/Becken (z. B. im Bereich Poppelsdorfer Platz)? Bisher kein Beleg gefunden – vor Verwendung des Arguments verifizieren
- [ ] NSG-Verordnung BN-011 im Wortlaut: exakte Grenze am Melbbad, Verbote/Erlaubnisvorbehalte
- [ ] Bachentwicklungsplan 2008 vollständig auswerten (dort steht der Status "renaturiert durchs Bad" + ggf. geplante Maßnahmen)
- [ ] Zwei Planungsbüros kontaktieren (Ortstermin), Wasserwirtschaftsbüro für N-A-Modell identifizieren
- [ ] Referenz "Wasserplatz"/multifunktionale Retention in DE dokumentieren (für Presse-Argumentation)

## 7. Quellen

- Wikipedia Melbbach (amtl. Gewässerdaten LANUV): https://de.wikipedia.org/wiki/Melbbach
- Wikipedia Melbtal (NSG, Geologie, Melbtalwind): https://de.wikipedia.org/wiki/Melbtal
- NSG-Fachinformation LANUV BN-011: https://nsg.naturschutzinformationen.nrw.de/nsg/de/fachinfo/gebiete/gesamt/BN-011
- Bachentwicklungsplan Stadt Bonn 2008: https://web.archive.org/web/20151213063607/https://www2.bonn.de/bo_ris/daten/O/pdf/08/0810154ED2.pdf
- Höhendaten: OpenTopoData EU-DEM 25 m: https://www.opentopodata.org/ (DGM1 NRW: https://www.opengeodata.nrw.de/produkte/geobasis/hm/dgm1_xyz/)
- Starkregen in Bonn (Tiefbauamt-Broschüre 2025): https://www.bonn.de/medien-global/amt-66/66.05_BR_Starkregen-2025_WEB.pdf
- Bachentwicklungsplan 2008, Steckbrief Engelsbach (5.1): HRB oberhalb des Melbbades (Stat. 3,27–3,30, Erdbecken, Neubau bei Offenlegung 2005); Rheinmündung seit 25.2.1994; Abfluss 5–40 l/s normal / 2.100 l/s Hochwasser
- RRB Hauweg (Venusberg), Stadt Bonn Pressemitteilung 30.1.2024: https://www.bonn.de/pressemitteilungen/januar-2024/vorbereitende-arbeiten-fuer-neues-regenrueckhaltebecken-am-hauweg.php · Baubericht 2026: https://www.treffpunkt-bau.eu/news/2026-01-22/kliemt-gruppe-mehr-schutz-bei-starkregen-neues-regenrueckhaltebecken-am-venusberg-in-bonn-erstellt/
- GA zum Starkregen 2020 ("Bach konnte Wasser … nicht mehr aufnehmen"): https://ga.de/bonn/stadt-bonn/bonn-melbbad-neues-lebenszeichen-nach-langem-stillstand_aid-146154641
- Planungsbüros: siehe Tabelle Abschnitt 5
