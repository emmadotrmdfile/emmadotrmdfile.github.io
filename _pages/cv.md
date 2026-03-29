---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/cv.pdf # you can also use external links here
cv_format: rendercv # options: rendercv, jsonresume
# description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
# toc:
#   sidebar: left
---

<div class="text-center">

  <!-- Download Button -->
  <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}" 
     class="cv-download"
     target="_blank">
    Download CV
  </a>

  <!-- PDF Container -->
  <div class="cv-container">
    <iframe 
      src="{{ '/assets/pdf/cv.pdf#toolbar=0' | relative_url }}" 
      width="110%" 
      height="900px"
      style="border: none;">
    </iframe>
  </div>

</div>

<style>
/* PDF container styling */
.cv-container {
  width: 90%;
  max-width: 900px;
  margin: 20px auto;
  border: 2px solid var(--global-theme-color);
  border-radius: 12px;
  overflow: hidden;
}

/* Download button styling */
.cv-download {
  display: inline-block;
  margin-bottom: 20px;
  padding: 10px 18px;
  border: 2px solid var(--global-theme-color);
  border-radius: 8px;
  text-decoration: none;
  color: var(--global-theme-color);
  font-weight: 500;
  transition: all 0.2s ease;
}

.cv-download:hover {
  background-color: var(--global-theme-color);
  color: var(--global-bg-color);
}
</style>