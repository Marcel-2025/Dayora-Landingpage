# Dayora — Landingpage und interaktive App-Konzeptvorschau

Ein responsives, statisches Premium-Webkonzept für die geplante App **Dayora** (Tageslicht & Schlafrhythmus).

## Öffnen

- `index.html`: Landingpage mit Tageslicht-Demo (Winter/Frühling/Sommer/Herbst), Themes, Rezeptideen und Roadmap.
- `app-preview.html`: klickbare Desktop-App-Konzeptvorschau mit Dashboard, Jahresverlauf, Schlafanalyse, Fokus-Timer und Rezepten.

Zum lokalen Testen empfiehlt sich ein kleiner Webserver: `python -m http.server 8080` im Projektordner, dann `http://localhost:8080` öffnen. Die HTML-Dateien können auch direkt geöffnet werden.

## Dateien

- `assets/dayora-icon.svg`: randloses 1024x1024-Vektoricon.
- `assets/dayora-icon.png`: 1024x1024-PNG-Version.
- `assets/dayora-icon-art.png`: alternative, aus der generierten Stilkonzeptgrafik ausgeschnittene Icon-Illustration.
- `assets/preview-dashboard.png`: gerenderte Dashboard-Konzeptvorschau.

## Hinweise

**Es handelt sich um eine gestaltete und teilweise interaktive Produktkonzept-/Marketingseite, nicht die Flutter-Windows-App.** Alle Nutzerdaten in der App-Vorschau sind ausdrücklich Beispiele. Die Webseite benötigt keinen externen Backenddienst. Die Schrift wird optional über Google Fonts geladen; ohne Internet werden Systemschriften verwendet. Winter-/Sommerzeiten im Demo-Simulator sind gerundete Monatsmitte-Beispieldaten für Sigmaringen. Veröffentlichung, App-Store-Verfügbarkeit, medizinische Funktionen und Bewertungen werden nicht vorgetäuscht.

## Technische Merkmale

- Responsives HTML/CSS/Vanilla-JS, keine Build-Pipeline.
- Interaktiver Jahreszeiten-/Aufstehzeit-Simulator, Theme-Toggle, App-Menüs, Checkliste, Fokus-Timer.
- Reduced-motion-Einstellung wird berücksichtigt.
- Alle UI-Texte deutsch, keine externen Tracker.
