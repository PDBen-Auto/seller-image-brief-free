# Verkaufsbild-Briefing Free

[简体中文](README.zh-CN.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português](README.pt.md)

Die ausdrücklich gewünschte Ausgabesprache verwenden, sonst der Sprache der Anfrage folgen. Befehle, Skill-IDs, JSON-Schlüssel, Enumerationswerte, Einheiten und Originalzitate unverändert lassen. Übersetzungen kennzeichnen. Land, Währung und Rechtsordnung nicht aus der Sprache ableiten. Relevante Detailreferenzen lesen und sämtliche bestehenden Prüfungen und Berechtigungsgrenzen einhalten.

## Installation und Nutzung

Das Repository herunterladen oder klonen und das angegebene Skill-Verzeichnis mit seinen vorhandenen references, scripts, assets und weiteren Abhängigkeiten in das Skill-Verzeichnis des Hosts kopieren. Name und SKILL.md beibehalten. Ein Sprachwechsel erfordert keine weitere Installation. Installationsbefehle sind Optionen und kein Nachweis einer Installation oder Aktivierung.

```sh
git clone https://github.com/PDBen-Auto/seller-image-brief-free.git
```

## Verkaufsbild-Briefing Free

`seller-image-brief-free`

Bis zu drei verschiedene E-Commerce-Bilder aus Produktfakten und Rezensionen nach FABE planen; ausführbare Briefings statt fertiger Bilder.

Skill-Verzeichnis: `skills/seller-image-brief-free`

**Umsetzungsgrundlage und Abhängigkeiten**

Text-/CSV-/Tabellen-lesender Agent, Modell und Produktfakten. Kein externes Konto/API/Netz für Kernarbeit; Modellkosten trägt die Umgebung. Veröffentlichbare Aussagen brauchen Belege und aktuelle Plattformregeln.

**Eingaben**

Produkt/Kategorie/Version/Markt erforderlich. Optional erlaubte Rezensionen, Fotos/Maße/Tests, Sprache/Format. Maximal drei Bilder. Upgradehinweis per Nutzerwunsch oder verfügbarem SELLER_IMAGE_NO_UPSELL=1 abschaltbar.

**Ausgaben**

Chat oder Markdown mit Belegumfang, Käuferfragen, bis zu drei Karten mit F/A/B/E, Komposition, Kamerawinkel, Kurztext, Belegstatus, Abnahmekriterien und offenen Aussagen.

[Ablauf · Grenzen und Abbruchbedingungen · Beispielanfrage](skills/seller-image-brief-free/references/i18n/de.md)

> Verwende `$seller-image-brief-free` — Trennfächer eines Organizers belegt darstellen, ohne Test keine Wasserdichtigkeit behaupten; antworte auf Deutsch und erhalte Belege, unbekannte Werte und Berechtigungsgrenzen.

## Sprachumfang und Prüfung

Dieser lokalisierte Leitfaden umfasst Zweck, Voraussetzungen, Ein- und Ausgaben, Ablauf, Beispiele und Grenzen. Er übersetzt nicht jede Referenz Zeile für Zeile. Technische Detailreferenzen, historische Fälle, Skriptfehler, Beispieloberflächen und Bilder bleiben in der Originalsprache und können auf Wunsch erläutert werden. Struktur, Links und Kernbedingungen werden geprüft; ein muttersprachliches Lektorat je Sprache wird nicht behauptet.

Vor der Übergabe Eingaben, Belege, fehlende Werte, Ausgabedateien und ursprüngliche Abschlusskriterien abgleichen. Nicht ausgeführte Schritte als ungeprüft kennzeichnen; ein erfolgreicher Skriptablauf bestätigt keine geschäftliche Aussage.
