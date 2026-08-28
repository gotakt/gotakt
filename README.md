## Marwan Saleh

Software für kleine Betriebe, die sich darauf verlassen — Hannover.

Ich führe **[gotakt](https://gotakt.de)**. Was ich abliefere, ist meist ein
fertiges System für einen einzelnen Betrieb und keine Bibliothek: eine
Stempeluhr auf dem Tablet neben der Tür, ein Nachweisportal, das eine
Gebäudereinigung ihren Kunden in die Hand gibt, ein Ablauf, der einen Ordner
voller PDFs und eine geteilte Tabelle ersetzt.

Diese Art Arbeit hat eine Eigenheit. Wenn sie ausfällt, sind die Stunden von
jemandem falsch, oder eine Rechnung geht diese Woche nicht raus. Keine Störung,
sondern ein Mensch mit einem Problem. Das ändert, was „fertig" bedeutet.

### Wie ich arbeite

**Ein kleiner Stapel, wenige Abhängigkeiten.** Jede Abhängigkeit ist etwas, das
ich an dem Tag verstehen muss, an dem sie ausfällt — meistens, während jemand
wartet.

**Klare Sprache in der Oberfläche.** Eine Fehlermeldung sagt, was wirklich
passiert ist und was jetzt zu tun ist. „Failed to fetch" ist ein Satz für mich,
nicht für die Person am Empfang.

**Tests dort, wo Geld hängt.** Keine Abdeckungsquote, sondern Tests um die
Stellen, die jemanden echtes Geld kosten würden, wenn sie still falsch wären.
Ein Test, der nichts beweist, ist schlimmer als kein Test — er sieht aus wie
ein Beweis.

**Gemessen, nicht angenommen.** Bevor eine Dokumentation behauptet, ein System
tue etwas, prüfe ich es gegen das laufende System. Die Fehler, die sich zu
finden lohnen, liegen meistens zwischen dem, was Software tut, und dem, was
ihre Dokumentation darüber sagt.

### Ausgewählte Arbeiten

**[TÜV Prüfstelle Pro](https://github.com/gotakt/tuv-workflow-web)**
Verwaltungssystem für TÜV-Prüfstellen: Terminplanung, Fahrzeuge,
Mängelkatalog, Statistik und druckbare Prüfberichte. React/Vite gegen eine
Express-Schnittstelle und MariaDB.

**[gotakt-claude-dashboard](https://github.com/gotakt/gotakt-claude-dashboard)**
Ein lokales Bedienfeld für parallel laufende Claude-Code-Sitzungen. Es liest
die Mitschriften, die Claude Code ohnehin schreibt, und zeigt, welche Sitzung
auf eine Antwort wartet, welche mitten im Zug stehengeblieben ist und was jede
gekostet hat. Der Zustand kommt aus Claude-Code-Hooks, mit dokumentiertem
Rückfallweg für den Fall, dass sie nicht greifen. Eine Datei, keine
Abhängigkeiten.

**[autobahn-strava](https://github.com/gotakt/autobahn-strava)**
Strava für Autobahnfahrten — nur dass die beste *legale* Fahrt gewertet wird
und nicht die schnellste.

Kundenarbeit liegt in privaten Repositories.

### Womit

| | |
|---|---|
| **Oberfläche** | React · Vite · Next.js · Astro · Tailwind |
| **Server** | Node · Express · Firebase · Supabase / Postgres · MariaDB |
| **Prüfung** | Vitest · Playwright · Regeltests gegen Emulatoren |
| **Außerdem** | Python · Tauri · Capacitor |

### Kontakt

[kontakt@gotakt.de](mailto:kontakt@gotakt.de) · [gotakt.de](https://gotakt.de)
