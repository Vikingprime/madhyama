---
title: Welcome
subtitle: A lens into various philosophical, political, and religious viewpoints from across the spectrum; sometimes controversial, other times mainstream, ideas are often presented with an Indic twist.
layout: page
hero_image: assets/images/lotussmall.jpg
hero_darken: true
hero_link: blog/
hero_link_text: Explore
menubar_toc: false
show_sidebar: true
---
<p class="title is-4">Selected Posts</p>

<div class="columns is-multiline">
    {% for post in site.posts %}
    <div class="column is-12">
        {% if post.selected %}
        {% include post-card.html %}
        {% endif %}
    </div>
    {% endfor %}
</div>
