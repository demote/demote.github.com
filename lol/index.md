---
layout: page
title: Blog
top: JiangJi
---
{% include JB/setup %}

## Trival...Sensitive...Memory...
-

This is the place where I write down some of trivial stuff in my life.

Well, you are not supposed to be here. However, if you find ANY error, you are still welcome to [tell me](/about.html) about it. 

### recent post

<ul class="posts">
  {% for post in site.categories.lol limit:10 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

-
