---
title: "Fixed-Wing Aerial Robot Sensing and Flight-Control Integration"
summary: "Flight-control integration, ROS/MAVLink data workflows, five-hole Pitot probe hardware, and wind-tunnel calibration for fixed-wing aerial robot testing."
date: 2024-10-01
toc: false
share: false
commentable: false
---

<div class="top-stack">
  <img src="1.png" alt="Five-hole Pitot probe and pressure-sensor electronics">
  <img src="2.png" alt="Five-hole Pitot probe CAD">
</div>

<div class="portfolio-hero">

<p class="project-kicker">Gharib Group · Aerial Robotics · 2024–2025</p>

<p class="project-lede">
I worked on a fixed-wing aerial robot test platform by integrating flight-control hardware, onboard computation, actuator systems, aerodynamic sensing, and ground-station communication.
</p>

<div class="skill-row">
  <span class="skill-chip">Fixed-wing UAV</span>
  <span class="skill-chip">Cube Orange+</span>
  <span class="skill-chip">Jetson</span>
  <span class="skill-chip">ROS/MAVLink</span>
  <span class="skill-chip">OptiTrack</span>
  <span class="skill-chip">Wind-tunnel calibration</span>
</div>

</div>

## Project Report

<div class="report-box">
  <div>
    <p class="report-label">Project report</p>
    <p class="report-title">X2 Fixed-Wing Aerial Robot Report</p>
  </div>
  <a class="report-button" href="Hanna_Park_X2%20Report.pdf">Open report</a>
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

## Additional Media

<div class="bottom-stack">
  <div class="bottom-top">
    <img src="16.png" alt="Fixed-wing aerial robot test platform">
  </div>

  <div class="bottom-two">
    <img src="3.jpeg" alt="PlotJuggler pressure data">
    <img src="4.jpeg" alt="ROS and MAVLink telemetry visualization">
  </div>
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
  margin-top: 2rem;
  margin-bottom: 2.3rem;
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
  font-size: 1.18rem;
  line-height: 1.65;
  color: #374151;
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

.report-box {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
  border: 1px solid #e5e7eb;
  background: #ffffff;
  border-radius: 18px;
  padding: 1rem 1.2rem;
  margin-top: 1rem;
  margin-bottom: 1.4rem;
  box-shadow: 0 8px 24px rgba(0,0,0,0.04);
}

.report-label {
  margin: 0;
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #4f46e5;
}

.report-title {
  margin: 0.2rem 0 0 0;
  font-size: 1rem;
  font-weight: 650;
  color: #111827;
}

.report-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  text-decoration: none !important;
  border-radius: 999px;
  background: #4f46e5;
  color: white !important;
  padding: 0.62rem 1rem;
  font-size: 0.88rem;
  font-weight: 700;
  white-space: nowrap;
}

/* top images stacked */
.top-stack {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-top: 1rem;
  margin-bottom: 2.2rem;
}

.top-stack img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 18px;
  border: 1px solid #e5e7eb;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(0,0,0,0.05);
}

/* bottom layout */
.bottom-stack {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-top: 1rem;
  margin-bottom: 2.5rem;
}

.bottom-top img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 18px;
  border: 1px solid #e5e7eb;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(0,0,0,0.05);
}

.bottom-two {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}

.bottom-two img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 18px;
  border: 1px solid #e5e7eb;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(0,0,0,0.05);
}

@media (max-width: 850px) {
  .bottom-two {
    grid-template-columns: 1fr;
  }

  .report-box {
    flex-direction: column;
    align-items: flex-start;
  }
}
</style>
