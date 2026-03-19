---
layout: default
title: ニュース
---

# 📰 ニュース

{% for post in site.posts %}
  <h2>
    {% if post.tags contains "メンテナンス" %}
      <span class="tag tag-maintenance">メンテナンス</span>
    {% elsif post.tags contains "お知らせ" %}
      <span class="tag tag-news">お知らせ</span>
    {% else %}
      <span class="tag tag-other">その他</span>
    {% endif %}

    <a href="{{ post.url }}">{{ post.title }}</a>
  </h2>
{% endfor %}---
layout: default
title: ニュース
---

# 📰 ニュース

{% for post in site.posts %}
  <h2>
    {% if post.tags contains "メンテナンス" %}
      <span class="tag tag-maintenance">メンテナンス</span>
    {% elsif post.tags contains "お知らせ" %}
      <span class="tag tag-news">お知らせ</span>
    {% else %}
      <span class="tag tag-other">その他</span>
    {% endif %}

    <a href="{{ post.url }}">{{ post.title }}</a>
  </h2>
{% endfor %}
