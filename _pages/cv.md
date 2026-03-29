---
layout: cv
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
     class="btn btn-primary mb-4" 
     target="_blank">
    Download CV
  </a>

  <div style="display: flex; justify-content: center;">
    <iframe 
      src="{{ '/assets/pdf/cv.pdf' | relative_url }}" 
      width="80%" 
      height="800px"
      style="border: none;">
    </iframe>
  </div>

</div>