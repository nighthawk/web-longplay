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

## JSON Format

These collections are JSON files that can be hosted anywhere, and then opened in Longplay using a link like `longplay://show-collection?url={url}`.

They need to follow the following JSON format:

```json
{
  "name": "String",
  "articleURL": "URL",
  "showRank": Bool,
  "albums": [
    {
      "rank": Integer,
      "album": "String",
      "artist": "String",
      "year": Integer,
      "imageURL": "URL",
      "appleMusicID": "String",
      "albumURL": "URL"
    }, ...
  ]
}
```

Top level:

- `showRank` on the top level is optional, and defaults to `true`. Set this to false to not show the "Ranking" sort order in the app, and to not show the rank on each album.

Albums:

- `rank` is optional but should be provided unless the top level specifies `"showRank": false`.
- `year` is optional, but should be provided for sorting by release year.
- `appleMusicID` is optional, but is required to enable playback in the app.
- `imageURL` is optional, but should be provided to show cover arts.
- `albumURL` is optional, if present long-tapping an album will have anoption to open this link.
