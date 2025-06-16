# Megatutorial 2: Explorative Datenanalyse

In diesem Megatutorial beschäftigen wir uns noch etwas eingehender mit der Exploration unserer Daten. Heute wollen wir dazu aber bereits Machine-Learning-Techniken verwenden. Wie ihr bereits aus der VO wisst, gehört auch das unsupervised Learning zu den Techniken der deskriptiven Datenanalyse. Warum? Weil wir für diese Techniken kein Target benötigen, sondern die Daten einfach für sich sprechen lassen können - also eben deskriptiv arbeiten.

## Szenario

Wir beschäftigen uns in diesem Megatutorial noch einmal mit unseren Social-Media-Daten. Wir wissen bereits vom letzten mal, dass wir 576 Datensätze mit je 12 Features bekommen haben. Nun wollen wir versuchen, diese Daten mit Hilfe von (a) Agglomerativ Hierarchischem Clustering und (b) K-Means auszuwerten. Dazu wollen wir `scikit-learn` verwenden.

## Aufgaben

* Lade die Daten in `pandas`.
* Verschaffe dir einen Überblick über die Daten
* Lade `scikit-learn` und suche dir die Dokumentation zum [Clustering in `scikit-learn`](https://scikit-learn.org/stable/modules/clustering.html).
* Führe eine Datenanalyse mit Hilfe von  [`AgglomerativeClustering`](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html) druch.
* Führe eine Datenanalyse mit Hilfe von [`KMeans`](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) durch.
