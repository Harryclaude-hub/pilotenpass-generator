# Ausweis-Atlas

Nachschlagewerk: Land wählen und Reisepässe und Personalausweise mit Vorderseite, Rückseite, Datenseite und Eckdaten ansehen. Beschriftung in der Sprache des Landes (38 Sprachen, Arabisch, Persisch, Urdu und Hebräisch von rechts nach links). 213 Länder und Gebiete, mit Suche, Regionenfilter und Flaggen. Seitenränder: Merkliste mit Notizen (Kopieren, Drucken) und "Zuletzt angesehen".

**Als App installieren:** Auf dem Handy und in Chrome erscheint "Als App installieren". iPhone: Teilen, dann "Zum Home-Bildschirm". Die App startet auch offline, die Dokumentbilder und Flaggen brauchen aber Internet.

Reference viewer: pick a country, see its passports and national ID cards (front, back, data page, key facts). Labels follow the country's language.

**Website:** https://harryclaude-hub.github.io/pilotenpass-generator/ (4-stelliger Zugangscode)

## Woher die Daten kommen

Alle Bilder und Angaben stammen aus **PRADO**, dem öffentlichen Dokumentenregister des Rates der EU (https://www.consilium.europa.eu/prado/). Die Bilder werden direkt von dort geladen, nicht hier gespeichert. Pro Dokument gibt es einen Quelllink.

`data.json` enthält nur Kennung, Titel, Ausgabedatum, Format, Seitenzahl, Höchstgültigkeit und die Dateinamen der drei Bilder. Die Sicherheitsmerkmale und Detailseiten bleiben bei PRADO.

Für Länder ohne PRADO-Eintrag gibt es nur Links zu Wikipedia und Wikimedia Commons.

## Hinweise

- Länder ohne eigene Beschriftungssprache (zum Beispiel Paschtu, Türkisch-Zypern) zeigen Englisch. Die Dokumente selbst sind immer die Originale.
- Merkliste und Notizen liegen nur im Browser (localStorage) und sind nicht geräteübergreifend.

- Nur zur Anschauung. Keine Vorlagen zum Nachbauen, nichts davon ist ein Dokument.
- Der Zugangscode ist eine einfache Sperre im Browser, kein echter Schutz: Die Seite und `data.json` sind öffentlich abrufbar. Der Code ist nur als Prüfwert (SHA-256) im Quelltext, aber vier Ziffern lassen sich leicht durchprobieren.
- Die Nutzungsbedingungen für PRADO-Inhalte stehen auf der PRADO-Seite.
- Frühere Version (Pilotenpass-Generator) liegt in der Git-Historie, Commit `0112126` und älter.
