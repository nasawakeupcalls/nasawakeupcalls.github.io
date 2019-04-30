---
layout: general
title: "Search"
author: "NASA: Music to wake up by"
permalink: /search/
---

<form class="search" action="/search/" method="get">
  <input type="text" id="search-box" name="query" placeholder="Find specific wakeup calls here...">
  <button type="submit"><i class="fa fa-search"></i></button>
</form>
<br />
<ul id="search-results"></ul>
<script>
  window.store = {
    {% for post in site.posts %}
      "{{ post.url | slugify }}": {
        "title": "{{ post.title | xml_escape }}",
        "author": "{{ post.author | xml_escape }}",
        "category": "{{ post.category | xml_escape }}",
        "content": {{ post.content | strip_html | jsonify }},
        "url": "{{ post.url | xml_escape }}"
      }
      {% unless forloop.last %},{% endunless %}
    {% endfor %}
  };
</script>
<script src="/assets/javascript/lunr.min.js"></script>
<script src="/assets/javascript/search.js"></script>