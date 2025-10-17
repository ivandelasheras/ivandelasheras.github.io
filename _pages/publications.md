---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

## Working Papers 

1. Young Local Politicians and Deforestation in the Brazilian Amazon (with [Ricardo Dahis](https://www.ricardodahis.com) and [Santiago Saavedra](https://sites.google.com/view/santiago-saavedra)) _May 2025_. **Revise & Resubmit at JAERE**

## Selected Work in Progress

1. _Income Shocks and Land Use: Disentangling Extensive and Intensive Margins_ (with [Alipio Ferreira](https://www.alipioferreira.com))
2. _Estimating the eﬀect of the past on economic decisions: crop choice persistence_

<!-- New style rendering if publication categories are defined 
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
-->




