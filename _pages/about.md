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


<span class='anchor' id='about-me'></span>

{% include_relative sections/intro.md %}

{% include_relative sections/news.md %}

<!-- {% include_relative sections/publications.md %} -->

{% include_relative sections/honors.md %}

{% include_relative sections/education.md %}

{% include_relative sections/projects.md %}

{% include_relative sections/skills.md %}

{% include_relative sections/leadership.md %}
