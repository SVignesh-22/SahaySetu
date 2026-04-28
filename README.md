# SahaySetu  
### Bridge to Help — AI-powered NGO Volunteer Coordination

> Built for Google Solution Challenge 2026 · Problem Statement 5: Smart Resource Allocation

---

##  Problem Statement
NGO coordinators in India manage volunteer work through scattered WhatsApp messages, paper registers, and outdated spreadsheets. There is no clear, real-time visibility of which areas need help most urgently.

---

##  The Solution
SahaySetu enables field workers to report situations naturally in Hindi or English using text or voice. Gemini AI understands full context, extracts key information like location, urgency, resource type, and priority score — and plots it instantly on a live map.

All data is synchronized in real-time using Firebase, ensuring every volunteer sees the same updated information across devices.

---

##  How It Works
1. Field worker types or speaks a need  
   _"50 families in Dharavi have had no food for 2 days, very urgent"_  
2. Gemini AI analyzes context and extracts structured data  
3. Data is stored and synced in real-time using Firebase  
4. Need appears on a live map with color-coded urgency  
5. Coordinators view and prioritize needs  
6. Volunteers respond and mark tasks as resolved  

---

##  Tech Stack

| Technology | Use |
|-----------|-----|
| HTML / CSS / JavaScript | Frontend |
| Google Gemini AI | AI-powered need extraction |
| Puter.js | Gemini API access + Google Auth |
| Firebase Firestore | Real-time database & sync |
| Leaflet.js | Interactive map visualization |
| CartoDB / OpenStreetMap | Map tiles |
| Web Speech API | Voice input support |

---

##  Live Demo
 [Open SahaySetu](https://sahaysetu.netlify.app/)

---

##  Features
- AI-powered context understanding (Gemini)  
- Supports Hindi, English, and Hinglish input  
- Voice input support  
- Real-time synchronization across devices (Firebase)  
- Live map with color-coded urgency markers  
- Automatic urgency detection & priority scoring  
- Filter-based dashboard (urgent, high, medium, low)  
- One-click reporting and confirmation flow  
- Task resolution tracking (mark as done)  

---

##  Impact
SahaySetu reduces response time, improves coordination, and ensures help reaches the right place at the right time by converting unstructured human input into actionable intelligence.

---
