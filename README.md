# ODDLY Prototyp

Erlebbarer Desktop-Prototyp von ODDLY (Demo-Fall: LinkedIn-Kampagne zur TRUMPF TruLaser 1030).
Alles steckt in einer Datei: `index.html` enthält Code, Schriften, Bilder und Logos. Kein Build, kein Server nötig.

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen (z. B. `oddly-prototyp`).
2. Im leeren Repository auf **uploading an existing file** klicken und `index.html`, `.nojekyll` und `README.md` hineinziehen. Dann **Commit changes**.
   Tipp: `.nojekyll` ist auf dem Mac versteckt. Im Finder mit Cmd + Shift + . einblenden.
3. **Settings → Pages**: Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`, **Save**.
4. Nach ein bis zwei Minuten steht oben die Adresse, etwa `https://<name>.github.io/oddly-prototyp/`.

Aktualisieren: neue `index.html` hochladen und die alte damit ersetzen.

## Bedienen

- Empfohlen: Desktop, mindestens 1280 × 800, ideal 1440 × 1008. Läuft in Chrome, Safari, Edge und Firefox.
- Der Stand bleibt im Browser gespeichert, auch nach dem Neuladen.
- Demo-Menü: Alt + Shift + D oder fünfmal schnell aufs Logo tippen (Szenen, Zurücksetzen, Protokoll).
- Zurücksetzen: Alt + Shift + R.

## Bitte beachten

- **Öffentlich:** GitHub Pages ist bei kostenlosen Konten öffentlich, auch wenn das Repository privat ist. Wer die Adresse kennt, sieht den Prototyp. Suchmaschinen sind per `noindex` ausgeschlossen, das ist aber kein Schutz. Für einen Passwortschutz besser Vercel mit Basic Auth nutzen.
- **Inhalte:** Der Demo-Fall nennt TRUMPF und zeigt Motive und Texte zur TruLaser 1030. Vor dem Veröffentlichen klären, ob das öffentlich sichtbar sein darf.
- **Schriften:** Avenir ist eine lizenzpflichtige Schrift. Für eine öffentliche Webseite braucht es eine passende Weblizenz.
