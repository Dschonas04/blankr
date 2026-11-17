# Blankr

Kollaboratives Whiteboard im Browser. React als Oberfläche, ein Go-Server mit WebSockets für die Zusammenarbeit in Echtzeit. Konten, eigene Boards, Freigaben und optional Anmeldung über OpenID Connect (SSO). Alles steckt in einem Container, die Daten liegen in `/data`.

Quellcode und Anleitung: [https://github.com/Dschonas04/Blankr](https://github.com/Dschonas04/Blankr)

## Start

```bash
docker run -d --name blankr -p 8080:8080 -v blankr:/data dschohnas/blankr:1
```

Danach läuft Blankr unter `http://<host>:8080`.

## Tags

`latest`, die genaue Version (`1.1.0`) sowie `1.1` und `1`. Jedes Image gibt es für `linux/amd64` und `linux/arm64`. Dieselben Images liegen auch unter `ghcr.io/dschonas04/blankr`.

## Lizenz

Business Source License 1.1. Lesen, ändern, selbst betreiben und in der eigenen Organisation nutzen ist erlaubt, nicht aber der Betrieb oder Verkauf als kommerzielles Angebot für Dritte. Am 10. August 2030 geht diese Version in Apache 2.0 über.
