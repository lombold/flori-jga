# Flori Junggesellenabschied Quiz

Ein interaktives Quiz-Spiel für einen Junggesellenabschied.

## Entwicklungsserver starten

### Option 1: Mit npm (empfohlen)
```bash
# Dependencies installieren
npm install

# Entwicklungsserver starten
npm run dev
```

### Option 2: Mit npx (ohne Installation)
```bash
npx http-server . -p 3000 -o -c-1
```

### Option 3: Mit Python (falls verfügbar)
```bash
# Python 3
python3 -m http.server 3000

# Python 2
python -m SimpleHTTPServer 3000
```

## Zugriff

Nach dem Start des Servers ist die Anwendung unter folgender URL erreichbar:
- **Lokaler Zugriff:** http://localhost:3000
- **Netzwerk-Zugriff:** http://[deine-ip]:3000

## Features

- Interaktives Quiz mit 4 Stationen
- Responsive Design
- Automatische Weiterleitung nach korrekter Antwort
- Deutsche Benutzeroberfläche

## Projektstruktur

```
flori-junggesellenabschied-quiz/
├── index.html          # Hauptdatei mit Quiz-Logik
├── package.json        # Projekt-Konfiguration
└── README.md          # Diese Datei
```
