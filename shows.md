---
layout: default
permalink: /shows
title: Shows
---
  <div class="archive-group">
  <h2>Shows</h2>
{% assign sorted_shows = site.shows | sort %}

  {% for show in sorted_shows %}
  {% capture show_name %}{{ show | first }}{% endcapture %}
    <div id="#{{ category_name | slugize }}">
        <h2>{{ show_name }}</h2>
    </div>
  {% endfor %}
  </div>