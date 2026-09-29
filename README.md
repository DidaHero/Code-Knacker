# Code-Knacker Web-Editor

Probiere das Tool hier aus: https://didahero.github.io/codeknacker/

Ein didaktisches Tool zur Erstellung von **Codeknacker-/Mastermind-Spielen** mit frei konfigurierbaren Schwierigkeitsgraden.

Das Tool eignet sich insbesondere für den Unterricht rund um **Kennwortstärke und Schlüsselstärke**. Lernende können spielerisch untersuchen, wie sich die Anzahl möglicher Zeichen bzw. Farben und die Länge eines Codes auf die Schwierigkeit des Knackens auswirken.

## Funktionen

- Beliebig viele Schwierigkeitsstufen anlegen
- Anzahl der Code-Felder pro Stufe festlegen
- Farben pro Stufe frei auswählen und erweitern
- Direkte Spiel-Vorschau im Editor
- Konfiguration als JSON-Datei speichern und wieder laden
- Spielbare HTML-Datei ohne Editor exportieren
- Vollständig lokal im Browser nutzbar
- Keine Installation und kein Server erforderlich

## Didaktischer Einsatz

Der Code-Knacker kann als Einstieg oder Experimentierumgebung für Themen wie

- Kennwortstärke
- Schlüsselstärke
- Brute-Force-Verfahren

eingesetzt werden.

Durch das Verändern der Anzahl von Feldern und verfügbaren Farben können unterschiedliche Schwierigkeitsgrade erzeugt werden. So lässt sich anschaulich thematisieren, warum längere Codes und größere Zeichenvorräte das Knacken eines Codes erschweren.

## So funktioniert das Spiel

Für jede Spielstufe wird zufällig ein geheimer Farbcode erzeugt.

Die Spielerinnen und Spieler stellen einen eigenen Code zusammen und lassen ihren Versuch prüfen. Anschließend wird angezeigt:

- **Richtig** – Farbe und Position stimmen.
- **Falsch platziert** – die Farbe kommt im geheimen Code vor, befindet sich aber an einer anderen Position.

Ziel ist es, den vollständigen Code mit möglichst wenigen Versuchen zu ermitteln.

## Verwendung

1. Die Datei `code-knacker_editor.html` in einem aktuellen Webbrowser öffnen.
2. Im Editor eine vorhandene Stufe bearbeiten oder über **„Stufe hinzufügen“** eine neue Stufe erstellen.
3. Anzahl der Felder und gewünschte Farben festlegen.
4. Das Spiel direkt in der Vorschau testen.
5. Optional die Konfiguration als JSON-Datei speichern.
6. Über **„Spielbare Webanwendung exportieren“** eine eigenständige HTML-Datei erzeugen.

Die exportierte Datei kann anschließend ohne den Editor weitergegeben und direkt im Browser geöffnet werden.

## Technische Hinweise

Der Code-Knacker ist als einzelne HTML-Datei umgesetzt und verwendet HTML, CSS und JavaScript direkt im Browser.

Der Editor unterstützt unter anderem:

- 1 bis 20 Felder pro Stufe
- bis zu 30 Farben pro Stufe
- Speichern und Laden der Konfiguration im JSON-Format
- Export einer eigenständigen Spieler-Version als HTML-Datei

Dadurch eignet sich das Tool auch für Umgebungen, in denen keine zusätzliche Software installiert werden kann.
