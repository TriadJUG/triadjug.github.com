---
layout: page
title: TriadJUG - Java User Group
tagline:
---
{% include JB/setup %}


Welcome to TriadJUG!

![TriadJUG Banner](images/triadjug_logo.png)


#### Sponsors

[![TekSystems](images/tek_banner.png)](https://www.teksystems.com/en/locations/united-states/north-carolina/greensboro)

    
## Sample Posts

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


