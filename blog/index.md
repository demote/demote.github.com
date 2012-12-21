---
layout: page
title: Blog
top: JiangJi
---
{% include JB/setup %}

## Thoughts, Traces, Memos...
-

This is the place where I write down some of my thoughts(mostly technical) as well as some memos. 

If you find ANY error, you are more than welcome to [tell me](/about.html) about it. 

Some posts might be trivial and/or boring, just IGNORE them.

### recent post

<ul class="posts">
  {% for post in site.categories.blog limit:2 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

You can also find all past posts [here](/archive.html) or click "Archive" in front of the page.

-
