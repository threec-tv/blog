---
title: "Welcome to the blog"
---

I'm glad you are here. 

Here is a space for all things threeC.tv ranging from features, tech to people.

Enjoy...

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
