# 🩺 MediTrack
### Cloud-Based Medication Management System

MediTrack is a full-stack web application designed to help doctors and patients manage prescriptions and monitor medication adherence through a secure, role-based system.

The platform enables healthcare providers to issue and track prescriptions while allowing patients to monitor their daily medication intake through an intuitive web interface.

This repository serves as the central documentation hub for the MediTrack system and links to its frontend and backend components.

---

## 🔗 Project Repositories

🔸 Frontend (React + Vite)  
👉 https://github.com/spajetty/frontend-meditrack  

🔹 Backend (ASP.NET Core + Entity Framework Core)  
👉 https://github.com/spajetty/backend-meditrack  

---

## 📌 Problem Statement

Medication non-adherence is a common issue in healthcare systems. Patients often struggle to consistently track their prescriptions and daily intake, while doctors lack centralized visibility into patient adherence patterns.

MediTrack addresses this by providing a secure, role-based medication management platform that enables real-time prescription tracking and historical monitoring.

---

## 🏗️ System Architecture

MediTrack follows a layered full-stack architecture:

- **Frontend:** React.js Single Page Application (SPA)
- **Backend:** ASP.NET Core Web API
- **Database:** Azure SQL Server
- **ORM:** Entity Framework Core
- **Authentication:** Role-based authentication and authorization
- **Deployment:** Vercel (Frontend) + Azure App Service (Backend)

The backend is structured using separation of concerns principles (Controller → Service → Data Access Layer) to ensure maintainability and scalability.

The frontend communicates with the API via secure HTTP requests and implements protected routes for authenticated users.

---

## 🚀 Core Features

- Role-based access control (Doctor & Patient)
- Prescription creation and management
- Medication intake tracking
- Historical adherence monitoring
- Secure authentication workflow
- Cloud deployment for web access

---

## 🧑‍⚕️ User Roles

### 🩺 Doctor
- Secure login
- View assigned patients
- Issue and update prescriptions
- Monitor medication adherence statistics
- Review intake history

### 🤒 Patient
- Secure login
- View active prescriptions
- Track daily medication intake
- Edit medication records
- View intake history
- Manage personal profile information

---

## 💻 Tech Stack

### 🖥 Backend
![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-%23512BD4.svg?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework Core](https://img.shields.io/badge/Entity%20Framework%20Core-68217A?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Azure SQL](https://img.shields.io/badge/Azure%20SQL-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![CORS](https://img.shields.io/badge/CORS-Enabled-blue?style=for-the-badge)

### 🎨 Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

### ☁️ Deployment
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Azure App Service](https://img.shields.io/badge/Azure%20App%20Service-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)


---

## 🔐 Public Demo Accounts (Limited Access)

For quick evaluation, the following demo accounts are available:

### 🤒 Patient (Demo)
Email: patient1@gmail.com  
Password: patient1  

### 🩺 Doctor (Demo)
Email: trial2@gmail.com  
Password: trial2  

⚠️ These accounts contain dummy data for demonstration purposes only.

