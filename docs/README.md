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

## 👥 Team and Supervisors

| Role | E-Number | Name | Email |
| :--- | :--- | :--- | :--- |
| Team | E/21/007 | Abeynayake A.G.C.D. | e21007@eng.pdn.ac.lk |
| Team | E/21/006 | Abeykoon A.M.U.I.B. | e21006@eng.pdn.ac.lk |
| Supervisor | | Ms. Yasodha Vimukthi | yasodhav@eng.pdn.ac.lk |

---

## 💡 Introduction

The Organizer Dashboard Web UI is a feature-rich **Single Page Application (SPA)** developed using **React, TypeScript, and Tailwind CSS**. It serves as the primary client-side platform for interacting with the 75Exhibition backend microservices. The system enables organizers to monitor crowd activity, manage buildings and events, visualize **real-time analytics**, and communicate through live channels.

The application emphasizes high performance, **responsive UI design**, secure authentication mechanisms, and modular component architecture.

---

## ✨ Complete Frontend Solution

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

## 🛠️ Comprehensive Features and Architecture

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

## 🎨 UI and UX Design

* **Tailwind CSS-driven responsive layout.**
* Component-based structure with reusable UI elements.
* Interactive animations and transitions.
* Accessible navigation with ARIA roles and keyboard support.
* Clear validation messages and error feedback.

---

## How to Run

Before running the frontend, ensure the **backend services are running** (refer to the backend project page).

1. **Clone Repository**
   ```bash
   git clone [https://github.com/cepdnaclk/e21-co227-PeraVerse-Organizer-Dashboard-Frontend-UI.git](https://github.com/cepdnaclk/e21-co227-PeraVerse-Organizer-Dashboard-Frontend-UI.git)
   cd e21-co227-PeraVerse-Organizer-Dashboard-Frontend-UI
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Environment Configuration**
    * Create a `.env` file in the root directory and set the backend URL:
        ```bash
        VITE_BASE_API_URL=http://localhost:5000 
        ```

4. **Running the System Locally**
    ```bash
    npm run dev
    # The application will run on the port shown in the console (e.g., http://localhost:5173).
    # Navigate to http://localhost:5173/dashboard/
    ```

---

## Links

- [Frontend Repository](https://github.com/cepdnaclk/e21-co227-PeraVerse-Organizer-Dashboard-Core-Frontend)
- [Backend Repository](https://github.com/cepdnaclk/e21-co227-PeraVerse-Organizer-Dashboard-Core-Backend)
- [Project Page](https://cepdnaclk.github.io/e21-co227-PeraVerse-Organizer-Dashboard-Frontend-UI/)
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)

---

##  Project Tags

`React`, `TypeScript`, `Vite`, `Tailwind CSS`, `WebSocket`, `Real-Time Dashboard`, `SPA`, `Responsive Design`, `JWT Authentication`, `Data Visualization`, `Frontend`, `UI/UX`, `75Exhibition`, `Crowd Management`
