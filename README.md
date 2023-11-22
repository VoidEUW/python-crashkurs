# Python-Crashkurs
Dieser Crashkurs soll Anfängern versuchen Python schmackhaft zu machen. Es ist eine leichte Sprache zum Einsteigen in die Welt der Programmierer.
# Inhaltsverzeichnis
1. [Hinweise zur Benutzung](#1-hinweise-zur-benutzung)
    - [Allgemeine Hinweise](#1-hinweise-zur-benutzung)
    - [Das Importieren](#das-importieren)
    - [Vollständiges Beispiel zum Ausführen](#hier-ein-vollständiges-beispiel)
2. [Grundlagen](#1-grundlagen)
    - [Basics - Hallo Welt](#basics---hallo-welt)
    - [Basics - Variablen](#basics---variablen)
    - [Basics - if-Anweisungen](#basics---if-anweisungen)
    - [Basics - Operatoren](#basics---operatoren)
    - [Basics - (do)while-Schleife](#basics---dowhile-schleife)
    - [Basics - for-Schleife](#basics---for-schleife)
    - [Basics - Listen](#basics---listen)
    - [Basics - Funktionen](#basics---funktionen)
3. [Beispiele](#2-beispiele)
    - [Liste](#liste)
    - [Beispiel - Hallo Welt](#beispiel---hallo-welt)
    - [Beispiel - Variablen](#beispiel---variablen)
    - [Beispiel - if-Anweisungen](#beispiel---if-anweisung)
    - [Beispiel - Operatoren](#beispiel---operatoren)
    - [Beispiel - (do)while-Schleife](#beispiel---dowhile-schleife)
    - [Beispiel - for-Schleife](#beispiel---for-schleife)
    - [Beispiel - Listen](#beispiel---listen)
    - [Beispiel - Funktionen](#beispiel---funktionen)
4. [Aufgaben](#3-aufgaben)
    - [Aufgabe - Hallo Welt](#aufgabe---hallo-welt)
    - [Aufgabe - Variablen](#lösung---variablen)
---

# 1. Hinweise zur Benutzung
Die ```main.py``` Datei ist der Ort, an dem du den ganzen Code ausführen sollst, alle anderen Bereiche musst du nur bearbeiten, wenn das gefordert ist, beispielsweise in dem Aufgabenordner, oder, wenn du in den Beispielen nachschauen möchtest.

Am Ende nach Beendung des Crashkurses kannst du das wie eine Sammlung an Übungen nutzen! Ich hoffe es hilft beim Lernen :)

***Sollten sich irgendwo Fragen finden, ich helfe liebend gerne! Öffnet einfach ein issue und erklärt euer Problem. :)***

## Das Importieren
Wenn du nun die bestimmte Datei ausführen möchtest, musst du sie vorher in die ```main.py``` importieren. Das machst du, indem du den Pfad und die Zielklasse wie folgt einbaust:
```py
from *pfad.datei* import *klasse*
```
Zum Verständnis nehme ich die Beispieldatei ```helloworld.py```:
```py
from beispiele.helloworld import helloworld
```
Damit kannst du nun die Helloworld-Klasse nutzen und in der ```main.py```-Datei ausführen! :)
## Das Ausführen
In der ```main.py``` musst du dann nur die Klasse aufrufen, in der du den Code ausgeführt haben willst.

### Hier ein vollständiges Beispiel:
```py
# Die fertige Importierung nicht vergessen
from beispiele.helloworld import helloworld

helloworld() 
# -> führt Hello World aus dem Beispielordner aus
```

# 2. Grundlagen
## Basics - Hallo Welt
Ziel dieser Übung ist es, sein erstes Programm zu schreiben. Programmierer starten üblicherweise mit einem "Hallo Welt", das hat sich weit verbreitet und ist auch selbst für erfahrene Programmierer immer das erste Programm in einer neuen Sprache.

Für Dieses Programm brauchen wir den sogenannten ```print```-Befehl. Dieser wird wie folgt geschrieben:
```py
print() #in die Klammer wird nun ein Argument geschrieben
```
Der Hashtag ist ein Kommentar in der Python Programmiersprache. Ich habe dahinter eine Bemerkung hinterlassen für mehr Informationen zu dem Code.

**Am Ende sieht das so aus:**
```py
print('Hallo Welt')
```
***Glückwunsch, das ist dein erstes Programm in Python!***

Für ein Beispiel gehe zum [Beispiel](#beispiel---hallo-welt)

## Basics - Variablen
Es gibt verschiedene Variablentypen

## Basics - if-Anweisungen
```if-Anweisungen``` sind wichtig für alle Programmiersprachen, um etwas abfragen zu können. Man wöchte ja wissen, ob gewisse Bedingungen erfüllt sind.

Im Allgemeinen sind ```if-Anweisungen``` wie folgt aufgebaut:
```py
if(Bedingung):
    Anweisung1()
    Anweisung2()
```

Bedingungen können eine alternative Anweisung ausführen, wenn die ```if-Anweisung``` nicht erfüllt wurde. Diese Anweisungen stehen hinter einem sogenannten ```else```:
```py
if(Bedingung):
    Anweisung1()
    Anweisung2()

else:
    Anweisung3()
```

Alternativ gibt es noch die ```elif-Anweisung```, das genutzt wird um eine alternative Anweisung zu geben, die aber nicht für alle Fälle zutrifft:
```py
if(Bedingung):
    Anweisung1()
    Anweisung2()

elif(Bedingung):
    Anweisung3()

else:
    Anweisung4()
```

Für ein Beispiel gehe zum [Beispiel](#beispiel---if-anweisung)

## Basics - Operatoren
## Basics - (do)while-Schleife
## Basics - for-Schleife
## Basics - Listen
## Basics - Funktionen

# 3. Beispiele
## Liste
Alle Dateien in dem Beispielordner
- helloworld.py -> helloworld()
- variables.py -> variables()
- if_condition.py -> if_condition()
- if_and_else.py -> if_and_else_condition()
- operators.py -> operators()
- do_while_loop.py -> do_while_loop()
- for_loop.py -> for_loop()
- lists.py -> lists()
- functions.py -> functions()

## Beispiel - Hallo Welt
Das Beispiel kannst du wie folgt aufrufen:
```py
from beispiele.helloworld import helloworld

helloworld()
```

## Beispiel - Variablen
Das Beispiel kannst du wie folgt aufrufen:
```py
from beispiele.variables import variables

variables()
```

## Beispiel - if-Anweisung
Das Beispiel kannst du dann wie folgt aufrufen:

Hier *ohne* ```Else-Anweisung```
```py
from beispiele.if_condition import if_condition

condition = True # Oder False
if_condition(condition) # <- Hier wird dann die Bedingung übergeben, die die die Zeile darüber definiert hast
```

Hier *mit* ```Else-Anweisung```
```py
from beispiele.if_and_else import if_and_else_condition

condition = True # Oder False
if_and_else_condition(condition) # <- Hier wird dann die Bedingung übergeben, die die die Zeile darüber definiert hast
```

## Beispiel - Operatoren
## Beispiel - (do)while-Schleife
## Beispiel - for-Schleife
## Beispiel - Listen
## Beispiel - Funktionen

# 4. Aufgaben
## Aufgabe - Hallo Welt
Schreibe ein Hallo-Welt Programm in die Aufgabendatei in ```aufgaben/helloworld.py```. Dort schreibst du unter den Kommentar dein Programm
anschließend musst du nur noch in der ```main.py``` den Code ausführen, wie in dem Abschnitt [Ausführen](#das-ausführen) erklärt.

# 5. Lösungen
## Lösung - Hallo Welt
So sollte ```helloworld``` in der Funktion aussehen, damit es sinngemäß funktioniert:

```py
def helloworld():

    print('Hallo Welt')
```
## Lösung - Variablen