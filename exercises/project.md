# Angabe Gruppenprojekte

Dieses Projekt kann in Gruppen von 2 bis 4 Personen bearbeitet werden. Die Abgabe der Projektarbeit erfolgt via Sakai (siehe Sakai bzgl. Deadline).

## Szenario

Wir wurden vom botanischen Garten in Innsbruck damit beauftragt, ein Klassifikationsmodell für Iris-Pflanzen zu erstellen. Dazu stellt uns der botanische Garten Daten über 150 Iris-Pflanzen zur Verfügung, die in den vergangenen Jahren gesammelt wurden. Wir erhalten folgende Werte für jede Pflanze:

* **`instant`:** fortlaufende Nummer
* **`sepal_length_cm`:** Länge der Sepal-Blätter
* **`sepal_width_cm`:** Breite der Sepal-Blätter
* **`petal_length_cm`:** Länge der Petal-Blätter
* **`petal_width_cm`:** Breite der Petal-Blätter
* **`species`:** Gattung der Iris-Pflanze

## Aufgaben

### Explorative Datenanalyse

* Führt eine geeignete, statistische Gesamtauswertung aller nummerischer Features des Datensatzes durch.
* Wertet das Feature **`sepal_length_cm`** genauer aus.  Entwickelt dazu einen geeigneten Plot um die Verteilung des Features darzustellen. Wertet außerdem zwei sinnvolle nummerische Darstellungen zu diesem Merkmal aus.
* Wertet die Features **`sepal_length_cm`** und **`petal_length_cm`** genauer aus und untersuche die gemeinsame Bewegung der beiden
* Führt eine Korrelationsanalyse aller nummerischen Merkmale durch und stellt diese in einem geeigneten Plot dar.
* Erstellt einen Pairplot aller nummerischen Merkmale im Datenset.
* Interpretiert eure Darstellungen und Auswertungen aus den oberhalb ausgeführten Punkten schriftlich.

### Unsupervised Learning

* Erstellt mit Hilfe von `scipy` ein Dendrogram der gegebenen Daten. Verwendet dazu die Merkmale `sepal_length_cm`, `sepal_width_cm`, `petal_length_cm` und `petal_width_cm`. Ermittelt daraus eine Schätzung für die Clusterzahl.
* Führt eine Clusteranalyse mit den Merkmalen `sepal_length_cm`, `sepal_width_cm`, `petal_length_cm` und `petal_width_cm` durch. Verwendet dazu zwei geeignete Clusteralgorithmen aus `scikit-learn`.
* Interpretiert eure Clusteringergebnisse.

### Supervised Learning

* Vorbereiten
* Algorithmen anwenden
* Interpretiert eure Clusteringergebnisse.
