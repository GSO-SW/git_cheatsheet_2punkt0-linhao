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
  - Polymorphie
- Wie überschreibt man die Methode `virtual string ToString()`?
  - override string ToString() {return "Diese Methode macht nicht wirklich etwas."}
