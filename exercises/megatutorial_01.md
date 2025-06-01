# Megatutorial 1: Explorative Datenanalyse

In diesem Megatutorial beschäftigen wir uns mit der explorativen Datenanalyse in Python.

## Szenario

Wir wurden von einer Social-Media-Plattform damit beauftragt, einen Datensatz mit Profildaten auszuwerten. Das Unternehmen hat uns dazu einen Datensatz mit 576 Profilen zusammengestellt. Aus Datenschutzgründen wurden in diesen Profilen alle personenbezogenen Daten entfernt. Dennoch enthalten die Daten eine Menge an Daten, die Rückschluss auf die Art der Profile enthalten. Darunter sind folgende Merkmale:

* **`profile_pic`:** Eine Bool'sche Variable, die aussagt, ob bei dem Profil ein Profilbild enthalten war, oder nicht.
* **`rel_num_numeric_char_username`:** Die Anzahl der nummerischen Zeichen im Usernamen, in relation zur Gesamtlänge des Usernamen.
* **`words_fullname`:** Die Anzahl der Worte im Namensfeld.
* **`rel_num_numeric_char_fullnam`:** Die Anzahl der nummerischen Zeichen im Namen, in relation zur Gesamtlänge des Namen.
* **`name=username`:** Eine Bool'sche Variable, die aussagt, ob Username und Name übereinstimmen.
* **`description_length`:** Die Länge der Bio, die beim betreffenden Profil hinterlegt wurde.
* **`has_external_url`:** Eine Bool'sche Variable, die aussagt, ob beim Profil eine externe URL (z.B., zu einer Webseite) hinterlegt wurde.
* **`is_private`:** Eine Bool'sche Variable, die aussagt, ob das betreffende Profil als privat markiert wurde.
* **`num_posts`:** Die Anzahl der Posts, die von diesem Profil aus gesendet wurden.
* **`num_followers`:** Die Anzahl der Follower dieses Profils.
* **`num_follows`:** Die Anzahl der Personen, der dieses Profil folgt.
* **`is_fake`:** Eine nachträglich eingefügte Target-Variable, die Angibt, ob diese Profil ein Fake-Profil ist, oder nicht.

## Aufgaben

* Lade die Daten in `pandas`.
* Führe eine deskriptive Datenanalyse mit geeigneten, statisches Maßen durch.
* Führe eine deskriptive Datenanalyse mit Hilfe von geeigneten Visualisierungen durch.