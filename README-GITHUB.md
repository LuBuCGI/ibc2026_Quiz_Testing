# CGI Quiz Platform v1.5.2 – GitHub Pages

Diese Variante ist für einen statischen Test über GitHub Pages vorbereitet.

## Upload
Lade **den Inhalt dieses Ordners** in das Root-Verzeichnis Deines GitHub-Repositories.
`index.html` muss direkt im Repository-Root liegen.

## GitHub Pages aktivieren
1. Repository → **Settings**
2. **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main**
5. Folder: **/ (root)**
6. **Save**

Danach stellt GitHub eine URL wie
`https://<username>.github.io/<repository>/`
bereit.

## Hinweis zur Datenspeicherung
Die Anwendung bleibt eine statische Offline-/Browser-App. Teilnahme- und Analytics-Daten werden
weiterhin nur im jeweiligen Browser (`localStorage`) gespeichert. Bei Tests auf mehreren Geräten
werden die Daten daher **nicht zentral zusammengeführt**.

Version: 1.5.2 GitHub Pages
