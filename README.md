# ODDLY Prototyp

Erlebbarer Desktop-Prototyp von ODDLY (Demo-Fall: LinkedIn-Kampagne zur Exide Sprinter Pure Power FT; V1 bis V3 zeigen noch den alten Fall TRUMPF TruLaser 1030).
Jede Version steckt in einer einzigen Datei (Code, Schriften, Bilder und Logos eingebettet). Kein Build, kein Server nötig.

## Versionen

| Ordner | Link | Inhalt |
|---|---|---|
| `/` | `https://<name>.github.io/<repo>/` | aktueller Stand (in Arbeit) |
| `/v4/` | `https://<name>.github.io/<repo>/v4/` | Version 4: Exide Sprinter, Konzepte-Board, vier große Schritte, Stand 18. November |
| `/v3/` | `https://<name>.github.io/<repo>/v3/` | Version 3: Vorschläge als Board, Source Sans, Stand 17. November |
| `/v2/` | `https://<name>.github.io/<repo>/v2/` | Version 2: vereinfachte Version, Stand 16. November |
| `/v1/` | `https://<name>.github.io/<repo>/v1/` | Version 1: Agentur-Flow, Stand 12. November |

Alle Versionen merken sich ihren Stand getrennt und kommen sich nicht in die Quere.

## Auf GitHub Pages veröffentlichen

1. Auf github.com ein neues Repository anlegen (z. B. `oddly-prototyp`).
2. Im leeren Repository auf **uploading an existing file** klicken und alles aus dem entpackten ZIP hineinziehen: `index.html`, `.nojekyll`, `README.md` und die Ordner `v1`, `v2`, `v3` und `v4`. Dann **Commit changes**.
   Tipp: `.nojekyll` ist auf dem Mac versteckt. Im Finder mit Cmd + Shift + . einblenden.
3. **Settings → Pages**: Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`, **Save**.
4. Nach ein bis zwei Minuten steht oben die Adresse, etwa `https://<name>.github.io/oddly-prototyp/`.

Aktualisieren: neue `index.html` hochladen und die alte damit ersetzen. Die Ordner `v1`, `v2`, `v3` und `v4` bleiben einfach liegen.

## Bedienen

- Empfohlen: Desktop, mindestens 1280 × 800, ideal 1440 × 1008. Läuft in Chrome, Safari, Edge und Firefox.
- Der Stand bleibt im Browser gespeichert, auch nach dem Neuladen.
- Demo-Menü: Alt + Shift + D oder fünfmal schnell aufs Logo tippen (Szenen, Zurücksetzen, Protokoll).
- Zurücksetzen: Alt + Shift + R.

## Bitte beachten

- **Öffentlich:** GitHub Pages ist bei kostenlosen Konten öffentlich, auch wenn das Repository privat ist. Wer die Adresse kennt, sieht den Prototyp. Suchmaschinen sind per `noindex` ausgeschlossen, das ist aber kein Schutz. Für einen Passwortschutz besser Vercel mit Basic Auth nutzen.
- **Inhalte:** Der Demo-Fall nennt Exide Technologies und zeigt echte Motive aus einer nicht freigegebenen Planung, die älteren Versionen nennen TRUMPF. Vor dem Veröffentlichen klären, ob das öffentlich sichtbar sein darf.
- **Schriften:** Die UI-Schrift Source Sans steht unter der SIL Open Font License und darf frei eingebettet werden. Chillax (Überschriften) ist separat lizenziert.
