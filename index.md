---
layout: home
title: All my posts
---
<!-- theme from: https://github.com/pages-themes/hacker-->
<hr>

{% for post in site.posts %}
## {{ post.title }}

{{ post.excerpt }}

[Full Post]({{ post.url | relative_url }})
<hr>
{% endfor %}

