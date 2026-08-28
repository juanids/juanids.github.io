---
layout: archive
title: "Nanowire Network Simulation Platform"
permalink: /simulations/
author_profile: true
---

<p style="text-align: justify; font-size: 1.1em; margin-bottom: 40px;">
Welcome to the Python-based simulation framework designed to model, visualize, and analyze the electrical transport and neuromorphic dynamics of random nanowire networks. This platform offers a highly customizable environment to bridge the gap between theoretical models and experimental in-materia computing systems.
</p>

## 🎛️ Fully Customizable Network Topology
Generate complex, self-assembled network morphologies tailored to your specific experimental conditions. 
* **Adjustable Geometries:** Seamlessly modify the total number of nanowires, individual wire lengths, and overall network dimensions.
* **Electrode Configuration:** Define the horizontal width of the contact electrodes, while the vertical electrodes automatically span the full height of the simulated region.

<div style="text-align: center; margin-bottom: 40px; margin-top: 20px;">
  <img src="/images/Hilos.png" alt="Nanowire network simulation with electrodes" style="width: 85%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <span style="font-size: 0.85em; color: #666; display: block; margin-top: 8px; font-style: italic;">Randomly distributed nanowire network contacting parallel electrodes.</span>
</div>

## 🧠 Bring Your Own Physics (BYOP)
The greatest potential of this platform lies in its modularity. You are not restricted to predefined physical behaviors. 
* **Custom Resistance Models:** Inject your own custom mathematical equations to define the electrical behavior of the system.
* **Granular Control:** Assign unique static or dynamic physical rules independently to the **nanowires**, the **wire-to-wire junctions**, and the **electrode contacts**.

## ⚡ Dynamic Electrical Testing & Visualization
Stimulate your virtual materials just as you would in the laboratory. The framework tracks spatial current distribution and temporal evolution in real-time.
* **Arbitrary Waveforms:** Apply continuous voltage sweeps to extract complex I-V curves, or input custom pulse trains to study temporal dynamics.
* **Neuromorphic Emulation:** Observe critical state changes such as network activation, conductive filament formation, and current relaxation over time[cite: 2].

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-bottom: 40px; margin-top: 20px;">
  <div style="flex: 1; min-width: 300px; text-align: center;">
    <img src="/images/3205.png" alt="Real-time dynamics and I-V curves" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <span style="font-size: 0.85em; color: #666; display: block; margin-top: 8px; font-style: italic;">Instantaneous current mapping and I-V sweeps under an applied bias.</span>
  </div>
  <div style="flex: 1; min-width: 300px; text-align: center;">
    <!-- Asegurate de nombrar la foto de los pulsos como 'pulse-response.png' o cambiá este texto -->
    <img src="/images/pulse-response.png" alt="Pulse response and relaxation" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <span style="font-size: 0.85em; color: #666; display: block; margin-top: 8px; font-style: italic;">Network activation and relaxation dynamics under pulsed stimulation[cite: 2].</span>
  </div>
</div>

## 🔬 Proven Academic Track Record
This exact simulation engine was instrumental in extracting theoretical predictions and guiding material engineering for recent high-impact publications:
* **[Nanowire Nanocomposite Networks with Learning Abilities (2026)](/publications/)**: Provided the theoretical framework to optimize encapsulation strategies and achieve controlled associative learning.
* **[Two-Junction Model in Percolation Regimes (2024)](/publications/)**: Used to simulate distinct percolation regimes and explain the complex transport dynamics observed experimentally.

---

<div style="text-align: center; margin-top: 40px; padding: 20px; background-color: #f9f9f9; border-radius: 8px;">
  <h3 style="margin-top: 0;">Ready to run your own simulations?</h3>
  <p style="margin-bottom: 20px;">Dive into the code, explore the technical documentation, and start building your custom models.</p>
  <a href="https://github.com/juanids/agnws" target="_blank" style="display: inline-block; padding: 12px 24px; background-color: #24292e; color: white; text-decoration: none; border-radius: 6px; font-weight: bold; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <i class="fab fa-github" style="margin-right: 8px;"></i> View Source Code on GitHub
  </a>
</div>
