---
layout: home
title: "Home"
---

# Welcome to My Data Analysis Portfolio

Hi, I'm Ludvig Holm. Welcome to my portfolio where I showcase my data analysis projects. Here you'll find a collection of my work demonstrating my skills in data analysis, visualization, and interpretation.

Feel free to explore my projects and learn more about me.

## Featured Projects

{% for post in site.posts %}
  <div class="project">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}
