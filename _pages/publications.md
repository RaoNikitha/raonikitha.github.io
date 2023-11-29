---
layout: archive
title: "PUBLICATIONS"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=33De4NEAAAAJ&hl=en">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
    {% if post.venue != '' %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}
<br>

{% unless page.header.overlay_color or page.header.overlay_image %}
  <h1 class="page__title">PREPRINTS</h1>
{% endunless %}

{% for post in site.publications reversed %}
    {% if post.venue == '' %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}
<br>

