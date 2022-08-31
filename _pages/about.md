---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}



{% include_relative includes/intro.md %}

{% include_relative includes/pub.md %}

{% include_relative includes/award.md %}

{% include_relative includes/work.md %}


<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=USVT5ZdiMifi_f-uIMrY3tmJJC5s1RLU2rz5sVs8mjY&cl=ffffff&w=a"></script>