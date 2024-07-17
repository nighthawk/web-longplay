---
layout: page
title: visionOS Changelog
permalink: /visionos/changelog/
---

## 2.2.6, 17 July 2024

A round of improvements for the immersive Album Wall:
- The player in the immersive space is now the same Now Playing window as when using Longplay regularly; which means you get the same track list, queue controls, and context menus
- The immersive Album Wall space by default disables the selection and hover effect on the albums to provide a more calm experience while soaking in your albums; use the toggle in the revised control panel to enable selection to switch the playing album
- When albums are filtered if searching by name, the removal and resizing is no longer animated as that could be jarring when the window is wall sized
- Performance improvements for the immersive Album Wall space

New:
- Auto-populate release years (Apple Music only)
- Show percentage listened
- Show ratings at top level, if toggled on

Fixes:
- Fix release year not being used in Orderliness sort when sorting artists as in Music app (you'll need to do a manual album refresh once, by pulling to refresh)
- Fix album shuffle not being very random when selecting Random sort order
- Widgets that use the Random order will now (again) get a new set of albums every day
- Performance improvements, in particular when triggering new random album
- Style tweaks

## 2.2.5, 20 April 2024

In-app volume controls on the album wall and the mini player

Immersive space:
- Allow changing the size of albums, including zooming to fit all albums
- Make changing the sort order easier
- Much improved stability by making it more memory efficient

Fixed:
- Fixes scrobbling of first track in an album
- Fixes styling of playlists, especially when they are sized smaller
- Fixes issue where the selected collection would reset when returning from immersive space to album wall
- Remembers position in previously played album also when re-opening Longplay after a while
- Addresses issue where after re-opening the app the last played album might not re-start
- Various UX improvements and stylistic tweaks
- Further under-the-hood improvements for stability and memory usage

## 2.2.3, 15 April 2024

- Fix highlight of current track in track list when shuffling tracks
- Fix shuffled playback to start on random track, rather than always the first
- Fix albums sometimes getting displayed twice on album wall
- Improves reliability of Last.fm scrobbling
- Style tweaks for the collection picker

## 2.2.1, 2 February 2024

Intial release for Apple Vision Pro launch day

_**See [Press Release](https://impresskit.net/press-release/85e446f7-a8eb-43f6-97af-a3666825e572)**_