## System Update Manager

Ein fortschrittlicher System-Update-Manager für Ubuntu/Debian mit interaktivem Menü, Multi-Paketverwaltung (APT, Flatpak, Snap) und umfassender Protokollierung.

## Features

- Einfach zu bedienendes, interaktives Menü
- Unterstützt das Aktualisieren von APT-, Flatpak- und Snap-Paketen
- Komplettes System-Upgrade und Reinigungs-Workflow
- Systeminformationen und Erkennung des Paketmanagers
- Detaillierte Protokollierung mit automatischer Log-Rotation
- Farbige und informative Ausgaben
- Fehlerbehandlung und Benutzerführung

## Installation

Repository klonen:
```bash
git clone https://github.com/Alex-code-sudo/System-Update-Script-Bash.git && cd System-Update-Script-Bash
```

## Usage

Skript ausführbar machen:
```bash
chmod +x System-Update-Script
```

Skript starten:
```bash
./System-Update-Script
```

Folge dem Menü auf dem Bildschirm:
- Paketlisten aktualisieren
- Pakete upgraden
- System bereinigen
- Kompletter Update-Workflow
- Flatpak- oder Snap-Apps aktualisieren
- Systeminformationen anzeigen
- Beenden

**Hinweis:**
- Das Skript muss nicht als root ausgeführt werden. Es fragt bei Bedarf nach sudo.
- Eine Internetverbindung ist erforderlich.
- Logs werden unter `~/.update-logs/` gespeichert und nach 30 Tagen automatisch gelöscht.

## Anforderungen

- Ubuntu- oder Debian-basiertes System
- Bash-Shell
- APT-Paketmanager
- (Optional) Flatpak und Snap, falls installiert
