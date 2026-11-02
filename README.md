# Kuchl

Web-App (PWA) für iPhone und Android. Läuft offline, Daten bleiben auf dem Gerät.

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen, z. B. `kuchl`, **Public**.
2. „uploading an existing file“ anklicken und den **Inhalt** dieses Ordners hineinziehen
   (`index.html`, `manifest.webmanifest`, `sw.js`, `README.md` und den Ordner `icons`). „Commit changes“.
3. Repository → **Settings → Pages** → Source: „Deploy from a branch“, Branch: `main`, Ordner `/ (root)` → Save.
4. Nach 1–2 Minuten ist die App erreichbar unter `https://DEIN-NAME.github.io/kuchl/`.

## Installieren

- **iPhone:** Link in Safari öffnen → Teilen → „Zum Home-Bildschirm“.
- **Android:** Link in Chrome öffnen → Menü → „App installieren“.

## Updates

Geänderte Dateien wieder hochladen und in `sw.js` die Zeile `VERSION = 'kuchl-v1'` hochzählen
(`v2`, `v3` …). Die Handys laden die neue Version beim nächsten Öffnen.

## Backup

Meine Rezepte → Zahnrad → „Backup speichern“. Die Datei in pCloud ablegen.
Auf einem anderen Gerät mit „Backup laden“ zusammenführen oder ersetzen.
