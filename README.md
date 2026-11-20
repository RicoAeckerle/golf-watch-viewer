# Golf Zähler – Ansicht

Webseite zur Watch-App [Golf Zähler](https://github.com/RicoAeckerle/golf-watch): Sie zeigt geteilte Runden als
Tabelle pro Kind und erzeugt daraus ein Bild (Teilen, z. B. an WhatsApp) oder ein PDF (Drucken → Als PDF speichern).

**Datenschutz:** Hier liegen keine Daten. Die Uhr hängt sie an den Link hinter dem `#` an.
Dieser Teil wird vom Browser nie an einen Server übertragen, die Tabelle entsteht nur auf dem Handy.

Bereitgestellt über GitHub Pages (Branch `main`, Ordner `/`): https://ricoaeckerle.github.io/golf-watch-viewer/

Gestaltung im Stil des Golfclub Isernhagen (nur interne Nutzung): Farben, Wappen und Schriftzug von
golfclub-isernhagen.de (`assets/`), Schriften Inter und Playfair Display lokal in `fonts/` (SIL Open Font License),
also ohne Google-Fonts-Abruf.

`html2canvas.min.js` (v1.4.1, MIT-Lizenz, siehe `html2canvas-LICENSE`) liegt lokal bei, damit die Seite ohne
fremdes CDN funktioniert.
