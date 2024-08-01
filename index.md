---
layout: home

language: en
language_reference: index
---

![]({{"/assets/img/logo.png" | relative_url }} )

{% assign posts=site.posts | where: "language", page.language %}

<ul class="post-item-list">
  {% for post in posts %}
    <li class="post-item">
        <a class="post-item-title" href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }} <a class="post-item-excerpt" href="{{ post.url }}">read more</a>
    </li>
  {% endfor %}
</ul>

