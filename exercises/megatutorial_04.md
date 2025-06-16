# Megatutorial 4: Regression

In diesem Megatutorial wollen wir uns mit dem Thema Regression beschäftigen. Dazu werden wir unseren Datensatz wechseln. Fortan werden wir mit der `bikesharing.csv` arbeiten, die wir bereit in Orange kennengelernt haben.

## Szenario

Wir wurden von einem Bikesharing-Unternehmen damit beauftragt, einen historischen Datensatz zum Zweck der Erstellung eines Vorhersagemodells zu analysieren. Das Unternehmen möchte gerne die Anzahl der Verliehenen Bikes einen Tag im Vorhinein vorhersagen können. Dazu sollen Wetterdaten und Daten über den Vorhersagetag verwendet werden. Das Unternehmen kann uns folgende historische Daten zur Verfügung stellen:

* **``instant:``** record index
* **``day``** : day of date
* **``season:``** season (springer, summer, fall, winter)
* **``yr``** : year (2011, 2012)
* **``mnth:``** month ( 1 to 12)
* **``hr:``** hour (0 to 23)
* **``holiday:``** weather day is holiday or not (yes, no)
* **``weekday:``** day of the week (Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday)
* **``workingday:``** if day is neither weekend nor holiday is 1, otherwise is 0
* **``weathersit:``** weathersituation on the current day
* **``temp:``** temperature in Celsius
* **``atemp:``** feeling temperature in Celsius
* **``hum:``** humidity
* **``windspeed:``** wind speed. The values are divided to 67 (max)
* **``casual:``** count of casual users
* **``registered:``** count of registered users
* **``cnt:``** count of total rental bikes including both casual and registered

## Aufgaben

* Lade die Daten in `pandas`.
* Verschaffe dir einen Überblick über die Daten
* Lade `scikit-learn`.
* Entwickle zwei passende Regressionsmodelle in `scikit-learn`.
* Evaluiere deine Regressionsmodelle mit Hilfe der Trainingsdaten.
