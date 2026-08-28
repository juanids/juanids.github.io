---
layout: archive
permalink: /simulations/
author_profile: true
---

<!-- Pequeño enlace superior -->
<p style="font-size: 0.9em; margin-bottom: 5px; text-align: right;">
  <a href="https://github.com/juanids/agnws" target="_blank" style="text-decoration: none; color: #0366d6;">
    <i class="fab fa-github"></i> Acceder al repositorio de GitHub
  </a>
</p>

<!-- Título principal con hipervínculo -->
<h1 style="margin-top: 0; margin-bottom: 30px;">
  <a href="https://github.com/TU-USUARIO/agnws" target="_blank" style="text-decoration: none; color: inherit;">
    Nanowire Network Simulation Platform
  </a>
</h1>

<p style="text-align: justify; font-size: 1.1em; margin-bottom: 50px;">
Welcome to the Python-based simulation framework designed to model, visualize, and analyze the electrical transport and neuromorphic dynamics of random nanowire networks. This platform offers a highly customizable environment to bridge the gap between theoretical models and experimental in-materia computing systems.
</p>

<!-- SECCIÓN 1: 2 Columnas (Texto + Hilos.png) -->
<div style="display: flex; flex-wrap: wrap; gap: 30px; align-items: center; margin-bottom: 50px;">
  <div style="flex: 1; min-width: 300px;">
    <h2 style="margin-top: 0;">🎛️ Fully Customizable Network Topology</h2>
    <p style="text-align: justify;">Generate complex, self-assembled network morphologies tailored to your specific experimental conditions.</p>
    <ul>
      <li style="margin-bottom: 10px;"><strong>Adjustable Geometries:</strong> Seamlessly modify the total number of nanowires, individual wire lengths, and overall network dimensions.</li>
      <li><strong>Electrode Configuration:</strong> Define the horizontal width of the contact electrodes, while the vertical electrodes automatically span the full height of the simulated region.</li>
    </ul>
  </div>
  <div style="flex: 1; min-width: 250px; text-align: center;">
    <img src="/images/Hilos.png" alt="Nanowire network simulation with electrodes" style="width: 100%; max-width: 380px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <span style="font-size: 0.85em; color: #666; display: block; margin-top: 8px; font-style: italic;">Randomly distributed nanowire network contacting parallel electrodes.</span>
  </div>
</div>

<!-- SECCIÓN 2: 2 Columnas (Texto Física + Imagen Relajación) -->
<div style="display: flex; flex-wrap: wrap; gap: 30px; align-items: center; margin-bottom: 50px;">
  <div style="flex: 1; min-width: 300px;">
    <h2 style="margin-top: 0;">🧠 Bring Your Own Physics (BYOP) & Dynamics</h2>
    <p style="text-align: justify;">The greatest potential of this platform lies in its modularity. You are not restricted to predefined physical behaviors.</p>
    <ul>
      <li style="margin-bottom: 10px;"><strong>Custom Resistance Models:</strong> Inject your own custom mathematical equations to define the electrical behavior of the system.</li>
      <li style="margin-bottom: 10px;"><strong>Granular Control:</strong> Assign unique static or dynamic physical rules independently to the nanowires, the wire-to-wire junctions, and the electrode contacts.</li>
      <li><strong>Neuromorphic Emulation:</strong> Apply custom pulse trains to study temporal dynamics, observing critical state changes such as network activation and current relaxation over time.</li>
    </ul>
  </div>
  <div style="flex: 1; min-width: 250px; text-align: center;">
    <!-- Recordá nombrar tu imagen de los pulsos/relajación como pulse-response.png -->
    <img src="/images/pulse-response.png" alt="Pulse response and relaxation" style="width: 100%; max-width: 450px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <span style="font-size: 0.85em; color: #666; display: block; margin-top: 8px; font-style: italic;">Network activation and relaxation dynamics under pulsed stimulation[cite: 2].</span>
  </div>
</div>

<!-- SECCIÓN 3: Pantalla Completa (3205.png) -->
<div style="margin-bottom: 60px;">
  <h2 style="margin-top: 0;">⚡ Real-Time Electrical Testing & Visualization</h2>
  <p style="text-align: justify; margin-bottom: 30px;">Stimulate your virtual materials just as you would in the laboratory. The framework tracks spatial current distribution and temporal evolution in real-time, allowing you to apply continuous voltage sweeps and extract complex I-V curves.</p>
  
  <div style="text-align: center;">
    <img src="/images/3205.png" alt="Real-time dynamics and I-V curves" style="width: 100%; border-radius: 8px; box-shadow: 0 6px 12px rgba(0,0,0,0.15);">
    <span style="font-size: 0.85em; color: #666; display: block; margin-top: 12px; font-style: italic;">Instantaneous current mapping and I-V sweeps under an applied bias.</span>
  </div>
</div>

<!-- SECCIÓN 4: Publicaciones y Botón Final -->
<h2>🔬 Proven Academic Track Record</h2>
<p>This exact simulation engine was instrumental in extracting theoretical predictions and guiding material engineering for recent high-impact publications:</p>
<ul>
  <li><strong><a href="https://doi.org/10.1002/adfm.77408">Nanowire Nanocomposite Networks with Learning Abilities (2026)</a></strong>: Provided the theoretical framework to optimize encapsulation strategies and achieve controlled associative learning.</li>
  <li><strong><a href="https://doi.org/10.1002/adfm.202410766">Two-Junction Model in Percolation Regimes (2024)</a></strong>: Used to simulate distinct percolation regimes and explain the complex transport dynamics observed experimentally.</li>
</ul>

<div style="text-align: center; margin-top: 50px; padding: 30px; background-color: #f6f8fa; border-radius: 8px; border: 1px solid #e1e4e8;">
  <h3 style="margin-top: 0;">Ready to run your own simulations?</h3>
  <p style="margin-bottom: 20px;">Dive into the code, explore the technical documentation, and start building your custom models.</p>
  <a href="https://github.com/juanids/agnws" target="_blank" style="display: inline-block; padding: 12px 24px; background-color: #24292e; color: white; text-decoration: none; border-radius: 6px; font-weight: bold; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <i class="fab fa-github" style="margin-right: 8px;"></i> View Source Code on GitHub
  </a>
</div>
