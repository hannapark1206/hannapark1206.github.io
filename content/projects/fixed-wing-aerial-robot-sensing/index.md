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
  <span class="skill-chip">Fixed-wing UAV</span>
  <span class="skill-chip">Cube Orange+</span>
  <span class="skill-chip">Jetson</span>
  <span class="skill-chip">ROS/MAVLink</span>
  <span class="skill-chip">OptiTrack</span>
  <span class="skill-chip">Wind-tunnel calibration</span>
</div>

</div>

## Media

<div class="report-card">
  <div>
    <p class="report-label">Project report</p>
    <h3>X2 Fixed-Wing Aerial Robot Report</h3>
    <p>
      A more detailed write-up of the fixed-wing UAV platform, sensing hardware, and flight-control integration work.
    </p>
  </div>
  <a class="report-button" href="Hanna_Park_X2%20Report.pdf">Open report</a>
</div>

<div class="media-slider">
  <div class="media-slide">
    <img src="16.png" alt="Fixed-wing aerial robot test platform">
    <p>Fixed-wing aerial robot test platform</p>
  </div>

  <div class="media-slide">
    <img src="1.png" alt="Five-hole Pitot probe and pressure-sensor electronics">
    <p>Five-hole Pitot probe and pressure-sensor electronics</p>
  </div>

  <div class="media-slide">
    <img src="2.png" alt="Five-hole Pitot probe CAD">
    <p>Five-hole Pitot probe CAD</p>
  </div>

  <div class="media-slide">
    <img src="3.jpeg" alt="PlotJuggler pressure data">
    <p>Pressure data visualization</p>
  </div>

  <div class="media-slide">
    <img src="4.jpeg" alt="ROS and MAVLink telemetry visualization">
    <p>ROS and MAVLink telemetry visualization</p>
  </div>
</div>

<p class="scroll-note">Scroll sideways to view more images.</p>

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

<style>
.article-metadata,
.toc-sidebar,
.page-toc,
.docs-toc,
#TableOfContents {
  display: none !important;
}

/* 1 inch page margins */
.article-container,
.universal-wrapper,
.page-body,
main {
  max-width: none !important;
  width: auto !important;
  margin-left: 1in !important;
  margin-right: 1in !important;
  padding-left: 0 !important;
  padding-right: 0 !important;
}

.portfolio-hero {
  margin-top: 1.5rem;
  margin-bottom: 2rem;
  max-width: 1050px;
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

.report-card {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1.5rem;
  border: 1px solid #dbe3ff;
  background: linear-gradient(135deg, #f7f8ff 0%, #ffffff 70%);
  border-radius: 22px;
  padding: 1.4rem 1.5rem;
  margin-top: 1rem;
  margin-bottom: 1.6rem;
  box-shadow: 0 12px 32px rgba(0,0,0,0.06);
}

.report-card h3 {
  margin: 0.1rem 0 0.45rem 0;
  font-size: 1.25rem;
  color: #111827;
}

.report-card p {
  margin: 0;
  color: #4b5563;
  line-height: 1.55;
}

.report-label {
  font-size: 0.78rem;
  font-weight: 800;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: #4f46e5 !important;
  margin-bottom: 0.25rem !important;
}

.report-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  white-space: nowrap;
  text-decoration: none !important;
  background: #4f46e5;
  color: white !important;
  border-radius: 999px;
  padding: 0.7rem 1.05rem;
  font-size: 0.9rem;
  font-weight: 700;
  box-shadow: 0 8px 20px rgba(79,70,229,0.25);
}

.report-button:hover {
  transform: translateY(-1px);
  box-shadow: 0 12px 24px rgba(79,70,229,0.3);
}

.media-slider {
  display: flex;
  gap: 1rem;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  padding: 0.3rem 0 1rem 0;
  margin-bottom: 0.2rem;
}

.media-slide {
  flex: 0 0 min(78vw, 760px);
  scroll-snap-align: start;
  border-radius: 24px;
  overflow: hidden;
  background: #ffffff;
  border: 1px solid #e5e7eb;
  box-shadow: 0 14px 34px rgba(0,0,0,0.08);
}

.media-slide img {
  width: 100%;
  height: 430px;
  object-fit: cover;
  display: block;
}

.media-slide p {
  margin: 0;
  padding: 0.85rem 1rem;
  font-size: 0.92rem;
  font-weight: 650;
  color: #374151;
  background: #ffffff;
}

.scroll-note {
  margin-top: 0;
  margin-bottom: 2.2rem;
  font-size: 0.88rem;
  color: #6b7280;
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

@media (max-width: 768px) {
  .article-container,
  .universal-wrapper,
  .page-body,
  main {
    margin-left: 1rem !important;
    margin-right: 1rem !important;
  }

  .report-card {
    flex-direction: column;
    align-items: flex-start;
  }

  .media-slide {
    flex-basis: 88vw;
  }

  .media-slide img {
    height: 280px;
  }
}
</style>
