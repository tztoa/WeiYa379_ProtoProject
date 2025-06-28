# Wetteranzeige Berlin – Raspberry Pi Projekt mit Digilab

## Projektbeschreibung

Dieses Projekt zeigt das aktuelle Wetter in **Berlin** auf einem **LCD-Screen** im **Digilab** mithilfe eines **Raspberry Pi** an.  
Die Anzeige und Steuerung erfolgen über zwei Buttons:

### Button 1 – Wetter anzeigen
Beim Drücken dieses Buttons wird über eine Wetter-API die aktuelle Temperatur in Berlin abgerufen und auf dem LCD-Display angezeigt.

### Button 2 – Wetter Anzeige
Basierend auf der Temperatur zeigt der Raspberry Pi eine passende Nachricht auf dem Display:

- **Wenn Temperatur < 10°C**  
  > *„Zieh dich warm an“*

- **Wenn Temperatur zwischen 10°C und 30°C**  
  >  *„Perfektes Wetter“*

- **Wenn Temperatur > 30°C**  
  > *„Drink mehr Wasser, es ist warm“*

---

## Besonderheit: Scrollende Texte

Das LCD-Display hat nur begrenzten Platz pro Zeile.  
Deshalb wurde eine **automatische Textverschiebung (Scrolling)** programmiert:  
> Wenn ein Satz zu lang für das Display ist, **scrollt der Text nach rechts**, sodass der ganze Satz sichtbar wird.

---

## 🔧 Verwendete Technologien

- **Raspberry Pi** mit Python
- **Digilab Umgebung**
- **LCD-Display**
- **Wetter-API** (z. B. [Die Website von wo ich mein API bekommen habe](https://openweathermap.org/))
-  Zwei Hardware-Buttons

---



