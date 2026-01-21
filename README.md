# Übung 9 - Strings, Java-Doc


## 1. Aufgabe

Folgendes Klassendiagramm soll umgesetzt werden:

<p align="center">
  <img src="/assets/images/UML1.png" alt="Bildbeschreibung" />
</p>

**Folgende Bedingungen gelten für die Eigenschaften:**
- `vorname` darf nicht leer sein und keine whitespaces beinhalten.
- `nachname` darf nicht leer sein und keine whitespaces beinhalten.

**Folgende Bedingungen gelten für die Methoden:**
- Im Konstruktor müssen statt der Zuweisung die `set`-Methoden aufgerufen werden.
- Die Parameternamen des Konstruktors müssen gleich den Eigenschaftsnamen sein. 
- `getInitialen()`: Gibt den ersten Buchstaben des Vornamen und Nachnamen zurück.
- `getAccount()`: Gibt die ersten fünf Buchstaben des Nachnamens und die ersten vier Buchstaben des Vornamens zurück. Falls die Namen zu kurz sind, soll alles zurückgegeben werden.
- `gleich()`: Liefert `true`, wenn der Vorname gleich dem Nachnamen ist.

Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Erstellen Sie eine Instanz der `Name`-Klasse mit Werten, welche Sie über einen Scanner einlesen. Testen Sie alle Methoden.

## 2. Aufgabe

Folgendes Klassendiagramm soll umgesetzt werden:

<p align="center">
  <img src="/assets/images/UML2.png" alt="Bildbeschreibung" />
</p>

**Folgende Bedingungen gelten für die Eigenschaften:**
- `vorname` darf nicht leer sein und keine whitespaces beinhalten.
- `nachname` darf nicht leer sein und keine whitespaces beinhalten.
- `accounttyp` darf nur die Werte “Girokonto“ oder “Sparbuch“ annehmen. Jedoch ist es egal, ob die Wörter mit kleinen oder großen Buchstaben geschrieben werden.

Bei falschen Werten soll eine Fehlermeldung ausgegeben werden.

**Folgende Bedingungen gelten für die Methoden:**
- Im Konstruktor müssen statt der Zuweisung die `set`-Methoden aufgerufen werden.
- Die Parameternamen des Konstruktors müssen gleich den Eigenschaftsnamen sein. 
- `print()`: Gibt alle Eigenschaften schön formatiert aus. Es soll jedoch vom Vornamen nur der erste Buchstabe, gefolgt von einem „.“ Ausgegeben werden. 
**Beispiel:** Der Vorname ist „Gustav“, der Nachname „Geldsack“. Dann soll die Ausgabe „G. Geldsack“ sein.
- `einzahlen(int betrag)`: Der Benutzer möchte `betrag` einzahlen. Prüfen Sie auf sinnvolle Werte und geben Sie in jedem Fall eine Meldung aus.
- `auszahlen(int betrag)`: Der Benutzer möchte `betrag` abheben. Prüfen Sie auf sinnvolle Werte und geben Sie in jedem Fall eine Meldung aus.
- `berechneZinsen(double rate)`: Der Benutzer kann Zinsen auf seinem Bankkonto berechnen lassen. `rate` soll dabei größer-gleich 0 sein. Geben Sie in jedem Fall eine Fehlermeldung aus.


Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Erstellen Sie mit dem Scanner eine Instanz der `BankAccount`-Klasse. Lesen Sie die Werte dafür mittels Scanner ein. Simulieren Sie einen realistischen Verlauf eines Benutzers. Mittels Eingabe von `e`, `a`, `z` soll der Benutzer jeweils einzahlen, auszahlen oder Zinsen berechnen können.
**Hinweis:** Sie können dafür ein `switch` oder `else-if` verwenden. Implementieren Sie dafür eine zusätzliche Methode in der `Main`-Klasse, welche Sie in der `main`-Methode öfter hintereinander aufrufen dürfen.

## 3. Aufgabe

Bauen Sie die Klasse `Kaffeemaschine` aus der letzten Übung um. In der `kochen`-Methode sollen nun keine Zahlen mehr vom Benutzer eingelesen werden, sondern gleich die Art des Kaffees. Es soll dabei egal sein, ob der Benutzer mit großen oder kleinen Buchstaben schreibt. Zudem muss die Kaffeemaschine nicht nur eingeschalten sein, wenn sie verwendet werden soll, sondern auch mindestens 200 Wasser beinhalten. Sollten Sie den Zusatz der letzten Übung noch nicht umgesetzt haben, so implementieren Sie diesen auch. Erstellen Sie für die Kaffeemaschinen-Klasse eine Java-Doc.

Der Zusatz war: Setzen Sie auch das Auffüllen von Wasser und Bohnen mit dem Scanner um.


Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Erstellen Sie eine Instanz der Kaffeemaschinenklasse. Erstellen Sie einen Scanner und testen Sie mit verschiedenen Eingaben Ihr Programm.

## 4. Aufgabe

Spielen Sie mit den `String`-Methoden herum. Probieren Sie möglichst viele verschiedene aus. Machen Sie dafür eine zusätzliche Methode `spieleMitStrings()` in der `Main`-Klasse und rufen Sie diese danach in der `main`-Methode auf.
