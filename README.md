# 🛡️ Mr Asish AI - Antivirus & EDR Platform

A modern, futuristic **AI-powered Antivirus and Endpoint Detection & Response (EDR)** desktop application prototype. Built with React, TypeScript, and Tailwind CSS featuring a premium cybersecurity SaaS design similar to CrowdStrike, Microsoft Defender, and SentinelOne.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-19.x-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.x-06B6D4?logo=tailwindcss)
![Vite](https://img.shields.io/badge/Vite-7.x-646CFF?logo=vite)

---

## ✨ Features

### 🎨 Design
- **Dark Cybersecurity Theme** — Professional dark mode UI
- **Glassmorphism Cards** — Modern frosted glass effects with backdrop blur
- **Neon Accents** — Cyan, green, red, and purple glow effects
- **Smooth Animations** — Transitions, counters, progress rings, and pulse effects
- **Responsive Layout** — Desktop-first design optimized for large screens

### 🔒 Security Modules

| Module | Description |
|--------|-------------|
| **Dashboard** | Real-time protection status, quick actions, threat overview, global attack map |
| **Smart Scan** | Quick, Full, Custom, and USB scanning with live terminal logs |
| **Live Protection** | Real-time file monitoring with automatic threat detection |
| **Threat Intelligence** | Global threat map with attack origins and threat feed |
| **AI Analysis** | Deep file analysis with risk scoring, behavior timeline, and API analysis |
| **Process Monitor** | Monitor running processes with CPU, RAM, and risk indicators |
| **Network Monitor** | Bandwidth usage, firewall activity, and connection tracking |
| **Quarantine Center** | Manage isolated threats with restore/delete options |
| **Scan History** | Historical scan records and statistics |
| **Reports** | Charts and analytics with PDF/CSV export |
| **AI Assistant** | Chat interface for security questions and guidance |
| **Settings** | Configure protection, schedules, and preferences |

---

## 🚀 Quick Start

### Prerequisites
- **Node.js** v18.0 or higher
- **npm** v9.0 or higher

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/mr-asish-ai.git

# Navigate to project directory
cd mr-asish-ai

# Install dependencies
npm install

# Start development server
npm run dev
```

### Open in Browser
```
http://localhost:5173
```

---

## 📦 Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |

---

## 🛠️ Tech Stack

- **Frontend Framework:** React 19
- **Language:** TypeScript 5
- **Styling:** Tailwind CSS 4
- **Build Tool:** Vite 7
- **Charts:** Recharts
- **Icons:** Lucide React
- **Animations:** Framer Motion (available)

---

## 📁 Project Structure

```
mr-asish-ai/
├── public/                  # Static assets
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── Sidebar.tsx      # Navigation sidebar
│   │   ├── TopBar.tsx       # Top navigation bar
│   │   ├── GlassCard.tsx    # Glassmorphism card component
│   │   └── AnimatedCounter.tsx
│   │
│   ├── pages/               # Application pages
│   │   ├── Dashboard.tsx    # Main dashboard
│   │   ├── SmartScan.tsx    # Scanning interface
│   │   ├── LiveProtection.tsx
│   │   ├── ThreatIntel.tsx  # Threat intelligence
│   │   ├── AIAnalysis.tsx   # AI threat analysis
│   │   ├── ProcessMonitor.tsx
│   │   ├── NetworkMonitor.tsx
│   │   ├── Quarantine.tsx
│   │   ├── ScanHistoryPage.tsx
│   │   ├── Reports.tsx      # Analytics & reports
│   │   ├── AIAssistant.tsx  # Chat interface
│   │   └── Settings.tsx
│   │
│   ├── data/
│   │   └── mockData.ts      # Sample data for demo
│   │
│   ├── utils/
│   │   └── cn.ts            # Utility functions
│   │
│   ├── App.tsx              # Main app component
│   ├── main.tsx             # Entry point
│   └── index.css            # Global styles & animations
│
├── index.html
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts
```

---

## 🎯 Key Components

### Dashboard Stats Cards
```tsx
// 6 animated stat cards with sparkline charts
- Files Scanned Today
- Threats Blocked  
- Processes Monitored
- Suspicious Files
- Live Connections
- Quarantined Files
```

### Protection Status Ring
```tsx
// Animated circular progress showing protection level
- 98% Protection Score
- Animated SVG ring
- Glow effects
```

### Global Threat Map
```tsx
// Interactive world map showing:
- Attack origins (Russia, China, N. Korea, Iran, India)
- Animated attack lines
- Risk level indicators
- Country labels
```

### AI Chat Assistant
```tsx
// Pre-built responses for:
- "Why is this file dangerous?"
- "Explain this malware"
- "How do I secure my PC?"
- "Show latest threats"
```

---

## 🎨 Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Cyber Dark | `#0a0e1a` | Card backgrounds |
| Cyber Darker | `#060a14` | Main background |
| Neon Blue | `#00c8ff` | Primary accent |
| Neon Cyan | `#00f5d4` | Secondary accent |
| Neon Green | `#39ff14` | Safe/Success states |
| Neon Red | `#ff3860` | Threats/Danger |
| Neon Yellow | `#ffd700` | Warnings |
| Neon Purple | `#bf5af2` | Special elements |

---

## ⚙️ Customization

### Adding New Pages

1. Create a new component in `src/pages/`
2. Add navigation item in `src/components/Sidebar.tsx`
3. Add route case in `src/App.tsx`

### Modifying Theme Colors

Edit the CSS variables in `src/index.css`:

```css
@theme {
  --color-cyber-dark: #0a0e1a;
  --color-neon-blue: #00c8ff;
  /* ... */
}
```

### Adding Mock Data

Add new data to `src/data/mockData.ts`

---

## 📸 Screenshots

<img width="1912" height="1096" alt="Screenshot 2026-07-07 153554" src="https://github.com/user-attachments/assets/07c407fa-adb0-4758-948a-4487b747c6ed" />
<img width="1917" height="1085" alt="Screenshot 2026-07-07 153622" src="https://github.com/user-attachments/assets/a89f6b98-b01b-4231-a881-ec5202cd765e" />
<img width="1916" height="1087" alt="Screenshot 2026-07-07 153656" src="https://github.com/user-attachments/assets/8da33261-cc02-4b1f-a463-7ccb8c8e9bf5" />
<img width="1916" height="1092" alt="Screenshot 2026-07-07 153715" src="https://github.com/user-attachments/assets/6d9b4778-b40f-4695-b82d-a0edc1a288cc" />
<img width="1916" height="1092" alt="Screenshot 2026-07-07 153715" src="https://github.com/user-attachments/assets/05f452a2-2455-4c9e-b0be-67c9fbde5e27" />

### Dashboard
- Protection status hero card
- Quick scan actions
- Threat statistics with trend indicators
- Global attack map
- Recent threat feed

### AI Analysis
- Risk score ring (0-100)
- File details & hash
- Behavior analysis
- Suspicious API calls
- Attack timeline

### Live Protection
- Real-time event feed
- Auto-scanning indicators
- Threat detection alerts

---

## 🔮 Future Enhancements

- [ ] Real backend integration
- [ ] Actual file scanning capability
- [ ] WebSocket real-time updates
- [ ] User authentication
- [ ] Multi-language support
- [ ] System tray integration (Electron)
- [ ] Custom scan scheduling
- [ ] Threat signature updates
- [ ] Cloud sync functionality

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Design inspired by **CrowdStrike**, **Microsoft Defender**, **SentinelOne**, and **Splunk**
- Icons by [Lucide](https://lucide.dev/)
- Charts by [Recharts](https://recharts.org/)
- Fonts: [Inter](https://fonts.google.com/specimen/Inter) & [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)

---

## 👨‍💻 Author

**Mr Asish AI Team**

---

<p align="center">
  <b>🛡️ Stay Protected. Stay Secure. 🛡️</b>
</p>
