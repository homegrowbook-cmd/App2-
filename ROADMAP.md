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
- [ ] IndexedDB für größere Datensätze *(verschoben auf v4.0)*

---

## Phase 3 – Inhalte & Struktur (v3.0–v3.5) ✅ *Abgeschlossen*

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

### Noch offen (für v3.3+) – alles implementiert ✅
- [x] **Satz-Builder (v3.3)** – Sätze aus Wörtern zusammensetzen (Tap-to-order)
- [x] **Dialog-Übungen (v3.3)** – Typische Alltagsgespräche nachspielen (12 Szenarien)
- [x] **XP-Strafpunkte (v3.4)** – XP-Abzug bei falschen Antworten
- [x] **Streak-Multiplikator (v3.4)** – Bonus-XP für lange Streaks
- [x] **Tägliches XP-Ziel (v3.4)** – Konfigurierbares Tagesziel mit Fortschrittsbalken
- [x] **Thematische Geschichten (v3.5)** – 5 interaktive A1/A2 Lesetexte mit tippbaren Vokabel-Highlights, Popup mit Übersetzung + Aussprache + TTS
- [x] **Leistungsnachweise / Level-Tests (v3.5)** – A1- und A2-Test (je 20 Fragen, Multiple Choice); Zertifikat bei ≥70% im Fortschritts-Tab; Ergebnis persistent gespeichert

---

## v3.5 – Neue Inhalte & Features (implementiert ✅)

> Vocabulary-Erweiterung, Story-Reader, Level-Tests, Favoriten, Wortliste

1. ✅ **+80 neue Vokabeln** – Je 5 neue Wörter pro Kategorie (IDs 317–396); jetzt 396 Einträge in 16 Kategorien
2. ✅ **Thematische Geschichten (Story Reader)** – 5 interaktive A1/A2 Lesetexte; markierte Vokabeln antippen → Popup mit Portugiesisch, Übersetzung, Aussprache + TTS-Wiedergabe
3. ✅ **Level-Tests mit Zertifikat** – A1- und A2-Einstufungstest (je 20 Multiple-Choice-Fragen); bei ≥70% Erfüllung: Zertifikat im Fortschritts-Tab; +10 XP pro richtige Antwort
4. ✅ **Favoriten-System** – Wörter beim Lernen mit ⭐ markieren; „Favoriten üben"-Modus im Lern-Tab; Favoriten werden im localStorage gespeichert
5. ✅ **Wortliste mit Suchfunktion** – Alle 396 Vokabeln durchsuchbar; Kategorie-Filter; SRS-Level-Badges; TTS-Wiedergabe per Klick; von der Startseite aus erreichbar

---


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

## v3.4 – Gamification & Motivation (implementiert ✅)

> Drei neue Features für ein faireres, motivierenderes Lernsystem

1. ✅ **XP-Strafpunkte bei falschen Antworten** – -5 XP für jede falsche Antwort in Quiz, Tipp-Übung, Hörquiz, Satz-Builder und Dialog-Übungen; XP kann nie unter 0 fallen; rote Abzugsanimation (−5 XP) sichtbar; ein/aus-schaltbar in den Einstellungen
2. ✅ **Streak-XP-Multiplikator** – Je länger die tägliche Lernsträhne, desto mehr Bonus-XP: Streak ≥ 3 Tage: +1 XP, ≥ 7 Tage: +2 XP, ≥ 14 Tage: +5 XP pro richtiger Antwort; Bonus-Badge im Header sichtbar; abschaltbar in den Einstellungen
3. ✅ **Tägliches XP-Ziel mit Fortschrittsbalken** – Konfigurierbares Tagesziel (Standard: 50 XP, von 10–500 einstellbar) mit Mini-Fortschrittsbalken direkt unter dem ⭐ XP-Zähler im Header; bei Zielerreichung erscheint eine Erfolgsmeldung (Toast); täglich automatisch zurückgesetzt

---

## Phase 4 – Social & KI (v4.0)

**Ziel:** Community und KI-gestützte Personalisierung

### Geplante Features
- [ ] **KI-Konversationspartner** – Chatbot für Übungsgespräche auf Portugiesisch
- [ ] **Sprachtausch-Matching** – Nutzer mit brasilianischen Muttersprachlern verbinden
- [ ] **Ranglisten & Challenges** – Wöchentliche Wettbewerbe mit Freunden
- [ ] **Spaced Repetition 2.0** – ML-basierte Anpassung der Lernintervalle
- [ ] **Benutzerkonten & Cloud-Sync** – Fortschritt geräteübergreifend speichern
- [ ] **IndexedDB** – Größere Datensätze effizient speichern (bessere Performance bei wachsendem Vokabular)
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
22. XP-Strafpunkte                → IMPLEMENTIERT ✅ (v3.4)
23. Streak-Multiplikator          → IMPLEMENTIERT ✅ (v3.4)
24. Tägliches XP-Ziel             → IMPLEMENTIERT ✅ (v3.4)
25. **Thematische Geschichten**        → IMPLEMENTIERT ✅ (v3.5)
26. **Level-Tests + Zertifikate**       → IMPLEMENTIERT ✅ (v3.5)
27. **Favoriten-System**               → IMPLEMENTIERT ✅ (v3.5)
28. **Wortliste mit Suche**            → IMPLEMENTIERT ✅ (v3.5)
29. KI-Konversation               → Phase 4 🔜
30. IndexedDB                     → Phase 4 🔜
```

---

## Zeitplan

| Phase | Dauer | Status |
|-------|-------|--------|
| v1.0 MVP | 1–2 Tage | ✅ Fertig |
| v2.0 Audio & Interaktion | 2–3 Wochen | ✅ Fertig |
| v3.0–3.5 Vollständiger Lehrplan + Übungstypen + Gamification + Stories + Level-Tests | 4–6 Wochen | ✅ Fertig |
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
