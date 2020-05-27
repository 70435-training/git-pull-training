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

* Git-Kommandozeilen-Tools sind installiert [(Hilfe)](cheat-sheet/0810.md)
* Gitg ist installiert [(Hilfe)](cheat-sheet/0900.md)
* Fork von diesem Repo ist angelegt, Arbeit erfolgt nur an
  diesem Fork
* Du hast zwei lokale Clones vom Fork [(Hilfe)](cheat-sheet/0910.md)
* Du hast zwei Kommandozeilenfenster, deren Arbeitsverzeichnis
  sich in jeweils einer lokalen Clone-Instanz befindet

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

- Stelle sicher, dass alle Änderungen am zentralen Repo bei Dir lokal verfügbar sind in beiden Fenstern [(Hilfe)](cheat-sheet/1010.md)
- Visualisiere die Situation in beiden Fenstern [(Hilfe)](cheat-sheet/1020.md)
- Kontrolliere, ob "master" und "origin/master" übereinstimmen in beiden Fenstern!

### Durchführung

- Fenster 1: Hierin erledigst Du "Deine Aufgaben"
- **Fenster 2**: Hierin simulierst Du einen Kollegen, der parallel zu Dir
  am gleichen Git-Projekt arbeitet
- Fenster 1: Lege eine neue Datei an
    - Name: pull-training-neu.txt
    - Inhalt: "Ich finde es gut!"
    - [Hilfe](cheat-sheet/1100.md)
- Fenster 1: Speichere die Datei lokal in GIT [(Hilfe)](cheat-sheet/1110.md)
- **Fenster 2**: Lege eine neue Datei an
    - Name: pull-training-kollege.txt
    - Inhalt: "Ich finde es supergut!"
    - [Hilfe](cheat-sheet/1120.md)
- **Fenster 2**: Speichere die Datei lokal in GIT [(Hilfe)](cheat-sheet/1130.md)
- **Fenster 2**: Veröffentliche die Änderung [(Hilfe)](cheat-sheet/1140.md)
- Fenster 1: Lege noch eine neue Datei an
    - Name: pull-training-nochmal.txt
    - Inhalt: "Langsam wird's langweilig!"
    - [Hilfe](cheat-sheet/1150.md)
- Fenster 1: Speichere die Datei lokal in GIT [(Hilfe)](cheat-sheet/1160.md)
- Fenster 1: Veröffentliche die Änderungen [(Hilfe)](cheat-sheet/1170.md)

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
