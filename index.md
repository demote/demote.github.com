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

## current situation

I am now looking for a job, and if you are interested in my resume:

-[.html](/resume.html)

-[.pdf](/resume.pdf)

Email me: [jiang.ji@hotmail.com](mailto:jiang.ji@hotmail.com)

---
