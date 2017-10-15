---
id: 71
title: Posts
date: 2014-07-24T10:05:53+00:00
author: Duncan Leo
layout: page
---

<div class="home">
  <ul class="post-list">
    {% for post in site.posts %}
      {% include post_preview.html %}
    {% endfor %}
  </ul>

  <a href="{{ "/feed.xml" | relative_url }}">RSS feed</a>

</div>  
