---
layout: post
title: ''
---

## MMMap 
MMMap is a tool that reads every track in your Spotify library, and creates a heatmap based on the birthplace of artists who contributed to the track.

To begin making a user's custom map, MMMap utilizes the Spotify API to fetch user's saved tracks. Next, for each artist in a user's library, there is a frequeny value that represents the number of times the artist is represented in the user's library. After using webscraping to extract each artist's birthplace and geocoding the provided birthplace, MMMap creates a heatmap! The MMMap database contains over 84,000 artists provided by Localify, a platform that personalizes local music recommendations by integrating Spotify playlists with tracks from local artists. Each time a new user uses MMMap, the artists they listen to are added to MMMap's database.

MMMap is still in the developer phase, meaning I have to approve each user (up to 25 users). If interested in trying out this tool, shoot me a message with the email address attached to your Spotify account so you can give it a try!

[www.mmmapproject.com](http://www.mmmapproject.com)





