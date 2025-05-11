## Voice Journal 🎤📔 + 🗄️
A full-stack voice-first journaling app that converts spoken thoughts into organized, searchable entries. Built with React, HTML, CSS and JS (frontend), Node.js/Express (backend), and Deepgram’s speech-to-text API.

👉 Live Demo: [https://ssubhashini2004.github.io/smart-journal-frontend/]

🚀 Backend Hosting: Render

🔗 Frontend Repo: [https://github.com/ssubhashini2004/smart-journal-frontend]

🔗 Backend Repo: [https://github.com/ssubhashini2004/server]

## Demo Screenshots - Experience the UI

Personalised Themes Resembling the conventional Light and Dark Modes

![image](https://github.com/user-attachments/assets/5784da23-95cb-48a4-ace6-fe6b65052b1e)


![image](https://github.com/user-attachments/assets/a8229f44-f2e0-4717-8d55-b26efb6976e4)


The Journals - Your thoughts poured into words

![image](https://github.com/user-attachments/assets/eb996a92-e2e3-4bff-920c-2d81c8ea39dd)

![image](https://github.com/user-attachments/assets/108e994e-2624-4b51-88a8-eb96cd6ebccb)

Want a short diary file based on your entries? Click on Export PDF and download it now:

![image](https://github.com/user-attachments/assets/baa17433-33df-4361-acca-da9c24136492)


Don't know how to describe your thoughts? We have you covered - just click on start recording and speak and let us transcribe them for you!

![image](https://github.com/user-attachments/assets/0f22e85c-8fa1-4ef2-9335-b98d9729056d)

Want a specific entry? Search for keywords to extract that entry:

![image](https://github.com/user-attachments/assets/40c52b87-21b7-45a8-a07b-df5d0f6b4b31)




## Introduction

Voice Journal eliminates the friction of traditional typing-based journaling by:

🎙️ Converting speech to text in real-time using Deepgram

🏷️ Auto-organizing entries with smart tags and search

🔒 Securing data via JWT authentication and encrypted storage

**Frontend:** Responsive React app for recording, editing, and browsing entries.
**Backend**: Node.js/Express API handling speech processing, database operations, and user auth.

## Features

**Core Features**

**Frontend	Backend**

🎤 Real-time voice recording & transcription	🔐 JWT authentication & authorization
📅 Date/tag-based entry filtering	🔊 Deepgram speech-to-text processing
🖋️ Entry editing & PDF export	🗃️ MongoDB CRUD operations for entries
🔍 Keyword search across entries	🔎 Full-text search & filtering API
🌓 Light/dark theme toggle	📈 Auto-tagging via NLP analysis

**Advanced Features**

Offline Drafts: Start journaling without internet - Download PDF Version


## Tech Stack

**Frontend:**

HTML
JavaScript
React
Tailwind CSS
Deepgram

**Hosting:** GitHub Pages

**Backend**
Node.js
Express
MongoDB

**Hosting: Render**

## Installation

**Prerequisites**

Node.js v18+

MongoDB Atlas account

Deepgram API key

**1. Frontend Setup**
bash
git clone https://github.com/ssubhashini2004/smart-journal-frontend.git  
cd smart-journal-frontend  
npm install  
Create .env:

env
REACT_APP_API_URL=<your_backend_url>  
REACT_APP_DEEPGRAM_API_KEY=<your_deepgram_key>  

**2. Backend Setup**
bash
git clone https://github.com/ssubhashini2004/server.git  
cd server  
npm install  
Create .env:

env
MONGODB_URI=<your_mongodb_uri>  
JWT_SECRET=<your_jwt_secret>  
DEEPGRAM_API_KEY=<your_deepgram_key>  

**3. Run Both**

In frontend directory:  
npm start  

In backend directory:  
npm run dev  
Usage Workflow
User Authentication

Sign up via frontend ➔ Backend creates JWT ➔ MongoDB stores encrypted credentials

## Voice Journaling

**Diagram**
![image](https://github.com/user-attachments/assets/59dedf3a-f6c6-48f9-bddc-9c0ef3e9e1ec)


## Contributing

**Frontend Changes**: 

Follow frontend guidelines here: [https://github.com/ssubhashini2004/voice-journal-frontend]

**Backend Changes:**

Write Jest tests for new API endpoints

Update API documentation in API_DOCS.md

Full-Stack Features: Coordinate environment variable updates

## License
MIT © Subhashini
