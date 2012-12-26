---
layout: page
title: Digest
top: JiangJi
---
{% include JB/setup %}


This place contains contents that are collected from Internet, et al.. Most of them are links to original page and some are reproduced copies  for personal memos and/or backup just in case. These reproduced copies are explicitly noted. If any content violates your rights, [contact me](/about.html) and I will remove it as soon as possible, sorry about that.

You can find all collections by [listing all digest pages](./archive.html).      

---

### recent post

<ul class="posts">
  {% for post in site.categories.digest limit:10 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

---
