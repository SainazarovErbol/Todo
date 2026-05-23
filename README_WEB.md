# TaskFlow - Web App Version

Eine moderne Web-basierte Todo-Anwendung, die die komplexe Tkinter Desktop-App ersetzt.

## 🚀 Features

- **~400 Zeilen Python** (vs. 1240 Zeilen Tkinter)
- **Responsive HTML/CSS/JavaScript** Frontend
- **JSON-basierte Persistierung** (kompatibel mit Originalapp)
- **Moderne Dark Theme UI**
- **Kategorien, Prioritäten, Fälligkeitsdaten**
- **Unteraufgaben Support**
- **Echtzeit Synchronisierung**

## 📋 Installation

### Windows
```bash
# Python 3.8+ erforderlich
pip install -r requirements_web.txt
```

### Linux/Mac
```bash
pip install -r requirements_web.txt
```

## ▶️ Starten

```bash
python app_web.py
```

Öffne dann im Browser: `http://localhost:5000`

## 📁 Struktur

```
TodoDesktop/
├── app_web.py          # Flask Web-App (alle Funktionen + HTML/CSS/JS)
├── tasks.json          # Datenbank (kompatibel mit Original)
├── requirements_web.txt # Dependencies
└── README.md           # Diese Datei
```

## 🔄 Migration von Tkinter App

Die Web-App nutzt die gleiche `tasks.json` Datei wie die Original-App. 
Alle Daten sind direkt kompatibel - keine Migration nötig!

### Vorher (Tkinter)
- 1240 Zeilen Code
- Nur Desktop
- Komplexe GUI-Rendering Logik

### Nachher (Web)
- ~400 Zeilen Code
- Responsive Design (Desktop/Tablet/Mobile)
- Schneller & moderner
- Leichter zu warten

## 🎨 Technologie

- **Backend**: Flask (Python)
- **Frontend**: HTML5 + CSS3 + Vanilla JavaScript
- **Datenbank**: JSON
- **Styling**: Dark Modern Theme

## 📊 Vergleich

| Feature | Tkinter | Web |
|---------|---------|-----|
| Code-Zeilen | 1240 | ~400 |
| Setup Zeit | 5 min | 1 min |
| UI Rendering | Custom | Browser |
| Performance | Gut | Besser |
| Mobile Support | Nein | Ja |
| Wartbarkeit | Schwer | Leicht |

## 🐛 Bekannte Issues

Keine bekannten Issues - vollständig kompatibel mit Originaldaten!

## 📝 ToDo

- [ ] Offline-Support (Service Worker)
- [ ] Progressive Web App
- [ ] Dunkler/heller Modus Toggle
- [ ] Drag & Drop für Tasks
- [ ] Export/Import Funktionen

## 📝 Lizenz

Open Source - frei verwendbar

---

**Entwickelt mit ❤️ als Verbesserung zur Original-App**