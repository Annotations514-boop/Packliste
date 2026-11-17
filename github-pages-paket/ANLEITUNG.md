# Reiseliste auf GitHub Pages (kostenlos, ohne Werbe-Badge)

Dauer: ca. 10 Minuten. Alles im Browser am Mac, kein Programm nötig.

## Vorher, in der alten App (Netlify-Adresse)
1. Mehr, "Sicherung speichern", Datei in "Dateien" oder iCloud ablegen.
2. Wichtig: Die Zettel-Fotos sind nicht in der Sicherung und gehen beim Umzug verloren.

## 1. GitHub-Konto
1. github.com, "Sign up".
2. Benutzername: etwas Neutrales ohne Klarnamen oder Firma. Er steht später in der Adresse (benutzername.github.io).
3. Bei den E-Mail-Einstellungen "Keep my email address private" aktiv lassen (Settings, Emails).

## 2. Repository anlegen
1. Oben rechts "+", "New repository".
2. Name: `reiseliste` (Adresse wird `https://BENUTZERNAME.github.io/reiseliste/`).
3. **Public** auswählen (der kostenlose Tarif braucht das). Im Repository liegt nur der App-Code, keine Reisedaten.
4. "Add a README" NICHT ankreuzen. "Create repository".

## 3. Dateien hochladen
1. Auf der leeren Repository-Seite auf den Link "uploading an existing file" klicken.
2. Den **Inhalt** des Ordners `hochladen` in das Fenster ziehen: `index.html`, `sw.js`, `manifest.webmanifest` und den Ordner `icons`.
   Nicht den Ordner `hochladen` selbst, sonst liegt alles eine Ebene zu tief und die Seite findet die Dateien nicht.
3. Warten, bis alle Dateien angezeigt sind, dann unten "Commit changes".

## 4. Pages einschalten
1. Im Repository "Settings", links "Pages".
2. Bei "Source" "Deploy from a branch" wählen.
3. Branch `main`, Ordner `/ (root)`, "Save".
4. Nach 1 bis 2 Minuten die Seite neu laden. Oben steht die Adresse der fertigen Seite.

## 5. Auf dem iPhone
1. Adresse in Safari öffnen, Teilen, "Zum Home-Bildschirm".
2. In der neuen App: Mehr, "Sicherung laden", die Datei von vorhin wählen.
3. Die alte App vom Home-Bildschirm entfernen.

## Neue Version später einspielen
Im Repository "Add file", "Upload files", die geänderten Dateien hineinziehen (gleiche Namen werden ersetzt), "Commit changes". Nach 1 bis 2 Minuten ist sie online. Auf dem Handy die App einmal komplett schließen und neu öffnen.

## Wenn etwas nicht klappt
- Seite zeigt 404: Pages noch nicht fertig (kurz warten) oder die Dateien liegen in einem Unterordner statt direkt im Repository.
- Seite sieht alt aus: App komplett schließen, neu öffnen.
- Hinweis: Die README.md liegt absichtlich nicht im Upload, weil das Repository öffentlich ist.
