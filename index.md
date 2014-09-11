---
title: index
---
{% for post in site.posts %}
* [ {{ post.date | date: "%d/%m/%Y" }} &middot; {{ post.title }}]({{ post.url | prepend: site.baseurl }}#disqus_thread)
{% endfor %}
