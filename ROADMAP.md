# LinguaBrasil – App Roadmap

## Vision
Eine kostenlose, browserbasierte HTML-App zum Erlernen von Brasilianischem Portugiesisch für Deutsch- und Englischsprachige – wissenschaftlich fundiert, gamifiziert und ohne Installation nutzbar.

---

## Phase 1 – MVP (v1.0) ✅ *Erledigt*

> **Abgeschlossen** – App läuft live unter: [https://homegrowbook-cmd.github.io/App2-/](https://homegrowbook-cmd.github.io/App2-/)

**Ziel:** Funktionsfähige Basis-App mit den wichtigsten Lernfunktionen

### Features
- [x] Sprachauswahl: Deutsch → Brasilianisches Portugiesisch / Englisch → Brasilianisches Portugiesisch
  *(ab v3.0: auch Brasilianisches Portugiesisch → Deutsch/Englisch)*
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

## Phase 2 – Audio & Interaktion (v2.0) ✅ *Abgeschlossen*

> **Abgeschlossen** – Alle v2-Features sind live in `index.html` integriert.

**Ziel:** Hör- und Sprachkompetenz verbessern

### Features
- [x] **Web Speech API (TTS)** – 🔊 Sprechen-Button auf Karteikarten, Wort-des-Tages und Fehler-Analyse
- [x] **Hörverständnis-Quiz** – TTS spielt Wort ab, Nutzer wählt richtige Übersetzung aus 4 Optionen
- [x] **Tipp-Übungen** – Wort eintippen statt Multiple Choice (mit Akzent-Normalisierung)
- [x] **Fehler-Analyse** – Häufig falsch gemachte Wörter im Fortschrittsbildschirm anzeigen
- [x] **Grammatik-Karten** – 7 aufklappbare Grammatikthemen (neuer Tab):
  - Artikel (o/a, um/uma)
  - Ser vs. Estar
  - Zahlen 1–20
  - Regelmäßige -ar Verben (Präsens)
  - Aussprache-Tipps für brasilianisches Portugiesisch
  - Essenzielle Gesprächsphrasen
  - Präpositionen & Ortsangaben
- [x] **Lernpfad-System** – A1/A2 Level-Badges auf allen Kategorien

### Technische Erweiterungen
- [x] **Service Worker** – Offline-Nutzung (PWA) via `service-worker.js`
- [x] **Web App Manifest** – App installierbar auf Smartphone via `manifest.json`
- [ ] IndexedDB für größere Datensätze *(für v3.0 verschoben)*

---

## Phase 3 – Inhalte & Struktur (v3.0) 🔄 *In Arbeit*

**Ziel:** Vollständiger A1–B1 Lehrplan + Reverse-Learning

### Geplante Features
- [x] **Portugiesisch → Deutsch/Englisch lernen** – Neue Lernrichtung PT→DE und PT→EN (Flashcards, Quiz, Tipp-Übung, Hörquiz alle unterstützen beide Richtungen)
- [x] **Erweiterte Kategorien** – 4 neue Themenbereiche: Körper 🧍, Kleidung 👕, Wetter 🌤️, Gefühle 😊
- [x] **Erweiterter Wortschatz** – 131 Vokabeln (12 Kategorien) – Ziel: 500+ *(in Arbeit)*
- [ ] **Grammatik-Lektionen** – Strukturierte Einheiten zu: Artikel, Präsens, Vergangenheit, Zukunft, Konjunktiv
- [ ] **Satz-Builder** – Sätze aus Wörtern zusammensetzen (Drag & Drop)
- [ ] **Dialog-Übungen** – Typische Alltagsgespräche nachspielen
- [ ] **Thematische Geschichten** – Kurze Texte auf Portugiesisch mit Vokabel-Highlighting
- [ ] **Kulturelle Lektionen** – Brasilianische Feste, Küche, Musik, Slang
- [ ] **Leistungsnachweise** – Level-Tests, Zertifikate (A1, A2)
- [ ] **IndexedDB** – Größere Datensätze effizient speichern

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

## Technische Architektur

```
LinguaBrasil/
├── index.html          # Haupt-App (v2.0: alle Features in einer Datei)
├── manifest.json       # PWA Manifest ✅
├── service-worker.js   # Offline-Support ✅
├── ANALYSIS.md         # App-Analyse & Methodik-Forschung
├── ROADMAP.md          # Diese Roadmap
└── v3/                 # Zukünftige Version (v3.0)
    ├── index.html
    ├── app.js
    ├── styles.css
    └── data/
        ├── vocab-pt-de.json
        ├── vocab-pt-en.json
        └── grammar.json
```

---

## Prioritäten nach Lernwirksamkeit

```
1. SRS + tägliche Wiederholung    → IMPLEMENTIERT ✅
2. Gamification (XP, Streaks)     → IMPLEMENTIERT ✅
3. Strukturierter Lehrplan        → IMPLEMENTIERT ✅ (12 Kategorien, A1/A2)
4. Multiple-Choice Übungen        → IMPLEMENTIERT ✅
5. Aussprache / Audio (TTS)       → IMPLEMENTIERT ✅ (v2.0)
6. Schreib-Übungen (Tippen)       → IMPLEMENTIERT ✅ (v2.0)
7. Hörverständnis-Quiz            → IMPLEMENTIERT ✅ (v2.0)
8. Fehler-Analyse                 → IMPLEMENTIERT ✅ (v2.0)
9. Grammatik-Karten               → IMPLEMENTIERT ✅ (v2.0)
10. PWA (Offline, Installierbar)  → IMPLEMENTIERT ✅ (v2.0)
11. PT→DE/EN Lernrichtung         → IMPLEMENTIERT ✅ (v3.0)
12. Grammatik-Lektionen (Detail)  → Phase 3 🔜
13. KI-Konversation               → Phase 4 🔜
```

---

## Zeitplan

| Phase | Dauer | Status |
|-------|-------|--------|
| v1.0 MVP | 1–2 Tage | ✅ Fertig |
| v2.0 Audio & Interaktion | 2–3 Wochen | ✅ Fertig |
| v3.0 Vollständiger Lehrplan | 4–6 Wochen | 🔄 In Arbeit |
| v4.0 Social & KI | 2–3 Monate | 🔜 Geplant |

---

## Erfolgsmetriken

- **Tägliche aktive Nutzer** (DAU)
- **Durchschnittliche Session-Dauer** (Ziel: 10–15 Min)
- **Streak-Länge** (Ziel: >7 Tage Durchschnitt)
- **Vokabeln bis Level 5** (Mastery Rate)
- **Genauigkeitsrate** im Quiz-Modus (Ziel: >70%)
- **Tipp-Übungen Genauigkeit** (Ziel: >60%)
- **PWA-Installationsrate** (Neue Metrik ab v2.0)
