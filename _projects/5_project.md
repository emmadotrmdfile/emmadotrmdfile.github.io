---
layout: page
title: Consequences of Abortion Restrictions
description: An analysis in python looking at abortion policy in the U.S. 
img: assets/img/projects/p5_wt.png
img_hover: assets/img/projects/p5.png
importance: 5
category: academic
---

This is my first project in Python, and I decided to include it on my website as a keepsake. For this project, I analyzed the socioeconomic impacts of abortion restrictions using data from the [Institute for Women’s Policy Research (IWPR)](https://iwpr.org/2024-analysis-costs-of-reproductive-health-restrictions/) and KFF.

Since the overturning of reproductive rights in 2022, the United States has experienced significant divergence in abortion policies across states. This policy fragmentation presents an opportunity to examine the broader implications of abortion access, particularly regarding women’s workforce participation and state-level economic performance.

I imported the datasets into Jupyter Notebook and merged them. I then modeled the relationship between abortion restrictiveness and economic outcomes using best-fit exponential models for GDP and labor force loss. I also created projected models beyond the highest observed restrictiveness level (level 8), accounting for potential scenarios such as total abortion bans. The data includes observations from 2022 - 2024. 

This analysis addresses the question: How does abortion access impact women’s workforce participation and a state’s economy?

The results indicate a modest upward trend: as abortion restrictions increase, the associated economic costs also rise, though gradually. Specifically:

- Around 10.5% of the variation in labor force loss across states is explained by the restrictiveness of abortion laws.
- Around 10.4% of the variation in GDP loss across states is explained by these laws.

While these percentages may seem modest, they translate to substantial impacts on women’s economic participation and millions of dollars in lost productivity.

If you would like to see the code for this project, you can view it [here.](https://github.com/emmadotrmdfile/abor-python-analysis)

## Figures

<hr>

<div class="row align-items-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/p5_1.png" title="dot plot" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/p5_2.png" title="results figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row align-items-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/p5_3.png" title="results fig" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/p5_4.png" title="results figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Analysis Figures
</div>

