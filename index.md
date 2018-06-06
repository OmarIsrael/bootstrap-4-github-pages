---
layout: page
title: Blog 
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a class="btn btn-primary btn-lg" href="{{ site.baseurl }}{{ post.url }}" role="button">Leer mas</a>
    </article>
  {% endfor %}
</div>

