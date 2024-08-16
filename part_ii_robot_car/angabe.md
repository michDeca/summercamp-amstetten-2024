# Micro:bit Smart Robot Car

In dieser Einheit werden wir mit dem mirco:bit ein kleines Roboterauto mittels verschiedener Sensoren steuern. Ziel ist, die verschiedenen Etappen des aufgebauten Hindernisparkours nacheinander zu bewältigen. Jedem Hindernis ist dabei eine Farbe zugeordnet, zum Beispiel hat der erste Parkour die Farbe Blau.

Um dir den Einstieg zu erleichtern, stellen wir dir hier eine kurze Programmvorlage bereit. Diese kannst du für die nachfolgenden Aufgaben einfach erweitern. Du findest sie unter:

https://makecode.microbit.org/S69777-18816-88594-19688

Bitte werfe einen kurzen Blick auf das bisherige Programm, um seine Funktionsweise grob zu verstehen: Die Idee ist, durch wiederholtes Drücken des „A“-Knopfes am Micro:Bit die Steuerung für das jeweilige Hindernis aufzurufen. Bis jetzt wird, für die Aufgabe 1, nur die blaue Farbe unterstützt. Für die nachfolgenden Hindernisse wirst du die Farben dann nach und nach ergänzen. Sobald eine Farbe ausgewählt wurde wird der Micro:bit nach einer kurzen Wartezeit die Funktion zur Steuerung für dieses Hindernis aufrufen. Für das blaue Hindernis heißt die Funktion zur Steuerung hierbei „blauesHindernis“ und wurde bereits für dich angelegt. Wie bei den Farben wirst du nach und nach weitere Funktionen ergänzen um die anschließenden Hindernisse zu lösen.


# Programmierung

## Manuelle Programmierung des Motors

- Erweiterung der Funktion „blauesHindernis“
- fünf Hilfsfunktionen fahreVorwärts, fahreRückwärts, dreheLinks, dreheRechts, stopp. Diese Funktionen werden auch in folgenden Aufgabenstellungen wiederverwendet werden.
- aufbauend auf den Hilfsfunktionen: vier funktionen um „1 Feld“ vor oder zurück zu fahren bzw um 90 Grad nach links oder rechts zu drehen. (hier muss noch eine Feldbreite definiert werden, idealerweise drucken wir diese direkt am Papier zur Orientierung ab)
- Mit diesen Funktionen kann dann schon die Funktion „blauesHindernis“ implementiert werden


## Line Tracking

- Ausgehend vom blauen Abschnitt startet roter Abschnitt bzw Linie fürs Line-Tracking
- Funktionsweise des Sensors kurz beschreiben
- Evtl müssen die Kids hier auch die Potentiometer korrekt einstellen oder wie übernehmen das vorab (?). Hängt evtl auch ein wenig an den Lichtverhältnissen des jeweilgen Tages
- Funktion „rotesHindernis“
- Erklären wie man „Line Tracking“ Wert in eine Variable liest und was die einzelnen Werte bedeuten. Auf welchen Wert muss wie reagiert werden?

## Folge dem Licht




