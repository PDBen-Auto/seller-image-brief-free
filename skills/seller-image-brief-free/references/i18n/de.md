# Verkaufsbild-Briefing Free

`seller-image-brief-free` · Deutsch

## Zweck und Einsatzbereich

Bis zu drei verschiedene E-Commerce-Bilder aus Produktfakten und Rezensionen nach FABE planen; ausführbare Briefings statt fertiger Bilder.

## Umsetzungsgrundlage und Abhängigkeiten

Text-/CSV-/Tabellen-lesender Agent, Modell und Produktfakten. Kein externes Konto/API/Netz für Kernarbeit; Modellkosten trägt die Umgebung. Veröffentlichbare Aussagen brauchen Belege und aktuelle Plattformregeln.

## Eingaben

Produkt/Kategorie/Version/Markt erforderlich. Optional erlaubte Rezensionen, Fotos/Maße/Tests, Sprache/Format. Maximal drei Bilder. Upgradehinweis per Nutzerwunsch oder verfügbarem SELLER_IMAGE_NO_UPSELL=1 abschaltbar.

## Ausgaben

Chat oder Markdown mit Belegumfang, Käuferfragen, bis zu drei Karten mit F/A/B/E, Komposition, Kamerawinkel, Kurztext, Belegstatus, Abnahmekriterien und offenen Aussagen.

## Ablauf

1. Umfang/Rezensions-IDs prüfen
2. Beobachtung und Schluss trennen
3. verschiedene Kaufhürden wählen und Doppeltes verbinden
4. Merkmal/Vorteil/Nutzen mit Beleg verbinden
5. Motiv, Position, Winkel, Aktion und Prüfung angeben
6. Passform-/Leistungslücken nennen
7. erst nach Lieferung höchstens einen passenden optionalen Hinweis.

## Grenzen und Abbruchbedingungen

Keine Sammlung, erfundenen Anteile, Konversionsversprechen oder fertigen Bilder behaupten. Wenig Belege erlauben weniger Karten. Keine Pro-Preise/URLs erfinden oder Upgrade erzwingen. Ohne Regelprüfung nicht listenfertig nennen.

## Beispielanfrage

Verwende `$seller-image-brief-free` — Trennfächer eines Organizers belegt darstellen, ohne Test keine Wasserdichtigkeit behaupten; antworte auf Deutsch und erhalte Belege, unbekannte Werte und Berechtigungsgrenzen.

## Vollständige Spezifikation

[Skill-Einstieg und Detailreferenzen](../../SKILL.md).

Die ausdrücklich gewünschte Ausgabesprache verwenden, sonst der Sprache der Anfrage folgen. Befehle, Skill-IDs, JSON-Schlüssel, Enumerationswerte, Einheiten und Originalzitate unverändert lassen. Übersetzungen kennzeichnen. Land, Währung und Rechtsordnung nicht aus der Sprache ableiten. Relevante Detailreferenzen lesen und sämtliche bestehenden Prüfungen und Berechtigungsgrenzen einhalten.

Vor der Übergabe Eingaben, Belege, fehlende Werte, Ausgabedateien und ursprüngliche Abschlusskriterien abgleichen. Nicht ausgeführte Schritte als ungeprüft kennzeichnen; ein erfolgreicher Skriptablauf bestätigt keine geschäftliche Aussage.

## Sprachumfang und Prüfung

Dieser lokalisierte Leitfaden umfasst Zweck, Voraussetzungen, Ein- und Ausgaben, Ablauf, Beispiele und Grenzen. Er übersetzt nicht jede Referenz Zeile für Zeile. Technische Detailreferenzen, historische Fälle, Skriptfehler, Beispieloberflächen und Bilder bleiben in der Originalsprache und können auf Wunsch erläutert werden. Struktur, Links und Kernbedingungen werden geprüft; ein muttersprachliches Lektorat je Sprache wird nicht behauptet.

