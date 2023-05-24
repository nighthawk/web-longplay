---
layout: app
title: Longplay
redirect_from:
  - /ios/
permalink: /
nomasthead: True

description: Longplay is the iOS app for music lovers who enjoy listening to full albums but have a hard time finding them in their music library. It provides a beautiful view of the album artworks of the (near) complete albums in your music library with one-tap access to play them.
image: /images/longplay/four.png
canonical_url: https://longplay.app
seo:
  type: MobileApplication

app:
  name: Longplay
  icon: /images/longplay/icon.png
  price: $3.99
  oneliner: Rediscover your album collection
  appstore_link: https://apps.apple.com/us/app/longplay/id1495152002
  presskit_link: longplay/ios/presskit.md
  changelog_link: longplay/ios/changelog.md
  privacy_link: longplay/ios/privacy.md
  screenshots: /images/longplay/four-1dot2.png

features:
  - title: Quickly access your complete albums
    description: Shows only those albums where you've added all or most of the songs. Listen with single tap.
    fontawesome: fas fa-rocket
  - title: Discover forgotten treasures
    description: Sort by negligence to reveal albums you haven't listened too in a while but rated highly.
    fontawesome: fas fa-gem
  - title: Your music
    description: Works any music that is in your Music app, be it from Apple Music, iTunes purchases or manually synced.
    fontawesome: fas fa-heart
  - title: Funky sort options
    description: Sort by name, addiction, brightness, negligence, recency or your ratings.
    fontawesome: fas fa-magic
  - title: Big and small
    description: Size albums by addiction, negligence, recency, your ratings or album length.
    fontawesome: fas fa-expand-arrows-alt
  - title: Home Screen widgets
    description: Mini album wall for your home screen, that doubles as a "Feeling lucky" play button.
    fontawesome: fas fa-home
  - title: Mobile data friendly
    description: Highlights albums you have downloaded when not connected to Wifi.
    fontawesome: fas fa-broadcast-tower
  - title: AirPlay aware
    description: Long tap album, tap "Play on…", tap speaker name. Done. So quick.
    fontawesome: fas fa-music
  - title: Shortcuts actions
    description: Includes Shortcuts action to play a random albums, optionally filtered by album, genre, or favouring a specific sort order.
    fontawesome: fas fa-robot

testimonials:
  - handle: jsnell
    avatar: jsnell.jpeg
    link: https://overcast.fm/+Fcm_g75R4/37:36
    quote: Steve Jobs would have loved it.
  - handle: gruber
    avatar: gruber.png
    link: https://twitter.com/gruber/status/1295828946391629826
    quote: I do like listening to albums front to back. What a great idea.
  - handle: marcoarment
    avatar: marcoarment.jpg
    link: https://twitter.com/marcoarment/status/1295810118106349570
    quote: Great idea and beautiful design. I love the different discoverability angles, especially Negligence.
  - handle: jason_tate
    avatar: jason_tate.png
    link: https://twitter.com/jason_tate/status/1295812410888974336
    quote: "Full album listeners: assemble!"
  - handle: mikker
    avatar: mikker.jpg
    link: https://twitter.com/mikker/status/1295801509435899905
    quote: This iOS music player is perfect. This is exactly how I like to play music; one record at a time, from start to finish. OUTSTANDING work, @nhawk!
  - handle: ivanski
    avatar: ivanski.jpg
    link: https://twitter.com/ivanski/status/1299218124688879616
    quote: Very nice job with Longplay! Love the wall-of-albums UX.
  - handle: selsrog
    avatar: selsrog.jpg
    link: https://twitter.com/selsrog/status/1296031743473078274
    quote: Thanks for Longplay, I miss the days I could stand before my collection to find forgotten treasures.
  - handle: edvinasbartkus
    avatar: edvinasbartkus.jpg
    link: https://twitter.com/edvinasbartkus/status/1259846198187474949?s=21
    quote: What a great app! Listening to full albums is the only proper way to consume great music.
---

**[Available](https://apps.apple.com/us/app/longplay/id1495152002) for iOS 15 for iPhone, iPad, and iPod Touch, in English and German.**

<div class="testimonials-wrapper">
  <div class="testimonials-flexslider">
    <ul class="testimonials-list slides">
      {% assign shuffled = page.testimonials | sample: 10 %}
      {% for testimonial in page.testimonials %}
      <li>
         <p>{{ testimonial.quote }}</p>
         <div class="testimonials-author">
            <img src="/images/avatars/{{ testimonial.avatar }}" alt="{{ testimonial.handle }}" />
            <ul class="testimonials-author-info">
               <li><a href="{{ testimonial.link }}">@{{ testimonial.handle }}</a></li>
            </ul>
         </div>
      </li>
      {% endfor %}
    </ul>

    {% comment %}
    <a href="#0" class="cd-see-all">See all</a>
    {% endcomment %}

  </div>
</div>

{% comment %}

<div class="cd-testimonials-all">
   <div class="cd-testimonials-all-wrapper">
      <ul>
         {% for testimonial in page.testimonials %}
         <li class="cd-testimonials-item">
            <p>{{ testimonial.quote }}</p>
        
            <div class="cd-author">
               <img src="/images/avatars/{{ testimonial.avatar }}" alt="{{ testimonial.handle }}" />
               <ul class="cd-author-info">
               <li><a href="{{ testimonial.link }}">@{{ testimonial.handle }}</a></li>
            </ul>
            </div> <!-- cd-author -->
         </li>

         {% endfor %}
      </ul>

   </div> <!-- cd-testimonials-all-wrapper -->

<a href="#0" class="close-btn">Close</a>

</div> <!-- cd-testimonials-all -->

<div class="flexslider">
  <ul class="slides">
    {% for tweet in page.tweets %}
      <li>{% twitter tweet width=350 align=center %}</li>
    {% endfor %}
  </ul>
</div>
{% endcomment %}
