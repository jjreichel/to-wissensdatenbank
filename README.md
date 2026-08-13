# Trans-Ocean WhatsApp Wissensdatenbank

Gesammeltes Segler-Wissen aus den Trans-Ocean WhatsApp-Gruppen — aufbereitet als durchsuchbare Wissensdatenbank.

🌐 **Online:** https://jjreichel.github.io/to-wissensdatenbank/

**Version 2.4** · 2.712 Einträge · 15 Themen · ausgewertet August 2025 bis August 2026

---

## Inhalt

**Technik an Bord** — 1.415 Einträge

| Thema | Inhalt | Einträge |
|-------|--------|---------:|
| Elektrik | Batterien, LiFePO4, Solar, Windgeneratoren, Victron, AIS/VHF, Blitzschutz | 385 |
| Motorentechnik | Dieselmotoren, Kraftstoff, Filter, Turbo, Propeller, Wellenanlage | 329 |
| Mechanik | Werften, Antifouling, Dichtungen, Dinghy, Rigg, Anker | 277 |
| Satellit | Starlink, Iridium, Garmin inReach, SIM-Karten, Router | 195 |
| Wassersysteme | Watermaker, Tanks, Boiler, Pumpen, Sanitär | 165 |
| Funk | VHF, SSB/HF, DSC, MMSI, Antennen, Funkzeugnisse | 64 |

**Reviere** — 645 Einträge

| Thema | Inhalt | Einträge |
|-------|--------|---------:|
| Mittelmeer | Häfen, Winterlager, Einklarieren, Bürokratie, lokale Adressen | 292 |
| Karibik | Einklarierung, Inseln, Werften, Hurricane-Holes | 133 |
| Atlantik | Überquerungsrouten, ARC, Kanaren, Kapverden | 86 |
| Navigation | Seekarten, Plotter, OpenCPN, Navionics, Tablets | 65 |
| Wetter | GRIB, PredictWind, Windy, Routing, Hurricane-Saison | 69 |

**Sicherheit** — 322 Einträge

| Thema | Inhalt | Einträge |
|-------|--------|---------:|
| Sicherheit | Rettungswesten, MOB, EPIRB, Brandschutz, Orca, Piraterie | 148 |
| Versicherungen | Yacht-, Kasko- und Krankenversicherung für Langfahrt | 174 |

**Weiteres** — 330 Einträge

| Thema | Inhalt | Einträge |
|-------|--------|---------:|
| Lossegler | Community, Treffen, Yachtkauf, Langfahrt-Alltag, Azoren, Biskaya | 106 |
| Diverses | Orcas, Angeln, Tauchen, 3D-Druck, Rotes Meer, Bordelektronik | 224 |

## Features

- **Fragen statt blättern** — Frage in eigenen Worten stellen, passende Einträge erscheinen; ohne Sprachmodell, es wird gefunden statt formuliert
- Volltext-Suche über alle Themen (`⌘ K`)
- Offline nutzbar — `index.html` und `data.js`, keine externen Abhängigkeiten
- Helles Layout im Stil eines Logbuchs
- Versionsanzeige mit Verlauf, direkt in der Oberfläche

## Versionierung

Die **Hauptversion** steht für den Stand der Sammlung, die **Nebenversion** für die umgesetzten Schritte der [Roadmap](ROADMAP.md).

| Version | Stand | Inhalt |
|---------|-------|--------|
| **2.4** | August 2026 | Phase 4 · Frageoberfläche über der Sammlung, ohne Sprachmodell |
| 2.3 | August 2026 | Phase 3 · Aktualität lösen — zeitkritische Einträge gekennzeichnet, Verfallslogik, Korrektur-Kanal |
| 2.2 | August 2026 | Phase 2 · Transparenz herstellen — Methodik-Seite, gemessene Quellgruppen-Matrix, Belegdichte, Quellgruppe und Fundzeitraum für 834 Einträge, Sicherheitshinweise |
| 2.1 | August 2026 | Phase 1 · Vertrauen sichern — Bestandsprüfung, Grundsätze, Fundstellen-Verfahren |
| 2.0 | August 2026 | Auswertung bis August 2026, Bestand auf 2.712 Einträge erweitert |
| 1.0 | April 2026 | Erste Fassung mit 1.629 Einträgen |

Geplant ist 2.5 für die Governance-Entscheidung der Phase 4. Der vollständige Verlauf steht im [Changelog](CHANGELOG.md) und ist in der Oberfläche über die Versionsanzeige abrufbar.

## Quelle

Aus Trans-Ocean WhatsApp-Gruppen extrahiertes Wissen. Ausgewertet: August 2025 bis August 2026.

Veröffentlicht wird ausschließlich verdichtetes Sachwissen — keine Chatverläufe, keine Zitate, keine Urheber, kein Personenbezug. Welche Gruppen ausgewertet werden und welche **dauerhaft ausgeschlossen** sind (u. a. Frauen-, Kinder- und Medizingruppen), steht verbindlich in den **[Grundsätzen](GRUNDSAETZE.md)**.

## Fundstellen-Verfahren

**Wer sich selbst oder Dritte in einem Eintrag wiedererkennt, meldet die Fundstelle — der Eintrag wird binnen 24 Stunden entfernt.**

So geht es:

1. **Fundstelle melden** — Kapitel und Wortlaut des Eintrags, per [Issue](https://github.com/jjreichel/to-wissensdatenbank/issues) oder direkt an den Verantwortlichen.
2. **Löschung binnen 24 Stunden** — ohne Begründungspflicht und ohne vorherige Prüfung, ob die Zuordnung zutrifft. Im Zweifel wird gelöscht, nicht diskutiert.
3. **Dokumentation** — die Löschung wird im [Changelog](CHANGELOG.md) festgehalten, ohne Angaben zur meldenden Person.

Meldungen werden vertraulich behandelt.

## Korrektur-Kanal

Für **veraltete oder fachlich falsche Einträge** gibt es einen eigenen Weg: In der Weboberfläche steht unter jedem Kapitel **Korrektur melden**, der Link öffnet ein vorbereitetes [Formular](https://github.com/jjreichel/to-wissensdatenbank/issues/new?template=veralteter-eintrag.yml) mit vorbelegtem Kapitel. Besonders hilfreich ist ein Stand — „Juli 2026 vor Ort geprüft" ist mehr wert als eine Zahl ohne Datum.

Zeitkritische Einträge (Preise, Gebühren, Behörden) sind in der Oberfläche als solche markiert; 205 von ihnen haben kein zuordenbares Datum.

## Grenzen

Die Sammlung ist eine Momentaufnahme von Community-Wissen, keine geprüfte Fachauskunft. Einträge können veraltet oder falsch sein. Sie sind **mit KI-Unterstützung aus den Gruppenbeiträgen verdichtet** und fachlich nicht systematisch geprüft — der Erhebungsweg und seine Folgen stehen auf der Methodik-Seite. Sie **ersetzt keinen fachlichen Rat**, insbesondere nicht bei medizinischen, rechtlichen, versicherungs- oder sicherheitsrelevanten Fragen.

Dies ist ein privates Projekt und keine Veröffentlichung des Trans-Ocean e. V.

## Weiteres

- [Grundsätze](GRUNDSAETZE.md) — Quellgruppen, Ausschlüsse, Fundstellen-Verfahren im Detail
- [Roadmap](ROADMAP.md) — geplante Weiterentwicklung
- [Changelog](CHANGELOG.md) — Versionen, Löschungen und Änderungen an den Grundsätzen

---

© J.J.Reichel
