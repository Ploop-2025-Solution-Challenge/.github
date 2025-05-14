<div align="center">
  
# Ploop

<img src='assets/ploop-applogo.png' width=150px/>
</br>

### Pick, Plog, and Keep the Loop Going!

APAC Solution Challenge 2025 Project
</br> </br>
Google Developer Group on Campus : SEOULTECH
</br> **Team Monday**

</div>

<hr />

## Content
- [Overview](#overview)
  - [What is Plogging?](#what-is-plogging)  
  - [Introducing Ploop](#then-what-is-ploop-app)  
  - [Goals of Ploop](#goal)  
- [Components](#components)  
- [Project Architecture](#project-architecture)  
- [Features](#application-features)  
  - [Signing In](#sign-up--sign-in)
  - [Settings & Preferences](#user-info-settings--preferences) 
  - [Weekly Missions](#weekly-missions)  
  - [Start Plogging](#plogging)  
  - [Map Components](#map-components)
  - [Uploading locations](#uploading-litter-area--trach-bin)
  - [Global Routes](#global-routes)
  - [Activity Dashboard](#activity-dashboard)
- [About Sensitive Information](#%EF%B8%8F-api-keys-are-not-included-in-this-repository)  
- [Contributors](#contributors)  

   
</br>

## Overview




### What is Plogging?
Plogging is a combination of "jogging" and the Swedish word "plocka upp", which means "to pick up."

> Plogging = jogging + plocka upp

In simple terms, plogging is an eco-friendly fitness activity where people pick up litter while jogging.

</br>

### Then, What is `Ploop` App?


Ploop is a mobile app designed to make plogging — the act of picking up litter while jogging — more accessible, purposeful, and fun.

In cities like Seoul, littering remains a social crisis, not only because of the growing volume of waste, but because it often goes unmonitored. Despite rising awareness around sustainability, daily habits are hard to change, and public systems can’t always keep up.

**Ploop aims to bridge that gap through simple, individual action.**

By turning everyday walks into missions, encouraging photo-based litter reports, and tracking activity with real-time maps and data, Ploop empowers users to make a measurable impact in their local communities.

Whether you’re walking alone or contributing to global routes, Ploop helps you visualize your actions, stay motivated, and be part of a wider movement—one walk at a time.

**Pick, Plog, and Keep the Loop Going.**

<br /><br />

▶ Ploop Demo Video  
<br />
<a href="https://youtu.be/rB9DLo2qyMw?feature=shared">
![thumbnail4](https://github.com/user-attachments/assets/a3802801-10bf-4716-8c4d-ea5c9a3510a9)
</a>

</br>

### Goal
Ploop’s goal is to transform the way individuals engage with environmental action—making it **part of their everyday routines**, not just occasional events.

Specifically, we aim to:
- 🌍 Encourage sustainable habits by turning walking or jogging into opportunities for litter cleanup

- 🤝 Encourage shared engagement through weekly partner missions and globally visible routes

- 📊 Generate meaningful data on litter patterns that can inform local policies and urban planning

- 📱 Make environmental contribution fun, accessible, and measurable through technology

- 🔁 Create a self-sustaining cycle of small actions that lead to long-term impact

With Ploop, we’re not just cleaning up trash—we’re building a culture of continuous environmental awareness and action

</br>


## Components

### Frontend

<img src="https://img.shields.io/badge/Framework-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white"><img src="https://img.shields.io/badge/3.29.2-515151?style=for-the-badge">  
<img src="https://img.shields.io/badge/Language-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white"><img src="https://img.shields.io/badge/3.7.2-515151?style=for-the-badge">

### Backend
<img src="https://img.shields.io/badge/Framework-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/Spring Boot-%236DB33F.svg?style=for-the-badge&logo=Spring&logoColor=white"><img src="https://img.shields.io/badge/3.4.4-515151?style=for-the-badge">  
<img src="https://img.shields.io/badge/Language-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white"><img src="https://img.shields.io/badge/17.0.14-515151?style=for-the-badge">  
<img src="https://img.shields.io/badge/Database-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=MySQL&logoColor=white"><img src="https://img.shields.io/badge/9.2.0-515151?style=for-the-badge">

### AI
<img src="https://img.shields.io/badge/Framework-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"><img src="https://img.shields.io/badge/0.110.0-515151?style=for-the-badge"><br>
<img src="https://img.shields.io/badge/Library-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"><img src="https://img.shields.io/badge/2.2.2-515151?style=for-the-badge"><br>
<img src="https://img.shields.io/badge/API-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white"><img src="https://img.shields.io/badge/v2.0 FLASH-515151?style=for-the-badge"><br>


### Design
<img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white">

<br />

### Devices used for testing
- Physical Devices
  - iPhone 16 Pro
  - Samsung Galaxy S23
  - Samsung Galaxy S21

- Virtual Devices
  - iPhone 16, iPhone 16 Plus, iPhone 16 Pro Max, iPhone SE (3rd Generation) (Xcode Simulator)
  - Medium Phone API 36 (Android Emulator)

<br/>

## Project Architecture
<img src="https://github.com/user-attachments/assets/5d383022-df0b-4b24-b157-4c3836eb3cfc"/></br>

<br/>

## Application Features
### Sign Up & Sign In

<img src="https://github.com/user-attachments/assets/fc0f7d18-2e93-4c5e-bcd2-22c1b7f98a15" height="300"></br>
Ploop uses Google OAuth for to sign up. Connect your Google profile to the service.  
<br/>

### User Info Settings & Preferences
<img src="https://github.com/user-attachments/assets/8db5e798-580f-4678-969f-da6512fc82b2" height="300"></br>
Set up your region, nickname, and so on.  
Your preferred area and engagement style reported on this step will be used for matching partner for weekly missions.  

<br/>

### Weekly Missions
<img src="https://github.com/user-attachments/assets/d1c3e297-48c2-4da3-9eea-8539bd06220d" height="300"/></br>
Ploop gives you 3 new missions every week. They're not mandatory, but they'll keep you engaged in small environmental actions.  
Set a goal to complete 100% of the missions each week with your partner!  

<br/>
if there's no mission this week, we'll show you this screen.  
<br/>

<img src="https://github.com/user-attachments/assets/cbbae95f-d5c6-4b10-a450-799c31b40755" height="300"/> 
<br/><br/>

### Plogging
<img src="https://github.com/user-attachments/assets/f748cd13-eac7-4397-a746-9bbbd209a61b" height="300"/>
<br/>
Ploop is designed to track your realtime activity, simple and efficiently.  
To track it more efficiently, please allow Ploop to access your location services.  

<br/>
<br/>

### Map Components
<img src="https://github.com/user-attachments/assets/91485af7-6f91-4708-a802-8990450a6a28" height="300"/>
<br/>
Ploop uses Google Maps API to display areas reported as heavily littered or locations of nearby trash bins.  
Based on this data, Ploop recommends a daily plogging route tailored to your surroundings.  
Start plogging with a motivational message powered by Gemini!  

</br>
<br/>

### Uploading litter area & trach bin
<img src="https://github.com/user-attachments/assets/d6d18cc0-4e25-4784-abcb-d6e0a7538f43" height="600"/>
<br/>
To report a littered area or a trash bin, simply open the camera on the map and take a photo.  
The location will be automatically uploaded to the server.  
All you need to do is specify whether you found litter or a bin.

<br/>
<br/>

### Global Routes
<img src="https://github.com/user-attachments/assets/44fc31d0-510b-4814-9c80-b573f456d465" height="300"/>
</br>
No manual uploads needed — explore the world and trace other users' footprints.
Others might even follow your plogging route, too.

<br/>
<br/>

### Activity Dashboard
<img src="https://github.com/user-attachments/assets/6a3ca752-2420-4afe-8c91-0addbb60236c" height="300"/>
<br/>
Track your environmental journey on your activity dashboard.
Ploop helps you look back on how much you've contributed to a cleaner planet with intuitive graphs.


### Logic


<br/>



## ⚠️ API Keys are not included in this repository

To run this app from code, follow these instructions:

- Please check submitted prototype folder.
- Add `.env` file at the root directory of the `Ploop-FE/` folder.
- Follow the next instructions for each platform.

### iOS

Add `GoogleService-Info.plist` file into `Ploop-FE/ios/Runner` folder.

### Android

Add `google-services.json` file into `Ploop-FE/android/app` folder.

<br/>

## Contributors
<center>
   <table>
  <tr>
    <td align="center">
       <a href="https://github.com/4ch1o3">
       <img src="https://avatars.githubusercontent.com/u/109056574?v=4" width="100px" alt=""/></a><br />
       <b>Jiwon Lee</b><br />
       Flutter
    </td>
    <td align="center">
       <a href="https://github.com/xxrainow">
          <img src="https://avatars.githubusercontent.com/u/90715224?s=70&v=4" width="100px;" alt=""/></a><br />
       <b>Jiwoo Shin</b><br/>
       Database & Server
    </td>
    <td align="center">
       <a href="https://github.com/hohosznta">
          <img src="https://avatars.githubusercontent.com/u/125850243?v=4" width="100px;" alt=""/></a><br />
       <b>Yoolim Han</b><br/>
       AI & Server
    </td>
    <td align="center">
      <a href="https://www.behance.net/SoyeonAhn_yyyy">
      <img src="https://github.com/user-attachments/assets/fdd97809-ec24-40ca-aad4-8c24ed298230" width="100px;" alt=""/></a><br />
      <b>Soyean Ahn</b><br/>
      Design
    </td>
  <tr>
<table>
</center>

