# 2025-2026-SWPP

### 1. GitHub Flow

**Merkmale**

* Nur ein Hauptbranch (`main`)
* Für jedes Feature ein eigener Branch
* Merge per Pull Request

**Vorteile**

* Sehr leicht verständlich
* Schnell einsetzbar
* Gut für kleine bis mittlere Projekte

**Nachteile**

* Weniger geeignet für große Release-Pläne
* Kaum Struktur für mehrere Versionen


### 2. GitFlow

**Merkmale**

* Zwei Hauptbranches (`main` und `develop`)
* Extra Branches für Features, Releases und Hotfixes
* Feste Struktur für Versionen

**Vorteile**

* Gute Übersicht bei großen Projekten
* Klare Trennung von Entwicklung und Produktivversion

**Nachteile**

* Komplizierter
* Mehr Aufwand beim Zusammenführen


### 3. Trunk-Based Development

**Merkmale**

* Ein zentraler Branch
* Sehr kurze oder keine Feature-Branches
* Häufiges Zusammenführen

**Vorteile**

* Schnelle Entwicklung
* Weniger Merge-Probleme

**Nachteile**

* Gute Tests sind wichtig
* Team muss gut zusammenarbeiten
