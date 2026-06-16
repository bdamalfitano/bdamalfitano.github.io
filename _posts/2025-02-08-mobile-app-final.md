---
layout: page
title: "Mobile App Final Project"
header-img: "img/city3.jpg"
tags:
  - Flutter
  - Dart
  - Firebase
  - Authentication
  - Mobile Development
---

<style>
  header.intro-header {
    background-position: center 50%;
    height: 470px;
  }
</style>


<div class="project-tags">
  <span>Flutter</span>
  <span>Dart</span>
  <span>Firebase</span>
  <span>Authentication</span>
  <span>Mobile Development</span>
</div>

## Overview

Designed and implemented a mobile authentication system using Flutter and Firebase Authentication. The app provides a full user account flow including login, registration, and password recovery, with persistent session state managed through a Provider-based architecture.

The project was built as part of a mobile application development course, demonstrating integration between a Flutter frontend and a live Firebase backend.

## Technologies Used

- Flutter  
- Dart  
- Firebase Authentication  
- Firebase Core  
- Provider (State Management)  

## System Design Process

### Step 1 Firebase Setup and Configuration

The project began with connecting the Flutter app to a Firebase project:

- Firebase initialized at app startup via `firebase_options.dart`  
- Platform-specific configuration for Android  
- Firebase Authentication enabled as the backend identity provider  

### Step 2 Authentication Provider and State Management

A `ChangeNotifierProvider` was used to manage auth state across the app:

- `AuthProvider` class tracks whether a user is currently authenticated  
- `AuthWrapper` widget listens to auth state and routes users automatically  
- Authenticated users are sent to the home screen; unauthenticated users to login  
- State updates propagate reactively throughout the widget tree  

### Step 3 Screen Architecture

The app was structured around four dedicated screens:

- **Login Screen** — email and password sign-in with Firebase  
- **Register Screen** — new account creation with validation  
- **Forgot Password Screen** — password reset email via Firebase  
- **Home Screen** — authenticated landing page with session info  

Named routes were used for clean navigation between all screens.

## Key Features

- Full user authentication flow with Firebase  
- Persistent session state using Provider  
- Automatic routing based on authentication status  
- Login, registration, and password reset screens   
- Clean separation of services, screens, providers, and widgets

<div style="text-align:center; margin:40px 0;">
  <img src="{{ site.baseurl }}/assets/images/projects/mobileappfinallogin.png"
       alt="Overlay Twitter"
       style="max-width: 400px; width: 100%; height: auto;">
</div>