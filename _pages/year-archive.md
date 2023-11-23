---
layout: archive
permalink: /year-archive/
title: "Code & Data"
author_profile: true
redirect_from:
  - /wordpress/blog-posts/
---

----

### An empirical approximation of the effects of trade sanctions with an application to Russia (2023)

The replication package for all tables and figures:

- The codes are available from [Zenodo](https://doi.org/10.5281/zenodo.10184324) and also this [GitHub repository](https://github.com/laurentpauwels/sanctionpaper).

- The data are available from [Zenodo](https://doi.org/10.5281/zenodo.10184324).

----

### Trade Sanction Dashboard: exposure.trade

The online Dashboard <https://exposure.trade> is based on this core code available on [GitHub](https://github.com/laurentpauwels/sanctiondashboard) and these [data](https://drive.google.com/drive/u/1/folders/1_SH2RaFT4RN5Mwa2SYWzUfHm8LzAU2WK). The data and code computes an empirical approximation to the costs of trade sanctions as displayed on the dashboard.
  
---- 

### Optimal forecast combination with mean absolute error loss (2022) 

This [GitHub repository](https://github.com/laurentpauwels/maeloss) contains codes, data, and other supplementary materials to the paper.

----

### Do external pressures affect the Renminbi exchange rate? (2012)

The data for this paper is available soon


----

<!-- {% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %} -->
