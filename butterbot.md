---
layout: post_default
title: ButterBot
description: A Documentation of the Build Process of ButterBot
---
## ButterBot

![](http://i.imgur.com/gUnJVZ4.jpg)

<ul>
    {% for post in site.posts %}
    <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
