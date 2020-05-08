---
permalink: /
title: "Home"
layout: splash
---
<ul class="social-icons">
  {% if site.data.ui-text[site.locale].follow_label %}
    <strong>{{ site.data.ui-text[site.locale].follow_label }}</strong>
  {% endif %}

  {% if site.author.links %}
    {% for link in site.author.links %}
      {% if link.label and link.url %}
        <a href="{{ link.url }}" rel="nofollow noopener noreferrer"><i class="{{ link.icon | default: 'fas fa-link' }}" aria-hidden="true"></i> {{ link.label }}</a>
      {% endif %}
    {% endfor %}
  {% endif %}

  
</ul>


Splash with sidebar, prueba 2
Home
