---
layout: archive
permalink: /hardware/
author_profile: true
---

<!-- Top right GitHub link -->
<p style="font-size: 0.9em; margin-bottom: 5px; text-align: right;">
  <a href="https://github.com/YOUR-USERNAME/YOUR-HARDWARE-REPO" target="_blank" style="text-decoration: none; color: #0366d6;">
    <i class="fab fa-github"></i> Access Hardware Repository
  </a>
</p>

<!-- Main Title -->
<h1 style="margin-top: 0; margin-bottom: 10px;">
  PUMA Platform
</h1>
<h3 style="margin-top: 0; color: #666; font-weight: normal; margin-bottom: 30px;">
  Pulse United Multielectrode Analyzer
</h3>

<p style="text-align: justify; font-size: 1.1em; margin-bottom: 50px;">
<strong>PUMA</strong> is an open-source hardware platform conceived to revolutionize the electrical characterization of complex materials. Whether you are working with nanowire networks, memristive devices, or neuromorphic architectures, PUMA enables precise, fast, and highly automated multi-terminal measurements to streamline your research.
</p>

<!-- SECTION 1: Hardware Capabilities & Limits -->
<div style="display: flex; flex-wrap: wrap; gap: 30px; align-items: center; margin-bottom: 50px;">
  <div style="flex: 1; min-width: 300px;">
    <h2 style="margin-top: 0;">⚡ Technical Specifications & Limits</h2>
    <p style="text-align: justify;">The board architecture leverages a standard ESP32 synchronized with dedicated high-performance ADCs (AD7606) and DACs (MCP4922) to deliver precise control and extreme routing versatility across the sample.</p>
    <ul>
      <li style="margin-bottom: 10px;"><strong>16 Independent Electrodes:</strong> Full state independence for each of the 16 terminals, allowing highly localized dynamic routing via onboard CD4051 multiplexers.</li>
      <li style="margin-bottom: 10px;"><strong>Dual Stimulation Channels:</strong> Capability to drive the network with two distinct arbitrary signals simultaneously.</li>
      <li style="margin-bottom: 10px;"><strong>Voltage Range & Resolution:</strong> Output compliance ranging from 0 to 10 V with a fine-tuning resolution of 2.5 mV.</li>
      <li style="margin-bottom: 10px;"><strong>High-Speed Acquisition:</strong> Sampling rate of 200 kHz to accurately capture fast transient responses and physical learning events.</li>
      <li style="margin-bottom: 10px;"><strong>Configurable Load Resistors:</strong> Independent series resistors to ground for each electrode, manually selectable from 5 k&Omega; up to 10 M&Omega; to limit compliance currents.</li>
      <li><strong>Ultra-Low Leakage:</strong> Exceptional electrical isolation, ensuring negligible current leakage when terminals are switched to a floating (High-Z) state.</li>
    </ul>
  </div>
  <div style="flex: 1; min-width: 250px; text-align: center;">
    <img src="/images/placa_v1_3.png" alt="PUMA Custom PCB Board" style="width: 100%; max-width: 400px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <span style="font-size: 0.85em; color: #666; display: block; margin-top: 8px; font-style: italic;">PUMA custom PCB featuring 16 independent terminals.</span>
  </div>
</div>

<!-- SECTION 2: Software Interface -->
<div style="display: flex; flex-wrap: wrap; gap: 30px; align-items: center; margin-bottom: 50px; flex-direction: row-reverse;">
  <div style="flex: 1; min-width: 300px;">
    <h2 style="margin-top: 0;">🐍 User-Friendly Python Interface</h2>
    <p style="text-align: justify;">You don't need to be an embedded systems expert to get the most out of PUMA. The platform includes a seamless control interface developed entirely in Python.</p>
    <ul>
      <li style="margin-bottom: 10px;"><strong>Plug & Play Control:</strong> Ready-to-use scripts to easily configure voltage parameters, pulse widths, and sampling frequencies.</li>
      <li style="margin-bottom: 10px;"><strong>Experiment Automation:</strong> Program complex physical learning routines, associative memory protocols, or standard I-V sweeps with just a few lines of code.</li>
      <li><strong>Real-Time Analysis:</strong> Direct integration with standard scientific libraries (NumPy, Matplotlib) to visualize temporal dynamics and log data instantly.</li>
    </ul>
  </div>
  <div style="flex: 1; min-width: 250px; text-align: center;">
    <img src="/images/puma-software.jpg" alt="Python Interface for PUMA" style="width: 100%; max-width: 400px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <span style="font-size: 0.85em; color: #666; display: block; margin-top: 8px; font-style: italic;">Automated data acquisition and real-time visualization via Python.</span>
  </div>
</div>

<!-- SECTION 3: Open Source & Final Button -->
<div style="text-align: center; margin-top: 50px; padding: 30px; background-color: #f6f8fa; border-radius: 8px; border: 1px solid #e1e4e8;">
  <h2 style="margin-top: 0;">🛠️ 100% Open Source Hardware</h2>
  <p style="margin-bottom: 20px; font-size: 1.05em; max-width: 700px; margin-left: auto; margin-right: auto;">
    My core philosophy is that scientific development should be highly accessible. That is why PUMA is completely free to use. In the repository, you will find absolutely everything needed to replicate, modify, and deploy this tool in your own lab: from the full schematics and <strong>Gerber files</strong> for PCB manufacturing, to the complete microcontroller firmware and Python API.
  </p>
  <a href="https://github.com/YOUR-USERNAME/YOUR-HARDWARE-REPO" target="_blank" style="display: inline-block; padding: 12px 24px; background-color: #24292e; color: white; text-decoration: none; border-radius: 6px; font-weight: bold; box-shadow: 0 4px 6px rgba(0,0,0,0.1); margin-top: 10px;">
    <i class="fab fa-github" style="margin-right: 8px;"></i> Download Gerber Files & Source Code
  </a>
</div>
