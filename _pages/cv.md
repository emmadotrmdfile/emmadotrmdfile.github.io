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

  <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}" 
     class="btn btn-outline-primary"
     target="_blank">
    Download CV
  </a>

  <div class="cv-container">
    <iframe 
      src="{{ '/assets/pdf/cv.pdf#toolbar=0' | relative_url }}" 
      width="105%" 
      height="900px"
      style="border: none;">
    </iframe>
  </div>

</div>

<style>
.cv-container {
  width: 80%;
  margin: 0 auto;
  border: 2px solid var(--global-theme-color);
  border-radius: 12px;
  overflow: hidden;
}
</style>