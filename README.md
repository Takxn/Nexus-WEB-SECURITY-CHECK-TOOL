# 🔒 Nexus Web Security Check Tool

<div align="center">
  <img src="logo.png" alt="Nexus Logo" width="120" height="120">
  
  ![Version](https://img.shields.io/badge/version-0.1.0-blue.svg)
  ![License](https://img.shields.io/badge/license-MIT-green.svg)
  ![TypeScript](https://img.shields.io/badge/TypeScript-5.7.2-blue.svg)
  ![React](https://img.shields.io/badge/React-18.3.1-61DAFB.svg)
  ![Tauri](https://img.shields.io/badge/Tauri-2.2.0-FFC131.svg)
  
  **Ein modernes, KI-gestütztes Web-Security-Analyse-Tool zur Identifizierung von Sicherheitslücken**
</div>

## 📋 Übersicht

Nexus Web Security Check Tool ist eine fortschrittliche Desktop-Anwendung zur umfassenden Sicherheitsanalyse von Webanwendungen. Entwickelt mit React, TypeScript und Tauri, bietet es eine intuitive Benutzeroberfläche für Penetrationstests und Sicherheitsaudits.

## ✨ Features

### 🔍 Security Scanner
- **Automatisierte Vulnerability-Scans** für Webanwendungen
- **Live-Logging** während des Scan-Vorgangs
- **Multi-Threading** für schnelle Analysen
- Unterstützung für verschiedene Scan-Profile (Quick, Normal, Deep)

### 🤖 KI-Analyse
- **Intelligente Risikobewertung** durch KI-Algorithmen
- **Automatische Priorisierung** von Sicherheitslücken
- **Empfehlungen** für Sicherheitsmaßnahmen
- Pattern Recognition für bekannte Angriffsvektoren

### 📊 Dashboard & Reporting
- **Echtzeit-Dashboard** mit Statistiken und Metriken
- **Interaktive Risiko-Charts** (powered by Recharts)
- **Detaillierte Findings-Tabelle** mit Filteroptionen
- **PDF/HTML Export** von Sicherheitsberichten

### 🎨 Moderne UI/UX
- **Responsive Design** mit Tailwind CSS
- **Smooth Animations** mit Framer Motion
- **Dark/Light Mode** Support
- **Intuitive Navigation** mit Sidebar

## 🚀 Quick Start

### Voraussetzungen

- **Node.js** (v18 oder höher)
- **npm** oder **yarn**
- **Rust** (für Tauri-Backend)
- **Git**

### Installation

1. **Repository klonen**
   ```bash
   git clone https://github.com/yourusername/Nexus_Web_Security_Check_Tool.git
   cd Nexus_Web_Security_Check_Tool
   ```

2. **Dependencies installieren**
   ```bash
   npm install
   ```

3. **Entwicklungsserver starten**
   ```bash
   npm run dev
   ```

4. **Tauri Desktop App starten**
   ```bash
   npm run tauri dev
   ```

### Build für Production

```bash
# Web Version
npm run build

# Desktop App (Windows/Mac/Linux)
npm run tauri build
```

## 🛠️ Technologie-Stack

### Frontend
- **React 18.3** - UI Framework
- **TypeScript 5.7** - Type Safety
- **Tailwind CSS 3.4** - Utility-First CSS
- **Framer Motion 11** - Animations
- **Recharts 2.15** - Data Visualization
- **Lucide React** - Icon Library

### Backend/Desktop
- **Tauri 2.2** - Desktop Framework
- **Rust** - Backend Logic
- **Vite 6.0** - Build Tool

## 📁 Projekt-Struktur

```
Nexus_Web_Security_Check_Tool/
├── src/
│   ├── components/
│   │   ├── AI/              # KI-Analyse Komponenten
│   │   ├── Dashboard/       # Dashboard Views
│   │   ├── Findings/        # Vulnerability Findings
│   │   ├── Layout/          # Layout Komponenten
│   │   ├── Legal/           # Rechtliche Hinweise
│   │   ├── Reports/         # Report Generation
│   │   └── Scanner/         # Scanner Interface
│   ├── App.tsx              # Haupt-App Komponente
│   ├── main.tsx            # Entry Point
│   └── index.css           # Global Styles
├── dist/                    # Build Output
├── src-tauri/              # Tauri Backend (Rust)
├── package.json            # Node Dependencies
├── tailwind.config.js      # Tailwind Konfiguration
├── tsconfig.json           # TypeScript Konfiguration
└── vite.config.ts          # Vite Konfiguration
```

## 🔧 Konfiguration

### Scanner Einstellungen

Die Scanner-Konfiguration kann in der App angepasst werden:

- **Scan-Tiefe**: Quick / Normal / Deep
- **Thread-Count**: 1-10 Threads
- **Timeout**: 5-60 Sekunden
- **Custom Payloads**: Eigene Test-Payloads hinzufügen

### API Integration

Für externe Security-APIs (optional):
```javascript
// Beispiel: API Konfiguration
const API_CONFIG = {
  endpoint: 'https://api.your-security-service.com',
  apiKey: process.env.SECURITY_API_KEY,
  timeout: 30000
}
```

## 📖 Verwendung

### 1. Target URL eingeben
Geben Sie die zu prüfende URL in das Eingabefeld ein.

### 2. Scan-Profil wählen
Wählen Sie zwischen Quick Scan, Normal Scan oder Deep Scan.

### 3. Scan starten
Klicken Sie auf "Start Scan" und beobachten Sie den Live-Log.

### 4. Ergebnisse analysieren
Überprüfen Sie die gefundenen Vulnerabilities im Dashboard.

### 5. Report exportieren
Exportieren Sie einen detaillierten Bericht als PDF oder HTML.

## 🔐 Sicherheitshinweise

⚠️ **WICHTIG**: Dieses Tool ist nur für autorisierte Sicherheitstests gedacht!

- Verwenden Sie das Tool **NUR** auf Systemen, für die Sie eine **explizite Erlaubnis** haben
- Unauthorisierte Penetrationstests sind **illegal**
- Der Entwickler übernimmt **keine Haftung** für Missbrauch
- Beachten Sie lokale Gesetze und Compliance-Anforderungen

## 🤝 Contributing

Beiträge sind willkommen! Bitte beachten Sie:

1. Fork das Repository
2. Erstellen Sie einen Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit Ihre Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffnen Sie einen Pull Request

### Code Style
- Verwenden Sie TypeScript strict mode
- Folgen Sie den ESLint Regeln
- Schreiben Sie aussagekräftige Commit Messages
- Dokumentieren Sie neue Features

## 📝 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert - siehe die [LICENSE](LICENSE) Datei für Details.

## 👥 Team

- **Entwickler** - [Takxn](https://github.com/Takxn)

## 📧 Kontakt

- **Discord**: [Community Server](https://discord.gg/nexus-plus)

## 🙏 Danksagung

- [Tauri](https://tauri.app/) für das großartige Desktop Framework
- [React](https://reactjs.org/) Community
- [OWASP](https://owasp.org/) für Security Best Practices
- Alle Contributors und Tester

---

<div align="center">
  Made with ❤️ and ☕ by the Nexus Team
  
  ⭐ Wenn Ihnen dieses Projekt gefällt, geben Sie ihm einen Stern!
</div>

<img width="2880" height="1824" alt="image" src="https://github.com/user-attachments/assets/82b2522b-3eb3-4945-8c9b-8b587d394262" />

<img width="2880" height="1824" alt="image" src="https://github.com/user-attachments/assets/e37487a7-2660-475f-983f-00436935fc9c" />

<img width="2880" height="1824" alt="image" src="https://github.com/user-attachments/assets/9f54d664-8526-45d5-8034-e8eadb57b67f" />


