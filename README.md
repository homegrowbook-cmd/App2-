# LinguaBrasil 🇧🇷

**Brasilianisches Portugiesisch lernen – für Deutsch- und Englischsprachige**  
*Learn Brazilian Portuguese – for German and English speakers*

Eine kostenlose, browserbasierte HTML-App ohne Installation, die wissenschaftlich fundierte Lernmethoden (Spaced Repetition, Gamification, strukturierter Lehrplan) vereint.

> **Aktueller Stand: v3.5** – 394 Vokabeln & Sätze, 16 Kategorien, 8 Übungstypen, Story-Reader, Level-Tests, Favoriten-System

---

## 🚀 App starten / Launch App

👉 **[LinguaBrasil direkt im Browser öffnen](https://homegrowbook-cmd.github.io/App2-/)** *(GitHub Pages)*

### 📱 Als PWA installieren (iOS & Android)

LinguaBrasil funktioniert auf Smartphone und Tablet als vollwertige Offline-App:

**iOS (Safari):**
1. Öffne **[https://homegrowbook-cmd.github.io/App2-/](https://homegrowbook-cmd.github.io/App2-/)** in **Safari**
2. Tippe auf das **Teilen-Symbol** (⬆️ unten in der Mitte)
3. Wähle **„Zum Home-Bildschirm"** (ggf. nach unten scrollen)
4. Tippe oben rechts auf **„Hinzufügen"**

**Android (Chrome):** Tippe auf das Menü → „Zum Startbildschirm hinzufügen"

Die App startet ohne Browser-Leiste, funktioniert offline und hat ein eigenes App-Icon – genauso wie eine native App.

Oder lokal: Lade `index.html` herunter und öffne sie in deinem Browser – keine Installation nötig!

```
open index.html
```

---

## ✨ Features (v3.5 – aktuell)

### 🗣️ Lerninhalte
- 🌍 **4 Lernrichtungen**: DE→PT, EN→PT, PT→DE, PT→EN
- 📚 **394 Vokabeln & Sätze** in **16 Kategorien** (A1/A2-Niveau)
- 💬 **30 Alltagssätze** mit kontextueller Bedeutungserklärung
- 📖 **14 Grammatik-Karten** inkl. 3 Kulturkarten (Karneval, Küche, Geografie)
- 📕 **5 thematische Geschichten** (Story Reader) – A1/A2 Lesetexte mit Vokabel-Popups + TTS

### 🎯 Übungstypen
- 🃏 **Karteikarten** mit Spaced Repetition (SRS Level 0–5)
- 🎯 **Multiple-Choice-Quiz** (12 Fragen, +15 XP)
- ⌨️ **Tipp-Übungen** mit Akzent-Normalisierung
- 🔊 **Hörverständnis-Quiz** (TTS-Audio → Übersetzung wählen)
- 🧩 **Satz-Builder** (Wörter in richtige Reihenfolge bringen, 8 Runden)
- 💬 **Dialog-Übungen** (12 Alltagsszenarien, +20 XP)
- 🎓 **Level-Tests A1 / A2** (je 20 Fragen; Zertifikat bei ≥ 70 %)
- ⭐ **Favoriten-Session** – markierte Wörter gezielt üben

### 🎮 Gamification & Motivation
- ⭐ **XP-System** mit konfigurierbarem Tages-Ziel (Standard 50 XP)
- 🔥 **Tages-Streaks** + Streak-XP-Multiplikator (≥3/7/14 Tage: +1/+2/+5 XP)
- ➖ **XP-Strafpunkte** bei falschen Antworten (−5 XP, abschaltbar)
- 🏆 **10 Achievements** (Wörter gelernt, Streaks, XP-Meilensteine)
- 📊 **Fortschrittsbildschirm** mit Kategorie-Balken, SRS-Verteilung, Fehler-Analyse

### ⚙️ Einstellungen & UX
- 🌙 **Dark Mode** (persistent gespeichert)
- 🔡 **Schriftgröße** (Klein / Normal / Groß)
- 🔍 **Wortliste** mit Suchfunktion, Kategorie-Filter, SRS-Level-Badge und TTS
- 🔄 **Force-Update** (Cache leeren ohne Browser-Einstellungen)
- 💾 **LocalStorage-Persistenz** – kein Server, kein Login nötig
- 📵 **Vollständig offline nutzbar** (PWA, Service Worker)

---

## 📖 Dokumentation

- [`ROADMAP.md`](ROADMAP.md) – Vollständiger Entwicklungsplan v1.0 → v4.0
- [`ANALYSIS.md`](ANALYSIS.md) – Analyse der Top 10 Sprachenlern-Apps & Lernmethoden

## 🗺️ Roadmap-Übersicht

| Phase | Inhalt | Status |
|-------|--------|--------|
| v1.0 | MVP: SRS, Karteikarten, Quiz, Gamification | ✅ Fertig |
| v2.0 | Audio (TTS), Tipp-Übungen, PWA, Grammatik | ✅ Fertig |
| v3.0–3.5 | 394 Vokabeln, alle Übungstypen, Stories, Level-Tests | ✅ Fertig |
| **v4.0** | **KI-Konversation, Cloud-Sync, Erweiterungen** | 🚀 In Planung |

Details → [`ROADMAP.md`](ROADMAP.md)

---

## 🛠️ Technischer Stack

- Reines **HTML5 + CSS3 + Vanilla JavaScript** (keine Abhängigkeiten)
- **Progressive Web App** (PWA) – offline nutzbar, installierbar
- **Service Worker** (Cache-Strategie: Network-first)
- Einzige App-Datei: `index.html`