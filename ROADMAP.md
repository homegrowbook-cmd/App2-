# LinguaBrasil – App Roadmap

## Vision
Eine kostenlose, browserbasierte HTML-App zum Erlernen von Brasilianischem Portugiesisch für Deutsch- und Englischsprachige – wissenschaftlich fundiert, gamifiziert und ohne Installation nutzbar.

---

## Phase 1 – MVP (v1.0) ✅ *Erledigt*

> **Abgeschlossen** – App läuft live unter: [https://homegrowbook-cmd.github.io/App2-/](https://homegrowbook-cmd.github.io/App2-/)

**Ziel:** Funktionsfähige Basis-App mit den wichtigsten Lernfunktionen

### Features
- [x] Sprachauswahl: Deutsch → Brasilianisches Portugiesisch / Englisch → Brasilianisches Portugiesisch
- [x] 8 Vokabelkategorien: Begrüßungen, Zahlen, Farben, Essen, Reisen, Familie, Wochentage, Verben
- [x] ~100 Vokabeln mit Ausspracheführer und Beispielsätzen
- [x] **Karteikarten-Modus** (Flashcard Mode) mit visueller Karte und Bewertung
- [x] **Quiz-Modus** (Multiple Choice, 4 Antwortmöglichkeiten)
- [x] **Spaced Repetition System (SRS)** – Level 0–5 mit intelligenten Wiederholungsintervallen
- [x] **XP-System** – Erfahrungspunkte für korrekte Antworten
- [x] **Tages-Streaks** – Motivation zur täglichen Nutzung
- [x] **Fortschrittsbildschirm** – SRS-Level, Kategorie-Fortschritt, Gesamtstatistiken
- [x] **LocalStorage-Persistenz** – Fortschritt bleibt gespeichert
- [x] **Mobil-responsives Design** – Brasilianisches Farbthema (Grün/Blau/Gelb)

### Technischer Stack
- Reines HTML5 + CSS3 + Vanilla JavaScript (keine Abhängigkeiten)
- Offline-nutzbar (keine Serveranforderungen)
- Einzige Datei: `index.html`

---

## Phase 2 – Audio & Interaktion (v2.0)

**Ziel:** Hör- und Sprachkompetenz verbessern

### Geplante Features
- [ ] **Web Speech API Integration** – Text-to-Speech für alle Vokabeln (brasilianisches Portugiesisch)
- [ ] **Aussprache-Übungen** – Mikrofon-Input, Vergleich mit Zielaussprache
- [ ] **Hörverständnis-Quiz** – Audio abspielen, richtiges Wort tippen/wählen
- [ ] **Tipp-Übungen** – Wort eintippen statt Multiple Choice
- [ ] **Lernpfad-System** – Sequenzieller Fortschritt (A1 → A2 → B1)
- [ ] **Fehler-Analyse** – Häufig falsch gemachte Wörter gezielt üben
- [ ] **Grammatik-Karten** – Kurze Grammatikregeln mit Beispielen (Genus, Konjugation)

### Technische Erweiterungen
- Service Worker für Offline-Nutzung (PWA)
- Web App Manifest (installierbar auf Smartphone)
- IndexedDB für größere Datensätze

---

## Phase 3 – Inhalte & Struktur (v3.0)

**Ziel:** Vollständiger A1–B1 Lehrplan

### Geplante Features
- [ ] **Erweiterter Wortschatz** – 500+ Vokabeln je Sprache
- [ ] **Grammatik-Lektionen** – Strukturierte Einheiten zu: Artikel, Präsens, Vergangenheit, Zukunft, Konjunktiv
- [ ] **Satz-Builder** – Sätze aus Wörtern zusammensetzen (Drag & Drop)
- [ ] **Dialog-Übungen** – Typische Alltagsgespräche nachspielen
- [ ] **Thematische Geschichten** – Kurze Texte auf Portugiesisch mit Vokabel-Highlighting
- [ ] **Kulturelle Lektionen** – Brasilianische Feste, Küche, Musik, Slang
- [ ] **Leistungsnachweise** – Level-Tests, Zertifikate (A1, A2)

---

## Phase 4 – Social & KI (v4.0)

**Ziel:** Community und KI-gestützte Personalisierung

### Geplante Features
- [ ] **KI-Konversationspartner** – Chatbot für Übungsgespräche auf Portugiesisch
- [ ] **Sprachtausch-Matching** – Nutzer mit brasilianischen Muttersprachlern verbinden
- [ ] **Ranglisten & Challenges** – Wöchentliche Wettbewerbe mit Freunden
- [ ] **Spaced Repetition 2.0** – ML-basierte Anpassung der Lernintervalle
- [ ] **Benutzerkonten & Cloud-Sync** – Fortschritt geräteübergreifend speichern
- [ ] **Weitere Sprachen** – Spanisch, Französisch, Italienisch

---

## Technische Architektur (Langfristig)

```
LinguaBrasil/
├── index.html          # Haupt-App (MVP: alles in einer Datei)
├── ANALYSIS.md         # App-Analyse & Methodik-Forschung
├── ROADMAP.md          # Diese Roadmap
├── v2/                 # Zukünftige Version
│   ├── index.html
│   ├── app.js
│   ├── styles.css
│   ├── data/
│   │   ├── vocab-pt-de.json
│   │   ├── vocab-pt-en.json
│   │   └── grammar.json
│   └── audio/          # Audiodateien (TTS-generiert)
└── pwa/
    ├── manifest.json
    └── service-worker.js
```

---

## Prioritäten nach Lernwirksamkeit

```
1. SRS + tägliche Wiederholung    → IMPLEMENTIERT ✅
2. Gamification (XP, Streaks)     → IMPLEMENTIERT ✅
3. Strukturierter Lehrplan        → IMPLEMENTIERT ✅ (8 Kategorien)
4. Multiple-Choice Übungen        → IMPLEMENTIERT ✅
5. Aussprache / Audio             → Phase 2 🔜
6. Schreib-Übungen                → Phase 2 🔜
7. Grammatik-Lektionen            → Phase 3 🔜
8. KI-Konversation                → Phase 4 🔜
```

---

## Zeitplan (Schätzung)

| Phase | Dauer | Status |
|-------|-------|--------|
| v1.0 MVP | 1–2 Tage | ✅ Fertig |
| v2.0 Audio & Interaktion | 2–3 Wochen | 🔜 Geplant |
| v3.0 Vollständiger Lehrplan | 4–6 Wochen | 🔜 Geplant |
| v4.0 Social & KI | 2–3 Monate | 🔜 Geplant |

---

## Erfolgsmetriken

- **Tägliche aktive Nutzer** (DAU)
- **Durchschnittliche Session-Dauer** (Ziel: 10–15 Min)
- **Streak-Länge** (Ziel: >7 Tage Durchschnitt)
- **Vokabeln bis Level 5** (Mastery Rate)
- **Genauigkeitsrate** im Quiz-Modus (Ziel: >70%)
