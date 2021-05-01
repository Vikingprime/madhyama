---
layout: page
title: Contributors
hero_height: is-half-height
---

<h1>Authors</h1>

<div class="columns is-multiline">
{% for author in site.authors %}
    <div class="column is-12"> 
     {% include author-card.html %} 
    </div>
{% endfor %}
</div>