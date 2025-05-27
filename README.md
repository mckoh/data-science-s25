# Data Science Übung

Willkommen im offiziellen Repository für den Kurs **Bachelor Management Communication & IT**. Hier findest du alle relevanten Code-Dateien, Materialien und Anleitungen zum Kurs. Zur besseren Nachverfolgbarkeit der Ergebnisse unserer beider LV-Gruppen gibt es im Repo einen IM und einen CT Ordner.

## 📂 Projektübersicht

Dieses Repository enthält:

- Angaben aus den Mega-Tutorials
- [Code](code/) aus den Mega-Tutorials
- [Projektdokumentationen](docs/) und Anleitungen
- [Daten](data/) für unsere Projekte

## 📑 Struktur des Repositories

```plaintext
├── code/               # Code-Dateien zu Vorlesungen & Übungen
│   ├── im/             # Inhalte für Information Management
│   ├── ct/             # Inhalte für Communication Technology
├── data/               # Datensätze & Ressourcen
├── docs/               # Kursdokumentationen
├── requirements.txt    # Paketliste für Virtualenv
├── README.md           # Diese Datei mit allen Infos
├── .gitignore          # Git-Ignore Datei des Repos

```

## 🚀 Einrichtung der Entwicklungsumgebung

Wir verwenden eine **virtuelle Umgebung (virtualenv)** namens `mlenv`. Bitte folge diesen Schritten zur Einrichtung:

### 1️⃣ Klonen des Repositories

Dieser Schritt kann auch mit Hilfe von Github-Desktop erfolgen. Falls ihr das Repo über die Kommandozeile clonen möchtet, könnt ihr das wie folgt machen:

```bash
git clone <REPO-URL>
cd <REPO-NAME>
```

### 2️⃣ Virtualenv erstellen

Diesen Schritt müssen wir nur einmal machen. Ab da ist das virtuelle Environmnet verfügbar und muss nur noch aktiviert werden (siehe nächster Schritt).

```bash
virtualenv <ENV-NAME>
```

### 3️⃣ Virtualenv erstellen & aktivieren

```bash
source <ENV-NAME>/bin/activate   # macOS / Linux
<ENV-NAME>\Scripts\activate      # Windows
```

### 4️⃣ Abhängigkeiten installieren

```bash
pip install -r requirements.txt
```

## 🛠️ Beitrag & Feedback

Falls du Fragen hast oder Fehler findest, erstelle bitte ein Issue oder einen Pull Request. Dein Feedback hilft, das Repository zu verbessern.

Viel Erfolg und happy coding! 🚀