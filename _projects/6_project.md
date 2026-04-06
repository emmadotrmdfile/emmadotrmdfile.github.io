---
layout: page
title: Analyzing and Visualizing Data in Politics
description: Two of my first projects in R
img: assets/img/projects/p6_w.png
img_hover: assets/img/projects/p6_wo.png
importance: 6
category: academic
---
<hr>

In 2023, I completed two of my first projects in R as part of a data visualization course.

The first project focused on reproductive rights and analyzed protest activity related to these issues. Using data from the [Crowd Counting Consortium](https://ash.harvard.edu/programs/crowd-counting-consortium/), I filtered events to those related to “women,” “women’s issues,” and “reproductive rights” to examine patterns in protest activity.

The second project used the [TRIP](https://www.myleswilliamson.net/trip-data) dataset to explore the legal protections afforded to transgender individuals across countries, highlighting both areas of protection and gaps in policy coverage worldwide.

To produce these reports, I used a LaTeX template, integrating figures and written analysis to create the final documents shown below. If you are interested in the code or replication materials, they are available [here.](https://github.com/emmadotrmdfile/pls-397/tree/main)

## Files

<hr>

<div class="pdf-row">

  <!-- PDF 1 -->
  <div class="pdf-container text-center">
    
    <a href="{{ '/assets/pdf/midterm_huizenga.pdf' | relative_url }}" 
       class="cv-download"
       target="_blank">
      Download The Recrudesence of Reproductive Justice
    </a>

    <div class="pdf-frame">
      <iframe 
        src="{{ '/assets/pdf/midterm_huizenga.pdf#toolbar=0' | relative_url }}" 
        width="100%" 
        height="700px"
        style="border: none;">
      </iframe>
    </div>

  </div>

  <!-- PDF 2 -->
  <div class="pdf-container text-center">
    
    <a href="{{ '/assets/pdf/final_huizenga.pdf' | relative_url }}" 
       class="cv-download"
       target="_blank">
      Download The Unique Challenges of Trans Identity
    </a>

    <div class="pdf-frame">
      <iframe 
        src="{{ '/assets/pdf/final_huizenga.pdf#toolbar=0' | relative_url }}" 
        width="100%" 
        height="700px"
        style="border: none;">
      </iframe>
    </div>

  </div>

</div>

<style>
    
/* Row layout */
.pdf-row {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
  width: 100%;
}

/* Container */
.pdf-container {
  flex: 1 1 48%;
  max-width: none;
}

/* Border around PDF */
.pdf-frame {
  border: 2px solid var(--global-theme-color);
  border-radius: 12px;
  overflow: hidden;
}

/* Button styling */
.cv-download {
  display: inline-block;
  margin-bottom: 12px;
  padding: 8px 16px;
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

