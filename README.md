# LibertyHUB

**Your Checklist and HUB to all important Links for Throne and Liberty**

[![Website](https://img.shields.io/badge/Website-janni.fun-1f2f38?style=flat-square)](https://janni.fun)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=flat-square&logo=discord&logoColor=white)](https://janni.fun/discord)

🇩🇪 [Deutsch](#deutsch) &nbsp;|&nbsp; 🇬🇧 [English](#english)

---

<a id="deutsch"></a>

## 🇩🇪 Deutsch

### Über das Projekt

LibertyHUB ist eine kostenlose, werbefreie Web-App, die als Checkliste und Link-Sammlung für das MMORPG **Throne and Liberty** dient. Sie hilft dabei, den Überblick über tägliche und wöchentliche Aktivitäten zu behalten und bündelt zudem die wichtigsten offiziellen und Community-Links (Discord, Builds, Tier Lists, Auction House, Server-Status u. v. m.) an einem Ort.

### Features

- ✅ Checkliste für tägliche und wöchentliche Aktivitäten
- 🔄 Automatischer Reset nach Ablauf des jeweiligen Zeitfensters
- 🌍 Auswahl der Zeitzone (Nord-/Südamerika, Europa, Ozeanien, Ost-/Südostasien)
- ⏳ Live-Countdown bis zum nächsten Daily- bzw. Weekly-Reset
- 💾 Speicherung des Fortschritts im `localStorage` des Browsers – kein Account nötig
- 🖱️ Drag & Drop zum freien Anordnen der Elemente
- 🔗 Schnellzugriff auf offizielle und Community-Links (Discord, Reddit, Builds, Tier Lists, Dungeons, Bosse, Codex, Build-Planer, Auction House, Server-Status, interaktive Karte)
- 🆓 Komplett kostenlos und ohne Werbung

### Tech Stack

- HTML5 / CSS3 / JavaScript (Vanilla)
- [Bootstrap 5](https://getbootstrap.com/)
- [Font Awesome 6](https://fontawesome.com/)
- [interact.js](https://interactjs.io/) für Drag & Drop
- Google Fonts (Bitter)

### Lokale Nutzung

Da es sich um eine reine Client-Side-Anwendung handelt, ist kein Build-Prozess oder Server notwendig:

```bash
git clone https://github.com/Ioannis-Toptsis/LibertyHUB.git
cd LibertyHUB
```

Anschließend einfach die `index.html` im Browser öffnen.

### Projektstruktur

```
website_LibertyHUB/
├── index.html              # Haupt-HTML-Datei
└── includes/
    ├── css/liberty.css     # Styling
    ├── js/
    │   ├── liberty.js      # Kernlogik (Checkliste, Countdown, Reset, localStorage)
    │   └── interact.js     # Drag & Drop-Anbindung
    ├── json/                # Task-Definitionen (Dailies, Weeklies, ...)
    └── img/                  # Icons & Grafiken
```

### Credits

Ein Großteil der ursprünglichen Arbeit stammt von [DailyArk](https://github.com/dailyark/). Vielen Dank für die Grundlage, auf der LibertyHUB aufbaut!

### Entwickler & Kontakt

**Ioannis Toptsis (Janni)**

- 🌐 Website: [janni.fun](https://janni.fun)
- 💬 Discord: [janni.fun/discord](https://janni.fun/discord)

---

<a id="english"></a>

## 🇬🇧 English

### About the Project

LibertyHUB is a free, ad-free web app that serves as a checklist and link hub for the MMORPG **Throne and Liberty**. It helps you keep track of your daily and weekly activities while also bundling the most important official and community links (Discord, builds, tier lists, auction house, server status, and more) in one place.

### Features

- ✅ Checklist for daily and weekly activities
- 🔄 Automatic reset once the respective time window expires
- 🌍 Timezone selection (North/South America, Europe, Oceania, East/South-East Asia)
- ⏳ Live countdown to the next daily/weekly reset
- 💾 Progress is saved in your browser's `localStorage` – no account required
- 🖱️ Drag & drop to freely rearrange elements
- 🔗 Quick access to official and community links (Discord, Reddit, builds, tier lists, dungeons, bosses, codex, build planner, auction house, server status, interactive map)
- 🆓 Completely free, no ads

### Tech Stack

- HTML5 / CSS3 / JavaScript (Vanilla)
- [Bootstrap 5](https://getbootstrap.com/)
- [Font Awesome 6](https://fontawesome.com/)
- [interact.js](https://interactjs.io/) for drag & drop
- Google Fonts (Bitter)

### Local Usage

Since this is a purely client-side application, no build step or server is required:

```bash
git clone https://github.com/Ioannis-Toptsis/LibertyHUB.git
cd LibertyHUB
```

Then just open `index.html` in your browser.

### Project Structure

```
website_LibertyHUB/
├── index.html              # Main HTML file
└── includes/
    ├── css/liberty.css     # Styling
    ├── js/
    │   ├── liberty.js      # Core logic (checklist, countdown, reset, localStorage)
    │   └── interact.js     # Drag & drop integration
    ├── json/                # Task definitions (dailies, weeklies, ...)
    └── img/                  # Icons & graphics
```

### Credits

Most of the original work was done by [DailyArk](https://github.com/dailyark/). Big thanks for the foundation LibertyHUB is built on!

### Developer & Contact

**Ioannis Toptsis (Janni)**

- 🌐 Website: [janni.fun](https://janni.fun)
- 💬 Discord: [janni.fun/discord](https://janni.fun/discord)
