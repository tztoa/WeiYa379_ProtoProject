## Projektziel

Ziel des Projekts ist es, mithilfe eines Raspberry Pi und eines LCD-Displays im Digilab das aktuelle Wetter in Berlin anzuzeigen. Per Knopfdruck wird entweder die Temperatur oder eine passende Handlungsempfehlung angezeigt (z. B. „Zieh dich warm an“). Bei langen Texten wird automatisch ein Scroll-Effekt auf dem Display ausgelöst, um die gesamte Nachricht sichtbar zu machen.

---

## Projektphasen und Arbeitsschritte

### Phase 1 – Planung
- Projektidee festlegen
- Anforderungen und Komponenten definieren (Buttons, API, LCD)
- API-Anbieter recherchieren (z. B. OpenWeatherMap)

**Wichtigkeit:** Sehr hoch – Grundlage für alle weiteren Schritte

### Phase 2 – Hardwareaufbau
- Raspberry Pi einrichten
- LCD und Buttons mit GPIO verbinden
- Funktionsprüfung der Hardware

**Wichtigkeit:** Hoch – ohne stabile Hardware keine zuverlässige Funktion

### Phase 3 – Softwareentwicklung
- Wetterdaten per API abrufen
- Temperatur auswerten und Empfehlung erzeugen
- LCD-Ausgabe mit Scroll-Funktion programmieren
- Button-Ereignisse verarbeiten

**Wichtigkeit:** Sehr hoch – zentrale Logik des Projekts

### Phase 4 – Test und Optimierung
- Funktionstests mit verschiedenen Temperaturen
- Überprüfung der Scrollfunktion
- Fehlerbehandlung einbauen

**Wichtigkeit:** Mittel – wichtig für Benutzerfreundlichkeit und Stabilität

### Phase 5 – Dokumentation
- README und Aufbauplan erstellen
- Code kommentieren
- Nutzung und Anschluss dokumentieren

**Wichtigkeit:** Hoch – sorgt für Verständlichkeit und Wiederverwendbarkeit

---

## Verwendete Technologien

- Raspberry Pi (mit GPIO)
- LCD-Display (16x2 oder 20x4)
- Zwei Buttons zur Steuerung
- Javascript/Json zur Ansteuerung und Logik
- OpenWeatherMap API zur Wetterabfrage

---

## Lösungsansätze

- Temperaturbereiche werden in Javascript logisch ausgewertet
- Scrolling-Funktion zeigt lange Texte auf kleinem Display lesbar an
- Bedienung erfolgt komplett über Hardware (keine Tastatur/Maus nötig)

---

## Besonderheiten

Das Projekt ist eine Kombination aus Hardware und Software mit einem klaren Alltagsbezug. Es zeigt, wie man mit wenig Komponenten ein interaktives, alltagstaugliches System bauen kann. Die automatische Textverschiebung auf einem begrenzten LCD-Display macht das Projekt besonders praktisch und benutzerfreundlich.
