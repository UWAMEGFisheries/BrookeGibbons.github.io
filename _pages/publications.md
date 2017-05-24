---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}

{% if forloop.first == true %}
{% capture yearindex %}{{ post.date | date: '%Y' }}{% endcapture %}
{% endif %}

{% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}

{% if year == yearindex %}
{% else %}

  <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
  {% endif %}
  
  {% include archive-single.html %}
{% endfor %}
