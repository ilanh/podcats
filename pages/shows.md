---
layout: page
permalink: /shows
title: Shows
---
{% assign sorted_shows = site.show | sort %}
{% for show in sorted_shows %}
  <div class="archive-group">
    {% capture show_name %}{{ show | first }}{% endcapture %}
    <div id="#{{ show_name | slugize }}">
        <h2>{{ show_name }}</h2>

        <ul>
          {% for post in site.show[show_name] %}
            <li><a class="archive-link" href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></li>
          {% endfor %}
        </ul>
    </div>
  </div>
{% endfor %}