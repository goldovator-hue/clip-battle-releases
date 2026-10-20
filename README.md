# Clip Battle – offizieller Windows-Download

**Aktuelle Version: 5.0.2 · 20. Oktober 2026**

**[Clip Battle 5.0.2 für Windows herunterladen](https://github.com/goldovator-hue/clip-battle-releases/releases/download/v5.0.2/Clip-Battle-Setup-5.0.2.exe)**

[Neueste Veröffentlichung](https://github.com/goldovator-hue/clip-battle-releases/releases/latest) · [Release 5.0.1 mit allen Dateien](https://github.com/goldovator-hue/clip-battle-releases/releases/tag/v5.0.1) · [Versionsarchiv](https://github.com/goldovator-hue/clip-battle-releases/releases)

## Neu in Version 5.0.2

- **Eigener Speicherort:** In der Windows-App unter **Einstellungen → Programm & Daten → Clip-Bibliothek speichern** eine private Festplatte und einen Ordner auswählen.
- **Bibliothek sicher übernehmen:** Vorhandene Medien, Vorschaubilder, Bibliothek, Backups und Einstellungen werden erst bei beendeter Show kopiert und mittels SHA-256 geprüft. Der alte Ordner bleibt als Sicherheitskopie erhalten.
- **Auch nach Updates:** Die neue Festplatte wird dauerhaft gemerkt. Ist sie nicht angeschlossen, wird keine leere Ersatzbibliothek angelegt.
- **Hinweis:** Der ausgewählte Datenordner enthält auch Einstellungen und lokale Zugangsdaten. Verwende eine private, dauerhaft angeschlossene Festplatte.

## Neu in Version 5.0.1

- **Voting-Overlay:** Die runde goldene VS-Medaille sitzt mittig zwischen den beiden Clips.
- **Chat-Abstimmung:** Neue, übersichtlichere Voting-Box mit gut lesbaren Befehlen **!A** und **!B**.
- **Clip-Titel und Anzeigen:** Mehr Platz für längere Clip-Namen und optimierte Darstellung in OBS und der Desktop-Vorschau.
- **Qualitätssicherung:** Node-, Chromium-, Windows- und Installer-Tests erfolgreich abgeschlossen.
- **Windows-Codesignatur:** Installer und Programmdatei wurden für diese Veröffentlichung kryptografisch geprüft. Die Signatur ist selbstsigniert; Windows/SmartScreen können weiterhin eine Warnung über den unbekannten Herausgeber anzeigen.

## Installation und Auto-Update

Clip Battle kann veröffentlichte Updates über den öffentlichen Release-Kanal erkennen, ohne dass ein GitHub-Konto oder GitHub-Token benötigt wird.

Für eine manuelle Installation oder Aktualisierung:

1. Beende zuerst eine laufende Show und erstelle ein vollständiges Backup deiner lokalen Clip-Battle-Daten.
2. Schließe Clip Battle vollständig.
3. Führe **Clip-Battle-Setup-5.0.1.exe** aus und aktualisiere damit deine bestehende Installation.
4. Prüfe danach unter **Einstellungen → Updates** die installierte Version.

Während einer laufenden Show soll das Programm keine automatische Update-Installation ausführen. Vorhandene OBS-/Twitch-Einstellungen und die lokale Clip-Bibliothek bleiben beim regulären Update erhalten.

## Prüfsummen und Update-Dateien

Zu dieser Version gehören der Windows-Installer, `Clip-Battle-Setup-5.0.1.exe.blockmap`, `latest.yml` und `checksums-sha256.txt`. Die Prüfsummendatei ermöglicht einen unabhängigen SHA-256-Vergleich des Installers.

Ältere Versionen und ihre Versionshinweise findest du im [Versionsarchiv](https://github.com/goldovator-hue/clip-battle-releases/releases).

