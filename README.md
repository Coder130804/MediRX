<h1 align="center">Pharmacy Management System - MediRX</h1>

---

## 🌐 Website  
**Live Deployment:**  
https://pharmacy-frontend-ashen.vercel.app/

---

## Overview

This Pharmacy Management System is designed to manage core pharmacy operations such as medicine inventory, billing, and reporting. The application is built with a focus on structured workflow and smooth user experience across all modules.

It follows a dashboard-driven approach where users can efficiently manage medicines, generate bills, and track pharmacy performance in a structured and intuitive way.

---

## Tech Stack

The frontend is built using Next.js with TypeScript to ensure scalability, maintainability, and type safety. Tailwind CSS is used for styling, enabling a clean and responsive UI across devices.

The application communicates with the backend through REST APIs, following a standard client-server architecture. React hooks such as useState and useEffect are used for state management and lifecycle handling.

The backend is built using Spring Boot, exposing RESTful APIs for all major operations including medicines, billing, and reporting. PostgreSQL is used as the database, ensuring structured and reliable data storage.

---

## Backend Integration

All application operations are powered through REST APIs developed in Spring Boot.

The frontend interacts with endpoints to fetch medicines, create bills, and generate reports. The backend handles all business logic, validations, and database operations, while the frontend focuses only on UI rendering and user interaction.

This separation ensures scalability, clean architecture, and easier maintenance.

---

## Features

The dashboard provides a centralized overview of pharmacy activity including inventory status and sales insights.

The medicines module allows adding, updating, and managing stock records. All changes are synced with the backend database in real time.

The billing module enables users to select medicines, specify quantities, and generate bills. The backend processes and stores billing data in PostgreSQL.

The reports module displays aggregated data based on stored transactions, helping analyze sales trends and inventory usage.

---

## Application Flow

1. User lands on Dashboard  
   Displays system overview and key metrics.

2. Medicine Management  
   Admin adds or updates inventory. Changes reflect across all modules.

3. Billing Process  
   Medicines are selected, quantities are added, and total is calculated automatically before generating a bill.

4. Reports Generation  
   Billing data is processed and displayed as structured insights for analysis.

---

## System Architecture

The system follows a layered architecture consisting of frontend, backend, and database layers.

The frontend handles UI rendering and communicates with backend services through REST APIs. The backend, built using Spring Boot, manages business logic, validations, and request processing.

PostgreSQL is used as the database layer to store structured data such as medicines, billing records, and reports. This ensures modularity, scalability, and maintainability of the system.
