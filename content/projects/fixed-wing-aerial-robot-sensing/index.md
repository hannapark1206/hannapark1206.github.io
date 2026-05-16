---
title: "Fixed-Wing Aerial Robot Sensing and Flight-Control Integration"
summary: "Flight-control integration, ROS/MAVLink data workflows, five-hole Pitot probe hardware, and wind-tunnel calibration for fixed-wing aerial robot testing."
date: 2024-10-01
toc: false
share: false
commentable: false
---

<div class="portfolio-hero">

<p class="project-kicker">Gharib Group · Aerial Robotics · 2024–2025</p>

<p class="project-lede">
I worked on a fixed-wing aerial robot test platform by integrating flight-control hardware, onboard computation, actuator systems, aerodynamic sensing, and ground-station communication.
</p>

<div class="skill-row">
  <span class="skill-chip">✈️ Fixed-wing UAV</span>
  <span class="skill-chip">⚙️ Cube Orange+</span>
  <span class="skill-chip">🤖 Jetson</span>
  <span class="skill-chip">🔗 ROS/MAVLink</span>
  <span class="skill-chip">📡 OptiTrack</span>
  <span class="skill-chip">🌬️ Wind-tunnel calibration</span>
</div>

</div>

## Project Snapshot

This system combined a fixed-wing aircraft, custom five-hole Pitot probe hardware, pressure sensing, motion capture, and ROS/MAVLink data workflows to support flight testing and aerodynamic measurement.

## My Role

I worked on the sensing, flight-control integration, and experimental setup side of the system.

My contributions included hardware integration, communication setup, data retrieval workflows, manual override support, motion-capture synchronization, and five-hole Pitot probe design for flow measurement.

## What I Built and Integrated

<div class="two-col">

<div>

### Flight-control and data system

- Integrated Cube Orange+ flight controller with onboard compute and actuator hardware
- Set up communication between aircraft hardware and ground station
- Worked with QGroundControl / Mission Planner, MAVLink, and ROS-based workflows
- Supported manual override and free-flight testing readiness

</div>

<div>

### Aerodynamic sensing system

- Designed five-hole Pitot probe hardware for local pressure and flow-angle measurement
- Worked on probe geometry, housing design, and sensor integration
- Considered tubing layout and pressure-loss effects
- Prepared hardware for wind-tunnel calibration

</div>

</div>

## Technical Stack

<div class="skill-row">
  <span class="skill-chip">ROS Noetic</span>
  <span class="skill-chip">MAVLink/MAVROS</span>
  <span class="skill-chip">QGroundControl</span>
  <span class="skill-chip">Mission Planner</span>
  <span class="skill-chip">Cube Orange+</span>
  <span class="skill-chip">Jetson</span>
  <span class="skill-chip">Teensy</span>
  <span class="skill-chip">OptiTrack</span>
  <span class="skill-chip">Pressure sensing</span>
  <span class="skill-chip">Wind-tunnel testing</span>
</div>

## Media

<div class="button-row">
  <a class="doc-button" href="Hanna_Park_X2%20Report.pdf">View X2 report</a>
</div>

<div class="media-grid">
  <img src="16.png" alt="Fixed-wing aerial robot test platform">
  <img src="1.png" alt="Five-hole Pitot probe and pressure-sensor electronics">
  <img src="2.png" alt="Five-hole Pitot probe CAD">
  <img src="3.jpeg" alt="PlotJuggler pressure data">
  <img src="4.jpeg" alt="ROS and MAVLink telemetry visualization">
</div>

<style>
.article-metadata,
.toc-sidebar,
.page-toc,
.docs-toc,
#TableOfContents {
  display: none !important;
}

.portfolio-hero {
  margin-top: 1.5rem;
  margin-bottom: 2.5rem;
  max-width: 980px;
}

.project-kicker {
  font-size: 0.9rem;
  font-weight: 700;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  color: #4f46e5;
  margin-bottom: 0.8rem;
}

.project-lede {
  font-size: 1.2rem;
  line-height: 1.65;
  color: #374151;
  max-width: 850px;
}

.skill-row {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin-top: 1rem;
  margin-bottom: 1.5rem;
}

.skill-chip {
  display: inline-flex;
  align-items: center;
  border: 1px solid #dbe3ff;
  background: #f5f7ff;
  color: #27324a;
  border-radius: 12px;
  padding: 0.42rem 0.75rem;
  font-size: 0.88rem;
  font-weight: 600;
  line-height: 1.2;
}

.two-col {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.4rem;
  margin-top: 1rem;
  margin-bottom: 2rem;
}

.two-col > div {
  border: 1px solid #e5e7eb;
  border-radius: 18px;
  padding: 1.2rem 1.3rem;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(0,0,0,0.04);
}
</style>
