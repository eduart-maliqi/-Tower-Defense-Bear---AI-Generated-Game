# 🐻 Tower Defense Bear - AI-Generated Game

Ein Tower Defense Spiel, das fast vollständig durch KI entwickelt wurde. Dieses Projekt ist ein Experiment, um zu sehen, wie weit man mit AI-assisted Development kommen kann.

![Game Status](https://img.shields.io/badge/status-experimental-yellow)
![AI Generated](https://img.shields.io/badge/AI-generated-blue)
![Firebase](https://img.shields.io/badge/Firebase-integrated-orange)

## 📖 Über das Projekt

Ich wollte testen, ob man ein funktionsfähiges Spiel fast nur mit KI erstellen kann - und hier ist das Ergebnis! Von der Architektur über die Implementierung bis zum Gameplay wurde der Großteil von AI-Tools generiert. Ich habe hauptsächlich die Ideen gegeben und die KI hat den Code geschrieben.

**⚠️ Wichtig:** Dies ist ein Lernprojekt und Experiment. Der Code ist nicht perfekt und folgt nicht immer Best Practices. Aber es funktioniert!(so halb) 😄

## 🎮 Features

- **Klassisches Tower Defense Gameplay**
  - 5 verschiedene Türme (Basic, Sniper, Ice, Bomb, Archer)
  - Tower-Upgrades mit verbesserter Reichweite, Schaden und Geschwindigkeit
  - Mehrere Maps mit unterschiedlichen Pfaden und Schwierigkeitsgraden

- **Champion System**
  - Spezielle Helden mit einzigartigen Fähigkeiten
  - Champion-Fähigkeiten mit Cooldowns
  - Freischaltbare Champions durch Gameplay

- **Progression System**
  - Gold und Gems als Währungen
  - Bear Knowledge System (permanente Upgrades)
  - Map-Fortschritt und Statistiken
  - Persistente Speicherung in der Cloud

- **Firebase Integration**
  - User Authentication (Google, Email/Password)
  - Cloud Firestore Datenbank
  - Echtzeit-Synchronisation des Spielfortschritts
  - Admin-System


## 🚀 Schnellstart

### Voraussetzungen

- Einen modernen Webbrowser (Chrome, Firefox, Edge)


### Installation

#### Nur zum spielen 
öffne diese website [https://bears-tower-defense.web.app/](https://bears-tower-defense.web.app/)

 ##### sonst
 
1. Repository klonen:
```bash
git clone https://github.com/eduart-maliqi/-Tower-Defense-Bear---AI-Generated-Game.git
cd -Tower-Defense-Bear---AI-Generated-Game
```

2. Firebase konfigurieren:
   - Erstelle ein Firebase-Projekt auf [firebase.google.com](https://firebase.google.com)
   - Kopiere deine Firebase-Config in `firebase-init.js`
   - Aktiviere Authentication und Firestore

3. Firebase Hosting deployen (optional):
```bash
firebase deploy
```

4. Oder lokal starten:
   - Öffne `index.html` in deinem Browser
   - Oder nutze einen lokalen Server:
```bash
python -m http.server 8000
# Dann öffne http://localhost:8000
```

## 🎯 Wie man spielt

1. **Einloggen:** Registriere dich oder logge dich mit Google ein
2. **Map wählen:** Wähle eine der verfügbaren Maps
3. **Türme platzieren:** Klicke auf ein Feld und wähle einen Turm aus
4. **Upgrades:** Klicke auf einen Turm um ihn zu upgraden
5. **Champions:** Wähle einen Champion aus und nutze seine Fähigkeiten
6. **Überleben:** Verteidige deine Basis gegen die Wellen von Gegnern!

## 📁 Projekt-Struktur

```
tower-defense-bear/
├── index.html                 # Main Menu
├── game.html                  # Game Canvas
├── main-menu.js              # Menu-Logik
├── tower-defense-game.js     # Haupt-Spiel-Engine
├── game-config.js            # Spiel-Konfiguration
├── firebase-init.js          # Firebase Setup
├── auth-system.js            # Authentication
├── firestore-service.js      # Datenbank-Operationen
├── map-system.js             # Maps & Pfade
├── tower-upgrade-system.js   # Tower-Upgrades
├── champion-system.js        # Champion-Logik
├── bear-knowledge-system.js  # Permanente Upgrades
├── progression-system.js     # Fortschritt & Stats
├── sound-system.js           # Audio
├── rendering-system.js       # Canvas Rendering
└── sounds/                   # Audio-Dateien
```

## 🛠️ Technologien

- **Frontend:** Vanilla JavaScript, HTML5 Canvas, CSS3
- **Backend:** Firebase (Authentication, Firestore)
- **Hosting:** Firebase Hosting (optional)
- **Development:** Hauptsächlich KI-generiert 🤖

## 🤖 KI-Entwicklung

Fast der gesamte Code in diesem Projekt wurde von AI-Tools (wie GitHub Copilot, claudeCode, etc.) generiert. Mein Beitrag war:
- Ideen und Konzepte vorgeben
- Features beschreiben
- Code testen und debuggen
- Integration der verschiedenen Systeme

Das Ziel war es zu sehen, wie effektiv man mit KI ein komplettes Spiel entwickeln kann - und ich bin überrascht wie gut es funktioniert hat!

## 🐛 Bekannte Issues

- Performance kann bei vielen Gegnern auf dem Bildschirm abnehmen
- Mobile Support ist noch nicht optimiert
- Einige Edge-Cases im Pathfinding
- Code-Qualität variiert (ist halt KI-generiert 😅)
- die sounds funktionieren nicht richtig
- 
## 🎨 Credits

- **Development:** Hauptsächlich KI + meine Anleitung
- **Sounds:** Von verschiedenen Free-Sound-Websites
- **Konzept & Design:** Meine Ideen

## 📝 Lizenz

Dieses Projekt ist Open Source und frei nutzbar. Da es hauptsächlich von KI generiert wurde, gibt's keine strikten Copyright-Claims. Mach damit was du willst! 🎉

## 🤝 Beitragen

Da dies ein experimentelles KI-Projekt ist, sind Pull Requests willkommen, aber ich kann nicht garantieren, dass ich sie alle reviewe. Feel free to fork und dein eigenes Ding zu machen!

## 📧 Kontakt

Bei Fragen oder Feedback: eduart.maliqi@edu.tbz.ch

---

**⭐ Falls dir das Projekt gefällt, gib dem Repo einen Stern!**

*Made with 🤖 AI assistance and **A LOT** of prompting*
