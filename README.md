# AeroGate3D v - 3D flight simulator 2026

> **A browser-based 3D aviation simulator for phones, tablets, and desktop computers. Built with HTML and Three.js, it combines selectable GLB aircraft, airport scenes, and touch-ready controls in one standalone HTML application.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/cartergreenuayl7595/aerogate3d-3d-flight-sim?style=flat-square)](https://github.com/cartergreenuayl7595/aerogate3d-3d-flight-sim)

---

<p align="center">
  <a href="https://cartergreenuayl7595.github.io/aerogate3d-3d-flight-sim/">
    <img src="https://img.shields.io/badge/Download-AeroGate3D%20Latest-brightgreen?style=for-the-badge" alt="Download AeroGate3D">
  </a>
</p>

> **[Download AeroGate3D v](https://cartergreenuayl7595.github.io/aerogate3d-3d-flight-sim/)**

---

[Download Latest Build](https://cartergreenuayl7595.github.io/aerogate3d-3d-flight-sim/)

---

## What is AeroGate3D?

AeroGate3D delivers a compact 3D flight experience directly in the browser. The project is packaged as a single HTML file and uses Three.js to render aircraft, airport settings, and interactive flight scenarios without the need for a separate application installer.

The simulator is intended for quick sessions on both mobile devices and desktop browsers. Players can choose from GLB aircraft, use touch-based controls, view radar information, and visit several airport modes in a lightweight experience suited to casual use and demonstrations.

---

## Highlights

- Choose between available GLB aircraft for each session
- Visit multiple airport environments
- Use Gate mode for airport-side ground interaction
- Try Runway mode for takeoff-oriented situations
- Practice approaches and touchdowns in Landing mode
- Operate the simulator through controls suited to touchscreens
- Follow nearby activity with the radar display
- Configure aircraft and session options through the interactive hangar
- Host and launch the project as a single HTML file

---

## Getting Started

1. Clone or download the repository:
   - `git clone https://github.com/cartergreenuayl7595/aerogate3d-3d-flight-sim.git
2. Move into the downloaded project directory.
3. Open the HTML file in a modern browser. Alternatively, run the project through a small local web server.

For example:
- `python -m http.server`

Visit the local address printed by the server to open the simulator.

---

## Playing the Simulator

1. Load AeroGate3D in your browser.
2. Enter the hangar and select a GLB aircraft.
3. Choose an airport environment.
4. Select Gate, Runway, or Landing mode.
5. Use touchscreen input on mobile, or the available browser controls on desktop.
6. Refer to the radar as you navigate the airport scene.

A normal session can follow this sequence:

- Open the hangar
- Select an aircraft
- Load an airport
- Choose a scenario mode
- Start using the simulator

---

## Project Configuration

Because AeroGate3D is distributed as an HTML application, configuration is generally performed within the project files instead of through an installation wizard.

When modifying the simulator, relevant areas include:

- References to aircraft models
- Airport and scene choices
- Input and control behavior
- Interface components, including the hangar and radar

Where asset or scene definitions are contained in script sections, make the required changes there before deploying or hosting the HTML file.

---

## System Requirements

- A current web browser capable of running HTML and JavaScript
- WebGL support for Three.js graphics
- Sufficient memory and local storage to load the 3D assets
- A touchscreen device when using mobile-oriented controls
- The aircraft and airport scene assets included with the project

---

## Frequently Asked Questions

**Can AeroGate3D run without an installer?**  
Yes. It is organized as a single HTML application that can be opened directly in a browser or served locally.

**Does the simulator support desktop browsers?**  
Yes. AeroGate3D is intended for both mobile and desktop browser use.

**How are aircraft and airports changed?**  
The available selections are normally defined in the HTML and script content, together with their related asset files.

**What can I check when an airport scene fails to appear?**  
Review the browser console, verify that the asset paths are correct, and confirm that the browser has access to the necessary files.

**How can I find newer versions?**  
Check the latest repository release or build from the project's main source as supplied by the maintainers.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
