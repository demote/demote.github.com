---
layout: page
title: Invisible
top: JiangJi
---
{% include JB/setup %}

## Trival...Moods...Memory...
-

This is the place where I write down some of trivial stuff in my life.

Well, you are not supposed to be here. Anyway, if you find ANY error, you are still welcome to [tell me](/about.html) about it. 

### recent post

<ul class="posts">
  {% for post in site.categories.lol limit:10 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

-
