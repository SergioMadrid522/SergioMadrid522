<h1 align="center">Hi 👋, I'm Sergio Acuña</h1>

<p align="center">
  <strong>Software Engineer · Backend & Full-Stack Developer · QA Automation Engineer</strong>
</p>

<p>
  I'm a Software Engineer from Mexico who enjoys building full-stack applications, backend services, automation tools, and pretty much anything that lets me understand how software works behind the scenes.
</p>

<p>
  Most of my work is around the JavaScript/TypeScript ecosystem, especially React, Next.js, Node.js, and NestJS. I also have experience building REST APIs with Java + Spring Boot and Python + FastAPI, as well as creating End-to-End automation with Playwright.
</p>

<p>
  Recently, I've also been getting more into Linux, self-hosting, backend architecture, and infrastructure by building and managing my own Debian home server.
</p>

---

## Featured Projects

### Self-Hosted Private Cloud Storage

A self-hosted private cloud storage platform I'm building from scratch as an alternative to services like OneDrive and iCloud. The project is focused on understanding and implementing the architecture behind a cloud storage system, from file management and physical storage to server administration and automated backups.

**Stack:** NestJS · Next.js · TypeScript · Node.js · Prisma ORM · PostgreSQL · Debian 13 · Bash · Python

**What I'm building:**
* Building a REST API with NestJS for authentication, users, folders, files, uploads, downloads, and storage operations.
* Separating the logical filesystem stored in PostgreSQL from the physical filesystem stored on a dedicated HDD.
* Using UUID-based storage identifiers (`storageName`) for physical files while preserving user-facing filenames and folder structures as database metadata.
* Implementing hierarchical folder management using PostgreSQL relationships and recursive queries.
* Using Node.js Streams for file uploads and downloads to avoid loading entire files into memory.
* Supporting single-file and folder downloads, including ZIP generation for directory downloads.
* Building a Bash-based Management CLI accessed through SSH for monitoring system resources, storage, logs, services, backups, and maintenance tasks.
* Developing an independent Python/Bash backup automation system scheduled through `cron`, including backup creation, verification, and retention.
* Designing the system around limited hardware resources, making storage efficiency, memory usage, and server reliability important architectural considerations.

**Current status:**
Authentication is complete, and the folder management system is nearly finished. File management, the frontend UI, responsive design, backup automation, and deployment are currently in development.

<p>The long-term goal is to turn the project into a fully functional private cloud that my family and I can use to store and access files through a web interface, while maintaining complete control over the infrastructure and data. The platform is designed to eventually support both local-network access and secure public access.</p>

---

### US Accident Risk Predictor
<p>A machine learning project I built to explore how historical traffic data can be used to predict accident severity.</p>

**Stack:** Python · Scikit-Learn · Pandas · FastAPI · Java · Spring Boot · React · Leaflet

**What I built:**
* Processed and analyzed 7.7M+ US traffic accident records from 2016–2023 using Pandas and Scikit-Learn.
* Performed data cleaning, preprocessing, and feature engineering before training the model.
* Trained a Random Forest classifier with 83.61% accuracy for accident severity prediction.
* Built a FastAPI microservice responsible for loading the trained model and serving predictions through a REST API.
* Built a Spring Boot Backend-for-Frontend (BFF) to communicate with the prediction service and expose data to the frontend.
* Created an interactive React + Leaflet map for exploring accident information and geographic risk data.

<p>This project was also my first real attempt at combining machine learning, microservices, Java, Python, and a web frontend into a single system.</p>

---

### Software Quality Management Platform (Bug Tracker MVP)
<p>A full-stack bug tracking and software quality management platform I originally built as my university residency project.</p>

**Stack:** Next.js · TypeScript · PostgreSQL · Prisma · Playwright · Recharts

**What I built:**
* Implemented authentication and Role-Based Access Control (RBAC) for Administrator, Developer, and Tester workflows.
* Built ticket management with priorities, modules, statuses, assignments, and complete status history.
* Added role-specific permissions to control which users can create, modify, assign, close, or cancel tickets.
* Integrated Google Gemini to automatically estimate issue severity when it isn't manually provided.
* Built analytics dashboards with Recharts, including open-ticket metrics, reopened vs. closed issues, and Mean Time to Resolution (MTTR).
* Added PDF metric summary export 

<p>The goal was not only to build a CRUD application, but to model an actual software QA workflow with different responsibilities and permissions.</p>

---

## Tech Stack

### Languages

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge\&logo=javascript\&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge\&logo=typescript\&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge\&logo=python\&logoColor=ffdd54)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
### Frontend

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge\&logo=react\&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge\&logo=next.js\&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge\&logo=tailwind-css\&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge\&logo=sass\&logoColor=white)

### Backend & Databases

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge\&logo=express\&logoColor=%2361DAFB)
![Nestjs](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/springboot-000000?style=for-the-badge&logo=springboot&logoColor=green)
![Prisma](https://img.shields.io/badge/prisma-2D3748?style=for-the-badge\&logo=prisma\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge\&logo=postgresql\&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge\&logo=mysql\&logoColor=white)
![MariaDB](https://img.shields.io/badge/mariadb-003545?style=for-the-badge\&logo=mariadb\&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge\&logo=rabbitmq\&logoColor=white)

### QA & Testing

![Playwright](https://img.shields.io/badge/Playwright-45ba63?style=for-the-badge\&logo=playwright\&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge\&logo=zod\&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge\&logo=postman\&logoColor=white)

### Cloud & DevOps

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/debian-red?style=for-the-badge&logo=debian&logoColor=orange&color=darkred)
![Docker](https://img.shields.io/badge/docker-0db7ed?style=for-the-badge\&logo=docker\&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-000000?style=for-the-badge\&logo=vercel\&logoColor=white)
![Render](https://img.shields.io/badge/render-46E3B7?style=for-the-badge\&logo=render\&logoColor=black)
![Cloudinary](https://img.shields.io/badge/cloudinary-3448C5?style=for-the-badge\&logo=cloudinary\&logoColor=white)
![Neon Server less](https://img.shields.io/badge/Neon-018281?logo=neon&logoColor=white)

---

## GitHub Stats
![GitHub Streak](https://streak-stats.demolab.com?user=SergioMadrid522)

---

## Currently Learning 

* GitHub Actions & CI/CD
* Linux system administration
* Backend and system architecture
* Self-hosting and infrastructure
* Building software that can actually run outside of my development machine :)

---

## Contact & Links

* **Portfolio:** [fabianmadrid.dev](https://fabianmadrid.dev/)
* **LinkedIn:** [linkedin.com/in/sergio-acuña-59735336b](https://www.linkedin.com/in/sergio-acu%C3%B1a-59735336b/)
* **Email:** [sergioac.madrid@hotmail.com](mailto:sergioac.madrid@hotmail.com)
