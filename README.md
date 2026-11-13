# ODDLY Prototyp

Erlebbarer Desktop-Prototyp von ODDLY (Demo-Fall: LinkedIn-Kampagne zur TRUMPF TruLaser 1030).
Jede Version steckt in einer einzigen Datei (Code, Schriften, Bilder und Logos eingebettet). Kein Build, kein Server nötig.

## Versionen

| Ordner | Link | Inhalt |
|---|---|---|
| `/` | `https://<name>.github.io/<repo>/` | aktueller Stand (vereinfachte Version, in Arbeit) |
| `/v1/` | `https://<name>.github.io/<repo>/v1/` | Version 1: Agentur-Flow, Stand 12. November |

Beide Versionen merken sich ihren Stand getrennt und kommen sich nicht in die Quere.

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen (z. B. `oddly-prototyp`).
2. Im leeren Repository auf **uploading an existing file** klicken und alles aus dem entpackten ZIP hineinziehen: `index.html`, `.nojekyll`, `README.md` und den Ordner `v1`. Dann **Commit changes**.
   Tipp: `.nojekyll` ist auf dem Mac versteckt. Im Finder mit Cmd + Shift + . einblenden.
3. **Settings → Pages**: Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`, **Save**.
4. Nach ein bis zwei Minuten steht oben die Adresse, etwa `https://<name>.github.io/oddly-prototyp/`.

Aktualisieren: neue `index.html` hochladen und die alte damit ersetzen. Der Ordner `v1` bleibt einfach liegen.

## Bedienen

- Empfohlen: Desktop, mindestens 1280 × 800, ideal 1440 × 1008. Läuft in Chrome, Safari, Edge und Firefox.
- Der Stand bleibt im Browser gespeichert, auch nach dem Neuladen.
- Demo-Menü: Alt + Shift + D oder fünfmal schnell aufs Logo tippen (Szenen, Zurücksetzen, Protokoll).
- Zurücksetzen: Alt + Shift + R.

## Bitte beachten

- **Öffentlich:** GitHub Pages ist bei kostenlosen Konten öffentlich, auch wenn das Repository privat ist. Wer die Adresse kennt, sieht den Prototyp. Suchmaschinen sind per `noindex` ausgeschlossen, das ist aber kein Schutz. Für einen Passwortschutz besser Vercel mit Basic Auth nutzen.
- **Inhalte:** Der Demo-Fall nennt TRUMPF und zeigt Motive und Texte zur TruLaser 1030. Vor dem Veröffentlichen klären, ob das öffentlich sichtbar sein darf.
- **Schriften:** Avenir ist eine lizenzpflichtige Schrift. Für eine öffentliche Webseite braucht es eine passende Weblizenz.
