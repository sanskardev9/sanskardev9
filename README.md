# Hey, I'm Sanskar 👋

Full-Stack Developer | React | Next.js | Node.js | Python  
Focused on real-time systems, geospatial applications & scalable full-stack architectures  

> I build apps that solve my own everyday problems, end to end.

---

## About Me

Most of my projects start with a problem in my own life. Losing track of my spending became **MoneyMate**. Riding with friends and losing each other on the road became **RideMate**. Applying to jobs one by one became **JobChain**. Struggling to stick to my workout and diet plans became **FitMate**.

I build each one end to end: the interface, the APIs and database, and the real-time and background parts that make it feel effortless to use.

Things I enjoy working on:
- Real-time data sync between devices and the cloud  
- WebRTC voice calls and live communication  
- Maps, live location and route optimisation  
- Planning how the frontend, servers and database fit together  

---

## Tech Arsenal

### Frontend
![React](https://img.shields.io/badge/React-black?style=for-the-badge&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js)
![React Native](https://img.shields.io/badge/React_Native-black?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-blue?style=for-the-badge&logo=typescript)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=for-the-badge&logo=javascript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css)
![ShadCN](https://img.shields.io/badge/shadcn/ui-black?style=for-the-badge)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa)

---

### Real-Time & Systems
![WebRTC](https://img.shields.io/badge/WebRTC-red?style=for-the-badge)
![WebSockets](https://img.shields.io/badge/WebSockets-grey?style=for-the-badge)
![Web Push](https://img.shields.io/badge/Web_Push-grey?style=for-the-badge)
![Canvas](https://img.shields.io/badge/HTML5_Canvas-orange?style=for-the-badge)

---

### Maps & Geospatial
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet)
![MapLibre](https://img.shields.io/badge/MapLibre-blue?style=for-the-badge)
![Google Maps](https://img.shields.io/badge/Google_Maps-green?style=for-the-badge&logo=googlemaps)
![Valhalla](https://img.shields.io/badge/Valhalla-grey?style=for-the-badge)

---

### Backend & Database
![Node.js](https://img.shields.io/badge/Node.js-green?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/Express-black?style=for-the-badge&logo=express)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-green?style=for-the-badge&logo=mongodb)

---

### Infra & Deployment
![Docker](https://img.shields.io/badge/Docker-blue?style=for-the-badge&logo=docker)
![Vercel](https://img.shields.io/badge/Vercel-black?style=for-the-badge&logo=vercel)
![Render](https://img.shields.io/badge/Render-purple?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
---

## Featured Projects

### 1. FitMate — Workout & Diet Plans That Are Easy to Follow
*Why I built it: I kept losing track of my workout and diet plans after the first week.*

An installable fitness app that turns any workout and diet plan into one daily checklist, with streaks, smart reminders and plans that progress on their own.

- Works without internet: data is saved on the device (IndexedDB / Dexie) and synced to Supabase  
- Progressive overload from logged sets, with 4-week blocks and a lighter recovery week  
- Adaptive diet: weekly menu rotation, macro gap suggestions, calories adjusted from the weight trend  
- Server-scheduled Web Push reminders (pg_cron + VAPID) and Duolingo-style streaks with freezes  
- AI plan builder, YouTube form/recipe videos and an in-app music player  

Live Demo: https://fitmateapp.vercel.app  
Repo: https://github.com/sanskardev9/Fitmate  

---

### 2. JobChain — Job Search, Tracking & Assisted Applying
*Why I built it: applying to jobs one by one, and keeping track of them all, took too much time.*

A job search and application tracker with JobPilot, a rule-based assistant that finds matching roles across Europe and drafts tailored application emails.

- Live job search across Europe (EURES, Arbeitnow) and remote roles (Remotive)  
- Transparent, rule-based job scoring against your profile (no AI black box)  
- Application tracker: applied → interview → offer / rejected  
- Draft-first emails you approve, sent from your own Gmail (send-only OAuth scope)  
- Next.js + Supabase (RLS, private CV storage) with a Python worker on Render  

Live Demo: https://job-chain.vercel.app  
Repo: https://github.com/sanskardev9/Job-Chain  

---

### 3. RideMate — Real-Time Group Riding & Safety
*Why I built it: on group rides we kept losing each other on the road.*

A mobile-first group riding application focused on live location sharing, real-time communication, and rider safety.

- Real-time location sharing using WebSockets  
- Interactive maps powered by Leaflet and OpenStreetMap  
- Ride sessions with duration, distance, and ride history  
- Emergency SOS alerts with live location sharing  
- Real-time group chat and WebRTC voice calling  
- Node.js / Express backend with a WebSocket server, JWT auth and PostgreSQL  

Live Demo: https://ride-mate-frontend-r1lp.vercel.app/  
Repo: [Frontend](https://github.com/sanskardev9/RideMate-Frontend) · [Backend](https://github.com/sanskardev9/RideMate-Backend)  

---

### 4. RouteMate — Real-Time Route Optimization & Simulation
A full-stack routing system with dynamic re-routing, geospatial constraints, and vehicle simulation.

- Real-time vehicle movement simulation along routes  
- Custom routing with toll/highway avoidance  
- No-entry zone detection using Supabase + Shapely  
- Valhalla-based routing engine with Docker setup  
- Map-based UI with interactive controls  

---

### 5. RealTimeRivals — WebRTC Multiplayer Fighting Game
A real-time 1v1 browser fighting game using peer-to-peer communication.

- WebRTC data channels for low-latency gameplay  
- Host-authoritative game state management  
- Integrated voice chat using WebRTC media streams  
- Canvas-based game engine with custom physics & combat logic  
- Room-based multiplayer with WebSocket signaling  

Repo: https://github.com/sanskardev9/RealTime-Rivals  
Demo: https://youtu.be/ph4oxrqVMrw  

---

### 6. MoneyMate — Personal Finance Habit Builder
*Why I built it: I never knew where my money went each month.*

A mobile-first finance app focused on improving user consistency in expense tracking.

- Budget planning & income tracking  
- Smart insights & behavioral nudges  
- SMS-based auto expense detection (Android)  
- Built with React Native + Supabase  

Repo: https://github.com/sanskardev9/MoneyMate  

---

## What I’m Interested In

- Building products that solve real problems, starting with my own  
- Real-time systems & data synchronization  
- Maps, live location and logistics applications  
- Fast, reliable apps that work on any connection  
- Planning how the frontend, servers and database fit together as an app grows  

---

## Connect With Me

- LinkedIn: [Sanskar Singh](https://www.linkedin.com/in/sanskar-singh-b17819241)  
- GitHub: [sanskardev9](https://github.com/sanskardev9)  
- Email: [sanskar.dev09@gmail.com](mailto:sanskar.dev09@gmail.com)  


---

## Fun Fact

Every app on this page started as an annoyance in my own life. If something bugs me twice, I build a fix for it 😄
