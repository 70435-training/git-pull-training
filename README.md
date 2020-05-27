Training: Git-Pull
==================

Dieses Training soll Dir den Befehl "git pull"
vermitteln und den Unterschied zwischen
"git pull" und "git pull --rebase".

Das Training ist intern und extern verfügbar.
Die externe URL ist: [github:git-pull-training](https://github.com/70435-training/git-pull-training).

Voraussetzungen
---------------

Seitens der "Infrastruktur" gibt es diese Voraussetzungen:

* Firefox ist installiert (Chrome geht nicht) [(Hilfe)](cheat-sheet/cheat-sheet.md#0800)
* Git-Kommandozeilen-Tools sind installiert [(Hilfe)](cheat-sheet/cheat-sheet.md#0810)
* Gitg ist installiert [(Hilfe)](cheat-sheet/cheat-sheet.md#0900)
* Fork von diesem Repo ist angelegt, Arbeit erfolgt nur an
  diesem Fork
* Du hast zwei lokale Clones vom Fork [(Hilfe)](cheat-sheet/cheat-sheet.md#0910)
* Du hast zwei Kommandozeilenfenster, deren Arbeitsverzeichnis
  sich in jeweils einer lokalen Clone-Instanz befindet
* Diese Anleitung kann in Firefox gesichtet werden: `firefox index.html`

Seitens der Kenntnisse:

* Erfahrung mit der Kommandozeile
* Erfahrung mit Git (clone, branch, pull/push, commit, ...)

Ausgangsituation
----------------

![Ausgangssituation](images/start.png)

Die Ausgangssituation sieht so aus:

- Es gibt einen Master-Branch
- In diesem sind einige Änderungen (Commits) verfügbar
- Die Ausgangssituation kannst Du visualisieren mit `gitg master origin/master`
- Visualisiere die Ausgangssituation in beiden Kommandozeilenfenstern,
  sie muß identisch sein!

Ablauf
------

### Vorbereitungen

- Öffne dieses Dokument in Firefox mit `firefox index.html`,
  damit Du direkten Zugriff auf die "cheat sheets" bekommen kannst
  (Chrome geht nicht, Browsen via Github o.ä. geht nicht)
- Stelle sicher, dass alle Änderungen am zentralen Repo bei Dir lokal verfügbar sind in beiden Fenstern [(Hilfe)](cheat-sheet/cheat-sheet.md#1010)
- Visualisiere die Situation in beiden Fenstern [(Hilfe)](cheat-sheet/cheat-sheet.md#1020)
- Kontrolliere, ob "master" und "origin/master" übereinstimmen in beiden Fenstern!

### Durchführung

- Fenster 1: Hierin erledigst Du "Deine Aufgaben"
- Fenster 2: Hierin simulierst Du einen Kollegen, der parallel zu Dir
  am gleichen Git-Projekt arbeitet
- Fenster 1: Lege eine neue Datei an
    - Name: pull-training-neu.txt
    - Inhalt: "Ich finde es gut!"
    - [Hilfe](cheat-sheet/cheat-sheet.md#1100)
- Fenster 1: Speichere die Datei lokal in GIT [(Hilfe)](cheat-sheet/cheat-sheet.md#1110)
- Fenster 2: Lege eine neue Datei an
    - Name: pull-training-kollege.txt
    - Inhalt: "Ich finde es supergut!"
    - [Hilfe](cheat-sheet/cheat-sheet.md#1120)
- Fenster 2: Speichere die Datei lokal in GIT [(Hilfe)](cheat-sheet/cheat-sheet.md#1130)
- Fenster 2: Veröffentliche die Änderung [(Hilfe)](cheat-sheet/cheat-sheet.md#1140)
- Fenster 1: Lege noch eine neue Datei an
    - Name: pull-training-nochmal.txt
    - Inhalt: "Langsam wird's langweilig!"
    - [Hilfe](cheat-sheet/cheat-sheet.md#1150)
- Fenster 1: Speichere die Datei lokal in GIT [(Hilfe)](cheat-sheet/cheat-sheet.md#1160)
- Fenster 1: Veröffentliche die Änderungen [(Hilfe)](cheat-sheet/cheat-sheet.md#1170)

**ABBRUCH**

Nachkontrolle
-------------

- Visualisiere die Situation [(Hilfe)](cheat-sheet/cheat-sheet.md#1210)
- Kontrolliere, ob "master" und "origin/master" übereinstimmen!
- Kontrolliere, ob "experiment" und "origin/experiment" übereinstimmen!
- Vergleiche Dein Bild strukturell mit [images/final.png](images/final.png)

Abschluß
--------

Nach Abschluß des Trainings bitte die URL zu dem bearbeiteten
Fork per Email schicken an "dp-training@daemons-point.com"!
