# HarriSimulator

Ein Lernsimulator für einen einfachen **Von-Neumann-Rechner** – gedacht für den Informatikunterricht und für Lehrkräftefortbildungen (z. B. Zertifikatskurs Informatik Sek I).

**Direkt im Browser starten:** https://nb-gsn.github.io/Harrisimulator/

## Was kann der HarriSimulator?

- **Schaubild des Rechners** mit Speicher, Adress- und Datenbus, Rechenwerk und Steuerwerk – die beteiligten Leitungen leuchten bei jedem Schritt auf.
- **Erklärungen in Alltagssprache** zu jedem Mikroschritt und jedem Befehl, getrennt nach Holphase und Ausführungsphase.
- **Geführte Tour** in sechs Kapiteln – vom allerersten Kontakt („Was ist ein Simulator? Was ist die Von-Neumann-Architektur?“) über den Handbetrieb bis zum eigenen Programm.
- **Handbetrieb:** Man spielt selbst das Steuerwerk und löst die Mikroschritte per Klick aus.
- **Programme bequem eingeben:** Zelle für Zelle mit Befehlsauswahl oder als Programmtext (`TAKE 10`, Kommentare, Sprungmarken).
- **Schritt zurück**, Tempo-Regler, Turbo-Modus.
- **Aufgaben mit automatischer Prüfung** (Standard- und Bonsai-Befehlssatz).
- **Befehlssatz & Mikrocode** ansehen, ändern und eigene Befehle erfinden.
- **Bonsai-Modus** mit nur fünf Befehlen (INC, DEC, JMP, TST, HLT).
- **Ansicht für PC, Tablet und Handy** – automatisch passend oder oben rechts umschaltbar. Auf dem Handy wechselt man über die untere Leiste zwischen Speicher, Rechner und Erklärung.

## Kompatibilität

Befehlssatz, Mikrocode und Dateiformate (`.ram`, `.mc`) entsprechen dem Simulator **Johnny** von Peter Dauscher (Web-Version: David Laubersheimer, https://www.inf-schule.de/rechner/johnny). Programme lassen sich zwischen beiden Simulatoren austauschen.

## Technik

Eine einzige Datei (`index.html`), keine Installation nötig. Nur die Schriftarten werden – falls erreichbar – von Google Fonts geladen. Läuft in jedem aktuellen Browser, auch offline mit Ersatzschriften (z. B. lokal gespeichert oder auf einem Schulserver). Der Speicherinhalt wird im Browser gemerkt.
