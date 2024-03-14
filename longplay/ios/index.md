---
layout: app
#title: Longplay // it's already the title of the whole page
redirect_from:
  - /ios/
permalink: /
nomasthead: True

description: Longplay is *the* iOS app for music lovers who enjoy listening to full albums, especially if they have a hard time isolating them in their music library. It provides a beautiful view of the album artworks of the (near) complete albums in their music library with one-tap access to play them.
image: /images/longplay/four.png
canonical_url: https://longplay.rocks
seo:
  type: MobileApplication

app:
  name: Longplay
  icon: /images/longplay/icon.png
  price: US$9.99
  # sale: $5.99
  price_note: One-time purchase
  oneliner: |
    Rediscover, enjoy and organise your album collection.
  appstore_link: https://apps.apple.com/us/app/longplay/id1495152002
  presskit_external_link: https://impresskit.net/longplay
  # presskit_link: longplay/ios/presskit.md
  changelog_link: longplay/ios/changelog.md
  privacy_link: longplay/ios/privacy.md
  screenshots: /images/longplay/four-2dot0.png

feature_groups:
  - title: Rediscover your album collection
    subtitle: Like standing in front of your album collection, but with superpowers.
    features:
      - title: Quickly access your complete albums
        description: Shows only those albums where you've added all or most of the songs. Listen with a single tap.
        fontawesome: fas fa-rocket
      - title: Funky sort options
        description: Sort by name, addiction, brightness, negligence, memory, recency, or your ratings. Explained via a little in-app dictionary.
        fontawesome: fas fa-magic
      - title: Big and small
        description: Size albums by addiction, negligence, recency, your ratings, or album length.
        fontawesome: fas fa-expand-arrows-alt
      - title: Discover forgotten treasures
        description: Sort by negligence to reveal albums you haven't listened to in a while but rated highly.
        fontawesome: fas fa-gem
      - title: Your music
        description: Works with any music that is in your Music app, be it from Apple Music, iTunes purchases or manually synced.
        fontawesome: fas fa-heart

  - title: Enjoy your music
    subtitle: Quickly start listening, stay in the flow with infinite album shuffle or your own queue, and take albums with you wherever you are.
    features:
      - title: Infinite album shuffle
        description: Stay in the flow, with smart shuffle depending on your current collection or sort order.
        fontawesome: fas fa-random
        new_in: 2.0
      - title: Shuffling becomes an experience
        description: Hold down the shuffle button to start cycling through albums. Let go to pick. Swipe left/right to manually go back or forward through the albums.
        fontawesome: fas fa-dice
        new_in: 2.0
      - title: Album queue
        description: Do it your way and queue up albums manually.
        fontawesome: fas fa-list-ul
        new_in: 2.0
      - title: Home Screen widgets
        description: Interactive widgets with a mini album wall or now playing information; control playback and shuffle right from your home screen.
        fontawesome: fas fa-th-large
        new_in: 2.1
      - title: CarPlay
        description: Access your albums and collection from the comfort of your driver's seat. Perfect for long road trips.
        fontawesome: fas fa-car
        new_in: 2.0
      - title: AirPlay aware
        description: Switch to an AirPlay speaker or headphones right from the Now Playing screen.
        fontawesome: fas fa-music

  - title: Organise the way you want
    features:
      - title: Organise albums into collections
        description: Group your albums and playlists, for a road trip, kids, by language, live albums, you name it.
        fontawesome: fas fa-folder
        new_in: 2.0
      - title: Star ratings make sense again
        description: Sort orders adapt to your star rating, or set your playback to auto-skip songs below a certain rating. Rate right in the app.
        fontawesome: fas fa-star
        new_in: 2.0
      - title: Scrobbling
        description: Track your listens through Last.fm or ListenBrainz.
        fontawesome: fas fa-music
        new_in: 2.0

  - title: And more...
    features:
      - title: Siri & Shortcuts support
        description: Use Siri or create Shortcuts to trigger playback using Longplay from outside the app.
        fontawesome: fas fa-microphone-alt
        new_in: 2.0
      - title: iCloud sync
        description: Your collections, hidden albums, ratings, and playback statistics sync automatically using iCloud.
        fontawesome: fas fa-cloud-upload-alt
        new_in: 2.0
      - title: Handles large collections
        description: Works with thousands of albums.
        footnote: Dynamic sizing is currently supported if you have less than 1000 albums.
        fontawesome: fas fa-expand-arrows-alt
        new_in: 2.0
      - title: Mobile data friendly
        description: Highlights albums you have downloaded when not connected to Wi-Fi.
        fontawesome: fas fa-broadcast-tower
      - title: Made with love
        description: The app is made by [myself](https://adrian.schoenig.me) and I use it pretty much every day. I love feedback, read all and try to reply to everything, too.
        fontawesome: fas fa-heart

testimonials:
  - handle: jsnell
    name: Jason Snell
    avatar: jsnell.jpeg
    link: https://overcast.fm/+Fcm_g75R4/37:36
    quote: Steve Jobs would have loved it.
  - handle: marcoarment
    name: Marco Arment
    avatar: marcoarment.jpg
    link: https://twitter.com/marcoarment/status/1295810118106349570
    quote: Great idea and beautiful design. I love the different discoverability angles, especially Negligence.
  - handle: jason_tate
    name: Jason Tate
    avatar: jason_tate.png
    link: https://twitter.com/jason_tate/status/1295812410888974336
    quote: "Full album listeners: assemble!"
  - handle: mikker
    name: Mikkel Malmberg
    avatar: mikker.jpg
    link: https://twitter.com/mikker/status/1295801509435899905
    quote: This iOS music player is perfect. This is exactly how I like to play music; one record at a time, from start to finish. OUTSTANDING work!
  - handle: ivanski
    name: Iván Cavero Belaunde
    avatar: ivanski.jpg
    link: https://twitter.com/ivanski/status/1299218124688879616
    quote: Very nice job with Longplay! Love the wall-of-albums UX.
  - handle: selsrog
    name: Roger
    avatar: selsrog.jpg
    link: https://twitter.com/selsrog/status/1296031743473078274
    quote: Thanks for Longplay, I miss the days I could stand before my collection to find forgotten treasures.
  - handle: gruber
    name: John Gruber
    avatar: gruber.png
    link: https://twitter.com/gruber/status/1295828946391629826
    quote: I do like listening to albums front to back. What a great idea.
  - handle: edvinasbartkus
    name: Ed Bartkus
    avatar: edvinasbartkus.jpg
    link: https://twitter.com/edvinasbartkus/status/1259846198187474949?s=21
    quote: What a great app! Listening to full albums is the only proper way to consume great music.
---

{% comment %}

<style>
  #container {
      position: relative;
      width: 238px;
      height: 461px;
      border-radius: 12px; 
      overflow: hidden;
      box-shadow: 1px 1px black;
      border: 3px solid black;
  }

  #hoverImage, #videoPlayer {
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
  }

  #videoPlayer {
      display: none;
  }

  #container:hover #hoverImage {
      display: none;
  }

  #container:hover #videoPlayer {
      display: block;
  }
</style>

<h1>Star ratings are useful again</h1>

<div class="features">

  <div class="feature">
      <div>
          <span class="fa-stack fa-1x">
              <i class="icon-back fas fa-circle fa-stack-2x"></i>
              <i class="icon-top {{ feature.fontawesome }} fa-stack-1x"></i>
          </span>
      </div>
      <div class="feature-text">
          <h3>
              {{ feature.title }}
          </h3>
          <p>
              {{ feature.description | markdownify }}
          </p>

          {% if feature.new_in %}
          <p style="font-weight: bold">
          ✨ New in {{ feature.new_in }} ✨
          </p>
          {% endif %}
      </div>

  </div>

  <div id="container">
      <img id="hoverImage" src="/images/longplay/features/rating.png" alt="Hover Image">
      <video id="videoPlayer" src="/images/longplay/features/rating_480p.mov" preload="auto"></video>
  </div>

</div>

<script>
    let videoPlayer = document.getElementById('videoPlayer');

    document.getElementById('container').addEventListener('mouseover', function() {
        videoPlayer.play();
    });

    document.getElementById('container').addEventListener('mouseout', function() {
        videoPlayer.pause();
        videoPlayer.currentTime = 0;
    });
</script>

{% endcomment %}

**[Available](https://apps.apple.com/us/app/longplay/id1495152002) for iOS 16 for iPhone, iPad, and iPod Touch, in English and German.**

<div class="testimonials-wrapper">
  <div class="testimonials-flexslider">
    <ul class="testimonials-list slides">
      {% for testimonial in page.testimonials %}
      <li>
         <p>{{ testimonial.quote }}</p>
         <div class="testimonials-author">
            <img src="/images/avatars/{{ testimonial.avatar }}" alt="{{ testimonial.handle }}" />
            <ul class="testimonials-author-info">
               <li><a href="{{ testimonial.link }}">{{ testimonial.name }}</a></li>
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
