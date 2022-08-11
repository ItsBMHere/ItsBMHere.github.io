---
layout: default.liquid
---
## Blog!
This site is under construction whilst I figure out how Cobalt works.


{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
