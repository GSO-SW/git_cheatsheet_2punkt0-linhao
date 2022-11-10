# gitStarted Zusammenfassung
In diesem Repo soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.
In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.

## TODO (Linhao)
- Begriffe definieren und erklären (z.B. repository, branch etc.)
- git Befehle für die Arbeit mit lokalen Repositories (inkl. Erläuterungen)
- git Befehle für die Arbeit mit entfernten Repositories (inkl. Erläuterungen)

## TODO2 (Quentin & Nico)
- Fachbegriffe OOP erklären (mit Beispielen)
  - abstract (Klassen)
    - Beschreibt einen Grundriss oder einen Überbegriff einer Mutterklasse, unter ihr können Kinderklassen erstellt werden die Thematisch abstammen
      - abstract class Raumarten
  - abstract (Methoden)
    - Beschreibt Methoden, welche zu einem späterem Zeitpunk bei der Vererbung noch implementiert werden müssen.
      - abstract double PreisberechnungZimmer()
  - virtual
    - Ermöglicht das überschreiben mit `override` in einer erbenden Klasse.
      - virtual void Preisberechnen()
      - override void Preisberechnen()
  - override
    - Eine override-Methode stellt eine neue Implementierung der Methode bereit, die von einer Basisklasse geerbt wurde.
    - Der override-Modifizierer wird benötigt, um die abstrakte oder virtuelle Implementierung einer geerbten Methode, Eigenschaft,   eines Indexers oder Ereignisses zu erweitern oder ändern.
    - Sie können keine nicht virtuelle oder statische Methode überschreiben. Die überschriebene Basismethode muss virtual, abstract oder override sein.
  - Polymorphie
    - Die Polymorphie der objektorientierten Programmierung ist eine Eigenschaft, die immer im Zusammenhang mit Vererbung und Schnittstellen (Interfaces) auftritt. Eine Methode ist polymorph, wenn sie in verschiedenen Klassen die gleiche Signatur hat, jedoch erneut implementiert ist.
    - Polymorphie oder Polymorphismus ist ein Konzept in der objektorientierten Programmierung, das ermöglicht, dass ein Bezeichner abhängig von seiner Verwendung Objekte unterschiedlichen Datentyps annimmt.
- Wie überschreibt man die Methode `virtual string ToString()`?
  - override string ToString() {return "Diese Methode macht nicht wirklich etwas."}
