# Anes V1 Website

Statische, eigenständige Website für Anes V1. Sie verwendet keine Build-Tools oder externen Bilddateien.

Live: <https://anes2321-pixel.github.io/Anes-V1-Updates/>

Mod-Download (immer neueste Version): <https://github.com/anes2321-pixel/Anes-V1-Updates/releases/latest/download/Anes-V1.jar>

## Automatische Mod-Updates

Installiere **Anes V1 v23.2.1** einmal im Minecraft-Ordner `mods`. Der eingebaute Updater prüft beim Start neue GitHub-Releases, lädt `Anes-V1.jar` herunter und setzt die Datei nach dem Beenden von Minecraft ein. Für jede neue Mod-Version muss eine höhere Release-Version veröffentlicht werden; der Release muss die Datei `Anes-V1.jar` enthalten. Der Release-Workflow aktualisiert anschließend die Versionsdatei und veröffentlicht die Website erneut.

## GitHub Pages veröffentlichen

Der Workflow `.github/workflows/deploy.yml` veröffentlicht die Seite bei jedem Push auf `main`.

GitHub Pages ist für dieses Repository auf **GitHub Actions** gestellt. Der Workflow veröffentlicht die Seite bei jedem Push auf `main`.

Die Download- und Update-Links führen zum Bereich **Releases**. Eine JAR erscheint dort erst, wenn sie separat als Release-Datei veröffentlicht wurde.
