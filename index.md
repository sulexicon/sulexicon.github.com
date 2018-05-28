---
layout: page
title: Home
tagline: Supporting tagline
---
{% include JB/setup %}

Hi,

I'm Di Wang, successfully complete an master degree, graduated from NEFU in 2018.


- Open source developer [@github](https://github.com/sulexicon)
- C++/Python/Java/Go
- `Hard-core` programming, like network programming/programming languages
- Programming language theory/Distributed system/Deep learning
- Fulltime developer at Easemob.
- Dota2 player.

You are welcome to contact me via:

Email: coder.sudo#outlook.com (replace # with @ please)

Github: [@mrmiywj](https://github.com/sulexicon)


#You can find my resume [here]({{BASE_PATH}}/resume.pdf).

> Recent Post:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
