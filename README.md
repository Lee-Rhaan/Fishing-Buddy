
# 🌊 TIDELINE
### Your Coastal Fishing Companion

**Feel the ocean. Know your next catch.**

A mobile-first fishing companion built for recreational anglers exploring the coastline of South Africa's Western Cape.

TIDELINE combines marine forecasts, fish identification, fishing regulations, coastal exploration, bait preparation and practical tackle guidance in one immersive application.

### 🌐 [Launch TIDELINE](https://lee-rhaan.github.io/Fishing-Buddy/)

[![Live Website](https://img.shields.io/badge/Live_Website-Launch_TIDELINE-64d8d0?style=for-the-badge)](https://lee-rhaan.github.io/Fishing-Buddy/)
![Platform](https://img.shields.io/badge/Platform-Mobile_First-087eae?style=for-the-badge)
![Technology](https://img.shields.io/badge/Built_With-HTML_CSS_JS-103d55?style=for-the-badge)
![Hosting](https://img.shields.io/badge/Hosting-GitHub_Pages-222222?style=for-the-badge)

---

## 🌅 Experience the Ocean

TIDELINE goes beyond a traditional fishing or weather application.

The interface is designed around the coastal environment itself, creating an atmospheric experience with:

- 🌊 Animated ocean surfaces and moving water reflections
- ☁️ Cinematic skies and drifting clouds
- ☀️ Weather-inspired forecast animations
- 💨 Animated wind and wave indicators
- 💠 Underwater lighting and ocean-inspired backgrounds
- ✨ Interactive cards, transitions and photograph galleries
- 📱 Mobile-first navigation and responsive layouts

The goal is simple: **make understanding the coast as engaging as exploring it.**

---

## 🧭 Features

### ☀️ 01 — Today | Live Coastal Conditions

**Understand the ocean before you cast.**

The Today dashboard provides marine and weather forecasts for your selected coastal location.

#### Forecast information

- 🌡️ Air temperature
- 🌧️ Rain probability
- 💨 Wind speed and direction
- 🌊 Ocean wave height
- 🌡️ Sea temperature
- 🕒 Next 24-hour forecast
- 🎣 Fishing-condition interpretations

Each forecast card uses animated visual effects inspired by the surrounding weather conditions.

#### 📍 Location Selection

Switch between supported coastal locations to view location-specific forecast data.

Your selected location is remembered in the browser.

> **Note:** Forecasts are numerical model estimates, not direct measurements at the fishing location.

---

### 🐟 02 — Fish | Interactive Species Guide

**Know what you're fishing for.**

Explore fish species associated with the Western Cape coastline through an interactive field guide.

#### Species covered

| Species | Common Name |
|---|---|
| Galjoen | South Africa's national fish |
| Elf | Shad |
| Hottentot | Hottentot seabream |
| Kob | Kob |
| Yellowtail | Yellowtail |
| Garrick | Leervis |
| Baardman | Baardman |
| Strepie | Strepie |
| Zebra | Zebra seabream |
| White Stumpnose | White stumpnose |
| Additional species | See the live guide |

#### Explore Each Species

Six interactive sections help you understand your target fish:

| Section | Information |
|---|---|
| 🕒 **When** | Fishing windows, wind and wave conditions |
| 🦐 **Bait** | Bait selection and preparation |
| 📍 **Habitat** | Preferred environments and visual clues |
| 📏 **Size** | Species size information |
| 🎣 **Rod** | Species-specific tackle and rigging |
| 🍳 **Cook** | Preparation and cooking guidance |

#### 📸 Species Photography

Browse real fish photographs through interactive galleries to help with identification.

#### ⚖️ Fishing Regulations

Each supported species has a dedicated regulation guide covering available information about:

- Minimum legal sizes
- Daily bag limits
- Closed seasons
- Retention restrictions
- Important legal considerations

Seasonal restrictions are highlighted where applicable.

> Regulations can change. Always verify current rules with the Department of Forestry, Fisheries and the Environment (DFFE).

---

### 🏖️ 03 — Spots | Explore the Coastline

**Find your water.**

Explore coastal fishing areas across the southern Western Cape.

#### Available Locations

- 📍 Die Dam
- 📍 Buffeljagsbaai
- 📍 Pearly Beach
- 📍 Franskraal
- 📍 Gansbaai

#### Explore Each Location

- 🗺️ Interactive coastal maps
- 📸 Nearby geotagged photographs where available
- 📍 GPS positioning with permission
- 🌊 Coastal habitat guidance
- 🐟 Species associated with suitable habitats
- ⚠️ Shoreline safety considerations

#### 🔎 Learn What to Look For

Understand the coastal features that can influence fishing opportunities:

- Sandy surf channels and gutters
- Rocky reefs
- Kelp fringes
- Sandbanks
- Baitfish activity
- Breaking-wave patterns

Educational example galleries help anglers recognise these features.

> Habitat guidance identifies possible fishing environments, not verified fish positions or guaranteed catches.

---

### 🎣 04 — Gear | The Angler's Workshop

**Know your setup.**

Learn about fishing styles and equipment suitable for different coastal environments.

Explore:

- Surf fishing
- Rock fishing
- Equipment considerations
- Species-specific tackle guidance
- Bait presentation and rigging
- South African fishing equipment retailers

Detailed species-specific recommendations are available through **Fish → Rod**.

---

### 📖 05 — Log | Your Fishing Journal

**Every catch has a story.**

Create a personal record of your fishing experiences.

#### Record Your Catch

- 🐟 Fish species
- 📸 Catch photograph
- 📏 Length and weight
- 🦐 Bait or lure
- 📍 Fishing location
- 🕒 Date and time
- ♻️ Released or retained
- 📝 Conditions and personal notes

#### 🔒 Local Storage

Your fishing records are stored in your browser.

No account or backend database is required for the local catch log.

You can export your fishing records as a backup.

> Browser storage may be cleared when browser or device data is removed. Export backups regularly.

---

## 🧠 Designed to Help You Learn

TIDELINE aims to explain **why fishing conditions matter**, rather than simply displaying numbers.

For example:

**Instead of:**
> Wind: 30 km/h

**TIDELINE helps explain:**
> Strong wind may affect casting distance, bait presentation and line control.

**Instead of:**
> Preferred habitat: Sandy gutters

**TIDELINE helps explain:**
> Look for deeper channels between breaking waves, where moving water can create feeding opportunities.

This approach makes the application especially useful for anglers learning to read the coastline.

---

## ⚙️ Technology Stack

TIDELINE is built using lightweight web technologies.

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling and cinematic animations |
| JavaScript | Interactivity and application logic |
| Open-Meteo | Weather and marine forecasts |
| iNaturalist | Fish photography |
| Wikimedia Commons | Coastal and educational photography |
| Leaflet | Interactive maps |
| OpenStreetMap | Geographic map data |
| Browser Storage | Catch records and preferences |
| GitHub Pages | Application hosting |

### 📦 Single-File Architecture

The core application is contained in a single `index.html` file.

This includes:

- Application structure
- Styling and animations
- JavaScript functionality
- Interactive navigation
- Application logic

**No backend server, database or build pipeline is required to host the core application.**

External forecasts, maps and photograph services require internet access.

---

## 📱 Mobile-First Experience

TIDELINE was designed with smartphones as the primary platform.

The interface features:

- Touch-friendly navigation
- Responsive layouts
- Swipeable forecast cards
- Full-screen image galleries
- Scrollable information popups
- Animated interactive elements
- Lightweight browser-based deployment

Simply open the website on your mobile device.

No installation is required.

---

## 🚀 Getting Started

### 🌐 Use the Live Application

Open:

**https://lee-rhaan.github.io/Fishing-Buddy/**

### 💻 Run Locally

Clone the repository:

```bash
git clone https://github.com/Lee-Rhaan/Fishing-Buddy.git
```

Open the project directory and launch `index.html` in a modern browser.

No package installation or build process is required.

Some browser features may work best when the application is served through a local web server or GitHub Pages.

---

## 🗺️ Future Development

TIDELINE is an evolving project.

Potential future improvements include:

- [ ] Expand the coastal location database
- [ ] Add more fish species
- [ ] Improve habitat-specific photograph libraries
- [ ] Expand bait preparation tutorials
- [ ] Add personal fishing statistics
- [ ] Introduce catch history visualisations
- [ ] Improve offline functionality
- [ ] Expand location-specific fishing intelligence
- [ ] Add more detailed marine conditions

---

## ⚠️ Disclaimer

TIDELINE is an independent recreational fishing information project.

Weather and marine forecasts are numerical model estimates and must not be treated as guarantees of safe conditions.

Fishing windows, species availability, habitat information and tackle recommendations are educational guidance rather than verified catch predictions.

Always confirm current fishing regulations, marine protected area restrictions, closed seasons, bag limits, minimum sizes and bait collection requirements with the appropriate South African authorities.

Photographs are provided by their respective sources and creators.

---

## 👨‍💻 Developer

**Lee-Rhaan King**

Created as a personal software development project focused on combining practical information, interactive design and modern web technologies.

TIDELINE demonstrates how a lightweight, single-file web application can deliver a rich and engaging mobile experience.

---

<div align="center">

### 🌊 TIDELINE

**Feel the ocean. Know your next catch.**

[🌐 **Launch Application**](https://lee-rhaan.github.io/Fishing-Buddy/)

*Built for the coast. Designed for the angler.*

</div>
