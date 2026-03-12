# 🐠 Reef Tracker — Demo

Eine vollständig funktionsfähige Demo-Version von Reef Tracker — kein Login, keine Cloud, läuft direkt im Browser.

👉 **[Demo öffnen](https://s1lum.github.io/reef-tracker-demo/)**

---

## Was ist die Demo?

Die Demo ist identisch mit der Vollversion — alle Funktionen sind enthalten. Der einzige Unterschied: Daten werden lokal im Browser gespeichert (`localStorage`) statt in der Cloud. Kein Google-Login erforderlich.

| | Demo | Vollversion |
|---|---|---|
| Login erforderlich | ❌ | ✅ Google |
| Datenspeicherung | Browser (localStorage) | Firebase Cloud |
| Sync zwischen Geräten | ❌ | ✅ Echtzeit |
| Alle Features | ✅ | ✅ |
| Offline-fähig | ✅ | ✅ |

---

## Features

### 📋 Log
- Manuelle Messeingabe mit allen Parametern (Salinität, KH, Ca, Mg, NO₃, PO₄, und viele mehr)
- ICP-Analysen importieren und mit eigenen Messungen vergleichen
- **Hanna PO₄ Umrechner** — ppb direkt in ppm umrechnen, Referenztabelle 1–200 ppb
- Kalibrierungs-Offsets pro ICP setzen (⚖️)

### 📈 Charts
- Zeitverlauf für alle Parametergruppen
- Kalibrierte Werte als Dreiecke ▲, ICP-Werte als Rauten ◆

### 📊 Stats
- Ampel-Auswertung aller Parameter gegen Zielwerte
- Min / Max / Durchschnitt auf einen Blick

### 🐠 Inhabitants
- Fische, Korallen und Wirbellose mit Emoji und Notizen erfassen

### 🔔 Reminders
- Erinnerungen für Wasserwechsel, Dosierung, Tests

### 🧰 Tools
- **💊 Dosing Journal** — Dosiervorgänge dokumentieren
- **🧂 Salt Calculator** — Salzmenge für Wasserwechsel berechnen
- **⚗️ Balling Light** — Ca / Alk / Mg Nachfüllung berechnen

### Mehrere Becken
- Beliebig viele Becken anlegen und zwischen ihnen wechseln

---

## Datenspeicherung

Alle Daten werden im **localStorage** des Browsers gespeichert. Sie bleiben erhalten solange der Browser-Cache nicht geleert wird. Für langfristige Sicherung empfiehlt sich ein **JSON-Backup** über das Menü (🐠 Avatar oben rechts → Backup).

---

## Als App installieren (iPhone)

1. Seite in **Safari** öffnen
2. Teilen-Button tippen → „Zum Home-Bildschirm"
3. Name bestätigen → „Hinzufügen"

Die Demo läuft dann wie eine native App — auch ohne Internetverbindung.

---

## Vollversion

Für geräteübergreifenden Sync und Cloud-Backup gibt es die Vollversion mit Google-Login:  
👉 [reef-tracker (Firebase)](https://s1lum.github.io/reef-tracker/)
