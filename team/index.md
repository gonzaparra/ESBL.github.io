---
title: Team
nav:
  order: 3
  tooltip: About our team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>

## Current Members

We are a group of diverse and enthusiastic scientists from different levels, backgrounds and nationalities. 

If you're interested in joining our team , please reach out!

{% include team-list.html role="principal-investigator" %}
{% include team-list.html %}

<!-- section break -->

## Alumni
We are grateful to all the people who have contributed to our research at any point.

{% capture html %}
{% include team-list.html role="pi" group="alum" mini="true" %}
{% include team-list.html role="phd_g" group="alum" mini="true" %}
{% include team-list.html role="undergrad" group="alum" mini="true" %}
{% endcapture %}

{% include centerer.html html=html %}
