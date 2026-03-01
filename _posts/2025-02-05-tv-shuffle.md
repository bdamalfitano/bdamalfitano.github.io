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
I purchased a 4 inch monitor secondhand to use as a little TV for my workspace, and I wanted to simulate the live TV experience using my favorite shows. The issue was I wanted to handpick the shows, shuffle it, all without having the files taking space on my PC. 

## Technologies
- Windows Batch Scripting
- PowerShell
- VLC Media Player
- rclone (Cloud Storage Integration)
- HTTP Streaming
- VFS Caching

## How It Works

1. A PowerShell script generates a new randomized `.m3u` playlist on each launch.
2. VLC is launched in fullscreen with randomization and looping enabled.
3. An rclone HTTP server is started in the background to stream media files from remote storage.
4. VFS caching is enabled to optimize playback performance.

All background processes are launched hidden, creating a seamless user experience. All video files are grabbed remotely through multiple Google Drive and Mega files remotely through rclone and outputed to VLC.

## Key Features
- Dynamic playlist generation
- Full automation (single-click execution)
- Background process management
- Remote media streaming
- Clean user-facing experience

# The Final Result:
<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/tvshuffle.jpg"
       alt="TV"
       style="max-width: 700px; width: 100%; height: auto;">
</div>
