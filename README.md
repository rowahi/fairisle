# Fair-Isle-Musterhilfe

Kleine Web-App (PWA, eine Datei, ohne Server) zum Entwerfen und Anpassen von Fair-Isle-Strickmustern.

## Funktionen

- **Rapport**: Breite und Höhe mit + / − ändern (gedrückt halten wiederholt). Bei − bleibt der ausgeblendete Inhalt erhalten und kommt mit + zurück (Breite: linke Spalte, Höhe: oberste Reihe).
  Malen, Füllen, Pipette, Rückgängig, Spiegeln beim Malen, Spiegeln/Verschieben des ganzen Rapports, Farbe ersetzen.
  Neben jeder Reihe: verwendete Farben und längster Spannfaden (Warnung über einstellbarem Maximum).
- **Farben**: Buchstaben A, B, C … stehen je für eine Farbe. Farbe per Farbwähler, Hex-Code oder Palette jederzeit änderbar, optional Name/Garn. Farben hinzufügen, letzte entfernen, Reihenfolge tauschen.
- **Vorschau**: Rapport beliebig oft nebeneinander/übereinander, als Kästchen oder als Maschenbild, mit Rapportgrenzen.
- **Muster**: mehrere Muster im Browser speichern, Vorlagen, Duplizieren, Löschen.
- **ODS speichern** (LibreOffice Calc): Blatt „Rapport“ mit Reihen-/Maschennummern und Farblegende, Blatt „Vorschau“ mit den eingestellten Wiederholungen. Alle Musterzellen haben bedingte Formatierung: *Zellwert = "A" → Farbe von A* usw.
  Wer die Buchstaben in Calc ändert, sieht sofort die passende Farbe.
- **Bestehendes Muster aufnehmen**: ODS-Datei öffnen (auch in Calc nachbearbeitete), Buchstaben-Raster einfügen (eine Zeile pro Reihe, oberste zuerst) oder einen Muster-Code (`FI1:…`) einfügen.

Lesen: Reihen von unten nach oben, Maschen von rechts nach links.
