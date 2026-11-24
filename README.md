# Passwort-Generator 🔑

Ein kleines Python-Programm, das zufällige, sichere Passwörter erzeugt.

> **Hinweis:** Dieses Projekt habe ich mit Unterstützung von KI (Claude Code) erstellt. Ich habe den Code durchgearbeitet, getestet und kann jeden Teil erklären.

## Was das Programm macht
- Länge und Anzahl der Passwörter frei wählbar
- Groß-/Kleinbuchstaben, Ziffern und Sonderzeichen einzeln an- und abschaltbar
- optional ohne verwechselbare Zeichen (l, I, 1, O, o, 0)
- mindestens ein Zeichen aus jeder gewählten Gruppe
- nutzt das Modul `secrets` (kryptografisch sicherer Zufall statt `random`)
- zeigt die geschätzte Stärke in Bit
- läuft komplett lokal, die Passwörter werden nirgends gespeichert

## Starten
```
python passwort_generator.py
```

## Was ich dabei gelernt habe
- Warum man für Passwörter `secrets` statt `random` verwendet: `random` ist vorhersagbar, `secrets` ist kryptografisch sicher.
- Wie man die Stärke eines Passworts in Bit schätzt: Länge × log2(Anzahl möglicher Zeichen).
- Wie man garantiert, dass aus jeder gewählten Zeichengruppe mindestens ein Zeichen vorkommt, und die Zeichen danach mischt, damit sie nicht immer am Anfang stehen.
- Wie man Benutzereingaben prüft, damit das Programm bei falschen Eingaben nicht abstürzt.

## Passt gut dazu
Mit meinem [Passwort-Prüfer](https://github.com/genaudielisa/Passwort-Pr-fer-) kann man testen, wie sicher ein Passwort ist.
