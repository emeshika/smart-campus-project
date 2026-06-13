# Facilities & Assets Catalogue Microservice — UniSphere 🏫📋

## Project Overview
This repository contains the **Facilities & Assets Catalogue Module**, a core functional microservice engineered for **UniSphere**—the centralized campus community and resource hub platform. This module digitizes traditional, fragmented university resource management by providing a standardized framework to catalogue, update, and manage university physical infrastructure and assets.

The primary objective is to enable campus administrators to maintain real-time asset visibility while allowing the student body to explore available facilities seamlessly through a full-stack, decoupled software architecture.

## Key Features
* **Dynamic Asset Cataloguing:** Implements structured management capabilities allowing university officials to register, update, and deprecate campus assets dynamically.
* **Granular Attribute Schema:** Maps flexible infrastructure data models to capture multiple asset parameters, including location grids, capacity indices, availability markers, and operational hours.
* **Interactive Resource Discovery UI:** Features a modern frontend cataloguing interface that offers responsive filtering, searching, and sorting of campus properties.
* **Secure Cloud Data Persistence:** Integrates persistent cloud storage to record transactions securely without disrupting adjacent campus microservices.

## Architectural Layering & Pipeline
1. **Frontend Presentation Layer (React.js):** A responsive, single-page application structure managing component states, cataloguing dashboards, and administrative controls.
2. **Backend Services Gateway (Java Spring Boot):** Built as a discrete microservice handling structural REST endpoints, input validations, and model mapping requests.
3. **Cloud Database Layer (MongoDB Atlas):** Utilizes a NoSQL document database schema configuration to easily handle non-homogeneous asset descriptions without schema-locking friction.

## Tech Stack
* **Frontend:** React.js, JavaScript (ES6+), HTML5, CSS3 / Tailwind
* **Backend Framework:** Java Spring Boot, Spring Data MongoDB
* **Database engine:** MongoDB Atlas (Cloud Persistent Instance)
* **API Architecture:** RESTful API Protocols (JSON payload exchanges)
* **API Development Tools:** Postman, IntelliJ IDEA, Maven
