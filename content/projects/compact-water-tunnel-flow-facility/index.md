---
title: "Compact Water-Tunnel Flow Facility"
summary: "Low-Reynolds-number flow facility work involving turbine-array hardware, electronics, power configuration, Arduino/PWM control, and PIV/dye-flow validation."
date: 2024-02-01
toc: false
share: false
commentable: false
---

<div class="top-stack">
  <img src="5.png" alt="Water tunnel CAD model">
  <img src="7.png" alt="PIV setup diagram">
</div>

<div class="portfolio-hero">

<p class="project-kicker">Gharib Group · Experimental Fluids · 2024</p>

<p class="project-lede">
I worked on a compact low-Reynolds-number water-tunnel facility by supporting hardware integration, turbine-array control, electronics, power configuration, Arduino/PWM control, and PIV/dye-flow validation.
</p>

<div class="skill-row">
  <span class="skill-chip">Water tunnel</span>
  <span class="skill-chip">Low-Reynolds-number flow</span>
  <span class="skill-chip">Turbine arrays</span>
  <span class="skill-chip">Arduino C++</span>
  <span class="skill-chip">PWM control</span>
  <span class="skill-chip">Electronics</span>
  <span class="skill-chip">Power configuration</span>
  <span class="skill-chip">PIV</span>
  <span class="skill-chip">Dye visualization</span>
  <span class="skill-chip">Kármán vortex streets</span>
</div>

</div>

## Project Snapshot

<div class="project-detail-box">

<p>
This project focused on building and improving a compact <strong>2 × 1 meter</strong> flow facility with a <strong>9 × 9 turbine array</strong>. The test section occupied about <strong>45%</strong> of the total facility area, which made the setup much smaller than a traditional pump-powered water tunnel with a similar test-section size.
</p>

<p>
Compared with traditional pump-powered facilities, the design achieved about a <strong>96% reduction in size</strong> and used less than <strong>6%</strong> of the overall footprint. I supported the hardware layout, electronics, wiring, power configuration, and turbine-array control needed to make the compact facility usable for flow testing.
</p>

<p>
For validation, I conducted <strong>Particle Image Velocimetry (PIV)</strong> to collect velocity-profile data and ran shear-layer dye-injection tests using UV light. These tests were used to observe Kármán vortex street patterns at different Reynolds numbers and showed roughly <strong>1–2% turbulence intensity</strong>.
</p>

<p>
I also worked on the Arduino C++ control code for shear-layer testing by implementing matrix-style control for individual turbines and line-based control on a <strong>3 × 3 array</strong>, with the structure designed to scale toward the full <strong>9 × 9 array</strong>. Our work was presented at the <strong>2024 SoCal XVI Fluids Conference</strong>.
</p>

</div>

<div class="report-box">
  <div>
    <p class="report-title">Water Tunnel in a Box</p>
  </div>
  <a class="report-button" href="Water%20Tunnel%20in%20a%20Box%20-%20Improvements%20to%20a%20compact%20flow%20facility.pdf">Open presentation</a>
</div>

## Additional Media

<div class="bottom-stack">
  <div class="bottom-two">
    <img src="8.png" alt="Dye visualization of vortex shedding">
    <img src="6.png" alt="Compact water tunnel facility">
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
  margin-bottom: 2rem;
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
  margin-bottom: 1.2rem;
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

.project-detail-box {
  border: 1px solid #e5e7eb;
  background: #ffffff;
  border-radius: 18px;
  padding: 1.2rem 1.35rem;
  margin-top: 1rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 8px 24px rgba(0,0,0,0.04);
}

.project-detail-box p {
  margin-top: 0;
  margin-bottom: 0.9rem;
  font-size: 0.98rem;
  line-height: 1.65;
  color: #374151;
}

.project-detail-box p:last-child {
  margin-bottom: 0;
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
  margin-top: 0.4rem;
  margin-bottom: 2rem;
  box-shadow: 0 8px 24px rgba(0,0,0,0.04);
}

.report-title {
  margin: 0;
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

.bottom-stack {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-top: 1rem;
  margin-bottom: 2.5rem;
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
