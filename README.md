# OMNIA – deine lokale KI-Plattform

OMNIA ist eine KI, die **komplett auf deinem eigenen PC** läuft: Chat, Wissensdatenbank, Code-Studio,
Spieleentwicklung (Godot und Roblox) und ein PC-Assistent. Deine Gespräche und Dateien verlassen deinen
Rechner nicht, es gibt kein Abo und keine Cloud.

## ⬇️ Download

**[OMNIA-Launcher.exe herunterladen](https://github.com/astdevin21-cmyk/omnia-releases/releases/latest/download/OMNIA-Launcher.exe)**
(ca. 80 KB, der Launcher lädt den Rest selbst)

Alle Versionen: [Releases](https://github.com/astdevin21-cmyk/omnia-releases/releases)

## So geht's

1. `OMNIA-Launcher.exe` starten.
   Windows zeigt beim ersten Mal „Der Computer wurde durch Windows geschützt“, weil die Datei noch kein
   gekauftes Herausgeber-Zertifikat hat → **Weitere Informationen** → **Trotzdem ausführen**.
2. **Installieren**: OMNIA wird geladen (ca. 180 MB) und **vor dem Entpacken auf eine digitale Signatur geprüft**.
3. **Ollama installieren**, falls noch nicht vorhanden: offizieller Installer von ollama.com, dessen Signatur
   vorher geprüft wird.
4. **Modelle laden**: Pflicht ca. 5,5 GB, empfohlen weitere ca. 15 GB.
5. **OMNIA starten**: Die Oberfläche öffnet sich im Browser. Dort legst du dein Besitzer-Konto mit Passwort und PIN an.

## Voraussetzungen

| | Minimum | Empfohlen |
|---|---|---|
| System | Windows 10/11, 64 Bit | Windows 11 |
| Grafikkarte | 8 GB Grafikspeicher (NVIDIA) | 12–16 GB |
| Arbeitsspeicher | 16 GB | 32 GB |
| Speicherplatz | 10 GB | 25 GB |

## Datenschutz und Sicherheit

- OMNIA ist nur auf deinem PC erreichbar (`127.0.0.1`), nicht im Netzwerk oder Internet.
- Updates installiert der Launcher nur, wenn ihre **digitale Signatur** stimmt.
- Kritische Aktionen der KI (Dateien überschreiben, Programme bedienen, Code ausführen) brauchen deine Freigabe per PIN.
- Läuft ein Spiel mit Anti-Cheat, bedient OMNIA deinen PC nicht.

## Wo liegt was?

`%LOCALAPPDATA%\OMNIA`: `app\` (Programm, wird bei Updates ersetzt), `data\` (Gespräche, Konten, Wissen),
`config\` (Einstellungen), `workspaces\` (Projekte). Updates lassen deine Daten unangetastet.

---
Mitgelieferte Software Dritter und Lizenzen: siehe `LIZENZEN.txt` im Programmordner.
