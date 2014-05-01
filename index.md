---
name: Brandi
layout: default
---

# Hello world!

This is an example of my new page.

This page was made by {{ page.name }}.

{% for post in site.posts %}
 * [{{ post.title ]}}{{ post.url }}) 
 {% endfor %}
