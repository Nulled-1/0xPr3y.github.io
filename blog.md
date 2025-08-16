---
layout: default
title: Blog
permalink: /blog/
---
{% include header.html %}
# 📚 Blog

This is where I share my journey.

You’ll find short posts about:

- Learning programming step by step  
- Progress in building small games and tools  
- Reflections on what worked and what didn’t  
- Notes from experiments and projects  
- Personal thoughts as I grow from beginner to better

I don’t write as an expert.  
I write as a **beginner sharing the process** — honest and simple.

---

## Latest posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color:gray"> — {{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

Stay tuned.
