---
layout: default
permalink: /shows
title: Shows
---
{% assign sorted_shows = site.shows | sort %}
  <div class="archive-group">
  <h2>Shows</h2>
  {% for show in sorted_shows %}
  {{ show }}
  {% endfor %}
  </div>