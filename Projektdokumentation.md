# Projekt-Dokumentation


Projekt von Lukas Heiniger

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

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
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

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
