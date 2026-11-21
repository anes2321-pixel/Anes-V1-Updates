# Anes V1 Website

Statische, eigenständige Website für Anes V1. Sie verwendet keine Build-Tools oder externen Bilddateien.

## GitHub Pages veröffentlichen

Der Workflow `.github/workflows/deploy.yml` veröffentlicht die Seite bei jedem Push auf `main`.

Beim ersten Mal muss in GitHub unter **Settings → Pages → Build and deployment → Source** einmal **GitHub Actions** ausgewählt werden. Starte danach unter **Actions** den Workflow **Deploy Anes V1 website** über **Run workflow**. Sobald der erste Lauf erfolgreich war, zeigt GitHub die Seitenadresse im Pages-Bereich; spätere Änderungen werden automatisch veröffentlicht.

Die Download- und Update-Links führen zum Bereich **Releases**. Eine JAR erscheint dort erst, wenn sie separat als Release-Datei veröffentlicht wurde.
