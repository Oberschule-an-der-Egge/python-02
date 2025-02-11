# Projekt 2: Das Abi-Orakel

So soll das fertige Programm aussehen:

![image](02-screenshot.png)

Versucht, das abgebildete Programm selbst zu bauen. Der **weiße** Text ist die Ausgabe des Programms. Der **grüne** Text wird vom Benutzer eingegeben.

Schreibe dein Programm in die Datei `program.py`



## Das könnte dir helfen:

**Strings mit Variablen ausgeben**

`print(f"Deine Zahl war {zahl}."`

**If-Abfragen (Bedingte Anweisungen)**

    if TEST:
        Anweisung ausführen
    elif TEST:
        Anweisung ausführen
    else:
        Anweisung ausführen
        
**Schleifen**

    while TEST:
        Code im Loop ausführen
        Code im Loop ausführen

**Module importieren**

    import os
    print(os.sys.version)
    
**Zufallszahlen**

Zufallszahlen werden mit der Methode `randint()` im Modul `random` erzeugt. Du musst erst das Modul importieren und dann die Methode mit `random.randint(min,max)` aufrufen.

**Typumwandlung (Type Casting)**

Um zu testen, welcher Datentyp bei einer Variablen vorliegt, kannst du die Funktion `type(VARIABLE)` verwenden.

Um aus einem Textstring `str` eine Ganzzahl `int` zu machen, verwendest du die Funktion `str(GANZZAHL)` oder `int(STRING)` .  


## Quelle

Die Übungsaufgaben basieren auf [cmacht/python-grundlagen](https://github.com/cmacht/python-grundlagen) und dem englischen Original von Michael Kennedy auf [TalkPython Training](https://training.talkpython.fm/courses/explore_python_jumpstart/python-language-jumpstart-building-10-apps).


