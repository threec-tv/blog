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
      <h4><a href="{{ post.url }}">{{ page.date | date_to_string }}</a></h4>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
