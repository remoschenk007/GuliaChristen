# MASTERGIULIA — Master Dokumentation
**Giulia Christen · Dark Artisan Couture · Zürich & Hamburg**
*Stand: Mai 2026*

---

## 👤 ÜBER GIULIA CHRISTEN

- **Alter:** 38 Jahre
- **Ausbildung:** Kunstschule Zürich → NABA Milan (Fashion & Textile Design) → Guy Laroche Paris (Assistant Designer) → Hamburg (Leder & Silber)
- **Ateliers:** Zürich (Avery Manufattura) + Hamburg (Pyrate Style, Eppendorfer Weg 235, 20251 Hamburg)
- **E-Mail:** giulia@giuliachristen.com *(kein Bindestrich)*
- **Domain:** giuliachristen.com *(kein Bindestrich — überall so)*
- **Kunden:** Johnny Depp, Keith Richards, Lenny Kravitz, Lionel Richie, The Scorpions
- **Website-Entwicklung:** Remo Schenk (`remoschenk007`)

---

## 🌐 GITHUB REPOSITORY

- **Repo:** `github.com/remoschenk007/GuliaChristen` (Public)
- **Live URL:** `https://remoschenk007.github.io/GuliaChristen/`
- **Ziel-Domain:** `giuliachristen.com` *(noch nicht verbunden)*

### Aktuelle Dateistruktur auf GitHub:
| Datei | Inhalt | Status |
|-------|--------|--------|
| `index.html` | Intro-Splash (Rose + Unterschrift animiert) | ✅ Live |
| `main.html` | Hauptwebsite (5.2 MB) | ⚠️ Neue Version hochladen |
| `Impressum.html` | Impressum CH + DE + IT | ✅ |
| `Datenschutz.html` | Datenschutz DSG + DSGVO + IT | ✅ |
| `MASTERGIULIA.md` | Diese Dokumentation | ✅ |

### Noch hochzuladen:
- `main.html` — neue Version mit allen Änderungen
- `sitemap.xml`
- `robots.txt`

---

## 🎨 DESIGN-PHILOSOPHIE

**Konzept:** Dark Artisan Couture — Yamamoto-Geist, Wabi-Sabi, anti-fashion, anti-trend.
Nicht laut. Tiefe statt Lautstärke. Wie ein altes Pariser Atelier das keine Werbung braucht.

**Stil-Referenzen:** Yohji Yamamoto, Ann Demeulemeester, Rick Owens.
Nicht Gothic. Nicht Rock. Dark Artisan Couture.

**Positionierung:** Giulia ist der Star — nicht die Läden, nicht die Brands.
Pyrate Style und Avery Manufattura sind Kulissen. Sie ist die Geschichte.
Preise: CHF 1'800+ für Jacken. Zielgruppe: oberes Segment. Die Mittelschicht verschwindet.

### Design-System:
```css
--b:  #060606             /* fast schwarz */
--b2: #0b0b0b
--w:  rgba(237,232,223,0.95)  /* warmes Weiss — Haupttext */
--w2: rgba(237,232,223,0.70)  /* Fliesstext */
--w3: rgba(237,232,223,0.32)  /* Labels, Nav */
Font: Cormorant Garamond (italic, 200/300) + Cinzel (Versalien)
```

**Details:** Filmkorn-Overlay immer aktiv. Custom Cursor. Alle Fotos: grayscale + contrast + brightness gedämpft. Unterschrift schreibt sich via clip-path Animation.

---

## 📄 WEBSITE STRUKTUR (main.html)

Single-Page-App mit JavaScript Navigation.

| Seite | Inhalt |
|-------|--------|
| **Home** | Rose als Hero-Bild, Unterschrift animiert, "Every piece made once." |
| **About** | Giulia-Portrait (Augenbinde-Foto), kein Lebenslauf — nur wer sie ist, ihre Kunden |
| **Commission** | 6 Produkt-Karten mit Enquire-Modal → Formspree |
| **The Craft** | Leder + Silber — Philosophie, echte Bilder, Yamamoto-Quote |
| **Artisan Noir** | Kleider — avantgarde, Paris-DNA, schwarz |
| **Clients** | Johnny Depp · Keith Richards · Lenny Kravitz · Lionel Richie · The Scorpions |
| **Press** | 3 Artikel (Avery Magazin Zürich, Opium Hamburg, pyratestyle.com) |
| **Contact** | Formular (Formspree mpqnknvv) + Adresse |

**Separate Dateien:** `impressum.html` + `datenschutz.html` (eigene HTML-Files, vom Footer verlinkt)

**Nav-Reihenfolge:** Home → About → Commission → The Craft → Artisan Noir → Clients → Press → Contact

---

## 🔧 TECHNISCHES

### Formspree:
- **Account:** Giulia Christen (Registriert mit byraimondo@gmail.com)
- **Form-Name:** Giulia Christen Contact
- **Form ID:** `mpqnknvv`
- **Endpoint:** `https://formspree.io/f/mpqnknvv`
- **⚠️ TODO:** giulia@giuliachristen.com als Linked Email hinzufügen → Form auf diese E-Mail umstellen

### SEO (in main.html eingebaut):
- Title, Description, Keywords (Leder + Silber + Zürich + Hamburg)
- Open Graph (WhatsApp / LinkedIn / Facebook Preview)
- Schema.org: Person + LocalBusiness + FAQPage
- `robots.txt` — alle AI-Crawler erlaubt (GPTBot, Claude, Perplexity, Anthropic)
- `sitemap.xml` — alle Seiten

### Website-Grösse:
- `main.html`: 5.2 MB (alle Bilder als Base64 eingebettet)
- Bilder können später externalisiert werden → dann < 200 KB

---

## 📸 BILDER / ASSETS

### Intro (index.html):
- Rose: `5006DF63-BA66-42D9-AC22-4C3333EB8882.png` — Schwarze Rose in Glasglocke
- Unterschrift: `FullSizeRender.jpeg` → als transparentes PNG extrahiert

### About Portrait:
- `IMG_0279.jpeg` — Giulia mit Leder-Augenbinde ("Wake me up when stammerda ends")
- Instagram-Handle wurde weggecroppt (unterer schwarzer Balken entfernt)

### Artisan Noir (Kleider-Sektion):
- `IMG_0439.jpg` — Modell Lederweste outdoor, Schwarzweiss
- `IMG_0440.jpg` — Modell Turtleneck Leder, Schwarzweiss, nah
- `IMG_0433.jpg` — Dunkle Figur sitzend, atmosphärisch
- `IMG_0434.jpg` — Weisses Kleid mit Silberketten vorne
- `IMG_0436.jpg` — Weisses Kleid Rücken mit hängenden Silberketten

### The Craft — Leder:
- `IMG_0437.jpg` — Leder-Textur Nahaufnahme (fast abstrakt)
- `IMG_0438.jpg` — Lederschnittmuster flat lay, Schwarzweiss
- `IMG_0428.jpg` — Giulias Hände beim Arbeiten (Silberringe sichtbar) ← Stärkstes Bild

### The Craft — Silber:
- `IMG_0430.jpg` — Strukturierter Silber-Siegelring 1
- `IMG_0441.jpg` — Ovaler Ring mit geschnitztem Stein
- `IMG_0432.jpg` — Strukturierter Silber-Siegelring 2
- `IMG_0428.jpg` — Giulias Hände mit Silberringen (4. Bild im Grid)

### Lederjacken (Commission + Home):
- `IMG_9976.jpeg` bis `IMG_9996.jpeg` — j1 bis j12 (12 Jacken-Bilder)
- `IMG_0040.png` — Giulia Portrait (älteres Foto, Backup)

### Encoded Assets (temporär in /tmp, neuer Chat muss neu encodieren):
- `/tmp/imgs_new.json` — j1-j12, giulia
- `/tmp/new_imgs.json` — alle neuen Bilder (noir, craft, silver, hands)
- `/tmp/sig_b64.txt` — Unterschrift PNG transparent Base64
- `/tmp/rose_new.txt` — Rose JPEG Base64

---

## 📋 IMPRESSUM & DATENSCHUTZ

### Impressum (impressum.html):
- Verantwortlich: Giulia Christen
- Atelier Zürich: Avery Manufattura — **⚠️ Adresse noch ausfüllen: `[Adresse Zürich]`**
- Atelier Hamburg: Pyrate Style, Eppendorfer Weg 235, 20251 Hamburg
- Gerichtsstand: Zürich, Schweiz — mit EU-Verbraucherschutz-Klausel für DE + IT
- Hosting: GitHub Pages (GitHub Inc., USA)
- Kontaktformular: Formspree Inc., USA

### Datenschutz (datenschutz.html):
- Gilt nach: DSG (Schweiz) + DSGVO (EU/Deutschland) + D.lgs. 196/2003 (Italien)
- Keine Cookies, kein Tracking, keine Analytics
- Beschwerderecht: EDÖB (CH), Hamburg (DE), Garante (IT)

---

## ✅ WAS FERTIG IST

- [x] Intro-Seite (index.html) — Rose + Unterschrift animiert → main.html
- [x] Hauptwebsite (main.html) — alle 8 Sektionen komplett
- [x] Unterschrift als Logo in der Nav (statt Text)
- [x] About — kein Lebenslauf, sie ist der Star
- [x] The Craft — Leder + Silber mit echten Bildern
- [x] Artisan Noir — Kleider, Paris-DNA, Yamamoto-Philosophie
- [x] Clients — Johnny Depp als Erster, alle 5 Namen
- [x] Footer — eine Zeile: © + Impressum + Datenschutz
- [x] impressum.html — CH + DE + IT rechtssicher (separate Datei)
- [x] datenschutz.html — DSG + DSGVO + IT (separate Datei)
- [x] Formspree ID eingesetzt: mpqnknvv
- [x] E-Mail überall: giulia@giuliachristen.com (kein Bindestrich)
- [x] Domain überall: giuliachristen.com (kein Bindestrich)
- [x] SEO vollständig: Meta, OG, Schema.org, FAQPage
- [x] AI Search: robots.txt mit allen AI-Crawlern erlaubt
- [x] sitemap.xml erstellt
- [x] Nav-Links sichtbarer (opacity erhöht)

---

## ⚠️ NOCH OFFEN / TODO

1. **main.html auf GitHub hochladen** (neue Version, 5.2 MB) via "Add file → Upload files"
2. **sitemap.xml + robots.txt** auf GitHub hochladen
3. **Formspree:** giulia@giuliachristen.com als Linked Email → Form umstellen
4. **Impressum:** Zürich-Adresse ausfüllen (`[Adresse Zürich]` Platzhalter)
5. **Domain** giuliachristen.com verbinden: GitHub Pages → Settings → Pages → Custom Domain
6. **Weitere Bilder:** Mehr Silberschmuck wenn vorhanden
7. **Weitere Bilder:** Mehr Artisan Noir Kleider wenn vorhanden

---

## 🗂️ AUSGABE-DATEIEN

Alle Dateien unter `/mnt/user-data/outputs/` (Claude) bzw. heruntergeladen:

| Datei | Grösse | Aktion |
|-------|--------|--------|
| `main.html` | 5.2 MB | GitHub hochladen (ersetzt alte) |
| `impressum.html` | 37 KB | ✅ schon auf GitHub |
| `datenschutz.html` | 37 KB | ✅ schon auf GitHub |
| `sitemap.xml` | 1 KB | GitHub hochladen |
| `robots.txt` | 1 KB | GitHub hochladen |
| `MASTERGIULIA.md` | — | GitHub ersetzen |

---

*Letzte Aktualisierung: 30. Mai 2026*
*Dokument: MASTERGIULIA.md*
*Projekt: github.com/remoschenk007/GuliaChristen*
