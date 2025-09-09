<div align="center">
  
# Ploop

![AppLogo](https://github.com/user-attachments/assets/721b1091-9c59-404a-a9b7-cf93ced41987)

### Pick, Plog, and Keep the Loop Going!

APAC Solution Challenge 2025 Project </br>
Side Impact 2025 Project
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
- [AI](#ai-1)
  - [Trash Detection](#trash-detection)
  - [Team Matching](#team-matching)
- [Features](#application-features)  
  - [Signing In](#sign-up--sign-in)
  - [Settings & Preferences](#user-info-settings--preferences) 
  - [Weekly Missions](#weekly-missions)  
  - [Start Plogging](#plogging)  
  - [Map Components](#map-components)
  - [Uploading locations](#uploading-litter-area--trach-bin)
  - [Global Routes](#global-routes)
  - [Activity Dashboard](#activity-dashboard)
- [Releases](#releases)
- [About Sensitive Information](#%EF%B8%8F-api-keys-are-not-included-in-this-repository)  
- [Team](#team)  

   
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
<br/>

## AI
### Trash detection
We used YOLOv11 to detect trash real-time. YOLOv11 is the latest version in the Ultralytics YOLO series, achieving breakthroughs in accuracy, speed, and efficiency in the field of real-time object detection.

![image](https://github.com/user-attachments/assets/3956e647-8a10-42df-8314-31228bcce173)
<br/>
Since we expected users to take photos of trash outdoors, we selected a dataset that accurately reflects such outdoor environments. Transfer learning was performed on [trash detection dataset (TACO)](https://universe.roboflow.com/ptit-rbnp6/trash-detect-taco/dataset/2), and the resulting model was deployed as an API service using FastAPI on Google Cloud. You can see our model being used when [verifying missions](#weekly_missions). 

### Team Matching
Another way of using ai was in Team Matching in Missions. Text data from users was processed using PyTorch-powered sentence embeddings via SentenceTransformers, enabling us to compute semantic similarity across user motivations and behaviors. This allowed us to match users with others who share similar goals or engagement styles. Pinecone was used as our vector database for efficient real-time similarity search. <br/>

![image](https://github.com/user-attachments/assets/36e33440-defe-4665-9f28-f0e9c00e4f3e)




<br/>

## Application Features
### Sign Up & Sign In

![Frame 289992](https://github.com/user-attachments/assets/e138d0d4-aed0-4c11-a475-2d3c77f3e6b8)
- Ploop uses Google OAuth for to sign up. Connect your Google profile to the service.  
<br/>

### User Info Settings & Preferences
![signup](https://github.com/user-attachments/assets/c775142b-f610-45e5-a2a1-3861f1f85bda)

- Set up your region, nickname, and so on.  
Your preferred area and engagement style reported on this step will be used for matching partner for weekly missions.  

<br/>

### Weekly Missions
![mission](https://github.com/user-attachments/assets/e7c5a997-ede5-40be-aee9-93c701e49101)
- Ploop gives you 3 new missions every week. They're not mandatory, but they'll keep you engaged in small environmental actions.  
Set a goal to complete 100% of the missions each week with your partner!  

<br/>

- if there's no mission this week, we'll show you the screen below.
  
![missionno](https://github.com/user-attachments/assets/c8ad1371-92e9-4eaa-b608-c5b5bb54894b)

<br/>

### Plogging
![plogging](https://github.com/user-attachments/assets/1e36f39c-40c6-4d33-90f2-ecef92b482f6)

- Ploop is designed to track your realtime activity, simple and efficiently.  
To track it more efficiently, please allow Ploop to access your location services.  

<br/>

### Map Components
![segment-filter](https://github.com/user-attachments/assets/eaaaf192-0761-4c91-970f-c59daf3cbc1a)

- Ploop uses Google Maps API to display areas reported as heavily littered or locations of nearby trash bins.  
Based on this data, Ploop recommends a daily plogging route tailored to your surroundings.  
Start plogging with a motivational message powered by Gemini!  

<br/>

### Uploading litter area & trach bin
![map-integration](https://github.com/user-attachments/assets/77aa0f34-e98b-4664-a411-0320f577efe5)

- To report a littered area or a trash bin, simply open the camera on the map and take a photo.  
The location will be automatically uploaded to the server.  
All you need to do is specify whether you found litter or a bin.

<br/>

### Global Routes
![world](https://github.com/user-attachments/assets/731eed8e-b6e5-4dd4-875b-abc692f2019a)

- No manual uploads needed — explore the world and trace other users' footprints.
Others might even follow your plogging route, too.

<br/>

### Activity Dashboard
![activity](https://github.com/user-attachments/assets/471d6288-9159-466c-b7c7-e443fc96e0ed)

- Track your environmental journey on your activity dashboard.
Ploop helps you look back on how much you've contributed to a cleaner planet with intuitive graphs.



<br/>
<br/>

## Releases
|Version|Release Page|
|:--:|:--:|
|v0.1.0 **(Latest)** |[Ploop (0.1.0)](https://github.com/Ploop-2025-Solution-Challenge/Ploop-FE/releases/tag/v0.1.0)|

<br/>
<br/>


## ⚠️ API keys are not included in this repository
To run this app from the source code, please follow the instructions below:

- Check the submitted prototype folder.
  - Note: The folder is provided only to the judges.
- Add `.env` file to the root directory of the `Ploop-FE/` folder.

Alternatively, you can use your own client IDs and API keys.
Follow the platform-specific instructions below:


### iOS
- Add the `GoogleService-Info.plist` file to the `Ploop-FE/ios/Runner` folder.


### Android
- Add the `google-services.json` file to the `Ploop-FE/android/app` folder.

<br/>

## Team

   <table>
  <tr>
    <td align="center">
      <a href="https://www.behance.net/SoyeonAhn_yyyy">
      <img src="https://github.com/user-attachments/assets/fdd97809-ec24-40ca-aad4-8c24ed298230" width="100px" alt=""/></a><br />
      <b>Soyeon Ahn</b><br/>
      Design
    </td>
    <td align="center">
       <a href="https://github.com/4ch1o3">
       <img src="https://avatars.githubusercontent.com/u/109056574?v=4" width="100px" alt=""/></a><br />
       <b>Jiwon Lee</b><br />
       Flutter
    </td>
    <td align="center">
       <a href="https://github.com/xxrainow">
          <img src="https://avatars.githubusercontent.com/u/90715224?s=70&v=4" width="100px" alt=""/></a><br />
       <b>Jiwoo Shin</b><br/>
       Database & Server
    </td>
    <td align="center">
       <a href="https://github.com/hohosznta">
          <img src="https://avatars.githubusercontent.com/u/125850243?v=4" width="100px" alt=""/></a><br />
       <b>Yoolim Han</b><br/>
       AI & Server
    </td>
  <tr>
<table>


