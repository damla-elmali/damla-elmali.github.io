---
layout: page
title: Certificates
permalink: /certificates/
---

<style>
.cert-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 24px;
  margin-top: 2rem;
}

.cert-card {
  border: 1px solid #ddd;
  border-radius: 10px;
  padding: 16px;
  background: #fff;
}

.cert-card img {
  width: 100%;
  border-radius: 8px;
  cursor: pointer;
  border: 1px solid #ccc;
}

.cert-card h3 {
  margin: 12px 0 4px;
}

.cert-card .org {
  font-weight: 600;
  color: #555;
}

.cert-card .desc {
  font-size: 0.95rem;
  color: #444;
}

.cert-card a {
  display: inline-block;
  margin-top: 6px;
}

#lightbox {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.85);
  justify-content: center;
  align-items: center;
  z-index: 9999;
}

#lightbox img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 12px;
}
</style>

<h1>🎓 Certificates & Professional Training</h1>

<div class="cert-grid">

<!-- CAMPus -->
<div class="cert-card">
  <img src="_certificates/CAMPus/TR_2025_CAMPus_Syllabus.pdf" onclick="openLightbox(this.src)">
  <h3>CAMPus Program 2025</h3>
  <p class="org">CAMPus</p>
  <p class="desc">Program Syllabus & Overview</p>
  <a href="_certificates/CAMPus/TR_2025_CAMPus_Syllabus.pdf" target="_blank">View PDF</a>
</div>

<!-- YZTA -->
<div class="cert-card">
  <img src="_certificates/YZTA/TR_yzta_mezuniyet.jpg" onclick="openLightbox(this.src)">
  <h3>YZTA AI & Technology Academy</h3>
  <p class="org">YZTA</p>
  <p class="desc">Graduation & Technical Trainings</p>
  <a href="_certificates/YZTA/TR_yzta_mezuniyet.pdf" target="_blank">Graduation PDF</a>
</div>

<!-- Aspire Leaders -->
<div class="cert-card">
  <img src="_certificates/AspireLeaders/ENG_damla_elmali_alp_2025_certificate_of_completion_page-0001.jpg" onclick="openLightbox(this.src)">
  <h3>Aspire Leaders Program</h3>
  <p class="org">Aspire Institute</p>
  <p class="desc">Leadership, identity, global excellence</p>
  <a href="_certificates/AspireLeaders/ENG_damla_elmali_alp_2025_certificate_of_completion.pdf" target="_blank">View PDF</a>
</div>

</div>

<div id="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img">
</div>

<script>
function openLightbox(src) {
  document.getElementById("lightbox-img").src = src;
  document.getElementById("lightbox").style.display = "flex";
}
function closeLightbox() {
  document.getElementById("lightbox").style.display = "none";
}
</script>
