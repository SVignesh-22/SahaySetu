# SahaySetu 
### Bridge to Help — AI-powered NGO Volunteer Coordination

> Built for Google Solution Challenge 2026 · Problem Statement 5: Smart Resource Allocation

---

## The Problem
NGO coordinators in India manage volunteer work through scattered WhatsApp messages, paper registers and outdated spreadsheets. There's no clear picture of which area needs help most urgently.

## The Solution
SahaySetu lets field workers describe any situation naturally in Hindi or English using text or voice. Gemini AI reads the full context, extracts the location, urgency level, resource type and priority score — then plots it instantly on a live map of India.

---

## How It Works
1. Field worker types or speaks a need — _"50 families in Dharavi have had no food for 2 days,very urgent "_
2. Gemini AI analyses the full context and extracts structured data
3. Need appears on the live map with colour-coded urgency
4. Coordinators see all active needs sorted by priority and assign volunteers

---

## Tech Stack
| Technology | Use |
|---|---|
| HTML / CSS / JavaScript | Frontend |
| Google Gemini AI | AI-powered need extraction |
| Puter.js | Gemini API access + Google Auth |
| Leaflet.js | Interactive live map |
| CartoDB / OpenStreetMap | Map tiles |

---

## Live Demo
Click the below link to open SahaySetu :  
[Open SahaySetu](https://sahaysetu.netlify.app/)

---

## Features
- Gemini AI understands Hindi, English and Hinglish
- Live map with colour-coded urgency pins across India
- Voice input support
- Google Sign-in via Puter
- Priority scoring and urgency filtering
