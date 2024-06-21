---
layout: home
title: "Training Diary"
---
Welcome to the Training Diary. Here you will find daily entries of training activities.

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%B %d, %Y" }}
{{ post.excerpt }}
{% endfor %}
