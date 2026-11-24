# Passwort-Generator 🔑

Ein kleines Python-Programm, das zufällige, sichere Passwörter erzeugt.

> **Hinweis:** > **Hinweis:** Dieses Projekt habe ich mit Unterstützung von KI (Claude Code) erstellt.


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

## Passt gut dazu
Mit meinem [Passwort-Prüfer](https://github.com/genaudielisa/Passwort-Pr-fer-) kann man testen, wie sicher ein Passwort ist.
