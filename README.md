# Hi there, I'm Todor! 👋

<p align="left">
        <a href="https://www.linkedin.com/in/todor-mitev-706b02339">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
    <a href="https://github.com/tdmitev">
    <img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://www.facebook.com/profile.php?id=100005648209189">
    <img src="https://img.shields.io/badge/-Facebook-00B2FF?style=for-the-badge&logo=Facebook&logoColor=white" alt="Facebook">
  </a>
  <a href="https://www.instagram.com/td_mitev/">
    <img src="https://img.shields.io/badge/-Instagram-e4405f?style=for-the-badge&logo=Instagram&logoColor=white" alt="Instagram">
  </a>
</p>

## 🚀 About Me

🔹 Passionate **Programmer** interested in both front-end and back-end development.  
🔹 I specialize in **JavaScript**, **TypeScript**, **Java Spring**, **Node.js**, **Express.js**, **Angular**, **MySQL**, and **MongoDB**.  
🔹 I work with various development tools like **Visual Studio Code**, **IntelliJ IDEA**, **Postman**, **MongoDB Compass**, **MySQL Workbench**, and **GitHub Desktop**.  
🔹 Constantly learning, innovating, and striving to build efficient and scalable applications.  

---

## 🏆 Featured Projects

### <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/NeoBook_icon.png" width="45" align="center"> **NeoBook** – Web-Based Electronic School Diary  
🔗 [GitHub Repository](https://github.com/tdmitev/NeoBook)

**NeoBook** is a **web-based electronic school diary system** built with a **microservice architecture** using **Spring Boot**, **Angular**, and **Keycloak**.  
It enables complete digital management of schools — including **students**, **teachers**, **parents**, **classes**, **grades**, and **absences** — all secured through role-based authentication and deployed in a **Docker Compose** environment.

#### ⚙️ Core Highlights
- 🧩 **Microservice Architecture:** `user-service`, `school-service`, and `notebook-service` integrated via **Spring Cloud Gateway**  
- 🔐 **Keycloak Authentication:** centralised realm with roles — `STUDENT`, `TEACHER`, `PARENT`, `HEADMASTER`, `ADMIN`  
- 🗄️ **Databases:** two **PostgreSQL** instances for relational data and one **MongoDB** instance for reactive records  
- ⚡ **Reactive Notebook:** built with **Spring WebFlux** for handling grades and absences efficiently  
- 💻 **Front-End:** **Angular 19 + Material Design**, featuring PKCE **SSO login** and role-based dashboards  
- 🐳 **Dockerized Deployment:** unified Docker Compose stack with Keycloak, microservices, and databases  
- 🔗 **API Gateway:** routes all traffic securely through JWT validation and OAuth2 login  

#### 🏗️ Architecture Overview
| Component | Description |
|------------|-------------|
| 👤 **user-service** | Manages users (students, parents, teachers); integrates with Keycloak |
| 🏫 **school-service** | Handles schools, classes, subjects, and schedules |
| 📝 **notebook-service** | Reactive service for grades and absences |
| 🌐 **api-gateway** | Central entry point with JWT validation and routing |
| 🗄️ **PostgreSQL / MongoDB** | Persistent storage per service |
| 🔐 **Keycloak** | Authentication & authorization provider |
| 💻 **Angular Frontend** | Interactive dashboards for all user roles |

#### 🧰 Technologies
`Java 23`, `Spring Boot 3.x`, `Spring Cloud Gateway`, `Spring WebFlux`, `Hibernate`, `MapStruct`, `Keycloak`,  
`PostgreSQL`, `MongoDB`, `Angular 19`, `Docker`, `Gradle`

### 📸 Gallery
<p align="center">
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/Neobook_icon2.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/Neobook_icon2.png" width="250">
  </a>
</p>

---

### **<img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/blueMainLogo.png" width="50"> LogiXpert** – Logistics Management System
🔗 [GitHub Repository](https://github.com/tdmitev/logiXpert)

**LogiXpert** is a **web-based logistics management system** built with **Spring Boot** and **Angular**, designed to digitalize shipment tracking, employee operations, and financial reporting for transport companies.  
The platform features full **authentication**, **role-based control**, **real-time shipment management**, and **automated invoice generation** — all deployed through a unified **Spring + Angular architecture**.

#### ⚙️ Core Highlights
- 🔐 **Authentication & Roles:** secure JWT-based login with `ADMIN`, `EMPLOYEE`, `COURIER`, and `CLIENT` roles  
- 📦 **Shipment Management:** full CRUD with automatic tracking number generation and assignment to couriers  
- 💰 **Pricing Calculator:** dynamic delivery cost calculation based on weight, distance, and delivery type  
- 🏢 **Company Operations:** management of employees, offices, and transport companies  
- 📄 **PDF & Barcode Generation:** integrated **iText7** and **ZXing** libraries for generating invoices and labels  
- 📊 **Reports & Analytics:** revenue summaries and shipment performance tracking per employee  
- ⚡ **Frontend Integration:** responsive Angular app with Tailwind UI and reactive forms  
- 🐳 **Docker-ready:** backend and frontend can run together with unified configuration  

#### 🏗️ Architecture Overview
| Layer | Description |
|--------|-------------|
| 🧠 **Backend (Spring Boot)** | `Java 23`, `Spring Boot 3.3.5`, `JPA`, `Spring Security`, `MapStruct`, `JWT`, `iText7`, `ZXing` |
| 💾 **Database** | **MySQL** with automatic schema updates |
| 🔧 **Build Tool** | **Gradle** |
| 💻 **Frontend (Angular 17)** | Standalone components, reactive forms, and Tailwind CSS + Flowbite |
| 🔒 **Security** | Stateless JWT auth, `httpOnly` cookies, CORS for Angular client |
| 🧩 **Integration** | Angular consumes REST APIs exposed by the backend |
| 🚚 **Deployment** | Unified configuration for both backend and frontend |

#### 🧰 Technologies
`Java 23`, `Spring Boot 3.3.5`, `Spring Security`, `JPA/Hibernate`, `MapStruct`, `JWT`,  
`Angular 17`, `TypeScript`, `Tailwind CSS`, `Flowbite`, `MySQL`, `Gradle`, `iText7`, `ZXing`

  ### 📸 Gallery
<p align="center">
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/admin_dashboard.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/admin_dashboard.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/admin_dashboard2.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/admin_dashboard2.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/modal.png">
     <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/modal.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/package.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/package.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/profile2.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/profile2.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/register.png">
     <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/register.png" width="250">
  </a>
</p>

---

### <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/hotel-logo.png" width="30" align="center"> **Hotel Manager** – Hotel Management System
🔗 [GitHub Repository](https://github.com/tdmitev/Hotel-helper)

**Hotel Manager** is a **comprehensive web-based hotel management system** for organizing **meal events**, **menus**, and **guest attendance** through an integrated **Angular** frontend and **Node.js/Express** backend.  
It allows hotel staff to plan, monitor, and analyse daily meals with precision — from guest check-ins to dish management and real-time participation tracking.

#### 🍽️ Core Features
- 🗓️ Create and manage **meal events** (breakfast, lunch, dinner) with specific dates  
- 🍲 Add predefined dishes with images to each event and customise active menus  
- 📋 Dynamic **menu page** displaying events and their respective dishes  
- 🧍 Guest **check-in/out** via room number or name search for accurate attendance tracking  
- 📊 Visual statistics of guest participation using **ApexCharts**  
- 💬 Built-in **chat module** integrated with a Flask API for real-time communication  
- 🔐 Secure **JWT authentication** with HTTP-only cookies and session handling  
- ⚙️ Preloaded **MongoDB resources** for quick startup with sample data  

#### 🏗️ Architecture Overview
| Layer | Description |
|--------|-------------|
| 💻 **Frontend (Angular 16)** | Tailwind + Flowbite UI, modular routing, reactive forms, ApexCharts visualisations |
| 🎨 **Core Modules** | Header/Footer/Chat components, MessageService for global toasts |
| 🧠 **Backend (Node.js/Express)** | REST API with JWT, cookie-based auth, and session management |
| 💾 **Database** | MongoDB with models for users, guests, meal events, menu items, and token blacklist |
| 🔧 **Integration** | Angular communicates with Express API (`http://localhost:3001/api`) |
| 💬 **Chat Module** | Animated interface connected to Flask microservice |
| 📂 **DB Resources** | BSON exports for users, guests, menus, events, and blacklists |

#### 🧰 Technologies
`Angular 16`, `Tailwind CSS`, `Flowbite`, `ApexCharts`,  
`Node.js`, `Express`, `MongoDB`, `Mongoose`, `JWT`, `bcrypt`, `cookie-parser`, `express-session`, `Flask`


  ### 📸 Gallery
  <p align="center">
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/home_page.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/home_page.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/meal-event-list.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/meal-event-list.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/meal-event.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/meal-event.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/menu-items.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/menu-items.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/menu.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/menu.png" width="250">
  </a>
  <a href="https://raw.githubusercontent.com/tdmitev/tdmitev/main/guest.png">
    <img src="https://raw.githubusercontent.com/tdmitev/tdmitev/main/guest.png" width="250">
  </a>
</p>

---

### **🚛 TransportCompany** – Transportation Management System
🔗 [GitHub Repository](https://github.com/tdmitev/transportCompany)

A system for managing transportation companies, featuring:
- Vehicle and driver management
- Trip registration with start and end locations, cargo details, and pricing
- Employee qualification tracking for specialized transport
- Revenue tracking and financial reports

---

## 💻 Tech Stack & Tools

### **Languages & Frameworks**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)

### **Databases**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### **Development Tools**
![Visual Studio Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![MongoDB Compass](https://img.shields.io/badge/MongoDB%20Compass-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![GitHub Desktop](https://img.shields.io/badge/GitHub%20Desktop-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📊 GitHub Stats

<a href="https://github.com/tdmitev">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=tdmitev&show_icons=true&theme=wight&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tdmitev&layout=compact&langs_count=6&theme=wight"/>
</a>

---

💡 **Let's connect! Feel free to explore my projects or reach out on social media.** 🚀
