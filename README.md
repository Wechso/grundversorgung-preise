# Grundversorgung Strom und Gas in Deutschland: Preise 2026 und 2027

Offene Daten von [Wechso](https://wechso.de), einem Vergleichsportal für Strom und Gas.
Wir lesen die Preise der Grundversorgung aus den veröffentlichten Preisblättern der Grundversorger ab. Jede Zeile nennt ihre Quelle.

**DOI:** [10.5281/zenodo.24486140](https://doi.org/10.5281/zenodo.24486140) · **Datenstand:** 23.11.2026 · **Lizenz:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de) · **Online:** [wechso.de/presse](https://wechso.de/presse/)

## Dateien

### `grundversorgung-strom-gas.csv`
Die Grundversorgungspreise für Haushalte in 316 Städten, getrennt nach Strom und Gas. Für 2027 sind Preise enthalten, soweit der Versorger sie angekündigt hat.
- Semikolon getrennt, Dezimalkomma, UTF-8.
- **gilt ab (bisher / neu):** Startdatum laut Preisblatt (JJJJ-MM-TT). Leer, wenn das Preisblatt keins nennt.
- **Arbeitspreis:** Cent je kWh, brutto.
- **Grundpreis:** Euro je Jahr, brutto.
- **Zaehler bisher / neu:** Zählerentgelt, wenn der Versorger es extra berechnet. 0 heißt im Grundpreis enthalten, leer heißt nicht angegeben.
- **Musterhaushalt:** Strom 2.500 kWh, Gas 15.000 kWh im Jahr.
- **Kosten:** Arbeitspreis × Musterhaushalt + Grundpreis + Zähler.
- **Aenderung:** Kosten neu − Kosten bisher.
- **Quelle / Quelle neu:** Preisblatt des Versorgers.
- **Daten geprueft bis:** Bis zu diesem Tag haben wir nach neuen Preisblättern gesucht.

### `stromsteuer-weitergabe.json`
Für jeden Grundversorger: Hat er erklärt, die geplante Senkung der Stromsteuer 2027 an Kunden weiterzugeben, oder rechnet sein Preisblatt die Senkung schon ein? Mit kurzem Zitat, Quelle und Funddatum.
- Die Senkung ist Stand 23.11.2026 geplant, aber noch nicht beschlossen.
- „Keine Angabe gefunden“ heißt nur, dass wir keine Aussage gefunden haben. Es heißt nicht, dass der Versorger die Senkung nicht weitergibt.
- Die Übersicht als Webseite: [wechso.de/stromsteuer-2027](https://wechso.de/stromsteuer-2027/).

## Nutzung
Die Daten stehen unter [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de). Bitte als Quelle nennen: „Wechso, wechso.de/presse, CC BY 4.0“. Zitierfähig: Wechso (2026): Grundversorgung Strom und Gas in Deutschland: Preise 2026 und 2027 in 316 Städten. Zenodo. https://doi.org/10.5281/zenodo.24486140
Maßgeblich bleibt im Zweifel das Preisblatt des Versorgers. Sondertarife sind nicht enthalten.

## Korrekturen
Sehen Sie einen Fehler, schreiben Sie an kontakt@wechso.de oder eröffnen Sie ein Issue. Wir prüfen ihn am Preisblatt und korrigieren ihn.

---

*English:* Open data on regulated default-supply (Grundversorgung) electricity and gas prices for households in 316 German cities, 2026 and 2027. Every row cites the supplier's price sheet. Licence: CC BY 4.0. Please attribute „Wechso, wechso.de“.
