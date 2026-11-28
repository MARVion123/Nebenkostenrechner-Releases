# Nebenkostenrechner

Ein kostenloses Programm für Vermieter, die ihre Nebenkostenabrechnung selbst machen. Es kann:

- Gebäude mit Stockwerken, Einheiten und Nebenräumen wie Kellerabteilen anlegen;
- Zähler und Zählerstände erfassen;
- Kosten verteilen: nach Verbrauch, nach Fläche oder zu gleichen Teilen;
- Müll nach Tonnen abrechnen;
- Mieterwechsel und Leerstand tagesgenau berücksichtigen;
- jede Abrechnung auf einem zweiten, unabhängigen Weg nachrechnen;
- vor jedem PDF die Eingaben auf wahrscheinliche Tippfehler prüfen, etwa einen Zählerstand mit verrutschtem Komma.

Am Ende gibt es je Mieter eine Abrechnung als PDF. Dazu kommen eine Gesamtaufstellung als Nachweis, mit jedem
Rechenschritt bis zum Zählerstand und ohne Mieternamen, und Tabellen für Excel. Alle Daten bleiben auf dem eigenen
Rechner.

Mehr dazu, mit Bildern: https://marvion123.github.io/Nebenkostenrechner-Releases/

Kostenlos nutzbar, privat und gewerblich (Freeware, siehe [LIZENZ.md](LIZENZ.md)). Der Quellcode ist nicht öffentlich.

## Herunterladen

Rechts unter **Releases** die neueste Version öffnen und die passende Datei laden:

| Dein Rechner | **Programm** (für echte Abrechnungen, startet leer) | **Demo** (zum Ansehen, mit erfundenen Daten) |
|---|---|---|
| Windows | `…-windows-x64.zip` | `…-windows-x64-demo.zip` |
| Mac (Apple-Chip) | `…-macos-arm64.zip` | `…-macos-arm64-demo.zip` |
| Linux (64 Bit) | `…-linux-x64.tar.gz` | `…-linux-x64-demo.tar.gz` |

- Programm und Demo können nebeneinander installiert sein; sie berühren sich nicht.
- Für den Mac gibt es nur eine Fassung für Apple-Chips (M1 und neuer), für Linux nur eine für 64-Bit-Rechner mit
  Intel- oder AMD-Prozessor (x64).

## Installieren

**Windows:**
1. ZIP an einen festen Ort entpacken und `Nebenkostenrechner.exe` starten. Java muss nicht installiert sein.
2. Beim ersten Start warnt Windows vor einer unbekannten App, weil die Datei nicht signiert ist: „Weitere
   Informationen“ → „Trotzdem ausführen“.

**Mac:**
1. ZIP entpacken und `Nebenkostenrechner.app` starten.
2. Beim ersten Start einmal freigeben: Systemeinstellungen → Datenschutz & Sicherheit → „Dennoch öffnen“.
3. Das Programm bietet dann an, sich in „Programme“ zu legen. Bitte annehmen: Nur von dort kann es sich selbst
   aktualisieren.

**Linux:**
1. tar.gz an einen festen Ort entpacken und im entpackten Ordner `bin/Nebenkostenrechner` starten. Java und root
   sind nicht nötig.
2. Die tägliche Prüfung läuft über einen Timer deines Benutzers; dafür braucht es systemd, wie bei den meisten
   Linux-Systemen.

## Updates

Neue Versionen meldet das Programm beim Start, mit dem, was sie Neues bringen.

- **Mac:** Das Programm installiert sie auf Wunsch selbst und behält die vorherige Version zum Zurückkehren.
- **Windows und Linux:** Das Programm lädt sie herunter. Dann den Programmordner durch den neuen ersetzen.

Die Daten liegen nicht im Programmordner und bleiben dabei, wie sie sind. Die Anleitung steht im Programm unter
„Mehr“ → „Anleitung“.

## Lizenz

Freeware von Nino Breuer, siehe [LIZENZ.md](LIZENZ.md). Kurz:

- Jeder darf das Programm kostenlos nutzen, privat und gewerblich.
- Es gibt es nur hier. Wer es empfehlen möchte, gibt den Link auf diese Seite weiter.
- Nicht erlaubt sind:
  - Weitergeben von Kopien;
  - Verändern;
  - Übernehmen von Teilen;
  - Verkaufen;
  - Veröffentlichen unter anderem Namen;
  - Entfernen des Urhebervermerks.
- Das Programm ersetzt keine rechtliche oder steuerliche Prüfung einer Abrechnung.

## Unterstützen

Wenn dir der Nebenkostenrechner hilft, freue ich mich über einen Kaffee: https://buymeacoffee.com/marvion
Freiwillig und ohne Anspruch auf eine Gegenleistung.
