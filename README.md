# Lebenslauf

Tabellarischer Lebenslauf für Schülerinnen und Schüler, gemacht fürs iPad.
Eine einzige HTML-Datei ohne Installation und ohne Abhängigkeiten.

**Seite:** https://christofheiss.github.io/lebenslauf/

- Zwei Registerkarten: **Lebenslauf** und **Motivationsschreiben**
- Lebenslauf in schlichten Abschnitten: Personalien mit Foto, Schule, Schnupperlehren, Sprachen in einer Zeile, sortiert von Muttersprache bis Grundkenntnisse, Hobbys, Stärken, Referenzen; am Schluss Ort und Datum. Leere Abschnitte fallen weg
- Motivationsschreiben: Absender, Ort und Datum kommen aus dem Lebenslauf; dazu Empfänger, Betreff, fünf geführte Textabschnitte, Unterschrift und Beilagen
- Jedes Dokument als Word-Datei über «Senden an» (Teilen-Menü, braucht HTTPS), sonst Download
- Jedes Dokument auch als PDF, gleich wie Word über «Senden an» oder als Download. Die Seite zeichnet das A4-Blatt (200 dpi, alle Zeichen) und legt eine unsichtbare Textebene darüber
- Die Angaben bleiben im Browser oder in einer selbst gesicherten `.json`-Datei. Die Seite sperrt jeden Netzverkehr.

Lokal testen:

```bash
python3 -m http.server 8765
```
