# Stufe 4: Meta-Daten und Schema

Ziel: Meta-Daten prüfen und strukturierte Daten erzeugen.
Hinweis: Später übernimmt ein Script diesen Schritt. Bis dahin erzeugst du ihn, und ich prüfe das Ergebnis im Schema-Validator.

## Meta-Daten

1. Prüfe Meta-Title (höchstens 60 Zeichen) und Meta-Description (120 bis 155 Zeichen) aus dem Cockpit. Gib die Zeichenzahl an.
2. Liegen sie außerhalb oder passen nicht mehr zum Text: schlage eine Alternative vor, markiert als Vorschlag. Ändere nie stillschweigend.
3. Meta-Description in Sie-Form, mit Keyword und Handlungsaufforderung.

## Schema (JSON-LD)

Erzeuge ein JSON-LD mit @graph und den Typen aus dem Frontmatter-Feld "schema".

- Article: headline = H1, description = Meta-Description, inLanguage = "de-DE", publisher = BOTfriends GmbH mit Logo-URL [PRÜFEN: Logo-URL], author = BOTfriends GmbH (Person nur, wenn im Cockpit angegeben), mainEntityOfPage = Ziel-URL, datePublished = "[BEIM VERÖFFENTLICHEN SETZEN]".
- FAQPage: jede Frage und Antwort aus dem FAQ-Block, Wort für Wort identisch. Nichts kürzen, nichts ergänzen.
- BreadcrumbList: aus dem Pfad der Ziel-URL, beginnend mit "Startseite" (https://botfriends.de/).
- ItemList (nur Listicles): Einträge in Reihenfolge, mit Name und Anker-URL.

## Ausgabe

1. Meta-Daten mit Zeichenzahl und gegebenenfalls Vorschlag
2. Das JSON-LD in einem Codeblock, ohne Kommentare im JSON
3. Ein Satz zu allem, was vor dem Veröffentlichen noch gesetzt werden muss
