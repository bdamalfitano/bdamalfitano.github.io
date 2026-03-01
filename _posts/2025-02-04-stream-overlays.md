---
layout: page
title: "Stream Overlays"
tags:
  - Twitch
  - Livestream
  - Graphic Design
  - Mix It Up
  - UI/UX Design
  - Live Data Integration
  - Javascript
---
<div class="project-tags">
  <span>Twitch</span>
  <span>Livestream</span>
  <span>Graphic Design</span>
  <span>Mix It Up</span>
  <span>UI/UX Design</span>
  <span>Live Data Integration</span>
  <span>Javascript</span>
</div>

## Overview
Designed and implemented dynamic stream overlays for streaming platforms, Twitch in this case but useable anywhere, for better interaction with streamers and their chats. I used a program called Mix It Up to code the backend of the overlay to allow chatters to be able to interact with the stream directly.

## Technologies
- HTML
- CSS
- JavaScript
- Mix It Up (Automation Software)
- Life Chat Event Hooks

## Key Features
- Responsive overlay components
- Real-time updates
- Custom animation effects
- Chat affects on-screen elements

# Implementation
The first two overlays were made to mimic popular social media platforms Twitter and Buzzfeed, the twist being that nearly all the text and images on screen are able to change through what the chatters do. On the Twitter one, when someone leaves a chat message their username, icon, and message will all appear on the screen as a fake Twitter comment. Platforms like Twitch allow frequent watchers to redeem rewards through a point system, and several of these point options would also affect on screen elements like the Twitter trending searches or the amount of "likes" the stream has.

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/overlaytwitter.png"
       alt="Overlay Twitter"
       style="max-width: 600px; width: 100%; height: auto;">
</div>

The second overlay, as I mentioned briefly, mimics Buzzfeed where the elements on the screen are made to look like you are reading an article on the website. Chatters are able to redeem their points to change the "trending" topics at the top of the screen or change the looping advertisements that appear above the streamers head. All of these elements come together to really give chatters the feel that they are watching something from the Buzzfeed website.

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/overlaybuzz.png"
       alt="Overlay Buzz"
       style="max-width: 600px; width: 100%; height: auto;">
</div>

The third and most recent overlay I designed was made to look similar to an old Windows 95 desktop and give viewers a nostalgic feel. Chat messages would come through as "Internet Mail" in a style that matches the original nearly identically. The streamer's reaction box, the gameplay live feed, and chatbox all have the appearance of computer tabs from that operating system. Users could spend points to make fake "pop-ups" show up from a random pool, and can change the appearance and text of icons on the desktop. Every tab featured on the screen acts and moves as if they we actually tabs on a desktop allowing the setup to move around and change the feel as frequently as wanted to give a new feel. Below is a picture of the overlay in use:

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/overlaywindows.png"
       alt="Overlay Windows"
       style="max-width: 600px; width: 100%; height: auto;">
</div>