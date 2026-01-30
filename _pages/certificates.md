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
  border: 2px solid #fff;
}

.cert-card img {
  width: 100%;
  border-radius: 8px;
  cursor: pointer;
  border: 1px solid #ccc;
}
</style>

<h1>🎓 Certificates & Professional Training</h1>

<div class="cert-grid">

{% include cert.html
   img="_certificates/CAMPus/TR_2025_CAMPus_Syllabus.pdf"
   title="CAMPus Program 2025"
   org="CAMPus"
   desc="Program Syllabus & Overview"
   pdf="_certificates/CAMPus/TR_2025_CAMPus_Syllabus.pdf"
%}

{% include cert.html
   img="_certificates/YZTA/TR_yzta_mezuniyet.jpg"
   title="YZTA AI & Technology Academy"
   org="YZTA"
   desc="Graduation & Technical Trainings"
   pdf="_certificates/YZTA/TR_yzta_mezuniyet.pdf"
%}

{% include cert.html
   img="_certificates/AspireLeaders/ENG_damla_elmali_alp_2025_certificate_of_completion_page-0001.jpg"
   title="Aspire Leaders Program"
   org="Aspire Institute"
   desc="Leadership, identity, global excellence"
   pdf="_certificates/AspireLeaders/ENG_damla_elmali_alp_2025_certificate_of_completion.pdf"
%}

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
