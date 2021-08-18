---
layout: page
title: Index
permalink: /index/
useurl: /san_cubec_blog\_posts
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{- post.url | useurl -}}">{{ post.title }}</a>
	  {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>