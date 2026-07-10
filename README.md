# Vermögensaufbau-Rechner

Ein Sparplan- und Vermögensrechner, der Zinseszins, deutsche Kapitalertragsteuer,
Inflation und eine anschließende Entnahmephase in einem einzigen, offline
lauffähigen HTML-Dokument abbildet — ohne Server, ohne Tracking, ohne externe
Abhängigkeiten.

**Live:** https://btm404.github.io/Vermoegensrechner/

---

## Was der Rechner kann

| Bereich | Funktion |
|---------|----------|
| **Sparphase** | Startkapital, monatliche Sparrate und optionale jährliche Erhöhung der Rate. Laufzeit per Schieberegler (1–45 Jahre). |
| **Drei Szenarien** | Vorsichtig, realistisch, optimistisch – Renditen frei einstellbar, farblich durchgängig bis ins Diagramm. |
| **Rendite & Kosten** | Rendite als Bruttowert; die laufenden Fondskosten (TER) werden abgezogen. |
| **Steuer** | Abgeltungsteuer 26,375 % (inkl. Soli), wählbare Teilfreistellung (Aktien-ETF 30 % / Misch 15 % / Zinsen 0 %) und Sparerpauschbetrag (einmalig oder jährlich). |
| **Inflation** | Reale Kaufkraft des Endkapitals in heutigem Geld. |
| **Diagramm** | Live-Wachstumskurven aller Szenarien plus Einzahlungslinie; antippbar für Zwischenwerte je Jahr. |
| **Entnahmephase** | Nachhaltige Rente nach der 4-%-Regel und Reichweite der gewünschten Entnahme (inflationsangepasst). |

---

## Bedienung

Werte eintragen oder Schieberegler bewegen – alle Ergebnisse aktualisieren sich
live. Anlageart und Sparerpauschbetrag werden über Schalter gewählt. Das
Diagramm zeigt beim Antippen die Werte des jeweiligen Jahres. Sämtliche
Berechnungen laufen ausschließlich im Browser; es werden keine Daten
gespeichert oder übertragen.

---

## Rechenannahmen & Grenzen

**Keine Anlageberatung.** Dies ist eine vereinfachte Modellrechnung, kein
Angebot und keine Finanzberatung. Renditen sind frei gewählte Annahmen, keine
Zusage – reale Kurse schwanken und können auch fallen.

Die Verzinsung erfolgt monatlich aus der effektiven Jahresrendite nach Kosten
(Rendite − TER), die Sparrate nachschüssig. Die Steuer wird beim Verkauf am
Ende angesetzt, nach Teilfreistellung und Sparerpauschbetrag. Der Rechner
unterstellt eine konstante Jahresrendite und blendet damit das Sequenzrisiko
aus (die Reihenfolge realer Renditen kann das Ergebnis deutlich verändern).
Nicht berücksichtigt: Vorabpauschale, Kirchensteuer und Ausgabeaufschläge. Die
tatsächliche Besteuerung kann abweichen.

---

## Technik

- Eine einzige HTML-Datei, reines HTML/CSS/JavaScript, keine Frameworks.
- Diagramm als dynamisch erzeugtes SVG, vollständig offline lauffähig.
- `index.html` ist minifiziert.

---

© 2026 tangomike. Alle Rechte vorbehalten. Siehe [LICENSE](LICENSE).
