# Guardian Grid 🚨

A real-time emergency response and disaster coordination platform designed to improve communication, situational awareness, and incident management during emergencies.

Guardian Grid enables authorities, responders, and civilians to coordinate effectively through live location tracking, interactive geospatial visualization, real-time alerts, and low-latency communication services.

## Features

### 🌍 Real-Time Incident Monitoring

* Report and track emergency incidents in real time.
* Monitor active events through an interactive dashboard.
* Visualize incidents on dynamic maps.

### 📍 Live Location Tracking

* Real-time location sharing and tracking.
* Geospatial visualization powered by Leaflet.
* Enhanced situational awareness for responders and administrators.

### ⚡ Real-Time Communication

* WebSocket-powered communication using Socket.IO.
* Instant alert delivery and notifications.
* Bidirectional client-server messaging for emergency coordination.

### 🔐 Secure Authentication & Authorization

* JWT-based authentication.
* Role-Based Access Control (RBAC).
* Protected routes and secure API access.

### 📊 Incident Management

* Create, update, and manage emergency events.
* Track incident status and response progress.
* Store and retrieve incident data efficiently.

## Tech Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Leaflet

### Backend

* Node.js
* Express.js
* MongoDB
* Socket.IO
* JWT Authentication

## System Architecture

```text
Civilian / Responder
          │
          ▼
    React Frontend
          │
          ▼
     Express API
          │
 ┌────────┴────────┐
 ▼                 ▼
MongoDB       Socket.IO
(Database)    Real-Time Layer
```

## Key Highlights

* Built a full-stack emergency response platform using the MERN stack.
* Implemented real-time communication infrastructure using Socket.IO and WebSockets.
* Integrated geospatial mapping and live location tracking with Leaflet.
* Designed scalable REST APIs for incident reporting and management.
* Developed secure authentication and authorization workflows using JWT.
* Enabled low-latency event coordination for disaster response scenarios.

## Installation

### Clone Repository

```bash
git clone https://github.com/<your-username>/guardian-grid.git
cd guardian-grid
```

### Backend Setup

```bash
cd backend
npm install
npm start
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Future Enhancements

* SMS and email alert integration
* AI-assisted incident prioritization
* Predictive risk analysis
* Mobile application support
* Multi-agency coordination tools

## Learning Outcomes

This project demonstrates:

* Full-Stack MERN Development
* Real-Time Systems Design
* WebSocket Communication
* Geospatial Data Visualization
* REST API Development
* Authentication & Authorization
* Event-Driven Architecture
* Scalable Backend Engineering
