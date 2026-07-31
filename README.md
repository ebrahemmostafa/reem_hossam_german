# Hochzeit von Hossam El-Din & Reem — Deutsche Version

Dies ist die vollständige deutsche Version der digitalen Hochzeitseinladung von **Hossam El-Din & Reem**. Alle arabischen Inhalte wurden entfernt und die englischen Texte wurden vollständig ins Deutsche übersetzt.

## Dateien

```
.
├── index.html        # HTML-Startpunkt (lädt die React-App auf #root mit deutscher Übersetzung)
├── bundle.js         # Produktion-JS-Bundle (React + App-Code, auf Deutsch übersetzt)
├── styles.css        # Produktion-CSS-Bundle
├── assets/           # Statische Assets (Bilder, Musik, Videos)
└── README.md         # Diese Datei
```

## Lokale Ausführung

Da es sich um eine statische Webseite handelt, kann jeder statische Webserver verwendet werden:

```bash
# Mit Python 3 im aktuellen Verzeichnis
python -m http.server 8080
# Öffnen Sie anschließend http://localhost:8080 im Browser
```

Oder mit Node.js:

```bash
npx serve .
```

*Hinweis:* Da das Bundle ES-Module verwendet (`<script type="module">`), muss die Seite über einen HTTP(S)-Server ausgeführt werden. Ein direktes Öffnen der Datei über `file://` wird von den Browser-Sicherheitsrichtlinien blockiert.
