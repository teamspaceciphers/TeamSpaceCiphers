<h1 align="center" style="font-size: 100px; font-family: 'Arial';"><strong> Team: Space Ciphers </strong></h1>

---

## Contents:

- [Introduction](#introduction)
- [Challenge: PACE in the Classroom](#challenge-pace-in-the-classroom)
  - [Challenge Overview](#challenge-overview)
  - [Summary](#summary)
- [Impact](#impact)
- [Challenge Faced & Solutions](#challenge-faced--solutions)
- [Tools We Use](#tools-we-use)
- [Features](#features)
- [Installation & Setup](#installation--setup)
- [Application](#application)
  - [Home Page](#home-page)
  - [Explore Page](#explore-page)
  - [Lessons Page](#lessons-page)
  - [Maps Page](#maps-page)
  - [Community Page](#community-page)
- [Team](#team)
  - [Members](#members)
  - [Mentors](#mentors)
  - [Special Thanks](#special-thanks)

---

## Introduction

This project bridges the gap between NASA’s PACE mission satellite data and educational resources. We aim to make oceanic and atmospheric data accessible and engaging for students of all age groups. Through interactive tools and lessons, we foster curiosity and encourage a deeper understanding of ocean literacy.

---

## Challenge: PACE In The Classroom

We are participating in the **Pace in the Classroom** challenge, which focuses on transforming complex data from NASA’s PACE satellite into engaging and digestible educational content for students worldwide.

### Challenge Overview

The **Plankton, Aerosol, Cloud, ocean Ecosystem (PACE) satellite** was launched on **February 8, 2024**, and has been gathering critical data about Earth’s oceans and atmosphere. This data, made publicly available by NASA, is often too technical for students and non-experts to grasp.

Our goal is to bridge this gap by developing engaging, kid-friendly educational materials that turn PACE’s scientific data into lessons for classrooms worldwide, promoting ocean literacy and inspiring curiosity.

### Summary

NASA’s PACE satellite collects essential data on Earth’s atmosphere and oceans, helping scientists understand phytoplankton and ocean-atmosphere interactions. However, the complexity of this data presents a barrier for students. 

Our project aims to convert this intricate data into interactive, engaging content that teachers can integrate into their curriculums, improving ocean literacy and inspiring the next generation to explore Earth sciences.

---

## Impact

With our interactive, easy-to-use tools, we aim to:

- **Increase ocean literacy** among students globally.
- **Inspire curiosity** about Earth sciences and climate change.
- **Empower students** to explore real-time satellite data in a fun and approachable way.

---

## Challenge Faced & Solutions

- **Challenge**: Making NASA’s complex PACE data accessible for younger audiences.
  - **Solution**: Simplified visualizations and tailored lesson materials to make the data engaging.

- **Challenge**: Managing large datasets with limited cloud storage.
  - **Solution**: Down-sampled the data to reduce size.

- **Challenge**: Slow rendering times when displaying the Earth globe data.
  - **Solution**: Added caching to speed up rendering.

- **Challenge**: Stack size exceeded error during data rendering.
  - **Solution**: Implemented data range limits based on metadata to prevent overflow errors.

---

## Tools We Use

- **Frontend**: React, Vite, Three.js, Node.js
- **Backend**: Python-Flask
- **Database/Cloud Storage**: MongoDB Atlas
- **Data Source**: [PACE Ocean Data API](https://oceandata.sci.gsfc.nasa.gov/api/file_search/)
- **AI Tools**: ChatGPT, Leonardo AI
- **Hosting**: Vercel (Frontend), GCP (Backend)
- **Domain**: Porkbun.com

---

## Features

- **Interactive 3D Globe Visualization** using Three.js
- Educational **videos** explaining how PACE collects data.
- Detailed exploration of PACE’s **scientific instruments**.
- **Kid-friendly lessons** and engaging materials.
- Easy-to-navigate **data visualizations**.
- **Simulations** for understanding marine life and atmosphere interactions.

---

## Installation & Setup

- *Clone the Repository:* 

```bash
git clone [repository link]
```

- *Backend:* 

```bash
cd path_to_folder\Hackathon-Team-Cipher\my-app\backend
```

```bash
pip install flask pymongo flask_cors
```

```bash
python .\app.py
```
 
- *Frontend:* 

```bash
cd path_to_folder\Hackathon-Team-Cipher\my-app\frontend\pace-in-the-classroom
```

```bash
npm install
```

```bash
npm run dev
```

---

## Application

### Home Page:

- Interaction with a 3D Earth globe.

  ![Home Page (1)](https://github.com/user-attachments/assets/9d1af1c4-691b-4bb6-90ae-9c5aa4c2258a)

  ![Home Page (3)](https://github.com/user-attachments/assets/f0198700-5575-4e7a-a408-f732bdcc732f)

### Explore Page:

- Learn about PACE’s instruments like **OCI**, **SPEXone**, and **HARP2**.

  ![Explore Page](https://github.com/user-attachments/assets/df82cf2d-3585-43a4-8401-f6d79e24b797)

### Lessons Page:

- Explore lessons on PACE, its instruments, and the ocean-atmosphere relationship.

  ![Lessons Page](https://github.com/user-attachments/assets/990a2d3b-73f8-48c3-82e3-f404717aa329)

  ![Lesson1 Page (1)](https://github.com/user-attachments/assets/0d70d257-a0cc-4b2f-9afb-d13992c5617a)

  ![Lesson2 Page](https://github.com/user-attachments/assets/26a2a2fd-89b2-4d06-8372-f447db773bc5)

  ![Lesson3 Page](https://github.com/user-attachments/assets/38e20309-395b-4e0c-a4b9-4f68857219a5)

### Maps Page:

- 2D Map & 3D Globe showing **Chlorophyll**, **Carbon** concentrations, and **Sea Surface Temperature**.

  ![Map Page](https://github.com/user-attachments/assets/8f760cb1-95e6-472e-9ad5-8d20cc8f4219)

### Community Page:

- Share your ideas and see what others have contributed.

  ![Community Page](https://github.com/user-attachments/assets/37bf811c-2685-4c3f-a2c4-873105f5e801)

---


## Team

### Members:

- **Devanshu Mangal** - Frontend & Backend
- **Ronit Rathod** - Backend, Database, Video Editor
- **Dhairya Prajapati** - Frontend
- **Manan Tarsariya** - Backend, Literature Survey
- **Jit Prajapati** - Website Deployment
- **Jainex Pumbhadiya** - Website Deployment

### Mentors:

- **Mr. Nishant Painter** - CEO & Founder, Shivantra.
- **Prof. (Dr.) Bintu Kadhiwala** - Assistant Professor, Computer Department, SCET.

### Special Thanks:

- Special thanks to **Prof. Dhatri Pandya** for her guidance. - Assistant Professor, Computer Department, SCET
- Thanks to **NASA** for access to PACE satellite data.

---
