# Lern-Bericht
Gruppe Rabbit: Suganthasri, Hassani, Karrer, Bürgi

## Einleitung

In diesem Projekt haben wir ein Programm codiert, mit welchem man Vokabel üben kann, indem man das gefragte Wort übersetzt.

## Was habe ich gelernt?
Wir habe gelernt wie man mit List arbeitet bzw. wie man es in einem Programm implementiert, und wie es funktioniert.

## Beschreibung

Wir haben ein Programm geschrieben, mit dem man selbst ausgewählte  Vokabeln lernen kann. Dazu mussten wir die Wörter speichern und das haben wir mit List gemacht. Erstellt, haben wir diese Lists mit dem folgenden Code:

```c#
static List<string> englishWords = new List<string>();     
static List<string> germanWords = new List<string>();
```

Um Wörter in die List hineinzufügen, braucht man nicht wie beim Array die [], sondern einfach nur ein ```.Add```. Es wird dann automatisch in die von 0-n Felder vom Programm hineingefügt, was auch einfacher ist als beim Array.
Dafür war es dann schwieriger beim Wörter abfragen, da man nicht einfach bei der for-Schleife ein int in die [] setzen konnte und diese dann hochzählen. Wir hatten dort lange Probleme und schlussendlich lösten wir es mit ```.Count```. Beim darauf folgenden if else code funktionierten dann aber die Klammern, was dann kein Problem mehr war.


* Ein deutliches, aussagekräftiges Bild oder eine kommentierte Bildschirm-Aufnahme!
 <img width="500" alt="2c95c38d-a3df-434d-8b30-6ab48ffe3737" src="https://user-images.githubusercontent.com/111045914/202409746-703a2e81-4bb8-47e0-b1e3-f0edcc9afad5.jpg">

* Ein gut dokumentierter Code-Fetzen
<img width='316' alt=' >

## Verifikation

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflexion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
