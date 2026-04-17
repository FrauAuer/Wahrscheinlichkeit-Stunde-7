# 🎡 Wie oft landest du auf welcher Farbe? (Ein Glücksrad)

Dieses Projekt ermöglicht es Schülerinnen und Schülern, Ergebnisse eines Glücksrads digital zu erfassen und gemeinsam auszuwerten. Die Daten werden in einer Firebase-Datenbank gespeichert und im Dashboard visualisiert.

---

## 📁 Projektstruktur

- index.html → Eingabeseite für die Schülerinnen und Schüler fileciteturn4file0  
- dashboard.html → Anzeige der Ergebnisse (Diagramm + Tabelle) fileciteturn4file2  
- firebase-config.js → Verbindung zur Firebase-Datenbank fileciteturn4file1  

---

## 🚀 Funktionen

### Eingabeseite (index.html)
- Eingabe der Gruppennummer
- Eingabe der Ergebnisse:
  - blaue Felder
  - gelbe Felder
- Automatische Berechnung der Gesamtanzahl der Drehungen
- Eingabefelder:
  - „0“ verschwindet beim Klicken
  - leere Felder werden wieder zu „0“
- Speicherung per Klick auf „senden“

---

### Dashboard (dashboard.html)
- Darstellung der Ergebnisse als **Säulendiagramm**
- Übersichtliche Tabelle aller Gruppen
- Automatische Sortierung nach Gruppennummer
- Anzeige von:
  - Anzahl der Gruppen
  - Gesamtanzahl der Drehungen

---

## 🔧 Einrichtung

1. Firebase-Projekt erstellen  
2. Firebase-Konfiguration in `firebase-config.js` eintragen  
3. Dateien hochladen (z. B. Firebase Hosting)  

---

## 🔑 Nutzung

### Für Schülerinnen und Schüler:
1. Eingabeseite öffnen (`index.html`)
2. Passwort eingeben (z. B. „22“)
3. Gruppennummer eintragen
4. Ergebnisse eintragen
5. Auf „senden“ klicken

---

### Für die Lehrkraft:
1. Dashboard öffnen (`dashboard.html`)
2. Passwort eingeben
3. Auf „anzeigen“ klicken
4. Ergebnisse gemeinsam auswerten

---

## 📊 Didaktischer Einsatz

- Einführung in Wahrscheinlichkeiten bei Glücksrädern
- Vergleich von Häufigkeiten
- Förderung mathematischer Argumentation:
  - „Welche Farbe kommt häufiger vor?“
  - „Ist das Glücksrad fair?“
- Visualisierung im Klassenverband

---

## 💡 Hinweise

- Nur numerische Gruppennummern erlaubt
- Mindestens ein Wert muss größer als 0 sein
- Speicherung erfolgt unter:
  ```
  Stunde7/{Passwort}/groups/{Gruppennummer}
  ```

---

## 👩‍🏫 Autorin

Leonie Auer  
Lehramtsanwärterin (Primarstufe)  
Fach: Mathematik  

---
