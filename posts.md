---
layout: page
title: Posts
permalink: /posts/

published: true
---

# Posts

Here is a list of the posts that have been written:

<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{post.url}}">{{post.title}}</a>
    </li>
    {% endfor %}
</ul>