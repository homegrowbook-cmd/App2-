# LuiBrasil – Roadmap 2.0
### Competitive Intelligence & strategischer Ausblick

> **Erstellt:** März 2026  
> **Basis:** Vergleich mit den Top 8 Sprach-Apps + aktuellem Feature-Stand LuiBrasil v7.0  
> **Status:** v0.75 implementiert – März 2026

---

## 🔍 Teil 1 – Wettbewerbsanalyse: Top 8 Apps vs. LuiBrasil

### Was machen die Marktführer besser?

| # | App | Was sie BESSER machen als wir | Unsere Lücke |
|---|-----|-------------------------------|--------------|
| 1 | **Duolingo** | KI-adaptiver Pfad, Ligas/Leaderboards, Push-Notifications, Herzen-System (Stakes), sprechende Charaktere | Kein geführter Lernpfad, keine Social-Elemente (**Onboarding ✅ erledigt, Pfad ⏳ offen**) |
| 2 | **Babbel** | Intelligenter Review-Manager, Speech-Recognition für Aussprache, Grammatik-Videos, klarer Kurspfad | Aussprache nur TTS (keine Bewertung), kein geführter Kurs-Flow |
| 3 | **Rosetta Stone** | TrueAccent™ Aussprache-Scoring, Vollimmersion ohne Übersetzung, Bild-basiertes Lernen, Live-Tutoren | Kein Aussprache-Feedback, keine Bildvokabeln, kein Live-Tutor |
| 4 | **Memrise** | Native-Speaker-Videos (echte Muttersprachler), „Difficult Words"-Modus, Merkhilfen (Mems) | Kein Video-Content, keine Mnemotechniken |
| 5 | **Busuu** | Muttersprachler-Korrekturen für Schreibübungen, offizielles McGraw-Hill-Zertifikat, Sprachlernplan mit Kalender | Zertifikate nicht offiziell anerkannt, kein Community-Feedback |
| 6 | **Pimsleur** | Audio-first (perfekt für unterwegs), bewährte Recall-Methode in 30-Min-Einheiten | Kein eigenständiger Audio-Modus für mobiles Lernen |
| 7 | **HelloTalk** | Echter Chat mit Muttersprachlern, Fehlerkorrektur-Funktion, Moments (social feed) | Keine echten Muttersprachler-Interaktionen |
| 8 | **Drops** | Wunderschönes visuelles UI, Wisch-Gesten, 5-Min-Session-Timer, Bild-Wort-Assoziationen (**Timer ✅ erledigt**) | Kein visuelles Assoziationslernen |

---

### Was LuiBrasil bereits BESSER macht (oder gleichwertig ist)

| Feature | LuiBrasil | Wettbewerber |
|---------|-----------|-------------|
| **Vollständig kostenlos** | ✅ 100 % gratis | ❌ Alle Top-Apps haben Bezahl-Features |
| **Fokus auf Brasilianisches Portugiesisch** | ✅ Spezialisiert | ⚠️ Meist generisch (PT + BR gemischt) |
| **Offline-fähig (PWA)** | ✅ Service Worker | ⚠️ Nur wenige Apps vollständig offline |
| **Keine Installation** | ✅ Reiner Browser | ❌ Fast alle brauchen App-Store |
| **DE→PT + EN→PT** | ✅ Dual-Sprache | ⚠️ Meistens nur eine Ausgangssprache |
| **Live-Übersetzung (DE→PT)** | ✅ Spracheingabe ✅ v8.1 | ❌ Kaum vorhanden in dieser Form |
| **SRS mit 5 Levels** | ✅ | ✅ Standard |
| **Konjugations-Trainer** | ✅ | ⚠️ Nur in Premium |
| **Stories + Level-Tests** | ✅ | ⚠️ Nur in Premium |
| **Onboarding-Wizard** | ✅ v8.0 | ✅ Standard bei Top-Apps |
| **Tages-Challenge** | ✅ v8.0 | ⚠️ Nur in Premium |
| **Streak Freeze** | ✅ v8.0 | ⚠️ Nur in Premium (Duolingo) |
| **Bild-/Emoji-Quiz** | ✅ v8.0 (Bilderraten) | ✅ Standard |
| **Heatmap-Fortschritt** | ✅ v8.0 | ⚠️ Selten |
| **iPhone 16 Pro / iOS-optimiert** | ✅ v8.2 | ✅ Native Apps |

---

## 🧠 Teil 2 – Analyse: Die 5 wichtigsten Lücken

### Lücke 1 – Kein strukturierter Lernpfad 🗺️
> **Problem:** Nutzer öffnen die App und sehen ein Raster von Übungstypen ohne klare Reihenfolge. Duolingo und Babbel haben einen geführten Pfad, der Anfängern zeigt, was als nächstes zu tun ist.  
> **Wirkung:** Neue Nutzer brechen früher ab, weil sie orientierungslos sind (sog. „Cold Start Problem").  
> **Status:** Onboarding Wizard ✅ erledigt (v8.0) | Geführter Pfad ⏳ noch offen

### Lücke 2 – Keine Aussprache-Bewertung 🎤
> **Problem:** Wir nutzen TTS (Text-to-Speech) zum Vorlesen, aber Nutzer können ihre eigene Aussprache nicht überprüfen. Rosetta Stone und Babbel bewerten die Aussprache mit Echtzeitfeedback.  
> **Wirkung:** Brasilianisches Portugiesisch hat komplexe Nasalvokale (ã, õ) und Laute, die ohne Feedback schwer zu erlernen sind.

### Lücke 3 – Fehlende Social-/Community-Features 👥
> **Problem:** Lernen ist isoliert. Kein Leaderboard, keine Freunde, kein Vergleich. Duolingo-Studien zeigen: Nutzer mit Liga-Feature lernen 3× häufiger.  
> **Wirkung:** Fehlende externe Motivation führt zu Abbruch nach wenigen Wochen.

### Lücke 4 – Kein visuelles/assoziatives Lernen 🖼️
> **Problem:** Wörter werden als Text gelernt. Drops und Rosetta Stone nutzen Bilder für schnellere, stärkere Gedächtnis-Anker.  
> **Wirkung:** Visuelle Lerner (ca. 65 % aller Menschen) lernen effizienter mit Bildern.  
> **Status:** Bilderraten (Emoji-Quiz) ✅ erledigt (v8.1) | Vollständige Bild-Vokabeln ⏳ noch offen

### Lücke 5 – Suboptimale Mobile-UX auf neuesten Geräten 📱
> **Problem:** iPhone 16 Pro hat Dynamic Island, 120 Hz ProMotion und Super Retina XDR (460 ppi). Die App brauchte angepasste Touch-Targets (≥44pt), ProMotion-freundliche Animationen und korrekte Safe-Area-Nutzung.  
> **Wirkung:** Auf Premium-Geräten fühlte sich die App weniger poliert an.  
> **Status:** ✅ Erledigt in v8.2

---

## 🚀 Teil 3 – Roadmap 2.0: Konkrete Maßnahmen

> **Philosophie:** Wir bleiben **kostenlos, browserbasiert und offline-fähig** – das ist unser Alleinstellungsmerkmal. Wir verbessern gezielt die Bereiche, in denen Marktführer uns überlegen sind.

---

### ✅ ABGESCHLOSSEN – v8.0 / v8.1 / v8.2 / v0.75

#### 8.0 – Onboarding-Flow & UX-Grundlagen ✅
- [x] **Willkommens-Wizard** (3 Screens): Ziel auswählen, Level-Einschätzung, tägliches Zeitbudget
- [x] **„Weiter wo du aufgehört hast"**-Button auf der Startseite
- [x] **Fortschritts-Heatmap** (GitHub-Style) auf dem Homescreen: letzte 30 Lerntage
- [x] **5-Minuten-Session-Modus** (Drops-inspiriert): Timer-basierte Kurzeinheit
- [x] **Konfetti-Animation** bei Meilensteinen
- [x] **Tages-Challenge**: Täglich wechselnde Mini-Aufgabe
- [x] **Streak-Gefrierpunkte** (Duolingo-inspiriert): 1 verpasster Tag wird nicht gewertet (1× pro Woche)
- [x] **Bild-Quiz-Modus (Bilderraten)**: Emoji-Bild → 4 Wörter zur Auswahl

#### 8.1 – Live-Übersetzung & Bilderraten ✅
- [x] **Live-Translate Test-Panel**: DE→PT Spracheingabe mit Audio-Ausgabe
- [x] **Bilderraten-Spiel**: Alltags-Emojis erraten, 12 Runden pro Spiel

#### 8.2 – iPhone 16 Pro / iOS-Optimierung ✅
- [x] **Dynamic Viewport Height (`100dvh`)**: Verhindert Layout-Shift durch iOS Safari Toolbar
- [x] **Tap-Highlight entfernen** (`-webkit-tap-highlight-color: transparent`): Kein blauer Blitz beim Tippen
- [x] **Retina Text-Rendering**: `-webkit-font-smoothing: antialiased` für Super Retina XDR (460 ppi)
- [x] **Kein Body Rubber-Band** (`overscroll-behavior: none`): Verhindert unbeabsichtigtes Scrollen der Seite
- [x] **Scroll-Containment** (`overscroll-behavior: contain`): Bounce-Effekt nur innerhalb der Views
- [x] **44pt Touch-Targets**: Alle Buttons erfüllen Apple HIG Mindestgröße (Settings: 34→44px, Back: 40→44px)
- [x] **300ms Tap-Delay beseitigt** (`touch-action: manipulation`) auf allen interaktiven Elementen
- [x] **ProMotion 120Hz-optimiert** (`will-change: transform`) auf animierten Elementen
- [x] **Confetti-Canvas isoliert** (`contain: strict`) für keine Full-Page-Repaints

#### v0.75 – Haptic Feedback, Swipe-Gesten, Recommendation Engine ✅
- [x] **Haptic Feedback auf iOS/Android**: `navigator.vibrate()` bei richtiger (kurz) / falscher (lang) Antwort in allen Übungstypen
- [x] **Swipe-Gesten auf Karteikarten**: Links wischen = Nochmal, rechts wischen = Gewusst! (Drops/Tinder-inspiriert)
- [x] **Animated Score-Counter**: XP-Zahl zählt hoch beim Sammeln (visuell befriedigend, rAF-basiert)
- [x] **"Heute empfohlen"-Karte**: Personalisierte Tagesempfehlungen basierend auf SRS-Stand und Lernziel (Onboarding-Ziel: Reise, Konversation, Fließend)
- [x] **SRS-Fälligkeits-Zähler** im Home-Screen: Zeigt wie viele Wörter heute zur Wiederholung fällig sind
- [x] **Streak-Alarm**: Warnung am Abend (ab 18:00 Uhr), wenn kein Training heute
- [x] **Merkhilfen (Mems)**: Eselsbrücken-Texte für ausgewählte Vokabeln (Obrigado, Água, Amor, Saudade) auf der Karteikarten-Rückseite (🧠-Icon)
- [x] **`trackLastActivity` mit Datum**: Datumsfeld in lastActivity-Objekt für korrektes Streak/Empfehlungs-Tracking

---



#### 8.3 – Täglicher Lernplan (empfohlener Kurs) 📅
- [ ] **Empfohlener Tages-Kurs**: App zeigt täglich „Heute empfohlen: SRS-Wiederholung + 1 Dialog" (personalisiert nach Onboarding-Ziel)
- [ ] **Geführter Lernpfad für Anfänger**: Schritt-für-Schritt von Basics → A1 → A2 → B1 (Duolingo-Pfad-inspiriert)
- [ ] **Kategorie-Icons vergrößern** + Schwierigkeitsgrad-Anzeige (A1/A2/B1) prominenter

#### 8.4 – Haptic Feedback & Micro-Interactions 📳
- [x] **Haptic Feedback auf iOS**: `navigator.vibrate()` bei richtiger/falscher Antwort (kurz/lang), spürbare Rückmeldung ✅ v0.75
- [x] **Swipe-Gesten auf Karteikarten**: Links wischen = Falsch, rechts wischen = Richtig (Drops/Tinder-inspiriert) ✅ v0.75
- [x] **Animated Score-Counter**: XP-Zahl zählt hoch beim Sammeln (visuell befriedigend) ✅ v0.75

#### 8.5 – Aussprache-Trainer 🎤
- [ ] **Aussprache-Bewertung mit Web Speech API**: Nutzer spricht Wort → App vergleicht mit Zielwort → Feedback (✅ Gut / ⚠️ Versuche nochmal)
- [ ] **Phonetik-Hinweise** bei schwierigen Lauten: z.B. „ã" → „wie das 'ang' in Englisch ohne das 'g'"
- [ ] **Aussprache-Modus** als eigener Übungstyp (30 Wörter vorlesen, Bewertung am Ende)

#### 8.6 – Social & Motivation 👥
- [ ] **Wöchentliche Rangliste (Liga-System)**: Nutzer-Klassen nach Gesamt-XP in der aktuellen Woche (Bronze/Silber/Gold-Liga analog Duolingo)
- [ ] **Freunde einladen** via Share-Link (kein Account nötig, nur Link mit Streak-Vergleich)

#### 8.7 – Erweitertes Bild-Vokabular 🖼️
- [x] **Mnemotechniken (Mems)**: Kurze Merkhilfe bei ausgewählten Vokabeln optional anzeigen ✅ v0.75
- [ ] **Emoji-Assoziationen** zu allen Vokabeln ergänzen (bereits teilweise vorhanden)

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
- [ ] **Home-Screen-Widget (iOS/Android)**: Tagesvokabel oder Streak-Reminder direkt im Widget

#### 10.1 – Erweiterte Lernmethoden
- [ ] **Immersions-Modus**: Kompletter Interface-Wechsel auf Portugiesisch (Rosetta Stone-inspiriert)
- [ ] **Lese-Modus mit Vokabelüberlagerung**: Brasilianische Zeitungsartikel/Texte mit Tap-to-Translate
- [ ] **Schreib-Korrekturen durch Community**: Nutzer schreibt Satz auf Portugiesisch, andere Nutzer korrigieren (Busuu-inspiriert)

---

## 📊 Teil 4 – Priorisierungsmatrix

| Feature | Aufwand | Wirkung | Priorität | Version | Status |
|---------|---------|---------|-----------|---------|--------|
| Onboarding Wizard | Mittel | 🔥🔥🔥🔥🔥 | **P0** | v8.0 | ✅ Fertig |
| 5-Min-Session-Timer | Gering | 🔥🔥🔥🔥 | **P0** | v8.0 | ✅ Fertig |
| Fortschritts-Heatmap | Mittel | 🔥🔥🔥🔥 | **P0** | v8.0 | ✅ Fertig |
| Tages-Challenge | Gering | 🔥🔥🔥🔥 | **P0** | v8.0 | ✅ Fertig |
| Streak Freeze | Gering | 🔥🔥🔥 | **P0** | v8.0 | ✅ Fertig |
| Emoji-Bild-Quiz (Bilderraten) | Gering | 🔥🔥🔥🔥 | **P0** | v8.1 | ✅ Fertig |
| Live-Translate Test-Panel | Mittel | 🔥🔥🔥🔥 | **P0** | v8.1 | ✅ Fertig |
| iPhone 16 Pro / iOS-Optimierung | Gering | 🔥🔥🔥🔥🔥 | **P0** | v8.2 | ✅ Fertig |
| Empfohlener Tages-Kurs | Mittel | 🔥🔥🔥🔥🔥 | **P1** | v8.3 | 📋 Geplant |
| Geführter Lernpfad | Hoch | 🔥🔥🔥🔥🔥 | **P1** | v8.3 | 📋 Geplant |
| Haptic Feedback + Swipe-Gesten | Gering | 🔥🔥🔥🔥 | **P1** | v0.75 | ✅ Fertig |
| Animated XP Counter | Gering | 🔥🔥🔥🔥 | **P1** | v0.75 | ✅ Fertig |
| Recommendation Engine (Heute empfohlen) | Mittel | 🔥🔥🔥🔥🔥 | **P1** | v0.75 | ✅ Fertig |
| Mems / Merkhilfen | Mittel | 🔥🔥🔥 | **P2** | v0.75 | ✅ Fertig |
| Aussprache-Bewertung | Mittel | 🔥🔥🔥🔥🔥 | **P1** | v8.5 | 📋 Geplant |
| Wöchentliche Liga | Hoch | 🔥🔥🔥🔥 | **P2** | v9.0 | 📋 Geplant |
| Audio-Lektionen | Sehr hoch | 🔥🔥🔥 | **P3** | v9.0 | 📋 Geplant |
| KI-Personalisierung | Sehr hoch | 🔥🔥🔥🔥 | **P3** | v9.1 | 📋 Geplant |
| Druckbares Zertifikat | Gering | 🔥🔥🔥 | **P2** | v9.2 | 📋 Geplant |
| Cloud-Sync | Sehr hoch | 🔥🔥🔥 | **P4** | v10.0 | 📋 Vision |
| Immersions-Modus | Hoch | 🔥🔥🔥🔥 | **P3** | v10.1 | 📋 Vision |
| Home-Screen-Widget | Hoch | 🔥🔥🔥 | **P4** | v10.0 | 📋 Vision |

---

## ⏱️ Zeitplan Roadmap 2.0

| Version | Inhalt | Dauer | Status |
|---------|--------|-------|--------|
| **v8.0** | Onboarding, Session-Timer, Heatmap, Emoji-Quiz, Tages-Challenge, Streak Freeze | 3–4 Wochen | ✅ **Fertig** (März 2026) |
| **v8.1** | Bilderraten-Spiel, Live-Translate Test-Panel | 1 Woche | ✅ **Fertig** (März 2026) |
| **v8.2** | iPhone 16 Pro / iOS-Optimierung (44pt Targets, 100dvh, ProMotion, Tap-Delay) | 1 Tag | ✅ **Fertig** (März 2026) |
| **v0.75** | Haptic Feedback, Swipe-Gesten, Animated XP, Recommendation Engine, Mems | 1 Woche | ✅ **Fertig** (März 2026) |
| **v8.3** | Empfohlener Tages-Kurs, geführter Lernpfad | 3–4 Wochen | 📋 Geplant |
| **v8.4** | Haptic Feedback, Swipe-Gesten, Micro-Interactions | 1–2 Wochen | 📋 Geplant |
| **v8.5** | Aussprache-Trainer | 4–6 Wochen | 📋 Geplant |
| **v9.0** | Liga-System, Audio-Modus, erweiterte Statistiken | 6–8 Wochen | 📋 Geplant |
| **v9.1** | KI-Personalisierung, adaptives SRS 2.0 | 8–12 Wochen | 📋 Geplant |
| **v9.2** | Zertifikate (druckbar + LinkedIn), CEFR-Alignment | 2–3 Wochen | 📋 Geplant |
| **v10.0** | Code-Split, IndexedDB, Cloud-Sync, Widget | 8–12 Wochen | 📋 Vision |
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
✅ Optimiert für iPhone 16 Pro (Dynamic Island, ProMotion 120Hz, 44pt Targets)
```

**Positionierung:** *Die beste kostenlose, offline-fähige App für Deutschsprachige, die Brasilianisches Portugiesisch lernen wollen – mit iOS-Optimierungen für iPhone 16 Pro.*

---

## 📈 Erfolgsmetriken Roadmap 2.0

| Metrik | Aktuell (Schätzung) | Ziel v8.x | Ziel v9.0 |
|--------|---------------------|-----------|-----------|
| Ø Session-Dauer | ~8 Min | 12 Min | 15 Min |
| 7-Tage-Retention | ~15 % | 30 % | 45 % |
| Ø Streak-Länge | ~3 Tage | 7 Tage | 14 Tage |
| Onboarding-Abschluss | n/a | 70 % | 80 % |
| Wörter bis Mastery (≥5 richtig) | ~50/Nutzer | 100/Nutzer | 200/Nutzer |
| PWA-Installationsrate | ~5 % | 15 % | 25 % |
| Tap-Reaktionszeit (iOS) | ~350ms | <50ms | <50ms |

---

*LuiBrasil Roadmap 2.0 – Erstellt: März 2026 | Letzte Aktualisierung: März 2026 (v0.75)*  
*Analysierte Wettbewerber: Duolingo, Babbel, Rosetta Stone, Memrise, Busuu, Pimsleur, HelloTalk, Drops*
