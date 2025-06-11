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

<!-- Optional: show other groups individually -->
{% include team-list.html role="postdoc" %}
{% include team-list.html role="phd" %}
{% include team-list.html role="undergrad" %}

<!-- section break -->

## Alumni
We are grateful to all the people who have contributed to our research at any point.

{% capture html %}
{% include team-list.html role="pi" group="alum" mini="true" %}
{% include team-list.html role="phd" group="alum" mini="true" %}
{% include team-list.html role="undergrad" group="alum" mini="true" %}
{% endcapture %}

{% include centerer.html html=html %}
