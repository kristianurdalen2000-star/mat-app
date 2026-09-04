# Matplanlegger – PWA

`index.html` er originalfilen og er beholdt uendret.

Bruk `pwa.html` som startside når du hoster appen. Den:
- registrerer service worker
- laster manifestet
- viser original `index.html` uten å endre den
- gjør appen installerbar som PWA

Viktig: PWA/service worker krever HTTPS eller localhost.

Filer:
- index.html — original, uendret
- pwa.html — PWA-wrapper
- manifest.json — PWA-manifest
- service-worker.js — offline/cache
- icons/ — PWA-ikoner
