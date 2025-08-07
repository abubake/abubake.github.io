---
layout: page
title: Blog
permalink: /blog/
---

<h1>Technical Insights & Creative Writing</h1>
<p>Thoughts on ML/robotics and occasional short stories</p>

<div class="blog-posts">
  {% for post in site.posts %}
  <div class="post-item">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <div class="post-meta">
      <span>{{ post.date | date: "%B %d, %Y" }}</span> • 
      <span>{{ post.categories | join: ', ' }}</span>
    </div>
    <p>{{ post.excerpt | strip_html | truncatewords: 50 }}</p>
  </div>
  <hr>
  {% endfor %}
</div>