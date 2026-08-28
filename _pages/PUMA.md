---
layout: archive
permalink: /hardware/
author_profile: true
---

<!-- Pequeño enlace superior -->
<p style="font-size: 0.9em; margin-bottom: 5px; text-align: right;">
  <a href="https://github.com/TU-USUARIO/TU-REPOSITORIO-HARDWARE" target="_blank" style="text-decoration: none; color: #0366d6;">
    <i class="fab fa-github"></i> Acceder al repositorio de Hardware
  </a>
</p>

<!-- Título principal -->
<h1 style="margin-top: 0; margin-bottom: 10px;">
  PUMA Platform
</h1>
<h3 style="margin-top: 0; color: #666; font-weight: normal; margin-bottom: 30px;">
  Pulse United Multielectrode Analyzer
</h3>

<p style="text-align: justify; font-size: 1.1em; margin-bottom: 50px;">
Diseñada y desarrollada por Juan Ignacio Diaz Schneider, <strong>PUMA</strong> es una plataforma de hardware de código abierto (Open Source) concebida para revolucionar la caracterización eléctrica de materiales complejos. Ya sea que trabajes con redes de nanohilos, dispositivos memristivos o arquitecturas neuromórficas, PUMA te permite realizar mediciones multipunta de forma precisa, rápida y altamente automatizada.
</p>

<!-- SECCIÓN 1: Características Principales -->
<div style="display: flex; flex-wrap: wrap; gap: 30px; align-items: center; margin-bottom: 50px;">
  <div style="flex: 1; min-width: 300px;">
    <h2 style="margin-top: 0;">⚡ Capacidades de Hardware</h2>
    <p style="text-align: justify;">El corazón de la placa fue diseñado para maximizar la velocidad de adquisición y la versatilidad de enrutamiento sin sacrificar la fidelidad de la señal.</p>
    <ul>
      <li style="margin-bottom: 10px;"><strong>Matriz Multipunta:</strong> Integración de multiplexores de alta velocidad para enrutar señales a través de múltiples terminales simultáneamente.</li>
      <li style="margin-bottom: 10px;"><strong>Alta Precisión:</strong> Equipado con conversores analógico-digitales (ADCs) y digital-analógicos (DACs) dedicados para aplicar pulsos exactos y medir respuestas transitorias.</li>
      <li><strong>Arquitectura Robusta:</strong> Impulsada por un microcontrolador <strong>ESP32 estándar</strong>, garantizando un procesamiento rápido, bajo costo y máxima compatibilidad.</li>
    </ul>
  </div>
  <div style="flex: 1; min-width: 250px; text-align: center;">
    <!-- Imagen sugerida: Una buena foto cenital de tu placa PCB real -->
    <img src="/images/puma-board.jpg" alt="PUMA Custom PCB Board" style="width: 100%; max-width: 400px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <span style="font-size: 0.85em; color: #666; display: block; margin-top: 8px; font-style: italic;">Placa PCB personalizada PUMA (Pulse United Multielectrode Analyzer).</span>
  </div>
</div>

<!-- SECCIÓN 2: Software e Interfaz -->
<div style="display: flex; flex-wrap: wrap; gap: 30px; align-items: center; margin-bottom: 50px; flex-direction: row-reverse;">
  <div style="flex: 1; min-width: 300px;">
    <h2 style="margin-top: 0;">🐍 Interfaz Amigable en Python</h2>
    <p style="text-align: justify;">No necesitás ser un experto en sistemas embebidos para sacar el máximo provecho de PUMA. La plataforma incluye una interfaz desarrollada íntegramente en Python.</p>
    <ul>
      <li style="margin-bottom: 10px;"><strong>Control Plug & Play:</strong> Scripts listos para usar que permiten configurar parámetros de voltaje, ancho de pulso y frecuencias de muestreo.</li>
      <li style="margin-bottom: 10px;"><strong>Automatización de Experimentos:</strong> Programá rutinas complejas de aprendizaje físico (physical learning) o barridos I-V con unas pocas líneas de código.</li>
      <li><strong>Análisis en Tiempo Real:</strong> Integración directa con bibliotecas científicas (NumPy, Matplotlib) para visualizar dinámicas y guardar datos al instante.</li>
    </ul>
  </div>
  <div style="flex: 1; min-width: 250px; text-align: center;">
    <!-- Imagen sugerida: Captura de pantalla de un gráfico generado por Python o la terminal -->
    <img src="/images/puma-software.jpg" alt="Python Interface for PUMA" style="width: 100%; max-width: 400px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <span style="font-size: 0.85em; color: #666; display: block; margin-top: 8px; font-style: italic;">Adquisición y visualización de datos automatizada vía Python.</span>
  </div>
</div>

<!-- SECCIÓN 3: Open Source y Botón Final -->
<div style="text-align: center; margin-top: 50px; padding: 30px; background-color: #f6f8fa; border-radius: 8px; border: 1px solid #e1e4e8;">
  <h2 style="margin-top: 0;">🛠️ 100% Open Source Hardware</h2>
  <p style="margin-bottom: 20px; font-size: 1.05em; max-width: 700px; margin-left: auto; margin-right: auto;">
    Mi filosofía es que el desarrollo científico debe ser accesible. Por eso, PUMA es de uso libre. En el repositorio vas a encontrar absolutamente todo lo necesario para replicar, modificar y utilizar esta herramienta en tu propio laboratorio: desde los esquemáticos y <strong>archivos Gerber</strong> para mandar a fabricar tu propio PCB, hasta el código fuente completo del microcontrolador y la API de Python.
  </p>
  <a href="https://github.com/TU-USUARIO/TU-REPOSITORIO-HARDWARE" target="_blank" style="display: inline-block; padding: 12px 24px; background-color: #24292e; color: white; text-decoration: none; border-radius: 6px; font-weight: bold; box-shadow: 0 4px 6px rgba(0,0,0,0.1); margin-top: 10px;">
    <i class="fab fa-github" style="margin-right: 8px;"></i> Descargar Archivos Gerber y Código
  </a>
</div>
