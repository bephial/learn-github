# learn-github
Ressourcen um GitHub zu verstehen

## Was ist GitHub?
Github ist ein Hostingservice, der eine Software zur Versionsverwaltumg betreibt. Seit 2018 gehört das Unternehmen zu  Microsoft. Der Kern des Systems ist die Möglichkeit **gemeinsam an Programmcode zu arbeiten**, verschiedene Versionen zusammenzuführen oder ein Projekt abzuspalten (Fork). Neben der reinen Verwaltung von Programmcode kann GitHub **jede beliebige Form von Plain-Textdokumenten** verwalten. In der Zwischenzeit gibt es auch die Möglichkeit ein Wiki anzulegen und Projektfortschritte mittels der Kanban-Methode zu strukturieren. 
Letztlich kann GitHub aber auch für Projekte verwendet werden, die nichts mit Programmierung zu tun haben. Dokumente werden hauptsächlich mit der **Auszeichnungssprache Markdown** erstellt. Diese ist leicht zu lernen und sowohl von Maschinen verarbeitbar, als auch von Menschen zu lesen.

## Was ist Git?
Git ist eine Software, die es erlaubt Versionen zu verwalten. Dabei arbeitet das System nicht zentral, sondern verteilt. Das bedeutet, dass jeder Mitarbeiter ein lokale Kopie des Repositorys auf seinem Rechner hat und an einem Duplikat, beispielsweise des Programmcodes, arbeitet (branching)<sup>[1](#foot1)</sup>. Erst wenn sich die Veränderungen als gut und fehlerfrei herausgestellt haben, werden die Veränderungen dann in den "master" zurückgeführt (merging). Der Vorteil ist, dass im Falle eines Fehlers oder eines Datenverlustes mit sehr hoher Wahrscheinlichkeit "Backups" bei den anderen Mitarbeitern existieren, und somit das Projekt nicht verloren ist. Git kümmert sich auch darum, dass parallele Veränderungen mehrerer Mitarbeiter wieder zu einer neuen gemeinsamen Version zusammengeführt werden können.

## Was sind Repositories und Issues?
Repositories sind im Grunde **Ordner oder Verzeichnisse** (man könnte auch "Projekt" sagen, allerdings ist der Begriff irreführend, da es innerhalb von Repositories Projekte gibt). Innerhalb des Repositories können verschiedenen Dokumente angelegt werden und Vorgänge (Issues) ausgelöst werden.
Da GitHub auf die gemeinsame Arbeit fokussiert ist, kann man Issues als Diskussionsbeiträge verstehen (wörtlich "Angelegenheit").

## Watch & Star
GitHub ist auch ein soziales Netzwerk. Mittels des Auges kann man verschiedene Ebenen des Beobachtens einschalten. Je nach eimgestelltem Status bekommt man mehr oder weniger Benachrichtigungen bei bestimmten Vorgängen in einem Repo. Der Stern dient als eine Art "Like" um Gefallen an einem Projekt auszudrücken. Gleichzeitig ist er auch eine Art Lesezeichen, um Repos wiederzufinden, die man nicht beobachten will.

## Was ist ein Fork
Das Wort "Fork" leitet sich vom lateinischen "furca" (Gabel) ab. Der deutsche Begriff wäre "Gabelung", wie in einer **Weggabelung**. Gründe für einen Fork können im Wesentlichen sein, dass man **am Projekt mitarbeiten** möchte oder **das Projekt in eine andere Richtumg** entwickeln möchte, ohne die Veränderung in das Quellprojekt zurückzuführen.
Wenn man am Projekt mitarbeiten möchte, erstellt man einen Fork, also eine 1-zu-1 Kopie des Repos. Dann kann man Veränderungen durchführen und diese dem Originalprojekt zur Übernahme vorschlagen (pull request).

## Branches
Wenn man "Edits" durchführt, also eine Veränderung an einer Datei, kann man immer entscheiden, ob diese Änderung direkt in der Hauptquelle (main) durchgeführt wird oder ein "Branch" angelegt wird. Ein Branch ist eine Veränderung, die zunächst **außerhalb der Quelldatei parallel zu dieser** besteht. Das ist sinnvoll, weil man dadurch gefahrlos Veränderungen einarbeiten und ausprobieren kann, ohne das Hauptdolument zu gefährden. Wenn sich ein Branch als sinnvoll und fehlerfrei erweist, kann man einen "pull request" auslösen und diesen in die Hauptquelle ünernehmen (merge, zusammenführen).

## Weiterlesen
[GitHub-Anleitungen](https://guides.github.com) - Anleitungen zur Nutzung von GitHub

[GitHub-Markdown](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax) - Hilfeseite zur Markdown-Syntax von GitHub

[Git visualisieren[(http://git-school.github.io/visualizing-git/) - Ein Tool um verschiedene Operationen mit Git zu visualisieren und damit besser zu verstehen

<a name="foot1">1</a>: Die Wirklichkeit ist etwas komplizierter. Eigentlich ist ein Branch nur ein Zeiger (Pointer oder Reference) auf einen Commit im Repository.
