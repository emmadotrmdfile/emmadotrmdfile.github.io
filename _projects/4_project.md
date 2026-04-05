---
layout: page
title: TRIP Causal Analysis
description: Does a proportionate number of women in parliaments have an impact on trans non-discrimination policy?
img: assets/img/projects/p4_.png
img_hover: assets/img/projects/p4.png
importance: 4
category: academic
---
<hr>

In 2024, I had the opportunity to take a doctoral-level course, *Quantitative Techniques in Public Policy and Political Science II*. I was trained in advanced causal inference from observable data, the methods were difference-in-differences, instrumental variables, fixed effects, bootstrapping, weighting, propensity score matching, and regression discontinuity design. In class, we applied each method to both simulated and real-world data, gaining hands-on experience with quantitative social science analysis. This course was foundational in shaping my interest in using quantitative methods to study social science questions, as reflected in my recent work at IPPSR.

For this project, I merged the [Trans Rights Indicator Project (TRIP)](https://www.myleswilliamson.net/trip-data) dataset with global data on women’s parliamentary representation from the [World Bank](https://data.worldbank.org/indicator/SG.GEN.PARL.ZS). The analysis spans 2000–2024 across all countries. The TRIP dataset includes 13 indicators capturing the legal protections and restrictions faced by transgender people worldwide. I focused on a single composite indicator, the TRIP score, which combines all measures into one score reflecting the overall legal environment for transgender rights. Using this measure, I examined the effect of women’s parliamentary representation on transgender policy outcomes. 

Given that my confounding variables were observed and influencing both treatment and outcome, I decided to use
weighting to balance the covariates between the treated and control groups so that they would be independent of potential
outcomes. By giving more weight to observations that are not “doing what they are supposed to do," it ensures that the estimated treatment effect is not confounded by differences in the observed covariates. 

The analysis suggests that for every one percentage point increase in the proportion of women in national parliaments, there is a corresponding 0.018 increase in protections for transgender rights. While this effect may appear modest, it is highly meaningful given the vulnerability of the affected population.

At the end of the semester, I presented this work at a poster session hosted by the PhD Political Science department, where I discussed my methodology and received feedback on ways to improve the analysis. The code and replication materials for this project are available in my [repository](https://github.com/emmadotrmdfile/pls-802).
 
## Poster

<hr>

<div class="row justify-content-sm-center">
  <div class="col-10 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/trans poster.png" title="poster" 
        class="img-fluid rounded z-depth-1" %}
    </div>
</div>