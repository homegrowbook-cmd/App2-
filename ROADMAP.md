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

## Phase 3 – Inhalte & Struktur (v3.0–v3.2) ✅ *Weitgehend abgeschlossen*

**Ziel:** Vollständiger A1–B1 Lehrplan + Reverse-Learning

### Implementierte Features
- [x] **Portugiesisch → Deutsch/Englisch lernen** – Neue Lernrichtung PT→DE und PT→EN (Flashcards, Quiz, Tipp-Übung, Hörquiz alle unterstützen beide Richtungen)
- [x] **Erweiterte Kategorien** – 4 neue Themenbereiche: Körper 🧍, Kleidung 👕, Wetter 🌤️, Gefühle 😊
- [x] **Neue Kategorie: Alltagssätze 💬** – 30 häufig genutzte Sätze mit kontextueller Bedeutungserklärung
- [x] **Einstellungen-Seite** – Lernrichtungsauswahl, Fortschritt zurücksetzen und App-Info
- [x] **Grammatik-Lektionen** – 14 Grammatikkarten gesamt (Artikel, Ser/Estar, Zeiten, Imperative, Aussprache, Phrasen, Präpositionen + 3 Kulturkarten)
- [x] **3 neue Vokabelkategorien (v3.2)** – Zuhause 🏠 (15), Berufe 👔 (15), Natur 🌿 (15) → jetzt 314 Wörter, 16 Kategorien
- [x] **Kulturelle Lektionskarten (v3.2)** – 3 neue Grammatik-Karten über brasilianische Kultur: Karneval & Festa Junina, Küche & Getränke, Geografie & Fakten
- [x] **Erweiterter Wort-des-Tages (v3.2)** – 21 kuratierte brasilianische Wörter & Ausdrücke (statt 7)
- [x] **Achievement/Erfolgs-System (v3.2)** – 10 Meilenstein-Badges (Wörter gelernt, gemeistert, Streaks, XP) im Fortschritts-Tab
- [x] **„Schwache Wörter üben" Modus (v3.2)** – Direktzugriff auf Wörter mit SRS-Level 0–1 im Lern-Tab
- [x] **Dunkel-Modus (v3.2)** – Dark-Mode-Toggle in den Einstellungen, persistent gespeichert
- [x] **Schriftgröße wählbar (v3.2)** – Klein / Normal / Groß in den Einstellungen
- [x] **Verbessertes Quiz-Feedback (v3.2)** – Ausspracheführer `[ pron ]` und Beispielsatz bei Antworten
- [x] **Session-Zusammenfassung (v3.2)** – Richtig/Falsch-Auswertung am Ende jeder Karteikarten-Sitzung
- [x] **Hörquiz aus Kategorie-Karte (v3.2)** – 🎧-Button auf jeder Kategorie-Karte für gezieltes Hörtraining

### Noch offen (für v3.3+)
- [x] **Satz-Builder (v3.3)** – Sätze aus Wörtern zusammensetzen (Tap-to-order)
- [x] **Dialog-Übungen (v3.3)** – Typische Alltagsgespräche nachspielen (12 Szenarien)
- [ ] **Thematische Geschichten** – Kurze Texte auf Portugiesisch mit Vokabel-Highlighting
- [ ] **Leistungsnachweise** – Level-Tests, Zertifikate (A1, A2)
- [ ] **IndexedDB** – Größere Datensätze effizient speichern

---

## v3.2 – 5 Ausbau-Vorschläge (implementiert ✅)

> Eigenständig umsetzbare Erweiterungen zum Ausbau des Lernumfangs

1. ✅ **3 neue Vokabelkategorien** – Zuhause 🏠, Berufe 👔, Natur 🌿 mit je 15 Wörtern (+45 Einträge auf insgesamt 314 Wörter & 16 Kategorien)
2. ✅ **Kulturelle Lektionskarten** – 3 interaktive Grammatik-Karten über brasilianische Kultur: Feste (Karneval/Festa Junina), Küche (Feijoada, Caipirinha, Cafezinho) und Geografie
3. ✅ **Erweiterter Wort-des-Tages** – Pool von 7 auf 21 typisch brasilianische Ausdrücke und Slang-Wörter erweitert (Cafuné, Malandro, Valeu!, Mano u. v. m.)
4. ✅ **Achievement/Meilenstein-System** – 10 freischaltbare Erfolge (🌱 Erster Schritt, 📖 10 Wörter, 💯 100er Club, 🔥 Streak-Badges, 🏆 XP-Sammler) im Fortschritts-Tab
5. ✅ **„Schwache Wörter üben" Modus** – Schnellzugriff-Button im Lern-Tab filtert automatisch alle Wörter mit SRS-Level 0–1 für gezielte Wiederholung

## v3.2 – 5 Verbesserungs-Vorschläge (implementiert ✅)

> Eigenständig umsetzbare UX/UI-Verbesserungen

1. ✅ **Dunkel-Modus (Dark Mode)** – Toggle in den Einstellungen; vollständiges dunkles Farbschema für alle App-Bereiche; Einstellung wird im LocalStorage gespeichert
2. ✅ **Schriftgröße wählbar** – 3-Stufen-Auswahl (Klein / Normal / Groß) in den Einstellungen für bessere Lesbarkeit auf allen Geräten
3. ✅ **Verbessertes Quiz-Feedback** – Bei richtiger Antwort wird die Aussprache `[ pron ]` eingeblendet; bei falscher Antwort erscheint zusätzlich ein Beispielsatz für besseres Behalten
4. ✅ **Session-Zusammenfassung mit Auswertung** – Am Ende jeder Karteikarten-Sitzung werden Anzahl richtiger und falscher Antworten (✅ X richtig ❌ Y falsch) angezeigt
5. ✅ **Hörquiz aus Kategorie-Karte starten** – 🎧-Button auf jeder Kategorie-Karte ermöglicht gezieltes Hörverständnis-Training für eine einzelne Kategorie (wie Karten & Tippen-Modus)

## v3.3 – Neue Übungstypen (implementiert ✅)

> Zwei neue interaktive Lernmodi für aktiven Sprachaufbau

1. ✅ **Satz-Builder** – Wörter eines portugiesischen Beispielsatzes werden gemischt; der Lernende setzt sie durch Antippen in die richtige Reihenfolge (8 Runden, +25 XP pro korrektem Satz)
2. ✅ **Dialog-Übungen** – 12 typische Alltagsdialoge (Café, Hotel, Arzt, Taxi u. v. m.); Lernende wählen die passende Antwort aus 3 Optionen und hören die Lösung per TTS ab (+20 XP pro richtige Antwort)

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
3. Strukturierter Lehrplan        → IMPLEMENTIERT ✅ (16 Kategorien, A1/A2)
4. Multiple-Choice Übungen        → IMPLEMENTIERT ✅
5. Aussprache / Audio (TTS)       → IMPLEMENTIERT ✅ (v2.0)
6. Schreib-Übungen (Tippen)       → IMPLEMENTIERT ✅ (v2.0)
7. Hörverständnis-Quiz            → IMPLEMENTIERT ✅ (v2.0)
8. Fehler-Analyse                 → IMPLEMENTIERT ✅ (v2.0)
9. Grammatik-Karten               → IMPLEMENTIERT ✅ (v2.0, 14 Karten)
10. PWA (Offline, Installierbar)  → IMPLEMENTIERT ✅ (v2.0)
11. PT→DE/EN Lernrichtung         → IMPLEMENTIERT ✅ (v3.0)
12. Alltagssätze-Kategorie         → IMPLEMENTIERT ✅ (v3.0)
13. Grammatik-Lektionen (Detail)  → IMPLEMENTIERT ✅ (v3.1)
14. Alltagssätze mit Bedeutung    → IMPLEMENTIERT ✅ (v3.1)
15. Dark Mode + Schriftgröße      → IMPLEMENTIERT ✅ (v3.2)
16. Achievement-System            → IMPLEMENTIERT ✅ (v3.2)
17. Kulturelle Lektionen          → IMPLEMENTIERT ✅ (v3.2)
18. Schwache-Wörter-Modus         → IMPLEMENTIERT ✅ (v3.2)
19. Kategorie-Hörquiz             → IMPLEMENTIERT ✅ (v3.2)
20. Satz-Builder                  → IMPLEMENTIERT ✅ (v3.3)
21. Dialog-Übungen                → IMPLEMENTIERT ✅ (v3.3)
22. KI-Konversation               → Phase 4 🔜
```

---

## Zeitplan

| Phase | Dauer | Status |
|-------|-------|--------|
| v1.0 MVP | 1–2 Tage | ✅ Fertig |
| v2.0 Audio & Interaktion | 2–3 Wochen | ✅ Fertig |
| v3.0–3.3 Vollständiger Lehrplan + Übungstypen | 4–6 Wochen | ✅ Weitgehend fertig |
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
