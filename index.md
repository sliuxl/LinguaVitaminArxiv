---
layout: default
title: Home
---

Welcome to **LinguaVitamin arXiv Papers**!
Here you’ll find daily multilingual arXiv papers to boost your language learning.

---

## 📰 Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a><br />
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
