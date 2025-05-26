# Einführung in Git und GitHub

Git und GitHub sind leistungsstarke Werkzeuge für die Versionskontrolle und die Zusammenarbeit in Softwareprojekten. Dieses Dokument bietet eine grundlegende Einführung in deren Verwendung.

## Installation von Git

Um Git zu nutzen, muss es zunächst installiert werden. Besuche die offizielle Website [Git Downloads](https://git-scm.com/downloads) und folge den Installationsanweisungen für dein Betriebssystem.

## Grundlegende Git-Befehle

Sobald Git installiert ist, kannst du es über die Kommandozeile verwenden. Hier sind einige grundlegende Befehle:

```bash
# Ein neues Repository initialisieren
git init

# Den aktuellen Status eines Repositories anzeigen
git status

# Dateien zur Staging-Area hinzufügen
git add <datei>

# Änderungen mit einer Nachricht speichern
git commit -m "Meine Commit-Nachricht"

# Repository mit einem Remote verbinden
git remote add origin <URL>

# Änderungen zum Remote-Repository pushen
git push origin main
```

## Arbeiten mit GitHub
GitHub ist eine Plattform zur Verwaltung von Git-Repositories und zur Zusammenarbeit mit anderen Entwicklern.

Ein Repository auf GitHub erstellen:

1. Melde dich bei GitHub an.
1. Klicke auf "**New Repository**".
1. Vergib einen Namen und eine Beschreibung.
1. Wähle "**Initialize with a README**" (optional).
1. Klicke auf "**Create Repository**".

## Arbeiten mit GitHub ohne Kommandozeile

Git wurde ursprünglich hauptsächlich über die Kommandozeile bedient, was Entwicklern eine direkte und flexible Möglichkeit zur Versionskontrolle bot. Während diese Methode nach wie vor weit verbreitet ist, stehen uns heute auch moderne grafische Werkzeuge zur Verfügung, die den Umgang mit Git erleichtern und insbesondere für Einsteiger intuitiver machen.

Eines dieser Werkzeuge ist **GitHub Desktop**, eine Anwendung mit einer benutzerfreundlichen grafischen Oberfläche, die es ermöglicht, Git-Repositories komfortabel zu verwalten. Mit GitHub Desktop können wir Änderungen verfolgen, Commits erstellen, Branches verwalten und Repositorys synchronisieren, ohne auf die Kommandozeile zurückgreifen zu müssen. Dieses Tool eignet sich besonders für Teams und Entwickler, die einen visuellen Überblick über ihre Projekte schätzen und Arbeitsabläufe optimieren möchten.

GitHub Desktop kann kostenfrei heruntergeladen werden und ist sowohl für Windows als auch für macOS verfügbar. Eine Installation ist unkompliziert, sodass wir direkt loslegen können. [Hier geht’s zum Download](https://desktop.github.com/download/).

Alternativ kann **Git auch direkt aus VS-Code** heraus bedient werden. Dazu kann das Source-Control-Modul benutzt werden. Mehr dazu im Kurs, oder unter folgendem [Link](https://code.visualstudio.com/docs/sourcecontrol/overview).