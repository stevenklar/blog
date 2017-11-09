---
layout: post
title:  "blubb..."
categories: draft
permalink: blubb
---
This is my draft
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

{% for post in site.posts %}
{% if post.categories == 'draft' %}
<li>
  <a href="{{ post.url }}">{{ post.title }} - {{ post.categories }}</a>
</li>
{% endif %}
{% endfor %}

And so on...
