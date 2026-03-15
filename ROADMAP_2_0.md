# LuiBrasil – Roadmap 2.0
### Competitive Intelligence & strategischer Ausblick

> **Erstellt:** März 2026  
> **Basis:** Vergleich mit den Top 8 Sprach-Apps + aktuellem Feature-Stand LuiBrasil v7.0
> **Status:** v8.0 implementiert – März 2026

---

## 🔍 Teil 1 – Wettbewerbsanalyse: Top 8 Apps vs. LuiBrasil

### Was machen die Marktführer besser?

| # | App | Was sie BESSER machen als wir | Unsere Lücke |
|---|-----|-------------------------------|--------------|
| 1 | **Duolingo** | KI-adaptiver Pfad, Ligas/Leaderboards, Push-Notifications, Herzen-System (Stakes), sprechende Charaktere | Kein strukturierter Lernpfad, keine Social-Elemente, kein Onboarding |
| 2 | **Babbel** | Intelligenter Review-Manager, Speech-Recognition für Aussprache, Grammatik-Videos, klarer Kurspfad | Aussprache nur TTS (keine Bewertung), kein geführter Kurs-Flow |
| 3 | **Rosetta Stone** | TrueAccent™ Aussprache-Scoring, Vollimmersion ohne Übersetzung, Bild-basiertes Lernen, Live-Tutoren | Kein Aussprache-Feedback, keine Bildvokabeln, kein Live-Tutor |
| 4 | **Memrise** | Native-Speaker-Videos (echte Muttersprachler), „Difficult Words"-Modus, Merkhilfen (Mems) | Kein Video-Content, keine Mnemotechniken |
| 5 | **Busuu** | Muttersprachler-Korrekturen für Schreibübungen, offizielles McGraw-Hill-Zertifikat, Sprachlernplan mit Kalender | Zertifikate nicht offiziell anerkannt, kein Community-Feedback |
| 6 | **Pimsleur** | Audio-first (perfekt für unterwegs), bewährte Recall-Methode in 30-Min-Einheiten | Kein eigenständiger Audio-Modus für mobiles Lernen |
| 7 | **HelloTalk** | Echter Chat mit Muttersprachlern, Fehlerkorrektur-Funktion, Moments (social feed) | Keine echten Muttersprachler-Interaktionen |
| 8 | **Drops** | Wunderschönes visuelles UI, Wisch-Gesten, 5-Min-Session-Timer, Bild-Wort-Assoziationen | Kein visuelles Assoziationslernen, kein Timer-System |

---

### Was LuiBrasil bereits BESSER macht (oder gleichwertig ist)

| Feature | LuiBrasil | Wettbewerber |
|---------|-----------|-------------|
| **Vollständig kostenlos** | ✅ 100 % gratis | ❌ Alle Top-Apps haben Bezahl-Features |
| **Fokus auf Brasilianisches Portugiesisch** | ✅ Spezialisiert | ⚠️ Meist generisch (PT + BR gemischt) |
| **Offline-fähig (PWA)** | ✅ Service Worker | ⚠️ Nur wenige Apps vollständig offline |
| **Keine Installation** | ✅ Reiner Browser | ❌ Fast alle brauchen App-Store |
| **DE→PT + EN→PT** | ✅ Dual-Sprache | ⚠️ Meistens nur eine Ausgangssprache |
| **Live-Übersetzung (DE→PT)** | ✅ Spracheingabe | ❌ Kaum vorhanden in dieser Form |
| **SRS mit 5 Levels** | ✅ | ✅ Standard |
| **Konjugations-Trainer** | ✅ | ⚠️ Nur in Premium |
| **Stories + Level-Tests** | ✅ | ⚠️ Nur in Premium |

---

## 🧠 Teil 2 – Analyse: Die 5 wichtigsten Lücken

### Lücke 1 – Kein strukturierter Lernpfad 🗺️
> **Problem:** Nutzer öffnen die App und sehen ein Raster von Übungstypen ohne klare Reihenfolge. Duolingo und Babbel haben einen geführten Pfad, der Anfängern zeigt, was als nächstes zu tun ist.  
> **Wirkung:** Neue Nutzer brechen früher ab, weil sie orientierungslos sind (sog. „Cold Start Problem").

### Lücke 2 – Keine Aussprache-Bewertung 🎤
> **Problem:** Wir nutzen TTS (Text-to-Speech) zum Vorlesen, aber Nutzer können ihre eigene Aussprache nicht überprüfen. Rosetta Stone und Babbel bewerten die Aussprache mit Echtzeitfeedback.  
> **Wirkung:** Brasilianisches Portugiesisch hat komplexe Nasalvokale (ã, õ) und Laute, die ohne Feedback schwer zu erlernen sind.

### Lücke 3 – Fehlende Social-/Community-Features 👥
> **Problem:** Lernen ist isoliert. Kein Leaderboard, keine Freunde, kein Vergleich. Duolingo-Studien zeigen: Nutzer mit Liga-Feature lernen 3× häufiger.  
> **Wirkung:** Fehlende externe Motivation führt zu Abbruch nach wenigen Wochen.

### Lücke 4 – Kein visuelles/assoziatives Lernen 🖼️
> **Problem:** Wörter werden als Text gelernt. Drops und Rosetta Stone nutzen Bilder für schnellere, stärkere Gedächtnis-Anker.  
> **Wirkung:** Visuelle Lerner (ca. 65 % aller Menschen) lernen effizienter mit Bildern.

### Lücke 5 – Kein onboarding / Personalisierung beim Start 🎯
> **Problem:** Neue Nutzer starten ohne Profiling. Busuu und Babbel fragen: Warum lernst du? Wie viel Zeit hast du? Was ist dein Level?  
> **Wirkung:** Ohne Personalisierung fühlt sich die App generisch an und trifft nicht die Bedürfnisse des Nutzers.

---

## 🚀 Teil 3 – Roadmap 2.0: Konkrete Maßnahmen

> **Philosophie:** Wir bleiben **kostenlos, browserbasiert und offline-fähig** – das ist unser Alleinstellungsmerkmal. Wir verbessern gezielt die Bereiche, in denen Marktführer uns überlegen sind.

---

### 🟥 KRITISCH – Sofortmaßnahmen (v8.0)

#### 8.1 – Onboarding-Flow & Lernpfad
- [x] **Willkommens-Wizard** (3 Screens): Ziel auswählen (Reise / Alltag / Arbeit / Kultur), Level-Einschätzung (Anfänger/Fortgeschritten), tägliches Zeitbudget (5/10/20 Min)
- [ ] **Empfohlener Tages-Kurs** – App zeigt täglich: „Heute empfohlen: SRS-Wiederholung + 1 Dialog"
- [ ] **Geführter Lernpfad für Anfänger** – Schritt-für-Schritt von Basics → A1 → A2 → B1 (ähnlich Duolingo-Pfad)
- [x] **„Weiter wo du aufgehört hast"**-Button auf der Startseite

#### 8.2 – UX / Visual Refresh
- [ ] **Kategorie-Icons vergrößern** + Schwierigkeitsgrad-Anzeige (A1/A2/B1) prominenter
- [x] **Fortschritts-Heatmap** (GitHub-Style) auf dem Homescreen: letzte 30 Lerntage auf einen Blick
- [x] **5-Minuten-Session-Modus** (Drops-inspiriert): Timer-basierte Kurzeinheit mit automatischem Ende
- [x] **Konfetti-Animation** bei Meilensteinen (erste 50 Wörter, erster Streak-Week)

---

### 🟧 HOCH – Mittelfristig (v8.5 – v9.0)

#### 8.5 – Aussprache-Trainer 🎤
- [ ] **Aussprache-Bewertung mit Web Speech API**: Nutzer spricht Wort → App vergleicht mit Zielwort → Feedback (✅ Gut / ⚠️ Versuche nochmal)
- [ ] **Phonetik-Hinweise** bei schwierigen Lauten: z.B. „ã" → „wie das 'ang' in Englisch ohne das 'g'"
- [ ] **Aussprache-Modus** als eigener Übungstyp (30 Wörter vorlesen, Bewertung am Ende)

#### 8.6 – Social & Motivation 👥
- [ ] **Wöchentliche Rangliste (Liga-System)**: Nutzer-Klassen nach Gesamt-XP in der aktuellen Woche (Bronze/Silber/Gold-Liga analog Duolingo)
- [ ] **Freunde einladen** via Share-Link (kein Account nötig, nur Link mit Streak-Vergleich)
- [x] **Tages-Challenge**: Täglich wechselnde Mini-Aufgabe (z.B. „Lerne heute 5 Wörter aus Kategorie ‚Essen'")
- [x] **Streak-Gefrierpunkte** (wie Duolingo Streak Freeze): 1 verpasster Tag wird nicht gewertet (1× pro Woche)

#### 8.7 – Bild-Vokabular 🖼️
- [x] **Bild-Quiz-Modus**: Bild anzeigen → 4 Wörter zur Auswahl (Multiple Choice), nutzt Emoji als kostengünstige Bilder
- [ ] **Emoji-Assoziationen** zu allen Vokabeln ergänzen (bereits teilweise vorhanden in Kategorien)
- [ ] **Mnemotechniken (Mems)**: Kurze Merkhilfe bei jeder Vokabel optional anzeigen (z.B. „saudade – klingt wie ‚so da da' – die Sehnsucht nach jemandem, der ‚so da' war")

---

### 🟨 MITTEL – Langfristig (v9.0 – v10.0)

#### 9.0 – Audio-first Modus 🎧
- [ ] **Podcast-Style-Lektionen**: 10-minütige Audio-Einheiten mit eingebetteten Vokabeln (Pimsleur-inspiriert)
- [ ] **Unterwegs-Modus**: Nur Audiofeedback, keine Bildschirminteraktion nötig (ideal für Autofahren)
- [ ] **Echte Audio-Aufnahmen** für die 100 häufigsten Wörter (statt TTS) – bessere Aussprache-Qualität

#### 9.1 – KI-Personalisierung 🤖
- [ ] **Adaptiver Lernalgorithmus 2.0**: Nicht nur SRS-Level, sondern Fehlertyp, Lernzeit und Kategoriepräferenz berücksichtigen
- [ ] **KI-Satzgenerator**: Neue Beispielsätze basierend auf gelernten Wörtern generieren (OpenAI API oder lokales Modell)
- [ ] **Schwachstellen-Analyse 2.0**: Radar-Chart zeigt Stärken/Schwächen nach Skill (Vokabeln, Grammatik, Aussprache, Hören)

#### 9.2 – Zertifikate & Offizielle Anerkennung 🎓
- [ ] **Druckbares Zertifikat** für A1, A2, B1 mit QR-Code zur Online-Verifikation
- [ ] **CEFR-Alignment**: Alle Inhalte klar nach A1/A2/B1/B2 CEFR-Stufen strukturieren und kennzeichnen
- [ ] **LinkedIn-Zertifikat-Integration**: Badge für bestandene Level-Tests teilbar auf LinkedIn

#### 9.3 – Community & Native Speaker 👥
- [ ] **Muttersprachler-Phrasen-Datenbank**: Community kann kurze Audio-Snippets zu Vokabeln beisteuern
- [ ] **Sprachtausch-Board**: Einfaches Matching-System für DE↔PT Sprachaustausch (kein Account nötig, via anonymem Link)

---

### 🟩 NICE TO HAVE – Vision (v10.0+)

#### 10.0 – Technische Modernisierung
- [ ] **Code-Aufteilung**: `app.js`, `data.js`, `styles.css` als separate Dateien (Wartbarkeit)
- [ ] **IndexedDB** statt LocalStorage (>1000 Wörter, Medien-Caching)
- [ ] **Cloud-Sync** via Firebase/Supabase (geräteübergreifend, kein Pflicht-Account)
- [ ] **Mehrsprachig**: Spanisch 🇪🇸 oder Französisch 🇫🇷 als zweites Modul

#### 10.1 – Erweiterte Lernmethoden
- [ ] **Immersions-Modus**: Kompletter Interface-Wechsel auf Portugiesisch (Rosetta Stone-inspiriert)
- [ ] **Lese-Modus mit Vokabelüberlagerung**: Brasilianische Zeitungsartikel/Texte mit Tap-to-Translate
- [ ] **Schreib-Korrekturen durch Community**: Nutzer schreibt Satz auf Portugiesisch, andere Nutzer korrigieren (Busuu-inspiriert)

---

## 📊 Teil 4 – Priorisierungsmatrix

| Feature | Aufwand | Wirkung | Priorität | Version |
|---------|---------|---------|-----------|---------|
| Onboarding Wizard | Mittel | 🔥🔥🔥🔥🔥 | **P0** | v8.0 |
| 5-Min-Session-Timer | Gering | 🔥🔥🔥🔥 | **P0** | v8.0 |
| Geführter Lernpfad | Hoch | 🔥🔥🔥🔥🔥 | **P0** | v8.0 |
| Fortschritts-Heatmap | Mittel | 🔥🔥🔥🔥 | **P1** | v8.0 |
| Aussprache-Bewertung | Mittel | 🔥🔥🔥🔥🔥 | **P1** | v8.5 |
| Tages-Challenge | Gering | 🔥🔥🔥🔥 | **P1** | v8.5 |
| Streak Freeze | Gering | 🔥🔥🔥 | **P1** | v8.5 |
| Emoji-Bild-Quiz | Gering | 🔥🔥🔥🔥 | **P1** | v8.5 |
| Mems / Merkhilfen | Mittel | 🔥🔥🔥 | **P2** | v8.5 |
| Wöchentliche Liga | Hoch | 🔥🔥🔥🔥 | **P2** | v9.0 |
| Audio-Lektionen | Sehr hoch | 🔥🔥🔥 | **P3** | v9.0 |
| KI-Personalisierung | Sehr hoch | 🔥🔥🔥🔥 | **P3** | v9.1 |
| Cloud-Sync | Sehr hoch | 🔥🔥🔥 | **P4** | v10.0 |
| Druckbares Zertifikat | Gering | 🔥🔥🔥 | **P2** | v9.2 |
| Immersions-Modus | Hoch | 🔥🔥🔥🔥 | **P3** | v10.1 |

---

## ⏱️ Zeitplan Roadmap 2.0

| Version | Inhalt | Dauer | Status |
|---------|--------|-------|--------|
| **v8.0** | Onboarding, Lernpfad, Session-Timer, Heatmap, Emoji-Quiz, Tages-Challenge, Streak Freeze | 3–4 Wochen | ✅ **Fertig** (März 2026) |
| **v8.5** | Aussprache-Trainer, Liga-System, erweiterte Statistiken | 4–6 Wochen | 📋 Geplant |
| **v9.0** | Liga-System, Audio-Modus, erweiterte Statistiken | 6–8 Wochen | 📋 Geplant |
| **v9.1** | KI-Personalisierung, adaptives SRS 2.0 | 8–12 Wochen | 📋 Geplant |
| **v9.2** | Zertifikate (druckbar + LinkedIn), CEFR-Alignment | 2–3 Wochen | 📋 Geplant |
| **v10.0** | Code-Split, IndexedDB, Cloud-Sync | 8–12 Wochen | 📋 Vision |
| **v10.1** | Immersions-Modus, Sprachtausch, Schreib-Korrekturen | 6–8 Wochen | 📋 Vision |

---

## 🎯 Teil 5 – Unsere einzigartige Positionierung (USP)

> Trotz aller Verbesserungen bleibt unser Kernvorteil:

```
✅ 100 % kostenlos – kein Freemium, kein Paywall
✅ Browserbasiert – keine App-Store-Abhängigkeit
✅ Spezialisiert auf Brasilianisches Portugiesisch (nicht generisch)
✅ Deutsch-native Interface (nicht nur Englisch)
✅ Offline-first (PWA, Service Worker)
✅ Live-Übersetzung DE → PT (einzigartig)
```

**Positionierung:** *Die beste kostenlose, offline-fähige App für Deutschsprachige, die Brasilianisches Portugiesisch lernen wollen.*

---

## 📈 Erfolgsmetriken Roadmap 2.0

| Metrik | Aktuell (Schätzung) | Ziel v8.0 | Ziel v9.0 |
|--------|---------------------|-----------|-----------|
| Ø Session-Dauer | ~8 Min | 12 Min | 15 Min |
| 7-Tage-Retention | ~15 % | 30 % | 45 % |
| Ø Streak-Länge | ~3 Tage | 7 Tage | 14 Tage |
| Onboarding-Abschluss | n/a | 70 % | 80 % |
| Wörter bis Mastery (≥5 richtig) | ~50/Nutzer | 100/Nutzer | 200/Nutzer |
| PWA-Installationsrate | ~5 % | 15 % | 25 % |

---

*LuiBrasil Roadmap 2.0 – Erstellt: März 2026 | Letzte Aktualisierung: März 2026*  
*Analysierte Wettbewerber: Duolingo, Babbel, Rosetta Stone, Memrise, Busuu, Pimsleur, HelloTalk, Drops*
