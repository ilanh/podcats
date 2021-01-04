---
layout: default
permalink: /tags
title: Tags
---
{% assign sorted_tags = site.tags | sort %}
{% for tag in sorted_tags %}
  <div class="archive-group">
    {% capture tag_name %}{{ tag | first }}{% endcapture %}
    <div id="#{{ tag_name | slugize }}">
        <h2>{{ tag_name }}</h2>

        <ul>
          {% for post in site.tags[tag_name] %}
            <li><a class="archive-link" href="{{ site.url }}{{ post.url }}">{{post.title}}</a></li>
          {% endfor %}
        </ul>
    </div>
  </div>
{% endfor %}