---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Check out my Google scholar and ResearchGate profiles for scholarly impact statistics and citation metrics.

{% include base_path %}

{% for post in site.publications reversed %}


{% if forloop.index ==1 %}


  {% capture firstyear %}{{ post.date | date: '%Y' }}{% endcapture %}
  <h2 id="{{ firstyear | slugify }}" class="archive__subtitle">{{ firstyear }}</h2>

{% elsif forloop.index >1 %}

  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}

  {% if year==firstyear %}
  {% else %}

  {% capture firstyear %}{{ post.date | date: '%Y' }}{% endcapture %}
  <h2 id="{{ firstyear | slugify }}" class="archive__subtitle">{{ firstyear }}</h2>
  {% endif %}

{% endif %}


  {% include archive-single.html %}
{% endfor %}
