# LaTeX Vorlage für Abschlussarbeiten an der HTWK Leipzig

Dies ist eine **inoffizielle** LaTeX Vorlage für Abschlussarbeiten an der HTWK Leipzig.

Die Vorlage orientiert sich an der "Richtlinie für die Anfertigung von wissenschaftlichen Arbeiten" der Fakultät Ingenieurwissenschaften.

Es besteht kein Anspruch auf Richtigkeit.

## Update 

Die Entwicklung der Vorlage ist soweit beendet. Das Projekt wird bis auf Weiteres eingefroren.

Falls jemand die Vorlage weiterentwickeln möchte hier ein paar abschließende Gedanken:

- Optimierung des Codes in der main.tex -> Können Pakete wie "geometry" mit den KOMA Options ersetzt werden?

- Neue Implementierung der Formel- und Abkürzungsverzeichnisse mit dem "glossaries" Paket

## Auszug der Funktionen

- Automatisierte Erstellung des Deckblatts

- Inhaltsverzeichnis

- Abbildungs- und Tabellenverzeichnis

- Optionale Formel- und Abkürzungsverzeichnisse -> Mit Verlinkung aus dem Text

- Anhang mit Anhangsverzeichnis

- Literaturverzeichnis mit BibTeX

- Deutsche Anführungszeichen können mit " " gesetzt werden

- Kein Zeilenumbruch in den Literaturreferenzen

## Hinweis
  
- Ordner für Abbildungen, PDFs etc. müssen eigenhändig erstellt werden da die Repository keine leeren Ordner enthalten kann !

## Einrichtung

1. Öffnen der main.tex

2. Eingabe der persönlichen Daten in die MeineDaten.tex

3. Gegebenenfalls die Konfigurationsdateien Anpassen

4. Gegebenenfalls Sperrvermerk und Aufgabenstellung einbinden

5. Schreiben der Hauptkapitel

## Lizenz

**Veröffentlicht unter CC BY-SA 4.0 - Lizenz** 

## Quellen

Das Dokument basiert teilweise auf den Vorlagen von :

Markus Voerkel

https://de.overleaf.com/latex/templates/thesis-template-for-hochschule-fur-technik-wirtschaft-und-kultur-leipzig/nqpftcjmmtts

Linda Vogel & Jon Arnt Kårstad

https://www.overleaf.com/latex/templates/template-projekt-htwk/mphqwccfvvwy

Benutzung des aktualisierten "acronym" Paketes von Tobias Oetiker als "acronym_update.sty" um Kompatibilität sicherzustellen

Lizenz des Paketes: "The LaTeX Project Public License 1.3"

https://ctan.org/pkg/acronym
