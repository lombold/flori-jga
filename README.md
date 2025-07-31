# Flori Junggesellenabschied Quiz

Ein interaktives Quiz-Spiel für einen Junggesellenabschied.

## 🚀 Live Demo

Das Quiz ist live verfügbar unter: [https://lombold.github.io/flori-jga](https://lombold.github.io/flori-jga)

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

## 🚀 Deployment

Das Quiz wird automatisch auf GitHub Pages deployed:

1. **Automatisches Deployment**: Bei jedem Push zu `main` oder `master` wird das Quiz automatisch deployed
2. **GitHub Actions**: Verwendet GitHub Actions für CI/CD
3. **Static Site**: Wird als statische Website gehostet

### Deployment aktivieren:

1. Gehe zu deinem Repository auf GitHub
2. Klicke auf **Settings** → **Pages**
3. Wähle **Source**: "Deploy from a branch"
4. Wähle **Branch**: `gh-pages` → **Save**

## 📁 Projektstruktur

```
flori-jga/
├── index.html              # Hauptdatei mit Quiz-Logik
├── package.json            # Projekt-Konfiguration
├── README.md              # Diese Datei
├── .github/workflows/     # GitHub Actions
│   └── deploy.yml         # Deployment Workflow
└── assets/                # Bilder und Assets
    ├── splashscreen.png   # Splash Screen
    ├── frage-*.png        # Frage-Illustrationen
    └── frage-*-antwort.*  # Antwort-Illustrationen
```
