---
layout: page
title: "影评书评"
description: "电影书籍评论"
pos: "5"
---
<h3 class="section-heading text-center">影评</a></h3>
<div class="tiles">
{% for post in site.categories.movies %} 
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
{% endfor %}
</div><!-- /.tiles -->
<div class="tiles">
{% for post in site.categories.books %} 
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
{% endfor %}
</div><!-- /.tiles -->
