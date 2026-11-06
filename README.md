<h1 align="center">Hi there,  I'm Sergio Acuña</h1>

<p align="center">
  <strong>Software Engineer | Backend & Full-Stack Developer | QA Automation</strong>
</p>

I'm a Software Engineer from Mexico with a strong interest in backend development, software architecture, and quality engineering.

I primarily work with **JavaScript and TypeScript**, building web applications, REST APIs, and backend services using technologies such as Node.js, NestJS, React, and Next.js. I also have experience with **Java and Spring Boot**, **Python and FastAPI**, relational databases, and End-to-End test automation with Playwright.

My interests go beyond application development. I'm particularly interested in understanding how software works behind the scenes, from database design and asynchronous communication to Linux system administration, infrastructure, and self-hosting.

<h2 align="center">Featured Projects</h2>

<h3 align="center">Self-Hosted Private Cloud Storage</h3>

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
<h3 align="center">US Accident Risk Predictor</h3>

A machine learning project exploring how historical traffic data can be used to predict accident severity and visualize geographic accident patterns.

**Stack:** Python · Scikit-Learn · Pandas · FastAPI · Java · Spring Boot · React · Leaflet

**What I built:**

* Processed and analyzed 7.7M+ US traffic accident records from 2016–2023 using Pandas and Scikit-Learn.
* Performed data cleaning, preprocessing, and feature engineering before training the model.
* Trained a Random Forest classifier achieving 83.61% accuracy for accident severity prediction.
* Developed a FastAPI microservice to load the trained model and serve predictions through a REST API.
* Implemented a Spring Boot Backend-for-Frontend (BFF) to communicate with the prediction service and expose data to the frontend.
* Built an interactive React + Leaflet map to explore accident information and geographic risk data.

This project gave me hands-on experience integrating machine learning, microservices, Java, Python, and frontend development into a single application.

---
<div style="padding: 8px">
<h3 align="center">Software Quality Management Platform (Bug Tracker MVP)</h3>
</div>

A full-stack bug tracking and software quality management platform developed as my university residency project.

**Stack:** Next.js · TypeScript · PostgreSQL · Prisma ORM · Playwright · Recharts

**What I built:**

* Implemented authentication and Role-Based Access Control (RBAC) for Administrator, Developer, and Tester workflows.
* Developed ticket management with priorities, modules, statuses, assignments, and status history.
* Implemented role-specific permissions controlling which users can create, modify, assign, close, or cancel tickets.
* Integrated Google Gemini to automatically estimate issue severity when it isn't manually provided.
* Developed analytics dashboards with Recharts, including open-ticket metrics, reopened vs. closed issues, and Mean Time to Resolution (MTTR).
* Implemented PDF export for metric summaries.

The goal was to build more than a CRUD application by modeling a software quality workflow with distinct responsibilities, permissions, and reporting capabilities.


<h2 align="center" margin-button="3px">Tech Stack</h2>

### Languages

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=sass&logoColor=white)

### Backend & Databases

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![NestJS](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/springboot-000000?style=for-the-badge&logo=springboot&logoColor=green)
![Prisma](https://img.shields.io/badge/prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

### QA & Testing

![Playwright](https://img.shields.io/badge/Playwright-45ba63?style=for-the-badge&logo=playwright&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### Infrastructure & Tools

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-red?style=for-the-badge&logo=debian&logoColor=white)
![Docker](https://img.shields.io/badge/docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Cloudinary](https://img.shields.io/badge/cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-018281?style=for-the-badge&logo=neon&logoColor=white)


<h3 align="center">GitHub Stats</h3>

---

![GitHub Streak](https://streak-stats.demolab.com?user=SergioMadrid522)


<h3 align="center">Currently Learning</h3>

---

* GitHub Actions and CI/CD workflows.
* Linux system administration and infrastructure management.
* Backend and system architecture.
* Self-hosting and server administration.
* Building reliable and maintainable software beyond the development environment.


<h3 align="center">Contact & Links</h3>

---

* **Portfolio:** [fabianmadrid.dev](https://fabianmadrid.dev/)
* **LinkedIn:** [linkedin.com/in/sergio-acuña-59735336b](https://www.linkedin.com/in/sergio-acu%C3%B1a-59735336b/)
* **Email:** [sergioac.madrid@hotmail.com](mailto:sergioac.madrid@hotmail.com)
