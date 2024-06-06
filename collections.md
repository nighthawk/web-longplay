---
layout: default
---

# Featured Collections

Longplay, or at least an upcoming version of it, let's you not just browse and rediscover your own music library, but you can also use it to explore external collections in-app, listen to albums, track what you've listened to, and add albums to your library. All powered by Apple Music.

The collections can be published by anyone on their website, and I've collected a couple great ones here:

<ul>
  {% for collection in site.collections %}
    <li>
    <h3><a href="{{ collection.url }}">{{ collection.name }}</a></h3>
    </li>
  {% endfor %}
</ul>