---
layout: default
title: "Welcome to the GA Student Showcase"
---

# Welcome

Here are some fantastic projects carried out by new coders. 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<div class="footer-container">
    ![DJSIR Logo](/assets/images/DJSIR.png)
    ![GA Logo](/assets/images/GA.png)
</div>