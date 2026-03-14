# LuiBrasil – App Roadmap

## Vision
Eine kostenlose, browserbasierte HTML-App zum Erlernen von Brasilianischem Portugiesisch für Deutsch- und Englischsprachige – wissenschaftlich fundiert, gamifiziert und ohne Installation nutzbar.

---

## ✅ Phase 1 – MVP (v1.0) *Abgeschlossen*

> App läuft live unter: [https://homegrowbook-cmd.github.io/App2-/](https://homegrowbook-cmd.github.io/App2-/)

- [x] Sprachauswahl: DE→PT / EN→PT
- [x] 8 Vokabelkategorien, ~100 Vokabeln
- [x] Karteikarten-Modus, Quiz-Modus (Multiple Choice)
- [x] Spaced Repetition System (SRS, Level 0–5)
- [x] XP-System + Tages-Streaks
- [x] Fortschrittsbildschirm
- [x] LocalStorage-Persistenz
- [x] Mobil-responsives Design (Brasilianisches Farbthema)

**Stack:** HTML5 + CSS3 + Vanilla JS · offline nutzbar · eine Datei: `index.html`

---

## ✅ Phase 2 – Audio & Interaktion (v2.0) *Abgeschlossen*

- [x] Web Speech API (TTS) – 🔊 Sprechen-Button auf Karten, Wort-des-Tages, Fehler-Analyse
- [x] Hörverständnis-Quiz (TTS → Übersetzung wählen)
- [x] Tipp-Übungen (Eingabe statt Multiple Choice, mit Akzent-Normalisierung)
- [x] Fehler-Analyse (häufig falsch gemachte Wörter im Fortschrittsbildschirm)
- [x] 7 Grammatik-Karten (Artikel, Ser/Estar, Zahlen, Verben, Aussprache, Phrasen, Präpositionen)
- [x] A1/A2-Level-Badges auf Kategorien
- [x] Service Worker (PWA, Offline-Nutzung) + Web App Manifest

---

## ✅ Phase 3 – Inhalte & Struktur (v3.0–v3.5) *Abgeschlossen*

### v3.0 – Reverse-Learning & neue Inhalte
- [x] PT→DE / PT→EN Lernrichtung (alle Modi unterstützen beide Richtungen)
- [x] 4 neue Kategorien: Körper 🧍, Kleidung 👕, Wetter 🌤️, Gefühle 😊
- [x] Neue Kategorie: Alltagssätze 💬 (30 Sätze mit kontextueller Bedeutungserklärung)
- [x] Einstellungen-Seite (Lernrichtung, Reset, App-Info)

### v3.1 – Grammatik & Bedeutungsfelder
- [x] 11 Grammatik-Karten gesamt + `bedeutung`-Feld bei Satz-Karten

### v3.2 – UX & Vokabular-Ausbau
- [x] 3 neue Kategorien: Zuhause 🏠 (15), Berufe 👔 (15), Natur 🌿 (15) → 314 Wörter, 16 Kategorien
- [x] 3 Kulturkarten (Karneval/Festa Junina, Küche, Geografie)
- [x] Achievement-System (10 Meilenstein-Badges)
- [x] „Schwache Wörter üben"-Modus (SRS Level 0–1)
- [x] Dark Mode + Schriftgröße (Klein/Normal/Groß)
- [x] Verbessertes Quiz-Feedback (Aussprache bei Richtig, Beispielsatz bei Falsch)
- [x] Session-Zusammenfassung (Richtig/Falsch-Auswertung)
- [x] Hörquiz aus Kategorie-Karte starten

### v3.3 – Neue Übungstypen
- [x] Satz-Builder (Wörter in richtige Reihenfolge tippen, 8 Runden, +25 XP)
- [x] Dialog-Übungen (12 Alltagsszenarien, +20 XP)

### v3.4 – Gamification
- [x] XP-Strafpunkte bei falschen Antworten (−5 XP, abschaltbar)
- [x] Streak-XP-Multiplikator (≥3: +1, ≥7: +2, ≥14: +5 XP, abschaltbar)
- [x] Tägliches XP-Ziel (Standard 50 XP, 10–500 konfigurierbar, Fortschrittsbalken im Header)

### v3.5 – Stories, Level-Tests, Favoriten, Wortliste
- [x] +80 neue Vokabeln (IDs 317–396), gesamt 394 Einträge in 16 Kategorien
- [x] Story Reader: 5 interaktive A1/A2-Lesetexte mit tippbaren Vokabel-Popups + TTS
- [x] Level-Tests A1 & A2 (je 20 Multiple-Choice-Fragen; Zertifikat bei ≥ 70 %; +10 XP/Frage)
- [x] Favoriten-System (⭐ beim Lernen markieren, „Favoriten üben"-Modus)
- [x] Wortliste (alle 394 Wörter durchsuchbar; Kategorie-Filter; SRS-Badge; TTS per Klick)

---

## 🚀 Phase 4 – Erweiterungen & KI (v4.0) *In Arbeit*

**Ziel:** Sprach­kompetenz vertiefen, KI-gestützte Personalisierung, Community-Features

### ✅ 4.0 – Vokabular-Erweiterung & neue Übungstypen
- [x] **+60 neue Vokabeln** – Kategorien: Gesundheit 🏥 (20), Technologie 💻 (20), Sport ⚽ (20) – Gesamt: 565 Wörter, 19 Kategorien
- [x] **Lückentext-Trainer** – Fehlende Wörter in Sätzen ergänzen (+20 XP, Hint-Funktion)
- [x] **Neues Home-Design** – 2-Spalten-Raster für alle Übungstypen, übersichtlicher Navigation
- [x] **Lückentext-Button auf jeder Kategorie-Karte** (Lernen-Ansicht)
- [x] **Service Worker v11** – Neues Cache-Profil für v4.0

### 4.1 – Weitere Vokabeln
- [ ] **+40 neue Vokabeln** – Themen: Natur 2.0 🌊, B1-Wortschatz
- [ ] **5 weitere Geschichten** (B1-Niveau) mit komplexerem Wortschatz
- [ ] **A2-Level-Test erweitern** + neuer B1-Level-Test

### 4.2 – Neue Übungstypen
- [x] **Lückentext-Übungen** – Sätze mit fehlendem Wort ergänzen (✅ v4.0)
- [ ] **Aussprache-Bewertung** – Web Speech API zur Spracherkennung nutzen (Experimental)
- [ ] **Konjugations-Trainer** – Verbformen eingeben (Präsens, Vergangenheit, Futur)
- [ ] **Bild-Vokabular** – Wörter durch Bilder lernen (Bildauswahl-Quiz)

### 4.3 – KI & Personalisierung
- [ ] **KI-Konversationspartner** – Chatbot für Übungsgespräche auf Portugiesisch (OpenAI API oder lokales Modell)
- [ ] **Adaptives SRS 2.0** – ML-basierte Anpassung der Lernintervalle je Nutzerverhalten
- [ ] **Personalisierter Lehrplan** – App schlägt nächsten Schritt basierend auf Fehlerquote vor

### 4.4 – Social & Cloud
- [ ] **Benutzerkonten & Cloud-Sync** – Fortschritt geräteübergreifend speichern (Firebase / Supabase)
- [ ] **Ranglisten & Challenges** – Wöchentliche Wettbewerbe, Freundesvergleich
- [ ] **Sprachtausch-Matching** – Nutzer mit brasilianischen Muttersprachlern verbinden
- [ ] **IndexedDB** – Größere Datensätze effizient speichern (Performance bei >1000 Wörtern)

### 4.5 – Technische Verbesserungen
- [ ] **Code-Aufteilung** – Refactoring: `app.js`, `data.js`, `styles.css` als separate Dateien
- [ ] **Automatisierte Tests** – Unit-Tests für SRS-Logik, XP-Berechnung, Streak-Berechnung
- [ ] **Weitere Sprachen** – Spanisch, Französisch, Italienisch als optionale Module

---

## 📊 Prioritäten nach Lernwirksamkeit

```
1.  SRS + tägliche Wiederholung         → ✅ IMPLEMENTIERT (v1.0)
2.  Gamification (XP, Streaks)          → ✅ IMPLEMENTIERT (v1.0, v3.4)
3.  Strukturierter Lehrplan             → ✅ IMPLEMENTIERT (v3.x, 16 Kategorien, A1/A2)
4.  Multiple-Choice-Übungen             → ✅ IMPLEMENTIERT (v1.0)
5.  Audio / Aussprache (TTS)            → ✅ IMPLEMENTIERT (v2.0)
6.  Schreib-Übungen (Tippen)            → ✅ IMPLEMENTIERT (v2.0)
7.  Hörverständnis-Quiz                 → ✅ IMPLEMENTIERT (v2.0)
8.  Fehler-Analyse                      → ✅ IMPLEMENTIERT (v2.0)
9.  Grammatik-Karten (14 gesamt)        → ✅ IMPLEMENTIERT (v2.0, v3.x)
10. PWA (Offline, Installierbar)        → ✅ IMPLEMENTIERT (v2.0)
11. PT→DE/EN Lernrichtung              → ✅ IMPLEMENTIERT (v3.0)
12. Alltagssätze                        → ✅ IMPLEMENTIERT (v3.0)
13. Dark Mode + Schriftgröße            → ✅ IMPLEMENTIERT (v3.2)
14. Achievement-System                  → ✅ IMPLEMENTIERT (v3.2)
15. Kulturelle Lektionen                → ✅ IMPLEMENTIERT (v3.2)
16. Schwache-Wörter-Modus              → ✅ IMPLEMENTIERT (v3.2)
17. Satz-Builder                        → ✅ IMPLEMENTIERT (v3.3)
18. Dialog-Übungen                      → ✅ IMPLEMENTIERT (v3.3)
19. XP-Strafpunkte / Streak-Multiplikator → ✅ IMPLEMENTIERT (v3.4)
20. Story Reader                        → ✅ IMPLEMENTIERT (v3.5)
21. Level-Tests + Zertifikate           → ✅ IMPLEMENTIERT (v3.5)
22. Favoriten-System                    → ✅ IMPLEMENTIERT (v3.5)
23. Wortliste mit Suche                 → ✅ IMPLEMENTIERT (v3.5)
24. Lückentext-Übungen                  → 🔜 Phase 4.2
25. Konjugations-Trainer                → 🔜 Phase 4.2
26. KI-Konversation                     → 🔜 Phase 4.3
27. Adaptives SRS 2.0                   → 🔜 Phase 4.3
28. Cloud-Sync                          → 🔜 Phase 4.4
29. IndexedDB                           → 🔜 Phase 4.4
30. Weitere Sprachen                    → 🔜 Phase 4.5
```

---

## 🏗️ Technische Architektur (aktuell)

```
LuiBrasil/
├── index.html          # Haupt-App (alle Features in einer Datei, v3.5)
├── manifest.json       # PWA Manifest ✅
├── service-worker.js   # Offline-Support, Network-First-Strategie ✅
├── icon-192.png        # PWA Icon
├── icon-512.png        # PWA Icon
├── ANALYSIS.md         # App-Analyse & Methodik-Forschung
└── ROADMAP.md          # Diese Roadmap
```

**Geplant für v4.5 (Code-Aufteilung):**
```
LuiBrasil/
├── index.html
├── app.js              # App-Logik (Controller, Sessions, XP, SRS)
├── data.js             # WORDS, CATEGORIES, STORIES, DIALOGS
├── styles.css          # Alle Styles
├── manifest.json
└── service-worker.js
```

---

## ⏱️ Zeitplan

| Phase | Dauer | Status |
|-------|-------|--------|
| v1.0 MVP | 1–2 Tage | ✅ Fertig |
| v2.0 Audio & Interaktion | 2–3 Wochen | ✅ Fertig |
| v3.0–3.5 Lehrplan + Übungstypen + Gamification + Stories | 4–6 Wochen | ✅ Fertig |
| v4.0 Erweiterungen & KI | 2–4 Monate | 🚀 In Planung |

---

## 📈 Erfolgsmetriken

- **Tägliche aktive Nutzer** (DAU)
- **Durchschnittliche Session-Dauer** (Ziel: 10–15 Min)
- **Streak-Länge** (Ziel: >7 Tage Durchschnitt)
- **Vokabeln bis Level 5** (Mastery Rate)
- **Genauigkeitsrate** im Quiz-Modus (Ziel: >70 %)
- **Tipp-Übungen Genauigkeit** (Ziel: >60 %)
- **PWA-Installationsrate**
- **Level-Test Bestehenquote** (Ziel: >50 % nach 1 Woche Nutzung)
