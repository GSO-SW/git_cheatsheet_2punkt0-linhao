# gitStarted Zusammenfassung
In diesem Repo soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.
In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.

## TODO (Linhao)
- Begriffe definieren und erklären (z.B. repository, branch etc.)
  - branch ist ein "Namensschild" für bestimmte commit.
  - Ein Git-Repository verfolgt und speichert den Verlauf aller Änderungen, die an den Dateien eines Git-Projekts vorgenommen wurden.
- git Befehle für die Arbeit mit lokalen Repositories (inkl. Erläuterungen) 
  - git branch [branch-name]: Ein Branch erstellen.
  - git checkout [branch-name]: Wechseln nach andere branch. 
  - git merge [branch]: führt zwei branch zusammen.
  - git rebase [branch]: versetzt commit auf neue Basis.
  - git init: erstellen ein repository .git.
  - git diff <commit/branch> <commit/branch>: Zeigt Unterschniede zwischen zwei commit oder branch.
  - git log: Historie für den aktuellen branch.
  - git add [Dateinamen]/* "sternzeichen heißt alle Datei": Datei nach staging area bewegen(bereitet commit vor).
  - git branch -d [branch-name]: branch löschen.
  - git show[commit-name "**Wichtig** ist **Commit Name** nicht Nachricht"]: gibt die Inhaltsänderungen des angegebenen Commits aus.
  - git status: Aktiver Status bzw. Anzeige der aktiven branch.
  - git config [name]/[E-mail]/[editor]: Konfigurieren Sie die Benutzerinformationen für alle lokalen Repositories. 
- git Befehle für die Arbeit mit entfernten Repositories (inkl. Erläuterungen)
  - git clone [url]: Kopieren ein repository von Github bzw. Unterladen.
  - git push: alle local branch auf Github hochladen
  - git pull: Ein Kombination von git fetch und git merge
  - git fetch: Lädt alle Historien aus den entfernten Verfolgungszweigen herunter.
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
  - override string ToString() {return "Diese Methode macht nicht wirklich etwas.";}
