---
title: Projects
summary: Robotics, controls, experimental systems, and design projects.
date: 2026-05-16
type: page
---

<p class="projects-intro">
Selected research, class, and hardware projects in robotics, controls, aerial systems, experimental fluids, rapid prototyping, and instrumentation.
</p>

## Gharib Group Projects

<div class="project-grid">

<a class="project-card" href="/projects/x2-uav/">
  <div class="project-image">
    <img src="/projects/x2-uav/featured.jpg" alt="X2 UAV project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Aerial Robotics · Controls · Sensing</div>
    <h3>X2 UAV Sensing and Flight-Control Integration</h3>
    <p>Five-hole Pitot probe hardware, ROS/MAVLink workflows, flight-control integration, and wind-tunnel calibration.</p>
  </div>
</a>

<a class="project-card" href="/projects/water-tunnel/">
  <div class="project-image">
    <img src="/projects/water-tunnel/featured.jpg" alt="Water tunnel project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Experimental Fluids · Hardware</div>
    <h3>Low-Reynolds-Number Water Tunnel</h3>
    <p>Water-tunnel hardware, turbine-array fixtures, electronics, power configuration, Arduino/PWM control, and PIV/dye validation.</p>
  </div>
</a>

<a class="project-card" href="/projects/hebi-vision/">
  <div class="project-image">
    <img src="/projects/hebi-vision/featured.jpg" alt="HEBI vision tracking project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Vision · Motion Control</div>
    <h3>Real-Time Vision and HEBI Motion Control</h3>
    <p>Python/OpenCV target detection and HEBI actuator control for real-time pan–tilt tracking.</p>
  </div>
</a>

<a class="project-card" href="/projects/senior-thesis/">
  <div class="project-image placeholder"></div>
  <div class="project-body">
    <div class="project-tag">Research · Work in Progress</div>
    <h3>Senior Thesis</h3>
    <p>Independent research project in progress. This page will be updated as the thesis direction develops.</p>
  </div>
</a>

</div>

## Robotics and Field Systems

<div class="project-grid">

<a class="project-card" href="/projects/m4/">
  <div class="project-image">
    <img src="/projects/m4/featured.jpg" alt="M4 project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Robotics · Hardware · CFD</div>
    <h3>M4 Air–Ground Robot Platform</h3>
    <p>Air–ground robot hardware, propulsion/avionics integration, thrust-biasing deflector design, CFD checks, and bench testing.</p>
  </div>
</a>

<a class="project-card" href="/projects/firefighting/">
  <div class="project-image placeholder"></div>
  <div class="project-body">
    <div class="project-tag">Rapid Prototyping · Assembly</div>
    <h3>Firefighting Prototype Project</h3>
    <p>Rapid prototyping, mechanical assembly, hardware modification, and test-preparation support for a firefighting-related system.</p>
  </div>
</a>

</div>

## Instrumentation and Detector Systems

<div class="project-grid">

<a class="project-card" href="/projects/golwala-kids/">
  <div class="project-image">
    <img src="/projects/golwala-kids/featured.jpg" alt="Golwala KID detector project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Cryogenics · Instrumentation · Python</div>
    <h3>Cryogenic Detector Hardware</h3>
    <p>KID detector modifications, phonon guides, CAD mounting, wire-bonded assembly, and Python resonance fitting.</p>
  </div>
</a>

</div>

## Class and Design Projects

<div class="project-grid">

<a class="project-card" href="/projects/gearbox/">
  <div class="project-image">
    <img src="/projects/gearbox/featured.jpg" alt="Gearbox project image">
  </div>
  <div class="project-body">
    <div class="project-tag">Class Project · Mechanical Design</div>
    <h3>ME14 Transmission Gearbox</h3>
    <p>Multi-stage gearbox design with MATLAB performance modeling, SolidWorks CAD, keyed shafts, bearings, machining, and design reviews.</p>
  </div>
</a>

<a class="project-card" href="/projects/pillars/">
  <div class="project-image placeholder"></div>
  <div class="project-body">
    <div class="project-tag">Team Project · Aerospace Concept</div>
    <h3>NASA BIG Idea / PILLARS</h3>
    <p>Finalist proposal for a plume-deployed inflatable landing shield concept to reduce lunar regolith disturbance during landing.</p>
  </div>
</a>

</div>

<style>
.projects-intro {
  max-width: 850px;
  font-size: 1.05rem;
  line-height: 1.65;
  margin-top: -1.5rem;
  margin-bottom: 2.5rem;
  color: #4b5563;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(285px, 1fr));
  gap: 1.4rem;
  margin-top: 1.2rem;
  margin-bottom: 3rem;
}

.project-card {
  display: block;
  overflow: hidden;
  border: 1px solid #e5e7eb;
  border-radius: 20px;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(0,0,0,0.05);
  text-decoration: none !important;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 14px 34px rgba(0,0,0,0.09);
}

.project-image {
  width: 100%;
  aspect-ratio: 16 / 9;
  background: linear-gradient(135deg, #ede9fe, #fbcfe8);
  display: flex;
  align-items: center;
  justify-content: center;
}

.project-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.project-image.placeholder::after {
  content: "image coming soon";
  color: #ffffff;
  font-size: 0.95rem;
  letter-spacing: 0.04em;
}

.project-body {
  padding: 1.15rem 1.25rem 1.3rem;
}

.project-tag {
  display: inline-block;
  font-size: 0.76rem;
  font-weight: 600;
  color: #4f46e5;
  background: #eef2ff;
  border-radius: 999px;
  padding: 0.25rem 0.62rem;
  margin-bottom: 0.55rem;
}

.project-card h3 {
  font-size: 1.18rem;
  line-height: 1.25;
  margin: 0 0 0.55rem 0;
}

.project-card p {
  font-size: 0.93rem;
  line-height: 1.55;
  color: #4b5563;
  margin: 0;
}
</style>
