---
# layout: page
# title: Events
# permalink: /events/
---

Build4STL includes an entire month of community events.  We're also partnering with existing St. Louis Meetup groups so that tech meetups in May have a "civic" theme. 

<ul>
    {% for post in site.categories.events reversed %}
        <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
</ul>
