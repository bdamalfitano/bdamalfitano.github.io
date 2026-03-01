---
layout: page
title: "Stream Overlays"
header-img: "img/city1.jpg"
tags:
  - Twitch
  - Livestream
  - Graphic Design
  - Mix It Up
  - UI/UX Design
  - Live Data Integration
  - JavaScript
  - Photoshop
---

<div class="project-tags">
  <span>Twitch</span>
  <span>Livestream</span>
  <span>Graphic Design</span>
  <span>Mix It Up</span>
  <span>UI/UX Design</span>
  <span>Live Data Integration</span>
  <span>JavaScript</span>
  <span>Photoshop</span>
</div>

## Overview
Designed and implemented dynamic stream overlays for streaming platforms (primarily Twitch, but adaptable to others) to improve interaction between streamers and their audiences. I used Mix It Up to implement the backend automation logic that allows chat participants to interact directly with on-screen elements in real time.

## Technologies
- HTML
- CSS
- JavaScript
- Mix It Up (Automation Software)
- Live Chat Event Hooks
- Photoshop

## Key Features
- Responsive overlay components  
- Real-time updates  
- Custom animation effects  
- Chat-driven on-screen interactions  

All overlays were visually designed in Photoshop, while interactive elements were implemented using Mix It Up and integrated with Twitch’s event system.

---

# Implementation

The first two overlays were designed to mimic popular social media platforms, Twitter and BuzzFeed, with the twist that nearly all on-screen text and images dynamically change based on viewer interaction.

In the Twitter-themed overlay, when a viewer sends a chat message, their username, profile icon, and message appear on screen as a simulated Twitter comment. Twitch allows frequent viewers to redeem channel points, and several of these redemptions trigger changes to on-screen elements such as trending topics or the number of “likes” displayed during the stream.

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/overlaytwitter.png"
       alt="Overlay Twitter"
       style="max-width: 600px; width: 100%; height: auto;">
</div>

The second overlay mimics the layout of BuzzFeed, where the stream presentation resembles an interactive online article. Viewers can redeem points to change the “trending” topics at the top of the screen or modify the rotating advertisements displayed above the streamer’s video feed. These interactive elements enhance immersion and create a more engaging viewing experience.

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/overlaybuzz.png"
       alt="Overlay Buzz"
       style="max-width: 600px; width: 100%; height: auto;">
</div>

The third and most recent overlay was designed to resemble a Windows 95 desktop, creating a nostalgic user experience. Chat messages appear as “Internet Mail” in a style closely matching the original operating system. The streamer’s camera feed, gameplay display, and chat box are styled as movable desktop windows.

Viewers can redeem points to trigger randomized pop-up notifications and modify desktop icons dynamically. Each on-screen window behaves like a movable desktop tab, allowing the layout to be rearranged during the stream and creating a constantly evolving interface.

Below is an image of the overlay in use:

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/overlaywindows.png"
       alt="Overlay Windows"
       style="max-width: 600px; width: 100%; height: auto;">
</div>