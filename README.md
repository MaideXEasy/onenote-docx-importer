# OneNote Docx Importer Add-in

## Einrichtung (einmalig, ~5 Minuten)

### Schritt 1: GitHub Repository erstellen
1. Gehe zu github.com → „New repository"
2. Name: `onenote-docx-importer`
3. Public auswählen
4. „Create repository" klicken

### Schritt 2: Dateien hochladen
Lade diese zwei Dateien hoch:
- `index.html`
- `manifest.xml`

### Schritt 3: manifest.xml anpassen
Öffne `manifest.xml` auf GitHub und ersetze:
```
DEIN-USERNAME
```
mit deinem echten GitHub-Benutzernamen.

### Schritt 4: GitHub Pages aktivieren
1. Repository → Settings → Pages
2. Source: „Deploy from a branch"
3. Branch: `main` → `/root`
4. Save

Nach ~2 Minuten ist das Add-in erreichbar unter:
`https://DEIN-USERNAME.github.io/onenote-docx-importer/`

### Schritt 5: Add-in in OneNote laden
1. OneNote öffnen
2. Einfügen → Add-ins → „Meine Add-ins verwalten"
3. „Hochladen" → `manifest.xml` auswählen
4. Add-in erscheint in der Symbolleiste

## Verwendung
1. Gewünschten Abschnitt in OneNote öffnen
2. Add-in öffnen
3. .docx Dateien reinziehen oder auswählen
4. „Import starten" klicken
