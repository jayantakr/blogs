---
layout: default
title: "BLOG"
---

# Blog Posts

{% for post in site.posts %}
  <h2><a href="{{ site.baseurl }}{{ post.url }}">Jekyll Blog</a></h2>  
{% endfor %}
<p>In this post I have setup my blog using Jekyll in GitHub page.</P>