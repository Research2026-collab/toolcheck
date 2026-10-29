# ToolCheck Inklusion · Projektwebsite

Statische Website des Projekts ToolCheck Inklusion der Katholischen Erwachsenenbildung Rheinland-Pfalz. Die Seite informiert über das Projekt und bietet die Infoblätter in Einfacher Sprache als PDF und Word-Datei zum Download an.

## Inhalt des Ordners

| Datei oder Ordner | Zweck |
|---|---|
| `index.html` | die komplette Website in einer Datei |
| `downloads/` | alle Infoblätter als PDF und als Word-Datei |
| `favicon.svg` | Symbol im Browser-Tab |
| `.nojekyll` | sorgt dafür, dass GitHub Pages die Dateien unverändert ausliefert |

Die Seite braucht keinen Server, keine Datenbank und kein Build-Programm. Nur die Schrift „Atkinson Hyperlegible“ wird von Google Fonts geladen.

## Auf GitHub Pages veröffentlichen

1. Im Repository `Research2026-collab/toolcheck` alle Dateien dieses Ordners hochladen („Add file“ → „Upload files“), den Ordner `downloads` eingeschlossen. Die bisherige `index.html` (Anmeldeformular) wird dabei ersetzt; sie bleibt in der Versionsgeschichte erhalten.
2. Unter „Settings“ → „Pages“ als Quelle „Deploy from a branch“, Branch `main`, Ordner `/ (root)` wählen.
3. Nach etwa einer Minute ist die Seite erreichbar unter `https://research2026-collab.github.io/toolcheck/`.

## Ein neues Infoblatt ergänzen

1. PDF und Word-Datei mit gleichem Namen in `downloads/` legen, zum Beispiel `Infoblatt_Rechnen_Einfache_Sprache.pdf` und `.docx`.
2. In `index.html` in der Liste `READY` einen Eintrag ergänzen (Dateiname ohne Endung, Titel, kurzer Text, Seitenzahl, Symbol).
3. Den passenden Eintrag aus der Liste `SOON` entfernen.

Verfügbare Symbole: `share`, `shield`, `chat`, `heart`, `mic`, `wallet`, `speaker`, `text`, `calc`, `globe`, `puzzle`.

## Später auf einen anderen Server umziehen

Den ganzen Ordner unverändert auf den neuen Webspace kopieren, zum Beispiel per FTP in ein Unterverzeichnis der KEB-Website. Alle Links in der Seite sind relativ, es muss nichts angepasst werden. Auf GitHub kann danach unter „Settings“ → „Pages“ eine Weiterleitung eingerichtet oder das Repository archiviert werden.

## Barrierefreiheit

Die Seite wurde automatisch nach WCAG 2.1 AA geprüft (axe-core, hell und dunkel, Desktop und Smartphone) und ist vollständig per Tastatur bedienbar. Ein Test mit Nutzer:innen und eine Erklärung zur Barrierefreiheit stehen noch aus.

## Lizenz

Die Infoblätter stehen unter CC BY-NC-SA 4.0. Gefördert vom Ministerium für Wissenschaft, Weiterbildung und Gesundheit Rheinland-Pfalz.
