# Net Zero Management Tool

Ein Werkzeug zur Planung und Bewertung von Net-Zero-Reduktionspfaden — als **einzelne
HTML-Datei**, die vollständig offline im Browser läuft. Keine Installation, kein Server,
keine externen Dienste.

## Was es kann

- **Reduktionspfad je Scope** — Basisemission, BAU-Wachstum und Zielreduktion für
  Scope 1, 2 und 3, daraus der Pfad bis zum Zieljahr
- **Maßnahmen** — Einzelmaßnahmen mit Wirkung und Zeitpunkt, daraus der Deckungsgrad
  gegenüber dem Ziel
- **Neutralisierung und Netto-Emission** — verbleibende Restmenge nach Maßnahmen
- **CO₂-Äquivalenzen** — Umrechnung in anschauliche Vergleichsgrößen auf Basis von
  UBA-Faktoren, mit Quellenangabe je Faktor
- **Scope 4** — vermiedene Emissionen, getrennt von der Bilanz geführt
- **Einheitencheck** — dimensionsgeprüfte Umrechnung (kg / t / kt / Mt)
- **Methodik** — Rechenwege, Glossar und Begründungen im Tool selbst
- **Audit-Trail** — nachvollziehbare Einträge zu Annahmen und Änderungen
- **Export / Import** — JSON, CSV, Bilder und ein Management-Bericht zum Ausdrucken
- Zweisprachig **Deutsch / Englisch**, hell- und dunkelfähig

## Nutzung

Datei öffnen — fertig. Entweder die veröffentlichte Adresse aufrufen oder
`index.html` herunterladen und lokal per Doppelklick starten.

## Datenschutz

Alle Eingaben bleiben **im Browser**. Es gibt keine Server-Verbindung, kein Tracking und
keine externen Schriften oder Bibliotheken. Der Arbeitsstand wird ausschließlich lokal
gespeichert (`localStorage`) und kann über die Export-Funktion als Datei gesichert werden.
Ein Teilen-Link kodiert den Stand in der Adresse selbst — er verlässt das Gerät nur, wenn
Sie ihn aktiv weitergeben.

## Technik

Eine Datei, keine Abhängigkeiten: HTML, CSS und JavaScript sind eingebettet, ebenso alle
Grafiken. Damit ist das Werkzeug archivfähig — es funktioniert auch in Jahren noch, ohne
dass ein Paket nachinstalliert werden muss.

## Stand

Zuletzt geprüft am 27.07.2026 (unabhängiges Review: alle Reiter fehlerfrei, Import- und
Speicherpfade abgesichert, keine externen Ressourcen).

---

Entwickelt von Dr. C. Kaiser.
