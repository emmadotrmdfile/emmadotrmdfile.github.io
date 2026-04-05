---
layout: page
title: Gendered Healthcare Policy Project
description: Novel dataset on gendered healthcare policy with causal analysis of women’s representation
img: assets/img/projects/p1_without_writing.png
img_hover: assets/img/projects/p1_with.png
importance: 1
category: work
related_publications: false
---
<hr>
This is my most recent project at the Institute of Public Policy and Social Research, called the Gendered Health Policy Project (GHPP). My co-author, [Chloe (Lola) Browne](https://sites.google.com/view/lbrownec/about), and I constructed a panel dataset on insurance mandates related to women’s, men’s, and transgender healthcare, along with the gender composition of U.S. state legislatures from 2010 to 2024. Using this dataset, we applied causal inference methods to examine how women’s representation in U.S. political institutions shapes the passage of gender-specific healthcare policies. More broadly, we aimed to understand the impact of women’s political representation on healthcare policy outcomes.

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
    Me presenting at MSU's Undergraduate Research and Arts Forum (where I won first place) and Mid-Sure.
</div>

## GHPP Dataset

<hr>

The GHPP dataset includes multiple indicators relating to gender-specific insurance mandates:

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

In light of observed policy restrictions, the dataset also includes three limitation categories: abortion coverage limits, erectile dysfunction coverage limits, and gender-affirming care coverage limits. 

Because no existing dataset catalogues these insurance mandates, legislative text was collected directly from state-level bill archives using LegiScan. We used keyword searches that yielded the raw text of thousands of bills, which we then manually reviewed to identify legislation mandating essential health insurance coverage for the policies of interest. We read each qualifying bill to verify statutory language before being coded as a binary indicator, where “1” denotes passage in a given state-year and “0” otherwise. At the same time, we also compiled existing data on the gender composition of state legislatures.

When this was completed, we merged the policy and gender composition datasets by state and year resulting in a panel dataset of all fifty states from 2010 to 2024. The final dataset includes binary indicators for the individual policies listed above, aggregated gender-specific policy variables, and measures of women’s legislative representation. 

## Methods & Findings

<hr>
After constructing the dataset, we applied causal inference methods to examine whether women’s representation influences the passage of gender-specific healthcare policies. Using a two-way fixed effects model, we estimated the effect of changes in women’s representation on policy adoption across states and over time. 

We find that increases in women’s representation are associated with a higher likelihood of enacting women’s health-related policies. The effects are smaller for men’s healthcare policies. We observe a similar positive relationship for transgender healthcare policies, suggesting that women legislators play a broader role in advancing gender-related healthcare policy. 

<div class="row align-items-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/dag.png" title="dag" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/women.jpeg" title="results figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row align-items-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/men.jpeg" title="results fig" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/trans.jpeg" title="results figure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Directed Acyclic Graph and Results Figures.
</div>

## Cosponsor Dataset 

<hr>

As a supplementary extension of this project, we constructed an additional dataset on the demographics of bill cosponsors for the policies in our main dataset. This includes counts by gender, party, and race for legislators supporting each policy. While not part of the primary analysis, these data provide suggestive evidence on who is supporting and advancing gender-related healthcare policies, offering insight into potential mechanisms underlying our main findings. The bar plots below were made through this data. 

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
    Cosponsor Figures. Made in R.
</div>

## Conferences & Publication 

<hr>

We have presented this research at two undergraduate forums now, [UURAF](https://www.instagram.com/reel/DIT3SWEA-M1/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA%3D%3D) and Mid-Sure, and will present a reformulated version at Loyola’s State Politics and Policy Conference in June! The working version of this paper can be viewed [here](/publications/).

## Repository

<hr>

If you would like to use the datasets or the codebook, my repository for this project can be found [here.](https://github.com/emmadotrmdfile/gendered-healthcare-policy-project/) My [paper](/publications/) for this project also provides a very detailed explanation of the variables included in the dataset and why. 

