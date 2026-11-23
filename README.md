# Fair-Isle-Musterhilfe

Kleine Web-App (PWA, eine Datei, ohne Server) zum Entwerfen und Anpassen von Fair-Isle-Strickmustern.

## Bedienung in Kürze

- **🗂 Meine Muster** (oben links): Muster öffnen, neu anlegen, Projekte und Motiv-Bibliothek.
- **Name** daneben: direkt umbenennen. **✓ Gespeichert** zeigt: alles wird automatisch im Browser gespeichert.
- **📄 Datei**: als ODS speichern, drucken/PDF, ODS öffnen, Text/Code einfügen, Gesamtsicherung.
- **☰**: wichtige Hinweise, Tastenkürzel, Feedback.
- Seltener gebrauchte Einstellungen stecken in Menüs (Grösse, Werkzeuge, Ansicht, Projekt, „⋯“ je Zeile), Erklärungen hinter „?“ – so bleibt der Bildschirm ruhig.

## Funktionen

- **Rapport**: Breite (links/rechts) und Höhe (oben/unten) an beiden Enden mit + / − ändern (gedrückt halten wiederholt). Bei − bleibt der ausgeblendete Inhalt erhalten und kommt mit + zurück.
  Am PC: Rechtsklick malt mit A, Tasten 1–9 wählen die Farbe, Strg+Z macht rückgängig.
  Malen, Füllen, Pipette, Rückgängig, Spiegeln beim Malen, Spiegeln/Verschieben des ganzen Rapports, Farbe ersetzen.
  Neben jeder Reihe: verwendete Farben und längster Spannfaden (Warnung über einstellbarem Maximum).
- **Farben**: Buchstaben A, B, C … stehen je für eine Farbe. Wahl über Farbverlaufsfläche mit Farbton-Leiste, Hex-Code, Pipette vom Bildschirm (Chrome/Edge) oder aus einem Foto (hochladen, hineinziehen oder mit Strg+V einfügen).
  Vergleich vorher/jetzt und als Maschenbild. **Paletten**: Standardfarben und **Hillesvåg Blåne** (40 Farben als Kacheln mit gezeichnetem Wollmuster, Name und Artikelnummer; belegte Farben mit Buchstabe markiert; Farben aus den Herstellerfotos abgeleitet – Näherungswerte, keine Herstellerfotos in der App); **Ístex Álafoss Lopi** (46 Farben, ebenfalls aus Produktfotos abgeleitet); weitere Garn-Paletten lassen sich in `YARNPAL` ergänzen. „Meine Garne“ speichert gekaufte Garne mit Namen zur Wiederverwendung.
- **Vorschau**: Rapport beliebig oft nebeneinander/übereinander, als Kästchen, als wolliges Maschenbild (Schattierung, Zwirn, Fasern) oder „verfilzt“ (verschwommene Maschen), mit einstellbarer Maschenhöhe (Standard 85 %, Kästchen gleich hoch wie Maschen), mit Rapportgrenzen und einfarbigem Rand oben/unten.
- **Zeichen pro Zelle**: Werkzeug „V Zeichen“ setzt bzw. entfernt ein V in Gegenfarbe – unabhängig von der Farbe der Zelle. Wird bei Spiegeln, Verschieben, Kopieren, Rückgängig, Vorschau (Kästchen; in der Maschen-Ansicht als dünnes V in Schwarz/Weiss), Strick-Modus, Druck und ODS (Zelltext „AV“, gleiche Farbformatierung) mitgeführt.
- **Keine Masche (Abnahme)**: eigenes Werkzeug ∅ (Taste 0) neben den Farben. Solche Kästchen erscheinen in Hintergrundfarbe ohne Rahmen (wahlweise schraffiert); echte weisse Maschen behalten ihren Rahmen. Neben jeder Reihe steht die Maschenzahl, Abnahmereihen sind mit „−n“ markiert; Spannfäden und Kontrast zählen nur echte Maschen. Strick-Modus zeigt die Maschenzahl der Reihe. Beim ODS-Öffnen wird ein Buchstabe, der in der Legende „keine Masche“ heisst, automatisch übernommen.
- **Projekte**: beliebig viele Projekte, jedes reiht mehrere Rapporte und einfarbige Streifen untereinander. Reihenfolge per Ziehen am Griff ⠿ (Maus und Finger) oder mit ↑ ↓. Jeder Rapport lässt sich mit ◀ ▶ seitlich verschieben (Versatz in Maschen), z. B. um Motive verschiedener Bänder aufeinander auszurichten. Rapporte dürfen unterschiedlich breit sein: geht einer in der Projektbreite nicht auf, wird der Rest mit seiner Hintergrundfarbe gefüllt (beidseitig, links oder rechts, Farbe wählbar). Projekte lassen sich duplizieren, löschen und als ODS speichern.
  **Projektfarben:** Alle Rapporte eines Projekts teilen dieselben Farben A, B, C … – eine Änderung (Farbe, Name, hinzufügen, entfernen, tauschen) gilt sofort für das ganze Projekt, Farbstreifen ziehen mit. Neu hinzugefügte Rapporte übernehmen die Projektfarben nach Buchstabe (A → A …); hat ein Muster mehr Farben, kommen die zusätzlichen ins Projekt. Neue Muster, die bei geöffnetem Projekt angelegt werden, kommen automatisch hinein. Unter „Farben“ lassen sich zwei Farben nur im aktuellen Muster tauschen (z. B. B ⇄ C); bei älteren Projekten mit unterschiedlichen Farben bietet die App „Farben angleichen“ an.
- **Layout**: für den PC ausgelegt – links Eingabe und Farben, rechts die Vorschau (live), Trenner dazwischen verschiebbar. Auf dem Handy über Reiter unten bedienbar.
- **Auswahl & Ablage**: Bereich aufziehen, kopieren, ausschneiden, spiegeln, mit A füllen; Ablage spiegeln und beliebig oft einsetzen (Strg+C / X / V, Entf, Esc).
- **Kontrast**: Graustufen-Ansicht (Editor und Vorschau), Helligkeit je Farbe und Warnung bei Farbpaaren mit wenig Helligkeitsunterschied in derselben Reihe.
- **Drucken / PDF**: Bei einem Projekt: Titelseite mit Vorschau, Farben und Reihenfolge, danach **jeder verwendete Rapport möglichst gross auf eigener Seite** (mit Nummern, Spannfäden, Farblegende). Bei einem einzelnen Muster: Diagramm gross, Farben, Vorschau auf eigener Seite. A4 (im Druckdialog „Als PDF speichern“).
- **Motiv-Bibliothek**: Peeries, Bänder (Raute, Welle, OXO) und Motive (Stern, Schneeflocke, Baum, Herz) – als neues Muster oder per „Einsetzen“ in den aktuellen Rapport.
- **🧶 Strick-Modus**: Vollbild nur zum Stricken – grosser Reihenzähler, aktuelle Reihe hervorgehoben, erledigte Reihen abgedunkelt, Riesige Knöpfe „Reihe fertig“ / „Zurück“, Reihe antippen zum Springen, Fortschritt je Muster/Projekt gespeichert, Bildschirm bleibt an (falls der Browser das unterstützt). Aktuelle Reihe grösser. Darüber ein Rapport der aktuellen Reihe vergrössert, mit Maschenzahl je Farbblock; spannt ein Faden über mehr als das eingestellte Maximum, empfiehlt die App, wo er eingefangen werden soll (▲-Markierung). Zoom über − / + oben, Tasten + / − oder Strg + Mausrad. Am PC: Leertaste = weiter, ↓ = zurück, Esc = beenden.
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
