# Der Sprint — Nächste Schritte

**Stand:** 15.09.2026 (Angebot im Interview festgelegt, Seite gebaut und live gestellt)
**Führendes Dokument:** ~/sprint/ANGEBOT.md
**Phase:** Angebot steht, Seite live, null Kunden. Es fehlt der erste Pilotkunde.

## Wo wir stehen

Das Angebot ist in einem Fünf-Stufen-Interview entstanden und vollständig in
ANGEBOT.md festgehalten. Kurzform: **Der Sprint**, 1:1, sechs Wochen, ein Ding
live, 3.000 € voll auch im Pilot, maximal drei Kunden gleichzeitig, zehn Stunden
pro Woche Aufwand. Zielgruppe sind Solo-Selbstständige, die seit Monaten etwas
Digitales fertig haben wollen und es allein nicht schaffen. Verkauft wird nicht
"wie man Claude benutzt", sondern die Arbeitsweise (Reihenfolge, Übergaben,
Feierabend, Kill-Kriterien). Garantie: weiter ohne Aufpreis, bis es steht,
solange der Kunde seine Termine hält. Erstfrage an jeden Interessenten:
"Seit wie vielen Monaten willst du das schon fertig haben?" — ab sechs ist Druck.

Felix' Rolle heißt Bauleiter, nicht Coach und nicht Mentor. Der Sprint ist
ausdrücklich Brücke, nicht Ziel: Er finanziert den Ausstieg aus der Ausbildung
und die Zeit für Guard und das Spiel.

Gestrichen im Interview: Kommunen, Kurs, Community, "Druck verkaufen". Den
Filter aus GUARD.md ("stärkt es die Großen?") hat Felix für diesen Fall
aufgehoben, mit dem Hinweis, dass jeder Kunde danach monatlich an Anthropic zahlt.

Gebaut heute: Repo Felix3c/sprint, Seite in site/ im Doorway-Stil, Veröffentlichung
über .github/workflows/pages.yml. **Live seit 15.09. abends unter
https://felix3c.github.io/sprint/** Der erste Lauf war rot, weil der Workflow
GitHub Pages nicht selbst einschalten darf — die Quelle steht jetzt in den
Repo-Einstellungen auf "GitHub Actions". Arbeitsverzeichnis sauber, alles gepusht.

Ehrlicher Stand: null Fremdergebnisse, null Verkäufe, kein warmes Netz. Felix
kennt niemanden persönlich, der in die Zielgruppe fällt. Der erste Kunde kommt
nur über das, was öffentlich sichtbar ist: belegbar.eu, Doorway, Festgehalten.

## Nächster konkreter Schritt

Anschrift ins Impressum eintragen (site/impressum.html, Zeile mit
`[Straße und Hausnummer]` und `[PLZ Ort]`), committen, pushen. Vorher darf der
Link nirgends verbreitet werden: ein gewerbliches Angebot ohne vollständiges
Impressum ist abmahnbar.

## Wartet auf Felix

- Die Anschrift fürs Impressum. Ungeklärt, ob Köln oder die Adresse der Eltern
  gemeint sein soll — Felix hat das im Gespräch nicht gesagt.
- Ob die Kontaktadresse auf der Seite die Gmail bleiben soll.
- Ob der Sprint einen eigenen Tab in REIHENFOLGE.txt bekommt. Steht heute unter
  "NEBENPROJEKT (kein Tab)", weil Felix das nicht entschieden hat.
- Abnahme der Seite: liest sie sich so, wie er gehört werden will?

## Blocker

Keiner für den nächsten Schritt außer der fehlenden Anschrift. Danach folgt
Schritt 2 aus ANGEBOT.md: zehn Solo-Selbstständige auf LinkedIn anschreiben,
erste Nachricht ist nur die Sechs-Monate-Frage, kein Pitch.

## Nicht tun

- Preis nicht unter 3.000 € anbieten, auch nicht "als Pilot"
- Kein Kurs, keine Community, kein Publikumsaufbau, bevor drei Fälle stehen
- Die Behauptung "nur 1 % der Menschheit zahlt für ein KI-Abo" ist unbelegt und
  darf so nicht auf die Seite
