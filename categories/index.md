---
layout: default
permalink: categories/
---

<section class="story-section section section-on-bg">

<h2>All Resource Posts</h2>

<ul>
  {% for post in site.posts %}
    {% if post.url %}
        <li><a href="{{site.baseurl}}/{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

</section>
