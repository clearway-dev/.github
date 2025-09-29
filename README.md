# ClearWay

ClearWay is a research and development project focused on **road passability detection** and **data-driven mobility solutions**.  
Our goal is to create an end-to-end system that collects, processes, and visualizes sensor data in order to help emergency services, municipalities, and other stakeholders understand whether vehicles can safely pass through city streets.

---

## 📂 Project Structure

The project is divided into three main repositories under this organization:

- **[clearway-data](https://github.com/clearway-dev/clearway-data)**  
  Mobile app and data ingestion pipeline. Collects raw measurements from sensors, simulates data, and stores them in the shared PostgreSQL database with optional preprocessing and cleaning.

- **[clearway-analytics](https://github.com/clearway-dev/clearway-analytics)**  
  Visualization and analytics layer. Provides dashboards, statistics, and interactive maps to evaluate road passability data, including integration with GIS systems.

- **[clearway-infra](https://github.com/clearway-dev/clearway-infra)**  
  Infrastructure and database setup. Contains PostgreSQL schema, Docker Compose setup, deployment scripts, and shared documentation.

---

## 🎯 Objectives

- Collect and manage **real-time sensor data** from vehicles.
- Apply **data cleaning and clustering** techniques to improve measurement quality.
- Provide **visual dashboards and maps** to analyze the state of urban road networks.
- Support **integration with GIS systems** and municipal infrastructure.

---

## 🛠️ Tech Stack

- **Backend:** PostgreSQL, Docker, Node.js (PoC), future migration to Spring Boot  
- **Frontend:** React, Flutter, Tailwind CSS  
- **Data Visualization:** Map libraries, GIS integration  
- **Infrastructure:** Docker Compose, pgAdmin, GitHub Actions (planned)

---

## 👥 Team

ClearWay is being developed as part of diploma theses at the **University of West Bohemia** in collaboration with **SIT Port Plzeň** and the **Faculty of Electrical Engineering (FEL)**.  

- **Data Acquisition & Processing:** Jakub Homolka  
- **Visualization & Analytics:** Jan Vandlíček  

---

## 📜 License

This project is currently under a **research prototype license**.  
Future licensing and distribution will be defined after the PoC phase.
