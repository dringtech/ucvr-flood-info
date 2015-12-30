---
layout: page
---

Welcome to the Upper Calder Valley Renaissance Flood Coordination page.
This site has been set up in response to the floods which affected the
Upper Calder Valley, including
[Todmorden](/communities/todmorden/),
[Hebden Bridge](/communities/hebden-bridge/),
[Mytholmroyd](/communities/mytholmroyd/) and surrounding settlements.

## Recent updates:

<ul>
{% for post in site.posts limit:3 %}
<li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a> ({{ post.date | date: "%b %-d, %Y" }})</li>
{% endfor %}
</ul>

## Please help

This is work in progress, so please alert us to any additional or incorrect
information on the site. The Feedback button at the bottom of each page is the
best route.
