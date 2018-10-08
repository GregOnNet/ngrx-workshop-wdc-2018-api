# Workshop API

Die API stellt einen die Taskboard API zur Verfügung.

## Contents

- [Setup](#installation-und-start)
- [Update](#update)
- ☁️ [HTTP API](#Dokumentation)

## Installation und Start

Bitte lade das Repository herunter und installiere sie, wie im folgenden Snippet beschrieben.
Nach der Installation läuft die API lokal und benötigt keinen Zugriff auf andere Netzwerkressourcen.

> **Hinweis** Nachdem `npm start` ausgeführt wurde, startet die API unter https://localhost:3000.

```bash
# Herunterladen
git clone https://github.com/GregOnNet/ngrx-workshop-wdc-2018-api.git

# In das API Verzeichnis wechseln
cd leipzig-2018-10-12-api

# Abhängigkeiten installieren
npm install

# API starten
npm start
```

## Update

Wenn diese API Aktualisierungen oder Bugfixes erfährt, kannst du diese wie
folgt beziehen.

```bash
cd leipzig-2018-10-12-api
git reset --hard # Setzt "database/" zurück
git pull         # Lädt Änderungen herunter
npm ci           # Installiert ggf. neue Pakete
```

## Dokumentation

Die RESTful APIs _Taskboard_ und _Dashboard_ wurden mit
[Swagger](https://swagger.io/) dokumentiert. Nach dem starten der API befindet
sich unter http://localhost:3000/api/ eine interaktive Dokumentation.

![Swagger Documentation](assets/images/swagger-docs.png)

