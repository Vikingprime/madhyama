---
layout: page
title: Contributors
hero_height: is-half-height
permalink: /contributors/
---

<h1>Authors</h1>

<div class="columns is-multiline">
{% for author in site.authors %}
    <div class="column is-12 is-clipped"> 
     {% include author-card.html %} 
    </div>
{% endfor %}
</div>