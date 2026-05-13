# iOS PWA Redirect

Diese PWA leitet nur weiter, wenn sie auf iOS/iPadOS als Home-Screen-Web-App im Standalone-Modus gestartet wurde.

## Ziel ändern

In `index.html` diese Zeile ändern:

```js
const TARGET_URL = "https://example.com";
```

## Installation auf iOS

1. Projekt per HTTPS hosten.
2. Seite in Safari öffnen.
3. Teilen → „Zum Home-Bildschirm“.
4. App vom Home-Bildschirm starten.

Im normalen Safari-Browser wird nicht weitergeleitet.
