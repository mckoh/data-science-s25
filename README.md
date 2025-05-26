# Data Science Übung

Willkommen im offiziellen Repository für den Kurs **Bachelor Management Communication & IT**. Hier findest du alle relevanten Code-Dateien, Materialien und Anleitungen zum Kurs. Zur besseren Nachverfolgbarkeit der Ergebnisse unserer beider LV-Gruppen gibt es im Repo einen IM und einen CT Ordner.

## 📂 Projektübersicht

Dieses Repository enthält:

- Angaben aus den Mega-Tutorials
- Code aus den Mega-Tutorials
- Projektdokumentationen und Anleitungen
- Skripte zur Installation und Nutzung der Entwicklungsumgebung

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

```bash
git clone <REPO-URL>
cd <REPO-NAME>
```

### 2️⃣ Virtualenv erstellen & aktivieren

```bash
python -m venv mlenv
source mlenv/bin/activate   # macOS / Linux
mlenv\Scripts\activate      # Windows
```

### 3️⃣ Abhängigkeiten installieren

```bash
pip install -r requirements.txt
```

## 🛠️ Beitrag & Feedback

Falls du Fragen hast oder Fehler findest, erstelle bitte ein Issue oder einen Pull Request. Dein Feedback hilft, das Repository zu verbessern.

Viel Erfolg und happy coding! 🚀