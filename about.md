---
title: O mě
order: 10
subtitle: Pár věcí o mé osobě a práci
tags: [Já, rozpracované]
date: 2020-02-21
---

Jsem Michal Rada.

## Příspěvky zde

  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}