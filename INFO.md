# Leipzig Tour - Verlorene Pracht

Mobile-optimierte Webseite für eine 1-stündige Stadtführung durch Leipzig mit historischen Fotos von zerstörten und erhaltenen Gebäuden.

## Live-Version

**https://konradreyhe.github.io/LeipzigTour/**

## Lokale Entwicklung

### Voraussetzungen
- Git
- Ein Webbrowser

### Repository klonen
```bash
git clone https://github.com/KonradReyhe/LeipzigTour.git
cd LeipzigTour
```

### Lokal öffnen
Die Webseite ist eine statische HTML-Datei ohne Build-Prozess:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

## Deployment

Die Webseite wird automatisch über GitHub Pages bereitgestellt.

### Änderungen pushen
```bash
git add -A
git commit -m "Beschreibung der Änderungen"
git push
```

Nach dem Push wird die Live-Seite automatisch aktualisiert (kann 1-2 Minuten dauern).

## Projektstruktur

```
LeipzigTour/
├── index.html          # Hauptseite (HTML, CSS, JavaScript)
├── INFO.md             # Diese Datei
├── qrcode.svg          # QR-Code zur Webseite
└── *.jpg               # Historische Fotos (48 Bilder)
```

## Bildnamenskonvention

Die Bilder folgen diesem Schema:
```
[STOP]_[ORT]_[GEBÄUDE].jpg
```

Beispiele:
- `01_AUGUSTUSPLATZ_Paulinerkirche.jpg`
- `05_WILHELM_LEUSCHNER_Markthalle.jpg`
- `06_HONORABLE_Krystallpalast_Variete.jpg`
- `07_SONSTIGE_Volkshaus.jpg`

## Stops der Tour

1. **Augustusplatz** - Universität, Paulinerkirche, Museum
2. **Grimmaische Straße** - Hansa-Haus, Café Felsche
3. **Markt** - Siegesdenkmal, Untergrund-Messhalle
4. **Thomasring** - Commandantur, Centraltheater
5. **Wilhelm-Leuschner-Platz** - Grassimuseum, Markthalle, Reformierte Kirche
6. **Bonus** - Honorable Mentions & Sonstige

## Lizenz

Historische Fotos: Gemeinfrei / Public Domain
