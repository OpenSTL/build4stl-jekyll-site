---
layout: page
title: Events
permalink: /events/
---

Build4STL includes an entire month of community events!  Here they are!

<ul>
    {% for post in site.categories.events %}
        <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
</ul>
