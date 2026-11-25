---
layout: home
---

## Featured Engineering Projects

[Resume (PDF)]({{ "/resume.pdf" | relative_url }})

<div class="projects-container">

  <!-- Project 1: Antweight Combat Robot -->
  <div class="project-card">
    <h3>Antweight Combat Robot</h3>
    <p><em>UC Riverside — Highlander Combat Robotics (2026)</em></p>

    <div class="image-gallery">
      <img src="images/combat-robot.jpg" alt="Antweight combat robot — 3D-printed chassis and wiring" class="carousel-thumb" onclick="openModal(this.src)">
    </div>
    <p class="image-hint"><em>Click thumbnail to expand</em></p>

    <ul>
      <li>Designed and built a 1-pound 3D-printed combat robot, modeling the chassis and components in Onshape.</li>
      <li>Wired and soldered the full electronics package: LiPo batteries, brushless motors, ESCs, and RC receiver.</li>
      <li>Integrated the weapon system with the drive electronics.</li>
      <li>The photo shows the build up close: 3D-printed chassis with brass heat-set inserts, drive motors, and the wiring harness packed into the 1-lb antweight limit.</li>
    </ul>
  </div>

  <hr>

  <!-- Project 2: Formula SAE Steering System -->
  <div class="project-card">
    <h3>Formula SAE Steering System</h3>
    <p><em>UC Riverside — Highlander Racing (2025)</em></p>

    <div class="image-gallery">
      <img src="images/fsae-chassis.png" alt="Formula SAE chassis and steering" class="carousel-thumb" onclick="openModal(this.src)">
      <img src="images/steering-wheel.png" alt="Formula SAE steering wheel" class="carousel-thumb" onclick="openModal(this.src)">
    </div>
    <p class="image-hint"><em>Click thumbnails to expand</em></p>

    <ul>
      <li>Modeled the Formula SAE steering system in SolidWorks.</li>
      <li>Member of Highlander Racing, UC Riverside's Formula SAE team, since January 2025.</li>
      <li>The steering system was modeled in SolidWorks as part of the full chassis assembly, with the wheel carrying the Highlander Racing mark.</li>
    </ul>
  </div>

  <hr>

  <!-- Project 3: SolidWorks V6 Engine -->
  <div class="project-card">
    <h3>SolidWorks V6 Engine Assembly</h3>
    <p><em>UC Riverside — Formula Society of Automotive Engineers (2026)</em></p>

    <div class="image-gallery">
      <img src="images/Engine.png" alt="V6 Engine Assembly" class="carousel-thumb" onclick="openModal(this.src)">
    </div>
    <p class="image-hint"><em>Click thumbnail to expand</em></p>

    <ul>
      <li>Modeled a fully assembled V6 engine in SolidWorks utilizing 30+ individual parts and complex subassemblies.</li>
      <li>Applied Design for Manufacturing (DFM) concepts and mechanical design principles under technical instruction.</li>
      <li>The render shows the full assembly, from the intake runners up top to the front pulley drive, with each system modeled as its own subassembly.</li>
    </ul>
  </div>

  <hr>

  <!-- Project 4: Java Discord Bot -->
  <div class="project-card">
    <h3>Java Discord Bot</h3>
    <p><em>Personal Project</em></p>

    <ul>
      <li>Utilized core Java programming principles to build a responsive automated chat tool.</li>
      <li>Accessed external API information to dynamically deliver time/date data and fun facts about pet breeds.</li>
      <li>Undertook several hours of rigorous testing, debugging, and continuous updating.</li>
      <li>Built around event-driven programming in Java — the bot listens for commands and replies with live data from external APIs.</li>
    </ul>
  </div>

</div>

<!-- Simple Lightbox Modal Container for Image Zooming/Carousel Effect -->
<div id="imageModal" class="modal" onclick="closeModal()">
  <span class="close">&times;</span>
  <img class="modal-content" id="modalImg">
</div>

<style>
  .image-gallery {
    display: flex;
    gap: 10px;
    margin: 15px 0 5px 0;
  }
  .carousel-thumb {
    width: 150px;
    height: 100px;
    object-fit: cover;
    cursor: pointer;
    border-radius: 4px;
    border: 1px solid #444;
    transition: transform 0.2s;
  }
  .carousel-thumb:hover {
    transform: scale(1.03);
  }
  .image-hint {
    font-size: 0.85rem;
    color: #888;
    margin-bottom: 15px;
  }
  /* Modal CSS */
  .modal {
    display: none;
    position: fixed;
    z-index: 1000;
    padding-top: 60px;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,0.85);
    text-align: center;
  }
  .modal-content {
    max-width: 80%;
    max-height: 80vh;
    margin: auto;
    display: block;
    border-radius: 6px;
  }
  .close {
    position: absolute;
    top: 20px;
    right: 35px;
    color: #f1f1f1;
    font-size: 40px;
    font-weight: bold;
    cursor: pointer;
  }
</style>

<script>
  function openModal(src) {
    document.getElementById("imageModal").style.display = "block";
    document.getElementById("modalImg").src = src;
  }
  function closeModal() {
    document.getElementById("imageModal").style.display = "none";
  }
</script>
