﻿# vuejs dev_environment

## übersicht - Einrichtung einer Entwicklungs-Umgebung in Docker und Linux

Dieses Projekt enthält eine Sammlung von Skripten und Konfigurationsdateien, um eine Entwicklungsumgebung in Docker mit einem simplen vuejs-Projekt einzurichten. Es ist empfohlen, WSL2 zu verwenden.

## Voraussetzungen

Vor der Einrichtung der Entwicklungs-Umgebung benötigen Sie:

- Docker Desktop (4.17.0+)

## Anleitung

Folgen Sie den folgenden Schritten, um die Entwicklungsumgebung einzurichten:

1. Klone das Projekt-Repository:

   ```bash
   git clone https://github.com/nile4000/dev_environment.git

   ```

1. > Nur bei Bedienung per Konsole:

   ```bash
   docker compose up -d
   ```

2. Docker Desktop starten & dev environment hinzufügen -> Start mit VS Code

4. Projekt öffnen:
   ```bash
   cd vuejs
   ```
5. Frontend im Browser über http://localhost:8080/ anzeigen, bei start von Entwicklung mit yarn http://localhost:8082/


## Konfiguration

Die Konfiguration der Entwicklungsumgebung erfolgt über die Datei `compose-dev.yaml`. In dieser Datei können Sie die folgenden Einstellungen vornehmen:

## Support

Bei Fragen oder Problemen wenden Sie sich bitte an [nile4000](mailto:nile@live.de).

## Lizenz

Dieses Projekt ist unter der [MIT-Lizenz](LICENSE) lizenziert.
