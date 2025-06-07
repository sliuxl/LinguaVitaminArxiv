---
layout: default
title: Home
---

Welcome to **LinguaVitamin arXiv Papers**!
Here you’ll find weekly multilingual arXiv papers to boost your language learning.

- Source code: [LinguaVitaminArxiv](https://github.com/sliuxl/LinguaVitaminArxiv)
- Read news instead: [https://sliuxl.github.io/LinguaVitaminNews](https://sliuxl.github.io/LinguaVitaminNews)

As of June 2025,
it covers a few subjects with German (title only) and Chinese translation:

1. [arXiv](https://arxiv.org)
    1. `cs.CL`
    1. `cs.DC`
    1. `cs.LG`
    1. `cs.MA`
    1. `cs.PL`
    1. `cs.SE`
1. [Hacker news](https://news.ycombinator.com): The most popular news by **ycombinator**


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
