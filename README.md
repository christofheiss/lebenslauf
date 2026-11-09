# Lebenslauf

Tabellarischer Lebenslauf für Schülerinnen und Schüler, gemacht fürs iPad.
Eine einzige HTML-Datei ohne Installation und ohne Abhängigkeiten.

**Seite:** https://christofheiss.github.io/lebenslauf/

- Zwei Registerkarten: **Lebenslauf** und **Motivationsschreiben**
- Lebenslauf: Foto oben rechts, Personalien, schulischer Werdegang, Schnupperlehren, Interessen, Referenzen, Ort, Datum und Unterschrift
- Motivationsschreiben: Absender, Ort, Datum und Unterschrift kommen aus dem Lebenslauf; dazu Empfänger, Betreff, fünf geführte Textabschnitte und Beilagen
- Jedes Dokument als Word-Datei über «Senden an» (Teilen-Menü, braucht HTTPS), sonst Download
- Die Angaben bleiben im Browser oder in einer selbst gesicherten `.json`-Datei. Die Seite sperrt jeden Netzverkehr.

Lokal testen:

```bash
python3 -m http.server 8765
```
