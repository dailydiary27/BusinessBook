DAILYDIARY – APP (PWA)

Diese Dateien machen deine bestehende DailyDiary-Website zu einer installierbaren App.
Deine bestehende index.html wird NICHT ersetzt, damit Kalender, Nachrichten,
Zeichnungen und Bilder erhalten bleiben.

1. Lade manifest.json, sw.js und den Ordner icons/ in dasselbe Verzeichnis wie index.html.
2. Füge den Inhalt von pwa-head-snippet.html.txt in den <head> deiner bestehenden index.html ein.
3. Füge den Inhalt von pwa-register.html.txt direkt vor </body> deiner bestehenden index.html ein.
4. Committe/pushe die Dateien nach GitHub Pages.
5. Öffne https://dailydiary27.github.io/ in Safari.
6. Teilen -> Zum Home-Bildschirm.

WICHTIG:
- Die App nutzt weiterhin deine bestehende Supabase-Konfiguration.
- Der Supabase Publishable Key muss nicht in manifest.json oder sw.js.
- Änderungen an deiner index.html können weiterhin übernommen werden; der Service Worker
  verwendet für Seitenaufrufe zuerst das Netzwerk.
- Falls iPhone einmal eine alte Version zeigt: App schließen, Website in Safari neu laden
  und anschließend die installierte App erneut öffnen.
