# 🛰️ OrbitX-An-Interactive-Space-Systems-Management-Platform

A suite of responsive, component-based interactive web applications developed for the **BSERC Def-Space Internship Programme**. This project translates complex aerospace systems, orbital mechanics, and launch vehicle trade studies into functional, self-contained client-side web tools.

---

## 🚀 Included Web Applications

This repository features three fully interactive, single-file HTML applications built with modern dark-mode aerospace styling and vanilla JavaScript:

### 1. Satellite Mission Operations Dashboard (`satellite-dashboard.html`)
A real-time ground-control telemetry monitoring interface featuring:
* **Subsystem Checklist:** Interactive toggle checkboxes for solar panels, reaction wheels, and communication links.
* **Mission Elapsed Timer:** Fully working start, pause, and reset timer loops.
* **Telemetry Inspection Stream:** Clickable data cards detailing altitude, battery state-of-charge, thermal readings, and signal strength.
* **Operational Mode Selector:** Dropdown switcher for nominal science, safe sun-pointing, station-keeping, and eclipse conservation modes.
* **Anomaly Resolution Protocol Quiz:** Interactive scenario-based troubleshooting test with instant dynamic score validation.

### 2. Interactive Satellite Orbital Simulator (`satellite-simulator.html`)
A real-time 2D Keplerian orbital mechanics simulator featuring:
* **Dynamic Sliders:** Real-time altitude (300–1200 km) and inclination angle (0–90°) controllers updating orbital velocity and period metrics live.
* **Station-Keeping Thruster Burn:** Interactive action button simulating orbit correction burns with animated thruster flames and $\Delta v$ consumption tracking.
* **Solar Array Toggle:** Switch between deployed and retracted states with live power generation readouts.
* **Space Overlay Toggles:** Checkboxes to overlay ground station coverage rings, orbital debris fields, and Earth magnetic field lines.

### 3. Launch Vehicle & Payload Decision Helper (`launch-decision-helper.html`)
A multi-parameter trade-study decision support matrix featuring:
* **Constraint Sliders:** Dynamic sliders for payload mass, target altitude, and budget caps that re-rank launch vehicles live.
* **Provider & Site Filters:** Checkbox filters for major global launch providers (ISRO, SpaceX, ESA, ULA) and launch complexes (SDSC SHAR, Kennedy Space Center, Kourou).
* **Comparative Matrix Table:** Interactive ranking table showing payload capacities, cost estimates, and success rates.
* **Mission Export Card:** Generates a locked summary configuration card for formal mission packaging.

---

## 🛠️ Tech Stack

* **Markup & Structure:** HTML5 (Single-file architecture per module)
* **Styling:** CSS3 / Modern CSS Variables (Custom dark-mode aerospace palette)
* **Logic & Rendering:** Vanilla JavaScript (ES6+), HTML5 Canvas 2D API (`requestAnimationFrame`)
* **Dependencies:** Zero external frameworks or libraries required (pure native web standards)

---

## ⚙️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
