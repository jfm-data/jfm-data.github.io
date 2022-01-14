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
{{ category.name }} - - - - - - - - - - 
{% else %} 
{{ Print }} 
{% endif %}
</code>
</h4>
<ul class="list-posts">
{% for post in category.items %}
<li class="post-teaser">
<a href="{{ post.url | prepend: site.baseurl }}">
<span class="post-teaser__title">{{ post.title }}</span>
<span class="post-teaser__title">{{ post.subtitle }}</span>
<span class="post-teaser__date">{{ post.date | date: "%B %d %Y" }}</span>
</a>
</li>
{% endfor %}
</ul>
{% endfor %}
</div>
