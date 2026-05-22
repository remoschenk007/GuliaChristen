# MASTERGIULIA — Projekt Timeline & Dokumentation
**Giulia Christen · Bespoke Leather Couture · Zürich & Hamburg**

---

## 🌹 PROJEKT ÜBERSICHT

Komplette Website + Intro-Splash-Seite für **Giulia Christen**, Master Leather Designerin.
- Ausgebildet: Kunstschule Zürich → NABA Milan → Guy Laroche Paris → Pyrate Style Hamburg
- Kunden: Keith Richards, Lenny Kravitz, Lionel Richie, The Scorpions
- Ateliers: Zürich (Hauptsitz) + Hamburg

---

## 📁 GITHUB REPOSITORY

**Repo:** `github.com/remoschenk007/GuliaChristen` (Public)  
**Live URL:** `https://remoschenk007.github.io/GuliaChristen/`

### Aktuelle Dateistruktur auf GitHub:
| Datei | Inhalt |
|-------|--------|
| `index.html` | Intro-Splash (Rose + Unterschrift) — **Startseite** |
| `main.html` | Vollständige Website (6.65 MB) — **Hauptwebsite** |

---

## 🗓️ TIMELINE

### Phase 1 — Hauptwebsite
- **Designsprache:** Tiefschwarz `#030303`, Weiß `rgba(237,232,223,0.48)`, Filmkorn-Overlay
- **Fonts:** Cormorant Garamond (Italic/Light) + Cinzel + Jost
- **Seiten:** Home, About, Commission, Clients, Press, Contact, Impressum, Datenschutz
- **Technologie:** Single-Page-App (JavaScript Navigation), Base64-eingebettete Bilder

**Design-Entscheidungen (final):**
- ❌ Keine Stats-Bar (30+, 100%, ∞) — zu werblich
- ❌ Kein Laufband mit Kunden-Namen
- ❌ Kein Pyrate Style / Hamburg-Partner erwähnt
- ✅ Clients als stille Liste — würdevoll, nicht laut
- ✅ "Er wählte ihre Hände. Nichts mehr muss gesagt werden."
- ✅ Schwarz/Weiß komplett, kein Gold

**Datei:** `giulia_v5.html` → auf GitHub als `main.html`

---

### Phase 2 — Intro Splash Seite

**Konzept:** Rose im Glas (zerfallend) + Unterschrift schreibt sich

**Rose-Bild:** `5006DF63-BA66-42D9-AC22-4C3333EB8882.png`  
→ Schwarze Rose in Glasglocke, hängend, zerfällt nach unten

**Unterschrift:** Echte Handschrift von Giulia Christen  
→ Foto auf weißem Papier, schwarze Tinte (`FullSizeRender.jpeg` — bestes Foto)

**Technische Lösung:**
- Unterschrift als transparentes PNG extrahiert (Tinte weiß, Papier = alpha 0)
- `clip-path: inset(0 100% 0 0)` Animation von links nach rechts → schreibt sich
- `drop-shadow` für leichten Glanz

**Finale Versionen (alle gespeichert):**
| Datei | Farbe | Status |
|-------|-------|--------|
| `intro_weiss.html` | Weiß `rgba(255,255,255)` | ✅ Approved |
| `intro_silbergrau.html` | Silbergrau `RGB(195,200,205)` | Option |
| `intro_champagne.html` | Champagner/Gold | Option |
| `intro_silver.html` | Silber-Blau | Option |

**Responsive:**
- **Mobile:** Rose fullscreen `center 42%/cover`
- **Desktop:** Rose kleiner `background-size: 70%` damit ganze Rose sichtbar

---

## ⚠️ AKTUELLE PROBLEME / TODO

### 1. main.html zeigt 404
**Problem:** `index.html` (Intro) verlinkt auf `giulia_v5.html` — die Datei heisst auf GitHub aber `main.html`

**Fix:** In `intro_weiss.html` ist der Link bereits auf `main.html` korrigiert.  
→ **Lösung:** Neue `intro_weiss.html` als `index.html` auf GitHub hochladen (alte ersetzen)

### 2. main.html zu groß (6.65 MB)
**Problem:** GitHub Editor kann sie nicht anzeigen ("Sorry, this file is too big")  
**Workaround:** Upload via "Add file → Upload files" funktioniert trotzdem  
**Langfristige Lösung:** Bilder externalisieren (separat hosten), dann wird HTML < 100 KB

### 3. Formspree noch nicht eingerichtet
In `main.html` steht `YOUR_FORM_ID` als Platzhalter  
→ **Lösung:** formspree.io → neues Formular → ID einsetzen

---

## 🔧 TECHNISCHE DETAILS

### Website (main.html)
```
Größe: 6.65 MB (Bilder als Base64 eingebettet)
Navigation: JavaScript SPA (Single Page App)
Kontaktformular: Formspree (action="https://formspree.io/f/YOUR_FORM_ID")
SEO: Schema.org JSON-LD, FAQPage, Person, LocalBusiness
Gerichtsstand: Zürich, Schweizer Recht
```

### Intro (index.html)
```
Größe: ~212 KB
Rose: JPEG Base64 eingebettet
Unterschrift: PNG transparent Base64 eingebettet
Animation: clip-path reveal + fadeIn
Link zu: main.html
```

---

## 🎨 DESIGN-SYSTEM

### Farben
```css
--background: #060606 (fast schwarz)
--text: rgba(237,232,223,0.88) (warmes Weiß)
--text-dim: rgba(237,232,223,0.18) (dezent)
--mid: rgba(237,232,223,0.055) (kaum sichtbar)
```

### Typografie
```css
--serif: 'Cormorant Garamond' (Hauptschrift, italic, 300)
--caps: 'Cinzel' (Navigation, Labels)
--sans: 'Jost' (Fließtext, 200)
```

### Philosophie
> Nicht laut. Nicht hausieren. Tiefe statt Lautstärke.  
> Haltung statt Marketing. Wie ein altes Atelier in Paris  
> das keine Werbung braucht — weil jeder der es kennt, es kennt.

---

## 📸 BILDER / ASSETS

| Asset | Beschreibung | Verwendung |
|-------|-------------|------------|
| `5006DF63...png` | Schwarze Rose in Glasglocke | Intro Hintergrund |
| `FullSizeRender.jpeg` | Giulias Unterschrift auf weißem Papier | Intro Signatur |
| `IMG_0266.jpeg` | Ältere Rose (erste Version) | Archiv |
| `photo.jpeg` | Unterschrift zweizeilig (G + C groß) | Archiv |
| `imgs2.json` | Alle Website-Bilder als Base64 | main.html |

---

## ✅ NÄCHSTE SCHRITTE

1. **Sofort:** `intro_weiss.html` herunterladen → als `index.html` auf GitHub hochladen (alte ersetzen)
2. **Formspree:** formspree.io → Account → Formular → ID in main.html einsetzen
3. **Optional:** Domain `giulia-christen.com` verbinden (GitHub Pages → Settings → Custom Domain)
4. **Langfristig:** Bilder aus main.html externalisieren → Dateigröße drastisch reduzieren

---

## 📞 KONTAKT / PROJEKT

- **Website-Entwicklung:** Remo Schenk (`remoschenk007`)
- **GitHub:** `github.com/remoschenk007/GuliaChristen`
- **Designerin:** Giulia Christen — `giulia@giulia-christen.com`

---

*Letzte Aktualisierung: Mai 2025*  
*Dokument: MASTERGIULIA.md*
