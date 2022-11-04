---
layout: page
title: Posts
permalink: /posts/
feature-img: assets/img/sample_feature_img_2.png
published: true
---

## Posts

Here is a list of the posts that have been written:

<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{post.url}}">{{post.title}}</a>
        {{ post.excerpt }}
    </li>
    {% endfor %}
</ul>