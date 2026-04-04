---
layout: page
title: Beyond The ACA
description: A causal inference analysis exploring the effects of women's representation
img: assets/img/projects/p1_without_writing.png
img_hover: assets/img/projects/p1_with.png
importance: 1
category: work
related_publications: false
---
This is my most recent project at the Institute of Public Policy and Social Research. My co-author, [Chloe (Lola) Browne](https://sites.google.com/view/lbrownec/about), and I constructed a panel dataset on insurance mandates related to women’s, men’s, and transgender healthcare, along with the gender composition of U.S. state legislatures from 2010 to 2024. Using this dataset, we applied causal inference methods to examine how women’s representation in U.S. political institutions shapes the passage of gender-specific healthcare policies. More broadly, we aimed to understand the impact of women’s political representation on healthcare policy outcomes.

<div class="row align-items-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/pres.JPG" title="presentation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/reward.png" title="award photo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/pres_mid.jpeg" title="presentation figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Me presenting at MSU's Undergraduate Research and Arts Forum (UURAF) and Mid-Sure, where I won first place!
</div>

## Dataset

To assess whether a policy was passed in a given state-year, we used LegiScan to obtain the full text of thousands of bills through keyword searches. We then manually reviewed each bill to verify whether it enacted a relevant policy. At the same time, we also compiled existing data on the gender composition of state legislatures. When this was completed, we merged these sources to construct the final state-year panel dataset. 

The dataset includes information on insurance mandates related to:

- Women-Friendly Policy
    - Contraceptives
    - Abortion
    - Fertility treatments
- Men-Friendly Policy
    - Vasectomies
    - Erectile dysfunction treatments
    - Prostate cancer screenings
- Transgender-Friendly Policy
    - Gender-affirming surgery
    - Hormone therapy 

## Methods & Findings

- Using a two-way fixed effects model, we estimated the effect of women’s representation on the passage of gender-specific healthcare policies across states and over time
- We find that increases in women’s representation are associated with a higher likelihood of enacting women’s health-related policies
- The effects are smaller for men’s healthcare policies
- We observe a similar positive relationship for transgender healthcare policies, suggesting that women legislators play a broader role in advancing gender-related healthcare policy 

<div class="row align-items-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/poster.jpg" title="presentation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/results_plot_MID.png" title="results figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    My poster and results figure used in UURAF
</div>

## Cosponsor data

As a supplementary extension of this project, we constructed an additional dataset on the demographics of bill cosponsors for the policies in our main dataset. This includes counts by gender, party, and race for legislators supporting each policy. While not part of the primary analysis, these data provide suggestive evidence on who is supporting and advancing gender-related healthcare policies, offering insight into potential mechanisms underlying our main findings. The bar plots above were made through this data. 

<div class="row align-items-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/fig6.png" title="results figure" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/fig7.png" title="cosponsor figure" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/fig8.png" title="cosponsor figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Cosponsor figures I made in RStudio
</div>

## Conferences & Publication 

We have presented this research at two undergraduate forums now, [UURAF](https://www.instagram.com/reel/DIT3SWEA-M1/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA%3D%3D) and Mid-Sure, and will present a reformulated version at Loyola’s State Politics and Policy Conference in June! The working version of this paper can be viewed [here](/publications/).

## Repository

The datasets and codebook can be found [here.](https://github.com/emmadotrmdfile/Beyond_the_ACA/)

