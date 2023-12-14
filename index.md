---
title: Welcome to my blog
---

# 💃　Shall we dance?
ダンスするよね？？

# 🥟 I love pao!
美味しいよねー

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
