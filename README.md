# Fair-Isle-Musterhilfe

Kleine Web-App (PWA, eine Datei, ohne Server) zum Entwerfen und Anpassen von Fair-Isle-Strickmustern.

## Funktionen

- **Rapport**: Breite (links/rechts) und Höhe (oben/unten) an beiden Enden mit + / − ändern (gedrückt halten wiederholt). Bei − bleibt der ausgeblendete Inhalt erhalten und kommt mit + zurück.
  Am PC: Rechtsklick malt mit A, Tasten 1–9 wählen die Farbe, Strg+Z macht rückgängig.
  Malen, Füllen, Pipette, Rückgängig, Spiegeln beim Malen, Spiegeln/Verschieben des ganzen Rapports, Farbe ersetzen.
  Neben jeder Reihe: verwendete Farben und längster Spannfaden (Warnung über einstellbarem Maximum).
- **Farben**: Buchstaben A, B, C … stehen je für eine Farbe. Wahl über Farbverlaufsfläche mit Farbton-Leiste, Hex-Code, Pipette vom Bildschirm (Chrome/Edge) oder aus einem Foto (hochladen, hineinziehen oder mit Strg+V einfügen).
  Vergleich vorher/jetzt und als Maschenbild. „Meine Garne“ speichert gekaufte Garne mit Namen zur Wiederverwendung.
- **Vorschau**: Rapport beliebig oft nebeneinander/übereinander, als Kästchen oder als Maschenbild, mit Rapportgrenzen und einfarbigem Rand oben/unten.
- **Projekte**: beliebig viele Projekte, jedes reiht mehrere Rapporte und einfarbige Streifen untereinander. Reihenfolge per Ziehen am Griff ⠿ (Maus und Finger) oder mit ↑ ↓. Rapporte dürfen unterschiedlich breit sein: geht einer in der Projektbreite nicht auf, wird der Rest mit seiner Hintergrundfarbe gefüllt (beidseitig, links oder rechts, Farbe wählbar). Projekte lassen sich duplizieren, löschen und als ODS speichern.
- **Layout**: für den PC ausgelegt – links Eingabe und Farben, rechts die Vorschau (live), Trenner dazwischen verschiebbar. Auf dem Handy über Reiter unten bedienbar.
- **Auswahl & Ablage**: Bereich aufziehen, kopieren, ausschneiden, spiegeln, mit A füllen; Ablage spiegeln und beliebig oft einsetzen (Strg+C / X / V, Entf, Esc).
- **Kontrast**: Graustufen-Ansicht (Editor und Vorschau), Helligkeit je Farbe und Warnung bei Farbpaaren mit wenig Helligkeitsunterschied in derselben Reihe.
- **Drucken / PDF**: Diagramm mit Reihen- und Maschennummern, Farblegende mit Maschenzahlen und Vorschau auf A4 (im Druckdialog „Als PDF speichern“).
- **Motiv-Bibliothek**: Peeries, Bänder (Raute, Welle, OXO) und Motive (Stern, Schneeflocke, Baum, Herz) – als neues Muster oder per „Einsetzen“ in den aktuellen Rapport.
- **Muster**: mehrere Muster im Browser speichern, Duplizieren, Löschen.
- **Feedback**: Link zum eigenen Feedback-Formular (Tally), wie in der Eindeckhilfe.
- **ODS speichern** (LibreOffice Calc): Blatt „Rapport“ mit Reihen-/Maschennummern und Farblegende, Blatt „Vorschau“ mit den eingestellten Wiederholungen. Alle Musterzellen haben bedingte Formatierung: *Zellwert = "A" → Farbe von A* usw.
  Wer die Buchstaben in Calc ändert, sieht sofort die passende Farbe.
- **Bestehendes Muster aufnehmen**: ODS-Datei öffnen (auch in Calc nachbearbeitete), Buchstaben-Raster einfügen (eine Zeile pro Reihe, oberste zuerst) oder einen Muster-Code (`FI1:…`) einfügen.

Lesen: Reihen von unten nach oben, Maschen von rechts nach links.

## Wichtig: Daten nur lokal

- Alle Muster, Projekte und Garne werden **nur im Browser auf diesem Gerät** gespeichert (localStorage), nicht auf einem Server. Andere Browser oder Geräte sehen sie nicht.
- **Browserdaten / Cache / Website-Daten nicht löschen** und nicht im privaten Fenster arbeiten – sonst sind die Daten weg.
- Regelmässig unter „Muster & Dateien“ eine **Gesamtsicherung** herunterladen (JSON-Datei); sie lässt sich dort auch wiederherstellen.
