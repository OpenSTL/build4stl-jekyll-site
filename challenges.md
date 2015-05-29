---
layout: page
title: Challenges
permalink: /challenges/
---
Anyone can participate in Build for STL! You don’t have to be an expert in technology, you just have to care about your community.

To celebrate National Day of Civic Hacking, over 30 federal agencies have released new datasets and challenges to hack. To help you navigate all the opportunities, here is a summary of this year’s challenges:  

<ul>
    {% for post in site.categories.challenges %}
        <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
