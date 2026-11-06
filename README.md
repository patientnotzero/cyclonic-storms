
# Supercharged: What Is the Effect of Earth's Temperature on Cyclonic Storms?

An interactive, data-driven web presentation tailored for high school Earth science classrooms. This project explores the thermodynamic and meteorological relationship between rising global temperatures and the frequency, intensity, and accumulated energy of tropical cyclones (hurricanes and typhoons) as well as severe convective storm environments.

---

## The Big Idea (The Myth-Buster)

> **Key Takeaway:** Earth is warming, but the planet is **not** spawning hundreds more storms each year. Instead, rising ocean heat is **supercharging** the storms that do form into far deadlier, higher-category systems that intensify rapidly and deliver historic rain and storm surge.

* **Frequency:** Global storm counts remain virtually flat at **~85 tropical storms per year**.
* **Intensity:** The proportion of Category 4 and 5 mega-cyclones has expanded significantly from **~23% (1999–2003)** to **~35% (2019–2024)**.
* **Energy:** Global Accumulated Cyclone Energy (ACE) mirrors the steep climb in Ocean Heat Content (OHC), providing prolonged kinetic lifecycles.

---

## Interactive Visuals Included

1. **Visual 1: Earth's Rising Fever**  
   A line chart featuring a multi-stop color gradient fill (cooling blue to deep red) showing NASA/NOAA global surface temperature anomalies climbing from $+0.45^\circ\text{C}$ to $+1.28^\circ\text{C}$ over the 25-year baseline (1999–2024).

2. **Visual 2: The Deceptive Flatline (Myth-Buster)**  
   A dual-axis comparative line chart plotting annual tropical cyclone counts from IBTrACS against rising global temperature anomalies, illustrating how storm numbers remain constant despite accelerated planetary warming.

3. **Visual 3: The Monster Shift (Intensity Distribution)**  
   A 100% stacked bar chart grouped in 5-year climatological windows, highlighting the expanding share of destructive Category 4–5 systems relative to minor Category 1–2 storms.

4. **Visual 4: The Power Surge (ACE & Ocean Heat)**  
   A multi-trend visualization contrasting global Accumulated Cyclone Energy (ACE) with NOAA upper Ocean Heat Content ($0\text{--}700\text{ m}$ depth in $10^{22}\text{ Joules}$).

5. **Geographical Map Visual: Genesis & Intensification Hotspots**  
   An interactive Leaflet world map marking marine basins, record-shattering rapid intensification events (e.g., Hurricane Otis, Hurricane Milton), and convective severe storm / tornado corridors.

6. **Visual 5: Ground Impact & Atmospheric Physics**  
   A side-by-side panel pairing Clausius-Clapeyron atmospheric water-holding metrics ($+7\%\text{ per }1^\circ\text{C}$ warming) and baseline sea-level rise with before-and-after photographic field evidence of catastrophic storm surge flooding.

---

## Data Sources

* **Global Surface Temperature Anomalies:** [NASA Goddard Institute for Space Studies (GISTEMP v4)](https://data.giss.nasa.gov/gistemp/) & [NOAA NCEI Climate at a Glance](https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/)
* **Tropical Cyclone Frequency & Intensity:** [NOAA IBTrACS v04 (International Best Track Archive for Climate Stewardship)](https://www.ncei.noaa.gov/products/international-best-track-archive)
* **Accumulated Cyclone Energy (ACE):** [Ryan Maue / NOAA National Hurricane Center (NHC)](https://www.nhc.noaa.gov/)
* **Upper Ocean Heat Content (0–700m):** [NOAA NCEI Ocean Climate Laboratory](https://www.ncei.noaa.gov/access/global-ocean-heat-content/)

---

## Tech Stack

* **HTML5 & CSS3**
* **Tailwind CSS** (via CDN for styling and layout)
* **Chart.js** (for high-performance data visualizations)
* **Leaflet.js** & **CartoDB Dark Matter tiles** (for interactive mapping)
* **FontAwesome 6** (for icons and visual badges)

---

## How to Deploy to GitHub Pages

1. **Create Repository:** Create a new public repository on GitHub (e.g., `cyclonic-storms-investigation`).
2. **Add Files:**
   * Create or upload `index.html` at the root of the repository.
   * Add this `README.md` file.
3. **Enable GitHub Pages:**
   * Open repository **Settings**.
   * Click on **Pages** in the left sidebar menu.
   * Under **Branch**, select `main` (or `master`) and folder `/ (root)`.
   * Click **Save**.
4. **View Live Presentation:** Within 1–2 minutes, your presentation will be live at:  
   `https://<your-username>.github.io/<your-repo-name>/`

---

## Classroom Discussion Prompts

1. **Frequency vs. Intensity:** Why doesn't a hotter atmosphere create hundreds more tropical storms, and what prevents storm genesis even when sea surface temperatures are warm?
2. **Thermodynamics of Rapid Intensification:** How does high upper ocean heat content ($>26.5^\circ\text{C}$) eliminate the cold-water wake effect that typically limits cyclone intensity?
3. **Severe Convective Storms:** How do plumes of warm, humid air from the Gulf of Mexico enhance convective available potential energy (CAPE) for tornado outbreaks across the central United States?
