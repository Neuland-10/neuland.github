# Mikroland Planning System

Dies ist die steuernde Arbeitsgrundlage für Mikroland bis zum 31. Dezember 2027. Sie verbindet die soziale Innovation – lokale Lebensmittelkreisläufe, Lernen und Teilhabe – mit den dafür nötigen Produkt-, Betriebs- und Erlösmodellen.

Der FarmBot ist darin ein Werkzeug. Das zu steuernde Produkt ist ein lokal betreibbarer **Supergarten mit Betriebssystem, Menschen, Geschichten und Absatzwegen**.

## Zielbild Ende 2027

- Die LAGA 2027 ist ein täglich sichtbares Reallabor mit funktionierenden Gärten und einer verlässlichen Redaktionsroutine.
- Mindestens drei tragfähige Anwendungsfelder sind als wiederholbare Angebote dokumentiert.
- OGOS ist als Minimum Viable Operating System im echten Betrieb: Projektakte, Pflanz- und Aufgabenplan, Gartenjournal, Ernte- und Wirkungsdaten.
- Wittenberge kann bis zu 100 Geräte endmontieren, prüfen, verpacken und an lokale Hubs übergeben.
- Die neue Gesellschaft hat ein belastbares Angebots-, Service- und erstes Franchise-Modell; Garten-Center sind der skalierbare Vertriebskanal, lokale Hubs der Servicekanal.

## Steuerungsprinzipien

1. **Ein Portfolio, getrennte Wirtschaftlichkeit.** Jede Anwendungslinie besitzt einen eigenen Kosten-, Finanzierungs- und Erfolgsnachweis. Gemeinsame Vorleistungen werden transparent als Plattformkosten ausgewiesen.
2. **Ein verbindlicher Takt.** Wöchentliche operative Planung, monatlicher Portfolio-Entscheid, quartalsweise Investitionsfreigabe.
3. **Kein Rollout ohne Betrieb.** Jeder Standort benötigt vor Aufbau eine namentliche Betreiberrolle, Wasserzugang, Wochenroutine und eine Servicevereinbarung.
4. **LAGA ist Beweis, nicht nur Bühne.** Alles, was dort gezeigt wird, braucht ein Wiederholungsangebot, eine Kostenlogik und eine Anschlussroute.
5. **PR ist Produktion.** Tägliche Geschichten, Fotos, Ernte- und Lernmomente entstehen im Betrieb und werden nicht nachträglich „gemacht“.

## Repository-Landkarte

| Bereich | Zweck |
|---|---|
| `portfolio/` | Anwendungsfelder, Angebote, Wirkung und Verantwortlichkeiten |
| `roadmap/` | Wochen- und Quartalsplan bis Ende 2027 |
| `finance/` | getrennte Budgets, Finanzierungslogik und Freigaben |
| `production/` | Montage bis 100 Geräte, Qualität, Material und Hubs |
| `ogos/` | Produktplanung, Datenmodell und Entwicklungsmeilensteine |
| `comms/` | LAGA-Redaktion, Geschichtenformat und PR-Kalender |
| `operations/` | Entscheidungslog, Risiken, Kennzahlen und Vorlagen |
| `.github/` | Issue- und Pull-Request-Vorlagen sowie Validierung |

## Arbeitsweise in GitHub

- **Ein Epic pro Linie** in GitHub Projects: mit Ziel, Quartalsbudget, verantwortlicher Person und nächstem Entscheidungstor.
- **Ein Issue pro überprüfbarem Ergebnis**, nicht pro Gespräch. Beispiel: „LAGA-Fläche: Wasseranschluss schriftlich bestätigt“.
- Issues erhalten genau eine Status-Spalte: `Backlog`, `Diese Woche`, `Warten auf Dritte`, `Review/Freigabe`, `Erledigt`.
- Jeder Kosten- oder Finanzierungsentscheid wird zusätzlich in `operations/decision-log.md` vermerkt.
- Änderungen an Annahmen erfolgen über Pull Requests. Dadurch bleibt sichtbar, wann und warum eine Planung verändert wurde.

## Die nächsten sechs Wochen

Die konkrete Reihenfolge und die Entscheidungstore stehen in [roadmap/master-roadmap.md](roadmap/master-roadmap.md). Vorrang haben jetzt: Gesellschaft/Verantwortung, LAGA-Standorte und Betriebszusagen, ein berechenbarer Pilotumfang, OGOS-MVP-Spezifikation, Montage-Entscheid bis 100 Geräte sowie der erste Redaktionsbetrieb.

## Startbefehl für das Team

1. Dieses Verzeichnis als neues Repository `mikroland-planning` anlegen.
2. Die Platzhalter `[OWNER]`, `[DATUM]` und `[BETRAG]` gemeinsam ersetzen.
3. Die als `P0` markierten Aufgaben als GitHub-Issues anlegen und dem Projektboard zuordnen.
4. Erst nach der ersten Monatsrunde die Budgetzahlen festschreiben – die Beträge sind Planwerte, keine Angebote oder Förderzusagen.
