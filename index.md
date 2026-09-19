---
layout: home
---

## Featured Engineering Projects

<div class="projects-container">

  <!-- Project 1: SolidWorks V6 Engine -->
  <div class="project-card">
    <h3>SolidWorks V6 Engine Assembly</h3>
    <p><em>UC Riverside - Formula Society of Automotive Engineers (2026)</em></p>
    
    <!-- Image Carousel Placeholder using HTML details/tabs or simple gallery -->
    <div class="image-gallery">
      <img src="images/engine-main.png" alt="V6 Engine Assembly Main View" class="carousel-thumb" onclick="openModal(this.src)">
      <img src="images/engine-exploded.png" alt="V6 Engine Exploded View" class="carousel-thumb" onclick="openModal(this.src)">
      <img src="images/engine-parts.png" alt="Subassemblies" class="carousel-thumb" onclick="openModal(this.src)">
    </div>
    <p class="image-hint"><em>Click thumbnails to expand</em></p>

    <ul>
      <li>Modeled a fully assembled V6 engine in SolidWorks utilizing 30+ individual parts and complex subassemblies.</li>
      <li>Applied Design for Manufacturing (DFM) concepts and mechanical design principles under technical instruction.</li>
    </ul>
  </div>

  <hr>

  <!-- Project 2: Java Discord Bot -->
  <div class="project-card">
    <h3>Java Discord Bot</h3>
    <p><em>Personal Project</em></p>
    
    <div class="image-gallery">
      <img src="images/bot-interface.png" alt="Discord Bot Interface" class="carousel-thumb" onclick="openModal(this.src)">
      <img src="images/bot-code.png" alt="API Integration Code Snippet" class="carousel-thumb" onclick="openModal(this.src)">
    </div>
    <p class="image-hint"><em>Click thumbnails to expand</em></p>

    <ul>
      <li>Utilized core Java programming principles to build a responsive automated chat tool.</li>
      <li>Accessed external API information to dynamically deliver time/date data and fun facts about pet breeds.</li>
      <li>Undertook several hours of rigorous testing, debugging, and continuous updating.</li>
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

# Posts
