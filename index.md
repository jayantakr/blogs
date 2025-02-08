---
layout: default
title: "BLOG"
---

# Latest Blog Posts

{% for post in site.posts %}
  <h2><a href="{{ site.baseurl }}{{ post.url }}">Jekyll Blog</a></h2>  
{% endfor %}
<p>This post is about how I was able to set up my Jekyll blog using Jekyll + GitHub-pages. It's from a perception of a person new to Jekyll.</p>