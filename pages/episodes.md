---
layout: page
title: Episodes
---
<div class = "episodes">

<h2> Episodes </h2>
<ul>
{% for post in site.posts %}    
    {% if post.type == "main" %}
        <li>
            <a href="{{ site.url }}{{ post.url }}"> {{ post.title }} </a>
        </li>
    {% endif %}

{% endfor %}
</ul>

<h2> Extra Episodes </h2>
<ul>
{% for post in site.posts %}    
    {% if post.type == "extra" %}
        <li>
            <a href="{{ site.url }}{{ post.url }}"> {{ post.title }} </a>
        </li>
    {% endif %}

{% endfor %}
</ul>
</div> 