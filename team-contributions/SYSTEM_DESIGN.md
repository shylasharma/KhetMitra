<!-- ===== KHETMITRA SYSTEM DESIGN (ANIMATED / COMPACT) ===== -->

<style>
/* Lightweight animation + tech vibe (GitHub-safe) */
.fade { animation: fadeIn 1.1s ease-in; }
.slide { animation: slideUp .9s ease-out; }
.pulse { animation: pulse 2.2s infinite; }
@keyframes fadeIn { from {opacity:0} to {opacity:1} }
@keyframes slideUp { from {transform:translateY(14px); opacity:0} to {transform:none; opacity:1} }
@keyframes pulse { 0%{opacity:.85} 50%{opacity:1} 100%{opacity:.85} }
.card { border:1px solid #1f2937; border-radius:14px; padding:14px; margin:14px 0; background:#0b1220; }
.center { text-align:center }
.badge { display:inline-block; padding:4px 10px; border-radius:999px; border:1px solid #334155; margin:4px }
.hr { height:1px; background:#1f2937; margin:18px 0 }
</style>

<div class="center fade">
  <h1>🌱⚡ KHETMITRA</h1>
  <p class="pulse">AI × IoT Smart Farming — <b>Soil → Sensor → Cloud → AI → Farmer</b></p>
  <span class="badge">IoT</span><span class="badge">AI</span><span class="badge">Cloud</span><span class="badge">Scalable</span>
</div>

<div class="hr"></div>

<div class="card slide">
<h3>System Snapshot</h3>

Soil → Sensors → ESP32 → APIs → AI Engine → Mobile/Web


<p class="center"><i>Visual Map</i></p>
<p class="center"><img src="flow1.png" width="88%"></p>
</div>

<div class="card slide">
<h3>Flow-1: IoT Data Capture</h3>

- NPK + Moisture sensors read soil parameters  
- ESP32 aggregates readings  
- SD-card fallback when network drops  
- Auto-sync on connectivity restore  

<p class="center"><img src="flow2.png" width="88%"></p>
</div>

<div class="card slide">
<h3>Flow-2: Backend & Data Core</h3>

- REST APIs ingest sensor data  
- Validation + normalization  
- MongoDB stores time-series & history  
- Secure access for AI & apps  

<p class="center"><img src="flow3.png" width="88%"></p>
</div>

<div class="card slide">
<h3>Flow-3: AI Decision Engine</h3>

- Soil data → ML models  
- Context reasoning (crop, water, fertilizer)  
- Explainable outputs for farmers  

<p class="center"><img src="flow4.png" width="88%"></p>
</div>

<div class="card fade">
<h3>Data Model (Compact ER)</h3>



User → Farm → Sensor → SoilReading → Recommendation → SustainabilityScore

</div>

<div class="card fade">
<h3>Tech Used</h3>

| Layer | Stack |
|---|---|
| IoT | ESP32, NPK Sensors |
| Backend | Node.js, Express |
| DB | MongoDB Atlas |
| AI | TensorFlow, Gemini API |
| Frontend | React, Kotlin |
</div>

<div class="card fade">
<h3>Scale & Reliability</h3>

- Stateless APIs (horizontal scale)  
- DB indexing + sharding  
- Async AI processing  
- Offline capture + retry sync  
</div>

<div class="center pulse">
<b>Result:</b> Clean, scalable, farmer-ready system powered by real flows.
</div>