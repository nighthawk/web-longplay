---
layout: page
title: Changelog
redirect_from:
  - /ios/changelog/
permalink: /changelog/
---

## 2.2.4, 15 April 2024

🎶 I thought you'd always be… my zero… 🎶

New:

- Remembers playback position in previously played session when re-opening Longplay after a while

Fixed all currently known issues:

- Addresses issue where the last played album might not re-start after re-opening the app
- Under-the-hood improvements for stability and memory usage

## 2.2.3, 27 Feb 2024

- Adds several keyboard shortcuts
- Update German translation

## 2.2.2, 20 Feb 2024

🎶 I thought you'd always be… my zero… 🎶

Fixed all currently known issues:

- Fix highlight of current track in track list when shuffling tracks
- Fix shuffled playback to start on random track, rather than always the first
- Fix album inspector sometimes not appearing on iOS
- Fix albums sometimes getting displayed twice on album wall
- Fix landscape layout on Max and Plus sized iPhones
- Improves reliability of Last.fm scrobbling
- Improves text contrast of sort order colours on iOS
- Style tweaks for the collection picker

If you come across a bug, please let me know by [mail](mailto:words@longplay.app), on [Mastodon](https://indieapps.space/@longplay), or on the [feedback website](https://feedback.longplay.app).

## 2.2.1, 10 Feb 2024

🎶 Show me how to… 🎶 create some Shortcuts.

New:

- Added several example Shortcuts accessible through the in-app settings

Changed:

- Longplay will now include albums with one or two tracks if you have all the tracks and they exceed a minimum duration.

Fixed:

- Tweak reports from Last.fm scrobbling
- Some minor style and wording tweaks

## 2.2, 6 Feb 2024

🎶 I've been looking for… 🎶

New:

- A search box to filter the albums view by artist or title
- Many, *many* new Shortcuts actions. Create a pretty image of your recently listened albums. Search albums by an artist, sort them by release date, and add them to your queue. Get album metrics and display them in Charty. Find albums by a genre and show them as an ad-hoc collection in the app. Resume your last Longplay session when putting on your smart glasses. Get creative!
- Album inspector to browse tracks of any album, see album stats, and set/overwrite release year and artist sorting
- Choose between skipping current track or album by long-tapping the "next" button in the Now Playing screen
- New 'Release' sort order (but see the in-app guide for how the enable that, as it's not automatic)
- Long-tapping an album will now also show release year, if known.

Improved:

- Refined the CarPlay experience
- Sorting by "Stars" now considers the percentage of the album rated, and five stars tracks give an extra bonus

Fixed:

- Minor styling tweaks and fixes

## 2.1.6, 18 Dec 2023

🎶 I can see clearly now 🎶

Fixes:

- Fixes low contrast of album queue icons on dark album artwork
- Fixes low contrast of album queue list when listening to an album with light album artwork
- Fix issue where Infinite Album Shuffle incorrectly shuffles from subset of albums
- Re-shuffle the albums "behind" the shuffle button every couple of presses
- Persist last used view between app restarts, i.e., in particular whether you were viewing albums or the player
- Keep album size more similar between portrait and landscape orientations
- Minor style tweaks for the track queue, improving contrast of the little stars, and automatically scrolling to the current track when it changes

## 2.1.5, 6 Dec 2023

> 🎶 Oops... I did it again. 🎶

A quick regression fix:

- Fix issue where Album Wall widgets might be stuck on message to open Longplay when randomising library

## 2.1.4, 5 Dec 2023

> 🎶 Unstuck in time, running free 🎶

Fixes:

- Fix issue where tapping "Random" sort order again would not always re-shuffle
- Fix issue where Album Wall widgets might be stuck on message to open Longplay
- Fix issue where Album Wall widget that's set to display a collection in random order would not randomise its albums
- Renames "Artist" parameter to "Album Artist" in "Find Album" shortcut to match what it actually does
- Minor performance and stability improvements

## 2.1.3, 19 Oct 2023

Improved:

- Adds page indicator on iPhone while swiping between settings, album wall and player. Fully VoiceOver accessible.
- Omit „The“ from playlists when sorting alphabetically.

Fixes:

- The shuffle button in the Now Playing widget now shuffles through all your albums, not just a subset.
- Fixes restoring selected collection on app-restart.
- Fixes issues where some compilations might be missing primary artist.
- Fix crash when using CarPlay when phone is set to German. 'tschuldigung.
- Robustness tweak for stats calculation.
- Reviewed and improved the VoiceOver support.

## 2.1.2, 13 Oct 2023

Adds:

- Tip jar
- New setting on "Now Playing" widget to make the shuffle button always pick a random album, rather than reflecting the app's sort order or collection.

Fixes:

- Fix progress for Current Album Artwork in StandBy if primary colour is black
- Fix playback from widget not restarting where you last left off
- Fix low contrast colour issues in Now Playing widget, on Sonoma, and sometimes in-app
- Fix for shuffle button occasionally getting stuck cycling through your albums
- Fix crash due to hitting memory limits when importing libraries with large numbers of albums or many large album artworks
- Fix album wall layout when selecting an album at the end
- Removes "(No Title)" shortcuts in Spotlight search on iOS 17
- Default "Now Playing" widget to show album art rather than spider chart
- Minor style tweaks
- Robustness and performance fixes

## 2.1.1, 21 Sep 2023

> 🎶 Baby, You Can Drive My Car 🎶

Added:

- New "Current Album Artwork" widget, which nicely complements the "Now Playing" widget in StandBy mode.
- Shuffle button on the "Now Playing" won't get disabled if album just started playing; or configure the widget to always have the button enabled.
- New "Recently Played" list item in CarPlay for your last listened album, in case you want to resume that in the car.

Fixed:

- Addresses issue where CarPlay might not show your collections
- Playlist tracks maintain their order as defined in the playlist
- Minor style tweaks for "Now Playing" widget

## 2.1, 18 Sep 2023

_**See [Press Release](https://impresskit.net/press-release/85e446f7-a8eb-43f6-97af-a3666825e572)**_

> 🎶 So Darlin', Darlin', Stand By Me 🎶

Updated **Album Wall** widget:

- Shows a grid of albums, tapping one starts playing it, tapping it again will pause playback.
- Playback status is indicated by the album resizing, just as in the app. Like an adorable mini Longplay.
- This widget is now available in sizes small (9 albums), medium (18 albums), and large (36 albums).

All new **Now Playing** widget:

- Show the currently playing album, or suggests a random one, if nothing is playing; with play/pause button.
- Shuffle button to switch to a random album (disabled while album is playing; pause playback first)
- Shows a spider chart of the album's metrics (recency, memory, length, negligence, stars, addiction) – tap it or the album artwork to toggle between the two.
- Available in small and medium.

Other improvements in this update:

- The "My Library" dropdown will fade away as you scroll through your albums, giving you a pristine chrome-free look of just your albums (can be disabled in the settings).
- New Shortcuts actions.
- Now requires iOS 16.1

## 2.0.1, 9 Sep 2023

> 🎶 Brand New Day 🎶 ...for a round of fixes:

New:

- Time in the track list of the current track ticks down
- Pull-to-refresh when viewing "My Library"

Fixes:

- Always show "Downloaded" smart collection
- Show sizing options also for large libraries
- Tweaks size of Now Playing buttons in CarPlay
- Fixes multi-selection gesture to add multiple items to a collection
- Fixes progress bar updates on Welcome Screen
- Fixes some typos
- Stability and performance improvements

## 2.0, 30 Aug 2023

_**See [annoucement](https://adrian.schoenig.me/blog/2023/08/31/longplay-2.0/) and [Press Release](https://impresskit.net/press-release/8455872c-94d1-4134-aa59-383372f46b8c)**_

> 🎶 Back in Black 🎶

- [New] Now Playing screen, including track list
- [New] Create collections of albums
- [New] Infinite album shuffle
- [New] Album queue
- [New] CarPlay support
- [New] Siri support
- [New] "Memory" sort order
- [New] Dictionary to explain sort orders
- [New] iCloud Sync
- [New] Last.fm and ListenBrainz support
- [New] Revised iPad layout
- [New] Much improved performance to handle thousands of albums

And a lot of other small-to-medium-sized improvements and fixes.

---

## 1.2, 21 Sep 2021

> 🎶 I Got Some If You Need It 🎶

- [New] In-app settings screen, including alternative app icons
- [New] New "Size by" option
- [New] New 'Random' sort order, re-shuffling whenever you tap the option again
- [New] iPad: Show a button in the bottom left when scrolling through the albums to quickly access your settings
- [New] iPad Keyboard support: Arrow keys to navigate around, play/pause via enter
- [New] Longplay, jetzt auch auf Deutsch
- [Fix] Fixes issue where second long tap on an album wouldn't show its title
- [Fix] Performance improvements for laying out the albums grid
- [Fix] Stability fix after Longplay went into background
- [Fix] Small tweak to light mode and when no albums are available
- [Change] Requires iOS 15

## 1.1.5, 19 Mar 2021

- [Fix] VoiceOver-related fix for the medium-sized widget
- [Fix] The widget configuration now uses Longplay's colours

## 1.1.4, 29 Jan 2021

> 🎶 Long Way To The Top 🎶

- [New] Tapping near the top now scrolls to the top, as you'd expect.

## 1.1.3, 25 Nov 2020

Interlude, with a few fixes:

- [Fix] Allow scrolling settings away even if you don't have many albums
- [Fix] Fix resizing glitch when scrolling playing album in and out of viewport
- [Fix] Fix settings sometimes overlapping albums when returning to the app on iPad

## 1.1.2, 10 Oct 2020

> 🎶 All The Small Things 🎶, something for everyone:

- [New] A new "Different day, different order" sort option for the widgets that keeps the widget fresh every day.
- [New] Related: You can now also opt to show the sort option's name in the widget, too.
- [New] The medium-sized widget now will start playing the album you tap on. That's 18 buttons in a widget! (And if you have larger fingers or just tap without aiming that means the old "Feeling lucky" behaviour is preserved, too.)
- [New] Sorting by addiction is now based on the median play counts, so if you just listen to selected songs in an album on repeat that won't lift the album's addiction level anymore.
- [New] Avoid switching to another album accidentally: If you're listening to an album, tapping another album won't immediately switch to that but first highlight that album; tap again to confirm to switch. (Abort highlight by tapping the playing album.)
- [New] Added an advanced setting to change the size of the album artwork with new "Large" and "Extra Large" settings.
- [New] The playback progress indicator is now offset from the album and adopts to the album's colours.
- [Fix] The album preview now immediately adjusts to the album's colours when long tapping it.
- [Fix] Yet another fix for Longplay not using highest resolution artwork when possible.
- [Fix] "No albums found" will no longer incorrectly appear before albums were properly loaded when triggering playback through the widget.
- [Fix] Setting for "Fade downloaded albums" was broken in V1.1.1 and should now be functional and pretty again.
- [Fix] Removes potential for a crash when clearing the cache.
- [Fix] Improved the performance for app start-up and when quickly scrolling through albums.

## 1.1, 17 Sep 2020

> 🎶 Another Brick in the Wall 🎶, ready for iOS 14:

- Your album wall right on your home screen, that doubles as a "Feeling lucky" button
- Customisable which sort order to use and what to do when tapping the widget

Plus more goodness:

- Two Shortcut actions: Play a random album by your nominated sort order (like the widget, but starting playback without opening hte app), and play a random album, optionally filtered by genre or artist.
- Actions on the now-playing item to skip to next or previous song, and to pick an AirPlay device
- A little gear icon to access the settings from the app

And a couple of fixes:

- Fix of album artwork resolution on the now-playing album
- Fix for size of background when long-tapping an album, maintaining symmetry
- Fix of Z-order of the side settings on an iPad on launch
- Address a crash after clearing the cache

## 1.0.3, 2 Sep 2020

> 🎶 So Much To Say 🎶

- More order when sorting by orderliness: Now sorts artists the same as the Music app, using "sort as" tags and properly handles compilations, intermingling them and and playlists according to their names. Also albums that include numbers are now sorted numerically; fans of the Dave Matthews Band and other jam bands might appreciate this.
- Performance improvements for start-up, especially for large libraries. Should be noticable on second start-up after updating, as the first start-up will migrate to an updated on-disk cache.

## 1.0.2, 24 Aug 2020

> 🎶 What Have We Found? 🎶

- Longplay now shows more of your albums by relaxing and tuning the filtering criteria and taking album duration into consideration. This if for you, Pink Floyd fans.
- Large albums showed during playback and when long-tapping now display in higher resolution.
- Automatic refresh of the albums when coming back to the app, so if you add an album through the Music app, it'll show up when you go back to Longplay.
- Sorting by orderliness now ignores "the" prefix of artists when using an English locale.
- Performance improvements and stability tweaks, in particular for very large album collections.
  Thanks again for all the feedback so far. Much appreciated! -->

## 1.0.1, 20 Aug 2020

🎶 Ch-ch-ch-changes 🎶

- Inverts the play/pause indicator to match the Music app (by unanimous and unarguably correct demand)
- Long-tapping an album now shows additional info based on your selected sort order, i.e., when sorting by "addiction" how many times you've listened to the album, when sorting by "recency" when you've added the album, and when sorting by "stars" what's the average rating.
- Fixes album's title and subtitle not always appearing when long-tapping album
