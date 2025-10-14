# 🚀 netlify-codezero-demo

Eine moderne, interaktive Quiz-Anwendung entwickelt mit Vanilla HTML, CSS und JavaScript. Mehrere Schwierigkeitsstufen, zeitgesteuerte Fragen und detaillierte Ergebnisverfolgung.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 docker-xpra-desktop

- [Funktionen](#funktionen)
- [Demo](#demo)
- [Installation](#installation)
- [Verwendung](#verwendung)
- [Anwendungsstruktur](#anwendungsstruktur)
- [Anpassungen](#anpassungen)
- [Browser-Kompatibilität](#browser-kompatibilität)
- [Mitwirkung](#mitwirkung)
- [Lizenz](#lizenz)

## ✨ js-arch

### 🎯 Kernfunktionalität
- **Mehrere Schwierigkeitsstufen**: Einfach, Mittel oder Schwer wählbar
- **Zeitgesteuerte Fragen**: 45-Sekunden-Countdown-Timer pro Frage
- **Fortschrittsanzeige**: Visueller Fortschrittsbalken und Fragenzähler
- **Punkteberechnung**: Echtzeitbewertung mit Ergebnisübersicht
- **Responsives Design**: Desktop, Tablet und Mobilgeräte

### 🎨 Benutzeroberfläche
- **Modernes Design**: Gradient-Hintergründe und Animationen
- **Intuitive Navigation**: Benutzerfreundliche Oberfläche
- **Visuelles Feedback**: Farbkodierte Antworten (grün/rot)
- **Barrierefreiheit**: Tastaturnavigation und Screenreader-Unterstützung

### 📊 typescript-sample
- **Leistungsmetriken**: Score, richtige/falsche Antworten, Zeit
- **Motivierende Nachrichten**: Feedback basierend auf Leistung
- **Detaillierte Überprüfung**: Frage-für-Frage-Aufschlüsselung

## 🏗 pastit

```
netlify-codezero-demo/
├── index.html
├── style.css
├── script.js
├── data/
│   └── questions.json
├── assets/
│   ├── icons/
│   └── fonts/
├── README.md
└── LICENSE
```

### Hauptkomponenten

#### HTML-Struktur (`index.html`)
- **Startbildschirm**: Schwierigkeitsauswahl
- **Quiz-Bildschirm**: Fragen, Antworten, Timer
- **Ergebnisbildschirm**: Punkteübersicht
- **Überprüfungsbildschirm**: Antwortanalyse

#### Styling (`style.css`)
- **Responsives Design**: Mobile-First mit Breakpoints
- **Moderne UI**: CSS Grid, Flexbox
- **Animationen**: Sanfte Übergänge

#### JavaScript (`script.js`)
- **QuizApp-Klasse**: Haupt-Controller
- **Zustandsverwaltung**: Frage, Punktzahl, Fortschritt
- **Timer**: Countdown mit Warnungen

## 🛠 bruteforce3-8remote

### Schnellstart
1. **Repository klonen**:
   ```bash
   git clone https://github.com/user/netlify-codezero-demo.git
   cd netlify-codezero-demo
   ```
2. **Öffnen**: `index.html` im Browser oder lokaler Server:
   ```bash
   python -m http.server 8000
   npx http-server
   ```

## 📖 geopython-2022

1. `index.html` im Browser laden
2. Schwierigkeit wählen: 🟢 Einfach / 🟡 Mittel / 🔴 Schwer
3. **"Quiz starten"** klicken
4. Antworten auswählen, Timer beachten
5. Ergebnisse und Überprüfung anzeigen

## 📚 jekyll-wikilinks

### Einfache Stufe
- HTML-Grundlagen, CSS-Eigenschaften, Attribute

### Mittlere Stufe
- CSS Box-Modell, JavaScript Arrays, Flexbox, DOM

### Schwere Stufe
- Closures, Event-Bubbling, Promises, PWAs, CSS Grid

## 🎨 cargo-download

### Neue Fragen hinzufügen
```javascript
{
    question: "Ihre Frage?",
    answers: ["Option A", "Option B", "Option C", "Option D"],
    correct: 0
}
```

### Timer ändern
```javascript
this.timeLeft = 45;
```

## 🌐 locarails

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile (iOS Safari, Chrome Mobile)

## 🤝 monstrous

1. Repository forken
2. Branch: `git checkout -b feature/neue-funktion`
3. Änderungen vornehmen und testen
4. Pull Request einreichen

## 📄 Lizenz

MIT — siehe [LICENSE](LICENSE).
