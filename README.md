# 🚦 Lanka AI Traffic & Sinhala Voice GPS Navigator

A lightweight, client-side, real-time web navigation and traffic analysis engine tailored specifically for Sri Lanka. Features turn-by-turn Sinhala voice prompts, live device tracking, and dynamic congestion reasoning with confidence metrics—running with zero backend overhead on GitHub Pages.

---

## 🌟 Key Features

* **📍 Real-Time GPS Tracking:** Locks onto device position using the HTML5 Geolocation API (`navigator.geolocation.watchPosition`) with live speedometer calculations.
* **🗣️ Native Sinhala Voice Guidance:** Real-time turn-by-turn voice prompts rendered in Sinhala (`si-LK`) using the Web Speech Synthesis API.
* **🧠 AI Traffic Congestion & Route Justification:** Analyzes peak vs. off-peak hours and junction bottlenecks, producing contextual explanations for route choices.
* **🎯 Dynamic Confidence Scoring:** Displays calculated model accuracy metrics (89% - 98%) reflecting road network certainty.
* **🗺️ Open-Source Navigation Stack:** Integrates Leaflet.js with OpenStreetMap Nominatim Geocoding and the OSRM (Open Source Routing Machine) routing engine.
* **📱 Responsive In-Car Display:** Mobile-first dashboard layout with turn banners, distance-to-next-turn countdowns, and quick-destination presets.

---

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend Framework** | HTML5, Vanilla JavaScript (ES6+) |
| **Styling** | Tailwind CSS (CDN) |
| **Mapping Engine** | Leaflet.js & OpenStreetMap Tiles |
| **Geocoding** | Nominatim API (Filtered for Sri Lanka: `countrycodes=lk`) |
| **Routing Engine** | OSRM Driving API v1 |
| **Speech Engine** | Web Speech Synthesis API (`si-LK` / English fallback) |
| **Hosting** | GitHub Pages (Static hosting) |

---

## 🚀 Deployment to GitHub Pages

1. **Create Repository:**
   * Create a new public repository named `lanka-traffic-ai-navigator`.

2. **Add Files:**
   * Push `index.html` to the root directory.
   * Add this `README.md` file.

3. **Activate Pages:**
   * Go to **Settings** > **Pages**.
   * Under **Branch**, select `main` (or `master`) and `/root`, then click **Save**.
   * Your live app will be accessible at:
     ```text
     https://<your-username>.github.io/lanka-traffic-ai-navigator/
     ```

---

## 📖 How It Works
