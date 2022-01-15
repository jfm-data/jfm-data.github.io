---
layout: page
title: Personal Blog
subtitle: Some shared thoughts...
---

<div>
{% assign postsCategory = site.posts | group_by_exp:"post", "post.categories"  %}
{% for category in postsCategory %}
<h4 class="post-teaser__month">
<code>
{% if category.name %} 
{{ category.name }}
</code>
 
{% else %} 
{{ Print }} 
{% endif %}
---
</h4>
<ul class="blog-posts">
{% for post in category.items %}
<li class="blog-posts">
<a href="{{ post.url | prepend: site.baseurl }}">
<p class="blog-posts__title">{{ post.title }}</p>
<p class="blog-posts__subtitle">{{ post.subtitle }}</p>
 <p class="blog-posts__date">{{ post.date | date: "%B %d %Y" }}</p>
</a>
</li>
{% endfor %}
</ul>
{% endfor %}
</div>
