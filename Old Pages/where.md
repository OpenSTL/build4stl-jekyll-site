---
# layout: page
# title: Event Sites
# permalink: /where/
---

Thanks to all our generous donors and partners who have provided our event sites this year!  

<ul>
    {% for post in site.categories.sites reversed %}
        <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
</ul>
