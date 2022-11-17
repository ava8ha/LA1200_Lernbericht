# Lern-Bericht
Gruppe Rabbit: Suganthasri, Hassani, Karrer, Bürgi

## Einleitung

In diesem Projekt haben wir ein Programm codiert, mit welchem man Vokabel üben kann, indem man das gefragte Wort übersetzt.

## Was haben wir gelernt?
Wir habe gelernt, wie man mit List arbeitet bzw. wie man es in einem Programm implementiert, und wie es funktioniert.

## Beschreibung

Wir haben ein Programm programmiert, mit dem man Wörter lernen kann. Es funktioniert so, dass es zuerst nach den Wörtern fragt, die man lernen möchte und die dazu gehörende Übersetzung. Diese speichert es dann in einer List. Eine List erstellt man mit folgendem Code:

```c#
static List<string> englishWords = new List<string>();     
static List<string> germanWords = new List<string>();
```

Um die Wörter in die List einzuspeichern, fügt man ein einfach .Add dazu, dass es dann automatisch in den nächsten leeren Speicher speichert. Bis hierhin ging unsere Arbeit auch mit dem restlichen ganz gut. Doch als nächstes kam das Wörterabfragen und hier hatten wir lange Probleme. Wir wussten von array, was eine andere Art von Liste ist, dass man dort ein int in die eckigen Klammern setzen konnte und wenn man diese dann jedes Mal erhöhte, es dann ein anderes eingespeicherte Wort rauskommt. Dies funktionierte auch bei der Korrektur, wo wir dann, falls der User das Wort falsch geschrieben hat, das abgefragte Wort nebendran richtig hinschrieben. Doch bei der for-Schleife ging das nicht. Wir suchten lange nach verschiedenen Lösungen und kamen am Ende auf die Lösung mit .Count. Dies zählt die Anzahl von etwas, hier jetzt die Wörter, und hier haben es dann so gemacht, dass es die Wörter abfragt, solang es die Anzahl abgefragter Wörter kleiner ist als alle Wörter, die eingegeben wurden.

Bei der Korrektur haben wir einfach die Farbe geändert. Da heißt, falls es richtig ist wird es grün angezeigt und wenn es falsch ist wird es rot angezeigt. Am Ende haben wir dann noch einen Score eingebaut, der zeigt wie viele Wörter man richtig geschrieben hat und wie viel Prozent das sind. Wir haben auch noch Schleifen eingebaut, das man direkt die gleichen Wörter nochmal lernen konnte oder auch neue Wörter.

 <img width="500" alt="2c95c38d-a3df-434d-8b30-6ab48ffe3737" src="https://user-images.githubusercontent.com/111045914/202409746-703a2e81-4bb8-47e0-b1e3-f0edcc9afad5.jpg">
 Im Bild ist erkennbar, dass das Programm die eingegebenen Wörter abgespeichert hat mit List, indem es sie als Korrektur zurückgibt.


## Verifikation

Der Codesnippet ist aus unserem Code für das Programm, was heisst, der Code wird so angewendet und funktioniert.
Das Bild soll die Ausgabe mit dem Verwenden von List aufzeigen und visualisieren.   

# Reflexion zum Arbeitsprozess

👍 Wir haben die Arbeit fair und so gleichmässig wie möglich verteilt, weshalb wir sehr effizient arbeiten konnten und schnell vorankamen. 

👎 Wir hatten daraufhin jedoch ein paar Probleme mit dem zusammen setzten der verschiedenen Code-Teile, da alle leicht unterschiedlich vorangingen und Gedankens Prozesse hatten. 
Unsere Variablen, und allgemein der Code war/en nicht glasklar verständlich, was im Nachhinein etwas schwieriger war, als es hätte sein müssen, um mitzuarbeiten 

**VBV**: 
Klare Struktur des Codes abklären, dass alle ein gleiches Gespür beim coden anwenden können. 
Von Anfang an Wert legen auf eine saubere, klare und verständliche Struktur. Um das Überarbeiten zu erleichtern.
