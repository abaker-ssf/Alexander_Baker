---
layout: page
title: Posts
permalink: /posts/
Alexander Baker's Website 
---

Hi this is Alexander Baker's Website and this is were all of the major info and projects he has worked on are kept.
I hope you enjoy exploring the main pieces of work I particpated in and to talk to you soon. 

{:.post-list }
{% for post in site.posts %}

{:.post-meta }
* {{ post.date | date: "%b %-d, %Y" }}

{: .post-link }
[{{ post.title }}]({{ post.url | prepend: site.baseurl }})

{% endfor %}
