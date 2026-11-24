# Jakob Abou-Zaher – Portfolio

Persönliches Portfolio, live auf **[abou-zaher.de](https://abou-zaher.de)**.

Eine handgebaute, statische Seite ohne Framework: HTML, CSS und Vanilla JavaScript in einer Datei.

- Interaktives Punkt-Raster im Hero (Canvas), 3D-Neigung des Porträts, Spotlight-Karten
- Animierte Systemkarte (SVG, responsiv per `ResizeObserver`)
- Scroll-Reveals, Zähler und Laufband, mit Rücksicht auf `prefers-reduced-motion`

## Struktur

```
public/          Inhalte der Website (index.html, Bilder, Video)
firebase.json    Firebase-Hosting-Konfiguration
.github/         Automatisches Deployment bei jedem Push auf main
```

## Deployment

Jeder Push auf `main` wird per GitHub Actions automatisch auf Firebase Hosting veröffentlicht.
