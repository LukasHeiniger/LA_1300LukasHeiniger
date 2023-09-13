# Projekt-Dokumentation


Projekt von Lukas Heiniger

| Datum  | Zusammenfassung                                              |
| ----- | ------------------------------------------------------------ |
|16.08       |    Anfang mit dem Projekt|
| 23.08  |    Erster Prototyp                                                          |
|11.09       |      Fertigstellung des Spieles.                                                        |

## 1 Informieren

### 1.1 Ihr Projekt

Ich mache ein Zahlenratespiel, bei welchem man eine zufällig generierte Zahl generiert wird.

Ich möchte in diesem Projekt ein spannendes Zahlenrate spiel machen, bei welchem man die Schwierigkeit selbst auswählen kann. Zudem möchte ich viel mit Try anc catch wie auch mit Funktionen arbeiten, damit der Code leserlicher wird und besser funktioniert. 

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | muss                | funktional       |Als ein Spieler möchte ich das ich eine Zahlraten kann, damit ich das Spiel spielen kann. |
| 2  | muss                | Rand     | Als ein Spieler möchte ich das ich Tipps bekomme nach dem Raten, damit ich nicht jede Zahl ausprobieren muss.   |
| 3    |  muss               | funktional     | Als ein Spieler möchte ich das fehlerhafte Eingaben abgefangen werden, damit ich das Spiel von vorne beginnen muss. |
| 4  |        kann         |   Rand   |  Als ein Spieler möchte ich das meine Resultate in einer Datei abgespeichert werden falls ich das möchte, damit ich meine Versuche vergleichen kann.   |
| 5    |          kann       | Rand     |Als ein Spieler möchte ich, dass nur eine Datei erstellt wird wenn keine vorhanden ist, damit der Desktop nicht überfluttet wird. |
| 6  |                kann |   Qualität   |Als ein Spieler möchte ich Sounds, welche den Guess bestätigen, damit man ein besseres Spiel                                    |
| 7   |                 kann|  Rand    | Als Spieler möchte ich die Schwierigkeit nach wiederholtem mal gewinnen ändern, damit das Spiel immer spannend bleibt. |
| 8  |                 kann|  Qualität    |Als ein Spieler möchte ich einen Farbirgen Hintergrund wie auch eine Farbige Schrift, damit das Spiel nicht so langweilig aussieht.                                    |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Zahl wird eingegeben             |  Eingabe einer Zahl       |  Zahl wird mit der Zufallszahl verglichen                 |
| 2.1  | Zahl wurde einmal Falsch geraten              | Falsche Zahl         |  Tipp ob die Zufallszahl < oder > als deine Zufallszahl ist.                 |
| 3.1  | Spieler ratet             |  Falsche Eingabe       |  Eingabe wird wiederholt                 |
| 4.1  | Spieler wird gefragt, ob die Daten gespeichert werden sollen        |  Ja       | Daten werden gespeichert                  |
| 5.1  | Spieler hat Spiel schon mal gespeichert.              |  Spiel speichern       |     Es wird in die vorhandene Datei geschrieben              |
| 6.1  | Spieler spielt Spiel             |  Eingabe wird getätigt       | Sound erklingt.                  |
| 7.1  | Spiel schon mehr mal durchgespielt             | Änderung der Schwierigkeit        |   Schwierigkeit wird geändert                |
| 8.1  | Spiel wird gestartet             | /        |     Spiel erscheint farbig.              |





## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 23.08      | Lukas          | Erstellen des Zufallsgenerator mit eigener Grenze   |20min               |
| 1.B  | 23.08       | Lukas          | Erstellen der Abfrage für das Raten + void funktion            |30min               |
| 2.A  | 30.08      | Lukas          |  Zaheln vergleiche plus attempts einbauen            |45min               |
| 3.A      | 30.08       | Lukas          |   Try and Catch           |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |
| 1.A  |       | Lukas          |              |45min               |


Total: 



## 3 Entscheiden
Ich habe mich während des Projektes dazu entschieden, das ich die rate Zahl nicht auf 100 festlege sonder, das der Benutzer die Schwierigkeit selbst entscheiden kann.
## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 12.09      | funktioniert         | Lukas       |
| 2.1  | 12.09        |funktioniert           | Lukas          |
| 3.1  | 12.09        |funktioniert           | Lukas          |
| 4.1  | 12.09        | funktioniert          |  Lukas         |
| 5.1  | 12.09        | funktioniert noch nicht         |  Lukas         |
| 6.1  | 12.09        |   funktioniert        |  Lukas       |
| 7.1  | 12.09        | funktioniert          |  Lukas         |
| 8.1  | 12.09        |funktioniert           |  Lukas         |


Fazit:
Ich denke das Spiel funktioniert recht gut, die meisten Sachen haben auch super funktioniert, deswegen würde ich sagen hat es super funktioniert.


## 6 Auswerten

Portfolio Link
https://portfolio.bbbaden.ch/view/blocks.php?id=31665
