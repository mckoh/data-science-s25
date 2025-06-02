# VIrtuelle Umgebungen

Virtuelle Umgebungen (virtual environments) ermöglichen es, abhängige Bibliotheken isoliert für verschiedene Projekte zu verwalten. Dadurch vermeidest du Versionskonflikte zwischen Projekten und kannst eine saubere Entwicklungsumgebung behalten. Darum ist es günstig, für jedes neue Projekt eine virtuelle Umgebung anzulegen.

## Installation von virtualenv

Falls die BIbliothek `virtualenv` noch nicht installiert ist, kannst du es mit pip nachinstallieren:

```bash
pip install virtualenv
```

## Ein virtuelles Environment erstellen

Navigiere in das gewünschte Projektverzeichnis und erstelle ein neues Environment:

```bash
virtualenv mein_env
```

Das erstellt einen Ordner mein_env, in dem alle Abhängigkeiten separat gespeichert werden können. Um das zu tun, muss `mein_env` jedoch aktiviert und benutzt werden.

## Aktivieren des virtuellen Environments

Je nach verwendetem Betriebssystem funktioniert dieser Schritt etwas anders. Unter **Windows** erfolgt die Aktivierung der virtuellen Umgebung so:

```sh
mein_env\Scripts\activate
```

Unter **Mac/Linux** erfolgt die Aktivierung der virtuellen Umgebung wie folgt:

```sh
source mein_env/bin/activate
```

Nach der Aktivierung wird der Name des Environments in der Konsole angezeigt.

## Pakete installieren

Nun kannst du Pakete innerhalb des Environments installieren, ohne das globale Python zu beeinflussen:

```bash
pip install numpy pandas
```

Falls eine Requirements-Date verwendet wird (`requirements.txt`), können Abhängigkeiten auch direkt aus dieser Datei heraus installiert werden:

```bash
pip install -r requirements.txt
```

Wer möchte, kann eine Liste von Abhängigkeiten auch direkt aus einer bereits benutzten Python-Umgebung exportiert werden. Hierzu kann folgendes Skript benutzt werden:

```bash
pip freeze > requirements.txt
```