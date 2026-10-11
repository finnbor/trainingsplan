# Trainingsplan

Simple Trainings-App fürs iPhone: Push / Pull / Legs & Bauch, Gewicht, Wiederholungen und Sätze eintragen, Trainingstage im Kalender abhaken.

## Auf GitHub hochladen (einmalig)

1. Auf [github.com/new](https://github.com/new) ein neues Repository anlegen, z. B. `trainingsplan`, auf **Public** stellen und auf **Create repository** tippen.
2. Auf der Repo-Seite auf **uploading an existing file** klicken.
3. Diese 5 Dateien reinziehen und auf **Commit changes** klicken:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon-180.png`
   - `icon-512.png`
4. **Settings → Pages**: bei *Source* „Deploy from a branch“ wählen, Branch **main** und Ordner **/ (root)**, dann **Save**.
5. Ca. 1–2 Minuten warten. Die App liegt dann unter:
   `https://DEIN-GITHUB-NAME.github.io/trainingsplan/`

## Aufs iPhone holen

1. Den Link in **Safari** öffnen (nicht Chrome).
2. Unten auf **Teilen** tippen, dann **Zum Home-Bildschirm**, dann **Hinzufügen**.
3. Ab jetzt immer über das Icon auf dem Home-Bildschirm öffnen.

> Wichtig: Das Icon auf dem Home-Bildschirm hat einen eigenen Speicher, getrennt von Safari. Trag deine Trainings deshalb immer über das App-Icon ein, nicht im Safari-Tab.

## Daten & Backup

- Alles wird nur auf deinem iPhone gespeichert, es gibt keinen Server und keinen Account.
- Wenn du ein Training anfängst und die App zwischendurch schließt, bleiben deine Eingaben erhalten.
- Unten in der App kannst du unter **Backup → Exportieren** ab und zu eine Sicherung in die Dateien-App legen. Mit **Importieren** holst du sie zurück, z. B. auf einem neuen iPhone.

## Später was ändern

Die Übungen stehen ganz oben im `<script>`-Teil von `index.html` (`const PLANS = …`). Nach einer Änderung die Datei auf GitHub einfach neu hochladen. Die App lädt die neue Version beim nächsten Öffnen mit Internet, deine gespeicherten Daten bleiben dabei erhalten.
