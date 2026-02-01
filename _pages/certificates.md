---
layout: page
title: "Certificates & Professional Training"
permalink: /certificates/
author_profile: true
---

<style>
/* Main container */
.cert-section {
  margin: 2rem 0 3rem 0;
}

.cert-section h2 {
  color: #2c3e50;
  border-bottom: 3px solid #3498db;
  padding-bottom: 0.5rem;
  margin-bottom: 1.5rem;
  font-size: 1.8rem;
}

.cert-section h3 {
  color: #34495e;
  font-size: 1.3rem;
  margin-bottom: 1rem;
}

/* Grid layout */
.cert-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin-bottom: 2rem;
}

/* Certificate cards */
.cert-card {
  border: 1px solid #e1e8ed;
  border-radius: 12px;
  padding: 1.2rem;
  background: #fff;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  transition: all 0.3s ease;
  display: flex;
  flex-direction: column;
}

.cert-card:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
  transform: translateY(-2px);
}

/* Image preview */
.cert-preview {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 8px;
  cursor: pointer;
  border: 1px solid #ddd;
  margin-bottom: 1rem;
  transition: opacity 0.3s ease;
}

.cert-preview:hover {
  opacity: 0.9;
}

/* Card content */
.cert-content {
  flex: 1;
  display: flex;
  flex-direction: column;
}

.cert-title {
  font-size: 1.1rem;
  font-weight: 600;
  color: #2c3e50;
  margin: 0 0 0.5rem 0;
}

.cert-org {
  font-weight: 600;
  color: #7f8c8d;
  font-size: 0.9rem;
  margin-bottom: 0.3rem;
}

.cert-desc {
  font-size: 0.9rem;
  color: #555;
  margin-bottom: 1rem;
  flex: 1;
}

.cert-date {
  font-size: 0.85rem;
  color: #95a5a6;
  font-style: italic;
  margin-bottom: 0.8rem;
}

/* Download button */
.cert-download {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  padding: 0.5rem 1rem;
  background: #3498db;
  color: white !important;
  text-decoration: none !important;
  border-radius: 6px;
  font-size: 0.9rem;
  transition: background 0.3s ease;
  align-self: flex-start;
}

.cert-download:hover {
  background: #2980b9;
}

/* Lightbox */
#lightbox {
  display: none;
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.9);
  justify-content: center;
  align-items: center;
  z-index: 9999;
  cursor: pointer;
}

#lightbox img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 8px;
  box-shadow: 0 0 30px rgba(255,255,255,0.2);
}

/* Responsive */
@media (max-width: 768px) {
  .cert-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<!-- CAMPus Programs -->
<div class="cert-section">
  <h2>🏕️ CAMPus - Competitive Analysis & Management Program</h2>
  <div class="cert-grid">
    
    <div class="cert-card">
      <img src="{{ site.baseurl }}/certificates/CAMPus/TR_DAMLAELMALI_CAMPus_Katilim.jpg" 
           alt="CAMPus Participation Certificate" 
           class="cert-preview"
           onclick="openLightbox(this.src)">
      <div class="cert-content">
        <h3 class="cert-title">CAMPus Program Participation</h3>
        <p class="cert-org">CAMPus</p>
        <p class="cert-date">2025</p>
        <p class="cert-desc">Intensive program focused on competitive analysis, strategic management, and business development methodologies.</p>
        <a href="{{ site.baseurl }}/certificates/CAMPus/TR_DAMLAELMALI_CAMPus_Katilim.pdf" 
           class="cert-download" 
           target="_blank">
          📄 View Certificate (PDF)
        </a>
      </div>
    </div>

    <div class="cert-card">
      <img src="{{ site.baseurl }}/certificates/CAMPus/TR_2025_CAMPus_Syllabus.jpg" 
           alt="CAMPus Syllabus" 
           class="cert-preview"
           onclick="openLightbox(this.src)">
      <div class="cert-content">
        <h3 class="cert-title">CAMPus Program Syllabus</h3>
        <p class="cert-org">CAMPus</p>
        <p class="cert-date">2025</p>
        <p class="cert-desc">Comprehensive program curriculum covering competitive strategy, market analysis, and management frameworks.</p>
        <a href="{{ site.baseurl }}/certificates/CAMPus/TR_2025_CAMPus_Syllabus.pdf" 
           class="cert-download" 
           target="_blank">
          📄 View Syllabus (PDF)
        </a>
      </div>
    </div>

  </div>
</div>

<!-- YZTA -->
<div class="cert-section">
  <h2>🤖 YZTA - AI & Technology Academy</h2>
  <div class="cert-grid">
    
    <div class="cert-card">
      <img src="{{ site.baseurl }}/certificates/YZTA/TR_yzta_mezuniyet.jpg" 
           alt="YZTA Graduation Certificate" 
           class="cert-preview"
           onclick="openLightbox(this.src)">
      <div class="cert-content">
        <h3 class="cert-title">YZTA Graduation Certificate</h3>
        <p class="cert-org">YZTA - Yapay Zeka ve Teknoloji Akademisi</p>
        <p class="cert-date">2024</p>
        <p class="cert-desc">Comprehensive training in artificial intelligence, machine learning, and emerging technologies.</p>
        <a href="{{ site.baseurl }}/certificates/YZTA/TR_yzta_mezuniyet.pdf" 
           class="cert-download" 
           target="_blank">
          📄 View Certificate (PDF)
        </a>
      </div>
    </div>

  </div>
</div>

<!-- Aspire Leaders -->
<div class="cert-section">
  <h2>🌟 Aspire Leaders Program</h2>
  <div class="cert-grid">
    
    <div class="cert-card">
      <img src="{{ site.baseurl }}/certificates/AspireLeaders/ENG_damla_elmali_alp_2025_certificate_of_completion_page-0001.jpg" 
           alt="Aspire Leaders Certificate" 
           class="cert-preview"
           onclick="openLightbox(this.src)">
      <div class="cert-content">
        <h3 class="cert-title">Aspire Leaders Program - Certificate of Completion</h3>
        <p class="cert-org">Aspire Institute</p>
        <p class="cert-date">2025</p>
        <p class="cert-desc">Leadership development program focusing on identity, global excellence, and strategic thinking.</p>
        <a href="{{ site.baseurl }}/certificates/AspireLeaders/ENG_damla_elmali_alp_2025_certificate_of_completion.pdf" 
           class="cert-download" 
           target="_blank">
          📄 View Certificate (PDF)
        </a>
      </div>
    </div>

  </div>
</div>

<!-- Lightbox -->
<div id="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img" alt="Certificate preview">
</div>

<script>
function openLightbox(src) {
  document.getElementById("lightbox-img").src = src;
  document.getElementById("lightbox").style.display = "flex";
}

function closeLightbox() {
  document.getElementById("lightbox").style.display = "none";
}

// ESC tuşu ile kapatma
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') {
    closeLightbox();
  }
});
</script>
```

## ⚠️ ÖNEMLİ: Dosya Yapısı

Sertifikalarınızın şu yapıda olması gerekiyor:
```
damla-elmali.github.io/
├── certificates/
│   ├── CAMPus/
│   │   ├── TR_2025_CAMPus_Syllabus.pdf
│   │   ├── TR_2025_CAMPus_Syllabus.jpg (OLUŞTURMANIZ GEREKECEK)
│   │   ├── TR_DAMLAELMALI_CAMPus_Katilim.jpg
│   │   └── TR_DAMLAELMALI_CAMPus_Katilim.pdf
│   ├── YZTA/
│   │   ├── TR_yzta_mezuniyet.jpg
│   │   └── TR_yzta_mezuniyet.pdf
│   └── AspireLeaders/
│       ├── ENG_damla_elmali_alp_2025_certificate_of_completion_page-0001.jpg
│       └── ENG_damla_elmali_alp_2025_certificate_of_completion.pdf