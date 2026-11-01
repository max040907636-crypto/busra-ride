# Büsra Ride – Motorrad-App

Eine Motorrad-App als **eine einzige HTML-Datei** (`index.html`) fürs Handy: Routen planen, Touren im Bergischen Land, Fahrten aufzeichnen, Top-Speed, geplante vs. echte Zeit, Garage und Notfall-Infos.

## Starten
- **Am PC testen:** `index.html` im Browser öffnen und im Tab „Fahren“ auf 🧪 (Demo-Fahrt) tippen.
- **Am Handy mit GPS:** Die Seite muss über **https** laufen (z. B. GitHub Pages). Beim Öffnen als Datei (`file://`) geht kein GPS.

## GitHub Pages einschalten
Repo → **Settings** → **Pages** → Source: „Deploy from a branch“ → Branch `main`, Ordner `/ (root)` → **Save**.
Nach 1–2 Minuten läuft die App unter `https://<benutzername>.github.io/<reponame>/`.

## Datenschutz
Alle Daten (Fahrten, Startorte, Notfall-Infos) bleiben nur lokal im Browser (IndexedDB). Kein Konto, kein Server, kein Tracking.

## Dienste
Karte: © OpenStreetMap-Mitwirkende · Routing: OSRM-Demo-Server (nur leichte Nutzung) · Adresssuche: Nominatim · Wetter: Open-Meteo
