# Praktikum Software Engineering: Lunchify
# Git
# 1. Was ist Git?
Git ist ein verteiltes Versionskontrollsystem, das es ermöglicht, Änderungen am Code zu verfolgen und in Teams effizient zusammenarbeiten.
* Dezentrales System - Jeder Entwickler hat eine eigene vollständige Kopie der Repos
* Offline-fähig - Man kann lokal arbeiten und später Änderungen hochladen.
# 2. Funktionen von Git
####  Versionierung & Historie
* Jeder Code-Änderung wird gespeichert (Commit)
* Möglichkeit, ältere Versionen wiederherstellen
####  Branching & Merging
* Parallele Entwicklung möglich
* Eigene Feature-Branches ohne das Hauptprojekt zu beeinflussen
* Merging: Änderungen aus einem Branche in einen anderen übernehmen
####  Staging Area
* Arbeitsbereich (Working Directory) -> Staging Area -> Repository (Commits)
* Änderungen können erst geprüft werden, bevor sie final gespeichert werden
####  Remote-Repositories & Zusammenarbeit
* GitHub, GitLab oder Bitbucket für Teamwork
* Push & Pull: Änderungen hochladen und abrufen
* Pull Requests & Code-Reviews: Zusammenarbeit im Team
####  Rollback & Fehlerkorrektur
* Änderungen zurücksetzen
* Letzten Commit ändern
# 3. Wichtige Git-Befehle
Hier sind die wichtigsten Git-Befehle für die täglichen Arbeiten:

* Neues Repository erstellen:
```
git init 
```
* Repository klonen:
 ```
git clone <URL>
```
* Status der Dateien anzeigen:
```
git status
```
* Datei zur Staging Area hinzufügen:
```
git add <Datei>

git add .
```
* Änderungen speichen:
```
git commit -m "Message"
```
* Änderungen hochladen:
```
git push
```
* Neuste Änderungen abrufen:
```
git pull
```
* Neuen Branch erstellen:
```
git branch <Name>
```
* In einem Branch wechseln:
```
git checkout <Branch>
```
* Branch in aktuellen Branch mergen:
```
git merge <Branch>
```
* Commit-Historie anzeigen:
```
git log
```

