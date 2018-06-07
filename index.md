---
layout: page
title: Blog
comments: true 
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>
      
      <a class="btn btn-success" type="button" href="{{ site.baseurl }}{{ post.url }}">Leer mas</a>

      <br>
    </article>
  {% endfor %}
</div>

