---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: cepdnaclk/e21-co227-PeraVerse-Organizer-Dashboard-Frontend-UI
title: Organizer Dashboard Web UI and Client of the Engex exhibition crowd management system
---

#  Peraverse Organizer Dashboard Web UI (Team-07)

The client-side interface for the 75Exhibition crowd management system.

---

##  Team & Supervisors

| Role | E-Number | Name | Email |
| :--- | :--- | :--- | :--- |
| **Team** | E/21/007 | Abeynayake A.G.C.D. | e21007@eng.pdn.ac.lk |
| **Team** | E/21/006 | Abeykoon A.M.U.I.B | e21006@eng.pdn.ac.lk |
| **Supervisor** | | Ms. Yasodha Vimukthi | yasodhav@eng.pdn.ac.lk |

---

##  Individual Component Contributions (E/21/007 - Abeynayake A.G.C.D.)

As part of the collaborative execution, my specific components and responsibilities on the **Frontend Web UI** included:

* **Authentication & Security Service:** Built the complete **Signup and Login interfaces**, implementing secure session persistence and JWT handling using **Axios** and **React Router**.
* **Building & Organizer Management:** Developed the complex **CRUD interfaces** for managing building records and organizer details, including dynamic state management for exhibits and tags.
* **Analytics & Feedback Services:** Built the interactive **Data Visualization dashboards** using Chart.js (key metrics, visitor check-ins) and implemented the **Visitor Feedback Module** with sentiment analysis and color-coding.
* **Real-Time Communication Client:** Developed the **WebSockets client** for the live chat system, handling real-time message display and connection status.

---

##  Introduction & Impact

The Organizer Dashboard Web UI is the **client-side interface** built using **React, TypeScript, and Tailwind CSS**. It provides organizers with a highly **responsive** and **intuitive** platform to interact with the backend microservices for the 75Exhibition crowd management system. The application delivers **real-time data visualization**, secure authentication, and a seamless user experience for managing complex exhibition operations through a modern **Single-Page Application (SPA)** architecture.

### Solution & Impact Highlights
* **Dynamic SPA Experience:** Provides **fast navigation** and smooth transitions using React Router for optimal user experience.
* **Real-Time Data Visualization:** Implements **live charts** and analytics using modern visualization libraries like Chart.js for quick decision-making.
* **Secure Client-Side Authentication:** Manages **JWT tokens** with automatic session handling and protected routes to ensure system security.
* **Component-Based Architecture:** Utilizes modular, **reusable components** for maintainable and scalable code development.

---

##  Features & Architecture

### Key Frontend Features

#### **Authentication & Session Management**
* **JWT Token Handling:** Uses **Axios interceptors** for automatic token injection and secure request handling.
* **Protected Routes:** **React Router guards** prevent unauthorized access to sensitive dashboard components.

#### **Dashboard Components**
* **Building & Organizer Management:** Provides full **CRUD** (Create, Read, Update, Delete) interfaces with complex **form validation** and dynamic state management.
* **Analytics Visualization:** Displays real-time and historical data (visitors, check-ins, session times) using **Chart.js**.
* **Feedback Module:** Implements **sentiment analysis** and visual display (color-coded cards) for visitor feedback.
* **Live Chat Client:** **WebSocket-based** client for real-time messaging with organizers and users.

#### **UI/UX Features**
* **Styling:** Uses **Tailwind CSS** for responsive design and modern aesthetics (e.g., glass morphism effects).
* **Interactive Elements:** Features smooth animations, collapsible cards, and **Toast notifications** for instant feedback.

### Architecture Overview

#### **Frontend Technology Stack**
* **Core Framework:** **React 18** with **TypeScript**.
* **Build Tool:** **Vite** for optimized production builds.
* **Styling:** **Tailwind CSS**.
* **Routing:** **React Router DOM**.
* **HTTP Client:** **Axios** with interceptors.
* **Real-Time:** Native **WebSockets**.

#### **Component Architecture**
* **Modular Design:** Reusable widgets with clear separation of concerns.
* **API Integration:** Full integration with RESTful backend microservices for data exchange.

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
