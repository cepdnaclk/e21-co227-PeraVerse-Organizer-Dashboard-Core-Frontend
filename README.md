---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: cepdnaclk/e21-co227-PeraVerse-Organizer-Dashboard-Frontend-UI
title: Organizer Dashboard Web UI and Client of the Engex Exhibition Crowd Management System
---

# Peraverse Organizer Dashboard Web UI (Team-07)

A complete frontend interface for the 75Exhibition crowd management system, designed to provide organizers with real-time data, analytics, communication tools, and an efficient building and event management workflow. 

---

##  Team and Supervisors

| Role | E-Number | Name | Email |
| :--- | :--- | :--- | :--- |
| Team | E/21/007 | Abeynayake A.G.C.D. | e21007@eng.pdn.ac.lk |
| Team | E/21/006 | Abeykoon A.M.U.I.B. | e21006@eng.pdn.ac.lk |
| Supervisor | | Ms. Yasodha Vimukthi | yasodhav@eng.pdn.ac.lk |

---

##  Introduction

The Organizer Dashboard Web UI is a feature-rich **Single Page Application (SPA)** developed using **React, TypeScript, and Tailwind CSS**. It serves as the primary client-side platform for interacting with the 75Exhibition backend microservices. The system enables organizers to monitor crowd activity, manage buildings and events, visualize **real-time analytics**, and communicate through live channels.

The application emphasizes high performance, **responsive UI design**, secure authentication mechanisms, and modular component architecture.

---

##  Complete Frontend Solution

### End-to-End Dashboard Application

The system provides a complete user experience, including:

* **Secure Authentication** and protected routing.
* **Real-time Crowd Monitoring** with visual analytics.
* **Building and Exhibit Management** via advanced CRUD workflows.
* Event scheduling and lifecycle tracking.
* Feedback analysis and **sentiment insights**.
* **Data Export** in multiple formats.
* **Live Chat** and communication between organizers.
* A responsive and accessible UI across devices.

---

##  Comprehensive Features and Architecture

### Authentication and Security

* **JWT-based authentication** flow.
* **Axios interceptors** for secure API calls with token injection.
* **Protected routes** using React Router DOM.
* Session persistence and automatic token refresh.

### Dashboard Component Suite
This modular approach ensures maintainability and clear separation of concerns.

| Component | Functionality | Key Technology |
| :--- | :--- | :--- |
| **Buildings Management** | CRUD for buildings, zones, exhibits; **Multi-tag architecture**. | React State |
| **Events Management** | Scheduling, creation, updates; Conflict detection. | React Router |
| **Heatmap & Analytics** | **Real-time heatmap** of exhibition zones; Historical trend analysis. | Chart.js / Visualization Library |
| **Feedback Widget** | Feedback listing, **Sentiment visualization**, Rating analysis. | Chart.js |
| **Chat Client** | **Real-time messaging** interface; Typing indicators; **WebSocket** client. | WebSockets |
| **Export Widget** | Export data in **CSV, Excel, JSON, and PDF** formats. | Client-side File Handling |

### Technology Stack Highlights
* **Core Technologies:** React 18, TypeScript, Vite, Tailwind CSS.
* **Architecture:** Modular component design, Centralized API handling (Axios).
* **Real-Time Support:** Native WebSockets.

---

##  UI and UX Design

* **Tailwind CSS-driven responsive layout.**
* Component-based structure with reusable UI elements.
* Interactive animations and transitions.
* Accessible navigation with ARIA roles and keyboard support.
* Clear validation messages and error feedback.

---

## How to Run

1.  **Clone Repository**
   ```bash
   git clone https://github.com/cepdnaclk/e21-co227-PeraVerse-Organizer-Dashboard.git
   cd e21-co227-PeraVerse-Organizer-Dashboard
   ```

2. **Install Dependencies**

   **a) Frontend**
   ```bash
   cd frontend
   npm install
   ```

   **b) Backend**

   *Websocket for kiosk*
   ```bash
   cd backend/backend/tools
   npm install
   ```

   *For Each Service*
   ```bash
   # go inside each service and run the follwing command in the directory where the src file is situated
   npm install
   ```

4. **Environmental Variables : Edit .env file inside the backend:**
   ```bash
   PORT=5000
   BASE_URL=http://localhost:5000
   JWT_SECRET="Your JWT secret key"
   DB_USER=postgres
   DB_PASSWORD="Your database password"
   DB_HOST=localhost
   DB_PORT=5432
   DB_NAME=organizer_dashboard
   ADMIN_EMAIL="Email sending approval request to admin"
   ADMIN_PASSWORD="your-app-password for ADMIN_EMAIL"
   ADMIN_NOTIFY_EMAIL="Admin’s email(this email receives the approval request)"
   ```

5. **Running the System Locally**

   **a) Frontend : will be running on http://localhost:5173**
   ```bash
   cd frontend
   npm run dev
   # Then navigate to http://localhost:5173/dashboard/
   ```

   **b) Backend : will be running on http://localhost:5000**
   ```bash
   # Websocket for kiosk : first you have to run the websocket
   cd backend/backend/tools
   nodemon ws-server.js

   # Then go inside each service and run the following command
   # inside the directory where the index.js file is situated
   nodemon index
   ```

---

## Links

- [Project Repository](https://github.com/cepdnaclk/e21-co227-PeraVerse-Organizer-Dashboard-Core-Backend)
- [Project Page](https://cepdnaclk.github.io/e21-co227-PeraVerse-Organizer-Dashboard-Core-Backend/)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)

### Tags
`React`, `Express.js`, `Node.js`, `Full-Stack`, `Microservices`, `RESTful API`, `JWT Authentication`,  
`Event Management`, `Dashboard`, `Crowd Management`, `75Exhibition`

[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
