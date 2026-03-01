---
layout: page
title: "TV Shuffle"
tags:
  - Windows Scripting
  - PowerShell
  - rclone
  - Automation
  - Media Streaming
  - VLC
---

<div class="project-tags">
  <span>Windows Scripting</span>
  <span>PowerShell</span>
  <span>rclone</span>
  <span>Automation</span>
  <span>Media Streaming</span>
  <span>VLC</span>
</div>

## Overview
I purchased a 4-inch monitor secondhand to use as a miniature TV for my workspace. I wanted to simulate a live television experience using my favorite shows, but with full control over the content. The challenge was to handpick specific shows, shuffle them dynamically, and stream them without storing the video files locally on my PC.

## Technologies
- Windows Batch Scripting
- PowerShell
- VLC Media Player
- rclone (Cloud Storage Integration)
- HTTP Streaming
- VFS Caching

## How It Works

1. A PowerShell script generates a new randomized `.m3u` playlist on each launch.
2. VLC launches in fullscreen mode with randomization and looping enabled.
3. An rclone HTTP server runs in the background to stream media files from remote cloud storage.
4. VFS caching is enabled to optimize buffering and playback performance.

All background processes run hidden, creating a seamless, single-click experience.

Video files are streamed remotely from multiple cloud storage providers (Google Drive and Mega) via rclone and piped directly into VLC for playback.

## Key Features
- Dynamic playlist generation
- Full automation (single-click execution)
- Background process management
- Remote cloud-based media streaming
- Seamless user-facing experience

# The Final Result
<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/tvshuffle.jpg"
       alt="TV Shuffle Setup"
       style="max-width: 700px; width: 100%; height: auto;">
</div>