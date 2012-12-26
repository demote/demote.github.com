---
layout: page
title: Home
top: JiangJi
tagline: -- JiangJi
---
{% include JB/setup %}

---

I am Jiang Ji, a 20-something, Chinese, student, programmer, nerd, pseudo-geek, pseudo-MANUTD fan and something else. You can find out more about me by poking around the links above and below.

---

## what can you find here


this is a personal page hosted by github.

You can find almost nothing so far.

---

## Blog


I keep a [BLOG](/blog) mostly on programming and sometimes on trivial stuffes in my life.       
If you have troubles viewing this site, try using another web browser like Chrome or Firefox.


---

### here are some recent posts

<ul class="posts">
  {% for post in site.categories.blog limit:5 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

---

I also maintain a [DIGEST](/digest) which contains contents that are collected from Internet, et al.. Most of them are links to original page and some are reproduced copies  for personal memos and/or backup just in case. These reproduced copies are explicitly noted. If any content violates your rights, [contact me](/about.html) and I will remove it as soon as possible, sorry about that.

---

## current situation

I am not eagerly looking for a job, but if you are interested in my resume:

-[.html](/resume.html)


Email me: [jiang.ji@hotmail.com](mailto:jiang.ji@hotmail.com)

---
